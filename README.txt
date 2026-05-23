# Tab Curriculum ZIP Sorter — V10.1

Teacher-first curriculum sorter for Tabernacle Sunday School curriculum.

## V10.1 focus

- Detects the quarter master file: `Leader Pack Schedule`, `Schedule of Studies`, scope/sequence files.
- Copies that schedule to `00 - START HERE - Quarter Overview`.
- Inserts the schedule page at the front of every generated Teacher Packet, Learner Guide, and monthly bundle.
- Produces shallow upload lanes:
  - `01 - UPLOAD TO PLANNING CENTER`
  - `02 - UPLOAD TO TABREADY`
  - `03 - OPTIONAL MONTHLY BUNDLES`
  - `04 - DO NOT UPLOAD - Archive and Extras`
  - `05 - DO NOT USE AT TAB`
- Uses sortable filenames such as:
  - `01 - JUN 07 - Meeting Needs - Adult CSB - Teacher Packet.pdf`
  - `01 - JUN 07 - Meeting Needs - Adult CSB - Learner Guide.pdf`
- Generates `TABREADY_IMPORT/manifest.json` where each `file_path` matches its `r2_key`.

## Deploy

Replace these files in GitHub:

- `public/index.html`
- `README.md`
- `wrangler.jsonc`

Then let Cloudflare redeploy.
