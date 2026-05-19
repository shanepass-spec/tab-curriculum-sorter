# Tab Curriculum ZIP Sorter — Version 4

Audience-first curriculum ZIP sorter for Lifeway-style Sunday School resources.

## What V4 does

- Upload one curriculum ZIP
- Scan all filenames inside the ZIP
- Sort into teacher/student-friendly folders
- Prioritize audience first:
  - Adult
  - Senior Adult
  - Spanish
- Then organize by:
  - Unit
  - Chronological lesson order
  - Session/title
  - Resource type
- Generate a new organized ZIP
- Include `_SORTING REPORT.txt`

## Important assumptions

- Adult and Senior Adult are CSB only.
- Spanish resources are Spanish only.
- Do not label anything King James / KJV.
- If a file cannot be confidently sorted, it goes to `Unknown - Review`.

## Deployment

Replace these files in GitHub:

- `public/index.html`
- `wrangler.jsonc`
- `README.md`

Cloudflare will auto-deploy.
