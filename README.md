# [dark-mode-pdf](https://dark-mode-pdf.portals.sh)

converts PDFs to dark mode

- features::
	- embeds dark or dimmed mode in PDF for export
	- applies balanced-contrast dark mode transform (i.e., not a pure inversion) so it's easier on the eyes
	- customize text to any color by specifying hex/rgb/hsl values
	- add a secondary gradient tone (experimental)
	- retain image colors in dark moded PDF (experimental)
	- OCR scanned documents to add a text layer to the PDF

setting up the python part
```
virtualenv virtual_environment
source virtual_environment/bin/activate
pip3 install -r requirements.txt
```