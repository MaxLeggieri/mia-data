# mia-data

Orario offline dei bus TUA (Pescara e dintorni) usato dall'app MIA per calcolare i percorsi sul telefono.

- `manifest.json`: versione, giorni coperti (`validFrom`, `days`), dimensione e sha256 del file dati.
- `timetable.json.gz`: orario compatto (formato 1), gzip.

I file sono aggiornati ogni notte da una GitHub Action a partire dagli orari pubblici. Contengono solo dati pubblici: fermate, linee e orari.
