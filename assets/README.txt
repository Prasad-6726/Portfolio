Place your CV PDF in this folder with the filename `Prasad_S_Kumbhar.pdf`.

The site expects the file at: assets/Prasad_S_Kumbhar.pdf

If you prefer to host your CV elsewhere (Google Drive, Dropbox, etc.), update the `externalFallback` variable in index.html near the bottom of the file to point to your public CV URL.

Notes:
- For the browser to trigger a download using the `download` attribute, the file must be served from the same origin.
- If testing locally by opening index.html directly (file://), some browsers may block the download attribute -- use a local dev server (e.g., `npx http-server` or `python -m http.server`) to test.
