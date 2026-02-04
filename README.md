# DevOps

Ett Python-baserat projekt för CSV-till-JSON-konvertering och datagenerering med webbvisualisering. Projektet innehåller verktyg för att generera testdata, konvertera mellan dataformat och presentera resultaten i en webbgränssnitt.

## Beskrivning

Detta är ett DevOps-utbildningsprojekt som demonstrerar databehandling och visualisering med Python och webbteknik. Projektet fokuserar på att automatisera konvertering av CSV-data till JSON-format samt generera syntetisk testdata för utvecklings- och testningsändamål.

Projektet består av tre huvudkomponenter: Ett Python-skript (csvtojson.py) som läser CSV-filer och konverterar dem till JSON-format, ett datageneratorskript (generate.py) som skapar syntetiska användarprofiler eller testdata, och ett webbgränssnitt (index.html + script.js) som visualiserar den konverterade datan i en användarvänlig form.

CSV-filen (profiles1.csv) innehåller strukturerad data som konverteras till JSON-formatet (data.json) för enklare integration med webbtjänster och moderna applikationer. Webbgränssnittet använder JavaScript för att dynamiskt ladda och presentera JSON-datan i webbläsaren.

Projektet illustrerar grundläggande DevOps-koncept som databehandling, filkonvertering, automatisering och separation av backend (Python) och frontend (HTML/JavaScript) komponenter. Det fungerar som en praktisk demonstration av hur olika verktyg och teknologier kan kombineras i en modern utvecklingsmiljö.

## Funktioner

- CSV-till-JSON konvertering
- Generering av syntetisk testdata (användarprofiler)
- Webbvisualisering av JSON-data
- Databehandling med Python
- Stöd för stora datamängder (433KB JSON-data)
- Enkel webbgränssnitt för datapresentation

## Teknikstack

- Språk: Python, JavaScript, HTML
- Backend: Python-skript för databehandling
- Frontend: HTML/JavaScript för visualisering
- Dataformat: CSV, JSON
- Inga externa ramverk (vanilla JavaScript)

## Projektstruktur

```
DevOps/
├── csvtojson.py                 # CSV-till-JSON konverteringsskript
├── generate.py                  # Datageneratorskript
├── main.py                      # Huvudskript (tom fil)
├── profiles1.csv                # Källdata i CSV-format (107KB)
├── data.json                    # Konverterad JSON-data (433KB)
├── index.html                   # Webbgränssnitt
├── script.js                    # JavaScript för datavisualisering
└── IbrahimAwad-anteckningar.txt # Projektanteckningar
