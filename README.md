# Google Colab Pdf OCR
![](banner.png)

Add OCR to your PDF books and documents easily using Google Colab , this will help you search text content or copy text form PDFs made from scanned images.

## How to use:
1. Open the notebook in Google Colab [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mossaybo/colab-book-ocr/blob/main/Colab_Book_OCR.ipynb)

1. Set variables in the first Cell
	* make sure `original_pdf` matches the pdf's file name.
	* set correct `lang_code` (ara = Arabic, eng = English , jpn = Japanese, ..etc ) more codes [here](https://tinyurl.com/tesslangcodes)
	* (optional) you can set first and last pages to ocr only a range/ chapter ..etc
1. Upload the pdf or uncomment `# !wget` in the second cell and set the correct url. `wget` will make sure to set the correct name to the PDF when downloaded .
1. DONE ! Run all cells  `Runtime > Run all` or run them cell by cell without skipping .

## Features
* Easy setup.
* Basic Error checking .
* Shows Progress.

## Credit:
[Google Colab](https://colab.research.google.com)
[Tesseract](https://github.com/tesseract-ocr/tesseract)

