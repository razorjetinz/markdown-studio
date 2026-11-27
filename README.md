# InfiOffice Markdown Studio

A lightweight, browser-based Markdown editor and reader. Create Markdown documents, edit with a live preview, open existing files, and export your work in common formats.

## Features

- Create and manage multiple Markdown documents
- Open `.md`, `.markdown`, `.mdown`, `.mkd`, and `.txt` files
- Live Markdown preview with headings, emphasis, links, lists, checklists, blockquotes, code blocks, and tables
- Five colour themes: Midnight, Light, Ocean, Forest, and Lavender
- Full-width, distraction-free reading mode
- Export Markdown, Word (`.docx`), HTML, and plain text
- Print to paper or save as PDF through the browser's print dialog
- Formatting toolbar and keyboard shortcuts (`Ctrl/⌘+S`, `Ctrl/⌘+O`, `Ctrl/⌘+B`, `Ctrl/⌘+I`)
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

Documents and theme preferences are stored in the browser's `localStorage` on the device and browser profile where the app is used. They are not synchronised between devices or uploaded to a server. Clearing browser site data can remove locally stored documents. Use **Export** to keep independent copies.

## Export formats

- **PDF:** Select PDF to open the browser print dialog, then choose **Save as PDF**.
- **Word:** Select Word (`.docx`) to download a Microsoft Word-compatible document.
- **HTML:** Download a standalone HTML document.
- **Plain text:** Download the rendered document as `.txt`.
- **Markdown:** Use the Markdown export button to download the original `.md` content.

## GitHub Pages

1. Open **Settings → Pages** in this repository.
2. Under **Build and deployment**, set **Source** to **GitHub Actions** and save.
3. The included workflow deploys automatically whenever changes are pushed to `main`.
4. When deployment completes, open [Markdown Studio](https://razorjetinz.github.io/markdown-studio/).

No build step is required.

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE).

---

Made by [InfiOffice](https://infioffice.com).
