# Tab Curriculum ZIP Sorter — V10.2

Teacher-first curriculum sorter for Tabernacle Sunday School.

## V10.2 focus

- No fixed quarter dates are pre-populated in the UI.
- The sorter finds `Leader Pack Schedule` / `Schedule of Studies` first.
- When possible, it builds the active lesson map from that schedule.
- If the schedule cannot be parsed, it uses an explicit fallback or requires a pasted custom map.
- Output uses `Learner Guide`, not `Student Packet`.
- Output creates action folders: upload to Planning Center, upload to TabReady, optional bundles, archive, and do-not-use files.
- TabReady manifest paths use exact `r2_key` values for per-file upload later.

## Update file

The primary file is `public/index.html`.
