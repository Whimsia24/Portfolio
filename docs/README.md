# Portfolio Website

This is a static HTML/CSS portfolio website. No build tools or package installs are required.

## Requirements

- A web browser (Chrome, Edge, Firefox, or Safari)
- Optional: VS Code with the Live Server extension
- Optional: Node.js (for an alternative local server)

## Run Option 1: Open directly in browser (fastest)

1. Go to the project folder.
2. Double-click `index.html`.
3. The site will open in your default browser.

Notes:
- This works for most static pages.
- If browser security blocks some local file behavior, use Option 2 or 3.

## Run Option 2: Use VS Code Live Server (recommended)

1. Open this folder in VS Code.
2. Install extension: **Live Server** (by Ritwick Dey).
3. Right-click `index.html` and choose **Open with Live Server**.
4. Your browser will open automatically with a local URL.

## Run Option 3: Run a local server with Node.js (optional)

From the project root folder, run:

```powershell
npx serve . -l 5500
```

Then open:

- http://localhost:5500/

To stop the server, press `Ctrl + C` in the terminal.

## Project Entry Points

- Main page: `index.html`
- Additional pages are in the `pages/` folder.

## Troubleshooting

- If links do not work when opening directly, use VS Code Live Server.
- If port 5500 is in use, run:

```powershell
npx serve . -l 8080
```

Then open http://localhost:8080/
