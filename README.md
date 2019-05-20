# MIME-EXT
MIME to File Extention list for archival preservation purposes.
Extension list to be transformed to pdf/a Archival format.

## 1. MIME to Extension list ##

Colon-seperated file
Columns: MIME - EXT
Filename: conversion_mapping.cfg

Excel spreadsheet with additional columns
Columns: MIME - EXT - TO_PDFA - NEW - DESCRIPTION
TAB MIME: Sorted by MIME
TAB EXT: Sorted by EXT
Filename: conversion_mapping_extended.xlsx

MIME: MIME Type shortname as commonly used by file-detector tools
EXT: File Extension
TO_PDFA: To be transformed to pdf/a (by default section 2. below)
NEW: Newly added to the list (not in previos version)
NAME: Full name of the MIME Filetype

## 2. Extension list for pfd/a transformation ##

Comma-seperated file
Lists all extensions to be transformed to pdfa/a archival format.
Filename: blob_conversion.properties

## 3. Archive folder ##

The subfolder "archive" holds the archived versions of the MIM to Extension and pdf/a transformation lists.
