# Mapping Medieval Vienna: Daten-Repository

Website und online-Edition: https://mapping-medieval-vienna.github.io/

Das Daten-Repository ist eine aufgeräumte und vervollständigte Version des alten Daten-Repository unter 
https://github.com/medieval-vienna/gesamt.

geplante Struktur:

```
/
├── README.md
├── quellen/
│   └── tei/
│       ├── zeilentreu/
│       └── formular/          ← TEI-Quelldateien, z.B. "KB-E formular.xml"
├── haeuser/
│   ├── biografien/            ← generierte Markdown-Dateien, eine pro Haus/Objekt
│   │   ├── DB1057.md
│   │   └── ...
│   ├── puzzle/
│   └── gis/
├── personen/
├── referenz/
│   ├── gazetteer.csv
│   ├── heiligenkalender/
│   └── konkordanzen/
├── skripte/
└── legacy/
```

Aus den TEIs der zeilentreuen und Formularansicht werden die TEI-Dateien für die online-Edition erstellt, siehe 
https://github.com/mapping-medieval-vienna/mapping-medieval-vienna.github.io/tree/main/data. 


