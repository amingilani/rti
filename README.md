# RTI data

This is a repository of RTI requests, responses, appeals and the information I've received through them.

Personal information is redacted, and text has been processed through OCR software where applicable.

## Submit Your Own :star:

If you've made an RTI request under Pakistani law, I urge you to submit it for publication here. Please email scanned copies of all letters exchanged, and any public information yielded, to [rti@gilani.me](mailto:rti@gilani.me?subject=RTI%20request%20%2B%20public%20information%20submission&body=Hi%20Amin%0A%0APlease%20find%20attached%20raw%20and%20high%20resolution%20scanned%20copies%20of%20my%20correspondence%20with%20the%20public%20information%20officer%2C%20along%20with%20the%20public%20information%20yielded.%0A%0APlease%20redact%20my%20personal%20information%20before%20publishing%20this.). I'll redact any personal information before publishing.


## Requests

Each request is filed by a unique ID and has 3 types of files:

+ Request: All correspondence exchanged with the public information officer
+ Appeal: All correspondence with the Information Commission if an appeal was filed
+ Information: If information is received

### 9449

PTA's Class Licensing and Registration Regulations, 2007 as amended up to 4 April 2016.  

**Status:** Information received

### 9449

The Gazette of Pakistan, requested from the Department of Stationary and Forms.

**Status:** Appeal successful, awaiting information

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
