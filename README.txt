# Tab Curriculum ZIP Sorter — V6

A browser-based ZIP sorter for Tabernacle Sunday School curriculum files.

## V6 Fixes

- Skips Mac junk files:
  - `__MACOSX`
  - `.DS_Store`
  - `._` AppleDouble shadow files
- Excludes KJV / KJ / King James resources across PDF and non-PDF files.
- Keeps the Tabernacle-used lanes clear:
  - Adult CSB
  - Senior Adult CSB
  - Spanish
- Preserves useful non-PDF files separately.
- Uses the Spring 2026 map for unit/date/session/title ordering.
- Adds a cleaner `_SORTING REPORT.txt`.

## Current Limitation

The Spring 2026 lesson map is still built in. The next version should support Quarter Map Mode so Summer/Fall/Winter can be added without rewriting the app.

## Deployment

Cloudflare serves files from:

```text
public/
```
