# PDF Toolkit

**A private PDF toolkit for sensitive documents.**  
Merge and compress visa, immigration, legal, and financial files locally on your computer — no uploads, no account, works offline.

🔗 **Live tool:** [ImanVRAD.github.io/pdf-toolkit](https://ImanVRAD.github.io/pdf-toolkit/)

---

## What it does

| Tool | Description |
|---|---|
| 🗜️ **Compress** | Shrink a PDF so it's easy to email or upload |
| 🔗 **Merge PDFs** | Combine several PDFs into one file — drag to reorder |
| 📷 **Images to PDF** | Convert JPG, PNG, WebP images into a PDF with A4, Letter, or custom sizing |
| ✂️ Split | Coming soon |
| 🔄 Rotate | Coming soon |

---

## Privacy — how it actually works

Most online PDF tools upload your file to a server. This one does not.

- **Everything runs in your browser.** Your files are processed locally using JavaScript — the same language that powers every website you visit.
- **Nothing is sent anywhere.** There is no server receiving your documents.
- **No account, no tracking, no ads.** Ever.
- **Open and auditable.** The entire tool is a single HTML file. Anyone can open it in a text editor and read exactly what it does.

---

## For maximum privacy — use it offline

If you're working with passports, legal documents, financial records, or anything sensitive, use the offline version:

1. Visit the [live tool](https://ImanVRAD.github.io/pdf-toolkit/)
2. Scroll to the **"Want maximum privacy?"** section
3. Click **Download offline version**
4. Open the downloaded `.html` file in any browser — no internet needed, ever

> **Not a virus, not an app.** It's a single `.html` file — the same kind of file that makes every webpage you visit. You can open it in Notepad and read every line yourself. No installation, no system access, no hidden behaviour.

---

## How to use

**Online:** Visit [ImanVRAD.github.io/pdf-toolkit](https://ImanVRAD.github.io/pdf-toolkit/) in any browser.

**Offline:** Download the offline version from the live tool (see above), then double-click the file to open it in your browser. Works with no internet connection.

No installation. No sign-up. Works on Windows, Mac, and Linux.

---

## Technical details

Built as a single self-contained HTML file using:

- [PDF.js](https://mozilla.github.io/pdf.js/) — reads and renders PDF files (by Mozilla)
- [jsPDF](https://github.com/parallax/jsPDF) — creates and packages PDF output

All processing happens inside the browser's JavaScript engine. The offline version bundles both libraries directly into the HTML file so it works with zero network access.

---

## Current version

`v2026-03-20-1`

---

## License

No license applied. Feel free to use for personal or internal use.
