# Breezy Video - releases

Windows video toolbox: stitch, convert & compress, trim, rotate & crop, stabilise, enhance (AI),
subtitles, subject tracking, organise, pipelines and watch folders.

This repository only holds the releases:

- **Installer** for Windows (per user, no administrator rights needed): see the newest file in
  [`installers/`](installers/). It isn't code-signed, so Windows SmartScreen may warn - choose
  *More info → Run anyway*. The first start sets up Python, the AI engine and FFmpeg (a few minutes).
- **Updates**: Breezy reads [`latest.json`](latest.json) once a day and offers the new version; the
  download in [`updates/`](updates/) is checked against its SHA-256 before it's installed.
