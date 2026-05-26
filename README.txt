# Tab Curriculum ZIP Sorter — V10.6

V10.6 keeps the V10.3/V10.4 map-first curriculum sorter and chooses the most automatic Word-to-PDF path available on a Mac.

When curriculum Word files are found, the output includes `06 - NEEDS PDF CONVERSION BEFORE FINAL UPLOAD` with:

- `00 - AUTO CONVERT WORD DOCS TO PDF.command` — tries LibreOffice first, then Microsoft Word AppleScript.
- `01 - INSTALL LIBREOFFICE WITH HOMEBREW.command` — optional helper if Homebrew is already installed.
- A README explaining PDFelement as a manual fallback.

Important limitation: a browser/Cloudflare Worker cannot directly convert old Microsoft Word `.doc` files into PDFs. The most automatic safe workflow is Mac-side conversion, then rerun the sorter with the converted PDFs included.

Recommended workflow:
1. Run sorter.
2. If `06 - NEEDS PDF CONVERSION BEFORE FINAL UPLOAD` appears, double-click `00 - AUTO CONVERT WORD DOCS TO PDF.command`.
3. Re-zip the original curriculum files plus `CONVERTED_PDFS`.
4. Rerun sorter.
5. Upload/import only when the report shows the required audience lanes are packet-ready.


V10.6 simplification: removes Mac command-file automation from the output and uses a plain PDFelement conversion workflow. Word files are placed in `06 - NEEDS PDF CONVERSION BEFORE FINAL UPLOAD` with clear instructions. Convert them to PDF, add those PDFs back to the curriculum package, and rerun the sorter.
