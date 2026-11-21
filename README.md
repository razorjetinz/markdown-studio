# InfiOffice Markdown Studio

A lightweight, browser-based Markdown editor and reader. Create Markdown documents, edit with a live preview, open existing files, and export standard `.md` files.

## Features

- Create and manage multiple Markdown documents
- Open `.md`, `.markdown`, `.mdown`, `.mkd`, and `.txt` files
- Live Markdown preview and clean reading mode
- Formatting toolbar for headings, emphasis, links, lists, checklists, quotes, code, and dividers
- Export documents as Markdown (`Ctrl+S` / `⌘S`)
- Keyboard shortcuts: `Ctrl+O` to open, `Ctrl+B` for bold, and `Ctrl+I` for italic
- Drag and drop Markdown or text files
- Automatic browser-local saving and recent document list
- Responsive desktop, tablet, and mobile layout
- Installable PWA with offline support when served over HTTPS
- No account, server, analytics, or external JavaScript dependencies

## Run locally

No build tools or package installation are required.

1. Clone or download this repository.
2. Open `index.html` in a modern browser.
3. Start writing.

For service-worker and PWA support, serve the folder over HTTP:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Storage and privacy

Documents are stored in the browser's `localStorage` on the device and browser profile where the app is used. They are not synchronised between devices or uploaded to a server. Clearing browser site data can remove locally stored documents. Use **Export .md** to keep independent copies.

## Deploy with GitHub Pages

1. Open **Settings → Pages** in this repository.
2. Under **Build and deployment**, select **Deploy from a branch**.
3. Select branch **main** and folder **/(root)**, then save.
4. After deployment completes, open [Markdown Studio](https://razorjetinz.github.io/markdown-studio/).

The app is static and requires no build step.

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE).

---

Made by [InfiOffice](https://infioffice.com).
