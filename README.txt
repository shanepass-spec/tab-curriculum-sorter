# Tab Curriculum ZIP Sorter — V9.2

Stable V8 sorter plus TabReady import package generation.

## V9.2 Fix

V9.1 failed when excluded or non-PDF files were copied into the output ZIP. This version reads those files as Blobs before adding them to the generated ZIP.

## Output

- Sorted curriculum folders
- Teacher Packet.pdf files
- TABREADY_IMPORT/manifest.json
- TABREADY_IMPORT/curriculum/{quarter_id}/{audience}/session PDFs
- Clean report by default
