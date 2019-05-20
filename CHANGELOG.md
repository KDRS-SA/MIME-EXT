# MIME-EXT CHANGELOG
MIME to File Extention list for archival preservation purposes.
Extension list to be transformed to pdf/a Archival format.

## 2019-05-20 15:15 ##

Updated MIME to EXT (v02): conversion_mapping.cfg
Added upgraded EXT to pdf/a (v01): blob_conversion.properties
Added subfolder "archival" for previous versions of the lists.

### MIME to EXT: conversion_mapping.cfg ###

Added 11 lines (v02)
application/octet-stream : bin
application/vnd.ms-outlook : msg
application/vnd.ms-tnef : tnef
application/vnd.oasis.opendocument.text : odt
application/x-gzip : gz
application/zip : zip
audio/x-mp4a-latm : m4a
image/gif : gif
message/rfc822 : eml
text/troff : troff
text/vcard : vcf

### EXT to pdf/a: blob_conversion.properties ###

Added OpenDocument Text and Spreadsheet (v01)
odt,ods

Original EXT to pdf/a list (v00)
extensions.to.convert=doc,docx,xls,xlsx,ppt,pptx,rtf,bmp,pdf

## 2019-04-23 22:07 ##

### MIME to EXT: conversion_mapping.cfg ###

Added 2 lines; an additional XML and a new RTF (v01)
text/xml : xml
text/rtf : rtf

## 2019-04-22 11:54 ##

### MIME to EXT: conversion_mapping.cfg ###

Initial MIME to EXT list with 16 MIME-types (v00)

application/msword : doc
application/pdf : pdf
application/vnd.ms-excel : xls
application/vnd.ms-powerpoint : ppt
application/vnd.oasis.opendocument.spreadsheet : ods
application/vnd.openxmlformats-officedocument.presentationml.presentation : pptx
application/vnd.openxmlformats-officedocument.spreadsheetml.sheet : xlsx
application/vnd.openxmlformats-officedocument.wordprocessingml.document : docx
application/xml : xml
image/jpeg : jpeg
image/png : png
image/tiff : tiff
image/x-ms-bmp : bmp
text/csv : csv
text/html : html
text/plain : txt
