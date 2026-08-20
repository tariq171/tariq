# Personal Website — Tariq

Quick instructions to preview the site locally.

Preview options:

- Python 3 (if available):
```bash
py -3 -m http.server 8000
# or
python -m http.server 8000
```
Open http://localhost:8000 in your browser.

- VS Code: install and use the Live Server extension, then click "Go Live" on `index.html`.

- Node (no install):
```bash
npx http-server -p 8000
```

Notes:
- Favicon added: `favicon.svg` is linked from each page head.
- If `python` is not on PATH, use the `py` launcher or the VS Code Live Server.
