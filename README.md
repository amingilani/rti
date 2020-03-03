# RTI data

This is a repository of raw RTI requests, responses, appeals and the information I've received through them.

Personal information is redacted, and text has been scanned through OCR.

## Requests

Each request is marked by a unique ID.

### 9449

PTA's Class Licensing and Registration Regulations, 2007 as amended up to 4 April 2016

### 9449

The Gazette of Pakistan, requested from the Department of Stationary and Forms.

## Tools

 - [Tesseract](https://github.com/tesseract-ocr/) for OCR
 - [Imagemagick](https://imagemagick.org/index.php) for image manipulation

To compile a set of JPEG images into a single TIFF image use:

```
convert *.jpeg request.tiff
```

To convert a TIFF file into a searchable PDF file and with an additional TXT containing text use:

```
tesseract -l eng request.tiff request txt pdf
```
