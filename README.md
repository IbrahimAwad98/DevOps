# DevOps

A small Python project that converts CSV to JSON, generates test data, and shows the result in a web page.

## What it does

- `csvtojson.py` reads a CSV file and writes it as JSON.
- `generate.py` creates fake user profiles as test data.
- `index.html` and `script.js` load the JSON and show it in the browser.

`profiles1.csv` is the source data. `data.json` is the converted output.

The project shows basic DevOps ideas: data processing, file conversion, automation, and a clear split between backend (Python) and frontend (HTML/JavaScript).

## Tech stack

- Python, JavaScript, HTML
- CSV and JSON
- No frameworks, plain JavaScript

## Structure

```
DevOps/
├── csvtojson.py                 # CSV to JSON converter
├── generate.py                  # test data generator
├── main.py                      # main script (empty)
├── profiles1.csv                # source data
├── data.json                    # converted data
├── index.html                   # web page
├── script.js                    # loads and shows the data
└── IbrahimAwad-anteckningar.txt # project notes
```
