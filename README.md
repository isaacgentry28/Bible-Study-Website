Want a Bible Study — static site

Quick start

1. Clone the repo:

   git clone <your-repo-url>
   cd "Website project for Wade"

2. Preview locally (Python HTTP server):

   python3 -m http.server 8000
   # then open http://localhost:8000 in your browser

Access from your phone

- Ensure your phone is on the same Wi‑Fi network.
- Start the server above, find your Mac's LAN IP (e.g., 192.168.1.12) and open http://<MAC_IP>:8000 on your phone.

Notes and recommendations

- Filenames: avoid spaces and uppercase in web assets. Consider renaming `images/Bible Image.jpg` to `images/bible-logo.jpg` and update the src in `index.html`.
- To publish publicly, you can enable GitHub Pages from the repository settings and select the `main` branch (or `gh-pages` if you prefer). For a simple static site, the repository root is fine.
- If you add build tooling (npm, bundlers), keep those artifacts out of version control (see .gitignore).

License

Add a license file if you want to publish this project publicly (e.g., MIT, CC-BY-SA).
