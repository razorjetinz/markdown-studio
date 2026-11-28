# SimBizz Markdown Studio

A lightweight, browser-based Markdown editor and reader owned and maintained by **SimBizz Services**. Create Markdown documents, edit with a live preview, open existing files, and export your work in common formats.

> **Free to use, not open source:** Anyone may use the unmodified application without a licence fee. Modification and derivative works are not permitted. The source is publicly viewable, but the software remains proprietary to SimBizz Services.

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
4. When deployment completes, open [SimBizz Markdown Studio](https://simbizz-services.github.io/markdown-studio/).

No build step is required.

## About SimBizz

SimBizz Services develops and maintains Markdown Studio as a browser-based tool for working with Markdown documents. The application stores documents locally in the user's browser and does not upload document content to a server.

## License and ownership

SimBizz Markdown Studio is distributed under the **SimBizz Free Use License**.

- Everyone may download, install, run, and use the unmodified application without a licence fee, including for commercial purposes.
- Modifying, adapting, or creating derivative versions of the application is not permitted.
- SimBizz branding and all copyright and ownership notices must remain intact.
- All ownership of the application, source code, design, and included assets remains with **SimBizz Services**.
- Documents you create with the application remain your property.

This is a custom proprietary licence, not an OSI-approved open-source licence. Public source-code visibility does not grant modification rights. Read [LICENSE](LICENSE) for the complete terms.

---

© 2026 SimBizz Services.
