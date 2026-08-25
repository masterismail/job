# Resume PDF compiler

This private repository is the free LaTeX compiler for the Google Sheets job
tracker. Apps Script commits `build/resume.tex` and `build/request.json`. The
workflow compiles the document and commits a versioned PDF under `pdf/`.

Keep this repository private because generated resume source and PDFs contain
personal information.

The workflow requires repository Actions to have read/write workflow
permissions. In GitHub, open **Settings → Actions → General → Workflow
permissions**, choose **Read and write permissions**, and save.
