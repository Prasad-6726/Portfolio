# Modern Portfolio — CV Download Instructions

This project includes a "Download CV" button in `index.html` that attempts to download a local file `assets/Prasad_S_Kumbhar.pdf`.

Steps to enable download locally:

1. Place your CV PDF at: `assets/Prasad_S_Kumbhar.pdf` (create the `assets/` folder if it doesn't exist).
2. Open the site using a local web server (recommended) rather than double-clicking the file. Examples:

   - Using Node (http-server):

     ```powershell
     npx http-server -c-1 . -p 8080
     ```

   - Using Python 3:

     ```powershell
     python -m http.server 8080
     ```

3. Visit `http://localhost:8080` in your browser and click "Download CV".

Notes:
- If the local file is missing, the site will automatically switch the button to an external fallback URL. Replace the placeholder `externalFallback` URL in `index.html` with your public CV link (Google Drive, Dropbox, etc.).
- The `download` attribute works best when the file is served from the same origin.

If you'd like, I can:
- Add an example `Prasad_S_Kumbhar.pdf` placeholder (small sample) into `assets/`.
- Replace the external fallback with an actual URL you provide.
