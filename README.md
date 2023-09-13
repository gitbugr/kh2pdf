# kh2pdf (KOReader Highlights 2 PDF)

Saves KOReader highlights to PDF file. (For that time you forgot to save the highlights to the PDF).

## Requirements

* python3
* pip3

## Installation

```
git clone <this repo> <dest>
cd <dest>
pip install -r requirements.txt
```

## Usage

### Basic Usage

`./kh2pdf <pdf_location>`

### Help

```
    ./kh2pdf -h
    usage: kh2pdf [-h] [-m METADATA_FILE] file

    kh2pdf (KOReader Highlights to PDF) reads KOReader metadata files, extracts highlights and saves them to the PDF.

    positional arguments:
    file The PDF file KOReader has highlights for.

    options:
    -h, --help show this help message and exit
    -m METADATA_FILE, --metadata-file METADATA_FILE
    The metadata file KOReader stores annotations in.
```

### License

MIT
