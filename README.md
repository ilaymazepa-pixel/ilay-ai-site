# ILAY AI public site

Static landing page and GitHub Pages workflow. The installer is uploaded as a GitHub Release asset (not a Pages asset) because it exceeds the Pages per-file size limit.

Before publishing, run `node work/build-public-site.mjs` from the project root with `GITHUB_OWNER` and `PUBLIC_SITE_URL` set to the final repository and Pages URL. Then create a public repository named `ilay-ai-site`, push this directory's contents to `main`, enable Pages via GitHub Actions, and create release `v0.1.0` with `ILAY-AI-Setup-0.1.0.exe` attached.
