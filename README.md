# 🔗 Ultimate Link Extractor & Sequential Opener

A powerful and easy-to-use web-based tool to **extract, manage, filter, and open multiple URLs** — sequentially or in bulk. Built entirely with HTML, CSS, and JavaScript, it supports importing from web pages, pasted content, and various file formats like PDF, DOCX, and HTML.

---

## 🌟 Features

- ✅ **Multiple Link Input Options:**
  - `Fetch from URL`: Crawl a webpage and extract all hyperlinks (CORS proxy used).
  - `Paste HTML`: Parse raw HTML content to extract `<a>` tag links.
  - `Paste URLs`: Input plain URLs directly (newline, space, or comma-separated).
  - `Import File`: Supports `.txt`, `.html`, `.pdf`, `.doc`, `.docx`, `.rtf`.

- 🧠 **Smart Link Handling:**
  - Auto-detects and deduplicates URLs.
  - Supports relative URL resolution using base URLs.
  - In-browser preview with indexing and optional filtering.

- ⚡ **One-Click Actions:**
  - Open **all links sequentially** with customizable delay.
  - Open links within a selected **range**.
  - **Remove** individual links or **clear** the entire list.

- 🌙 **Dark Mode** support (with persistent preference via `localStorage`).

---

## 📦 Technologies Used

- HTML5, CSS3, Vanilla JavaScript
- [PDF.js](https://mozilla.github.io/pdf.js/) – Extracts text and links from PDFs
- [docs-to-text](https://www.npmjs.com/package/docs-to-text) – Converts DOCX/DOC to plain text for link extraction
- CORS Proxy (`https://corsproxy.io/?`) for remote page access

---

## 📁 File Support

| Format     | Description                    |
|------------|--------------------------------|
| `.txt`     | Raw list of links              |
| `.html`    | Parses all anchor tags         |
| `.pdf`     | Extracts URLs using PDF.js     |
| `.doc`, `.docx` | Uses docs-to-text library      |
| `.rtf`     | Basic plain text parser        |

---

## 🚀 Getting Started

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/ultimate-link-opener.git
   cd ultimate-link-opener
