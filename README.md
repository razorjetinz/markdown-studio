# InfiOffice Markdown Studio

A lightweight, browser-based Markdown editor and reader. Create Markdown documents, edit with a live preview, open existing files, and export standard `.md` files.

## Features

- Create and manage multiple Markdown documents
- Open `.md`, `.markdown`, `.mdown`, `.mkd`, and `.txt` files
- Live Markdown preview with headings, emphasis, links, lists, checklists, blockquotes, code blocks, and tables
- Clean reading mode
- Formatting toolbar and keyboard shortcuts (`Ctrl/⌘+S`, `Ctrl/⌘+O`, `Ctrl/⌘+B`, `Ctrl/⌘+I`)
- Export documents as standard Markdown files
- Drag and drop Markdown or text files
- Browser-local autosave and recent document list
- Responsive desktop, tablet, and mobile layout
- Installable/offline-capable PWA when served over HTTPS
- No account, server, analytics, build tools, or external JavaScript dependencies

## Use locally

Open `index.html` in a modern browser. For service-worker and PWA support, serve the project over HTTP:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Storage and privacy

Documents are stored in the browser's `localStorage` on the device and browser profile where the app is used. They are not synchronised between devices or uploaded to a server. Clearing browser site data can remove locally stored documents. Use **Export .md** to keep independent copies.

## GitHub Pages

1. Open **Settings → Pages** in this repository.
2. Under **Build and deployment**, set **Source** to **GitHub Actions** and save.
3. Open the **Actions** tab and run **Deploy Markdown Studio to GitHub Pages**, or push another commit to `main`.
4. When deployment completes, open [Markdown Studio](https://razorjetinz.github.io/markdown-studio/).

The workflow deploys the static site from the repository root. No build step is required.

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE).

---

Made by [InfiOffice](https://infioffice.com).
