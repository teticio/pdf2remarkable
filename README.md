# PDF2Remarkable

Upload PDFs to the reMarkable Cloud, which is particularly useful on Linux as the official desktop application is not available.

## Installation

```bash
pip install pdf2remarkable
```

## Usage

To upload a PDF to the reMarkable Cloud simply run

```bash
pdf2remarkable "example.pdf"
```

The first time you run this, you will be asked to pair your device. Just follow the instructions and paste your OTC.

## Troubleshooting

* If you have authentication problems with `pdf2remarkable` or want to re-pair your device, delete the `.pdf2remarkable` file in your home directory and run the script again.
