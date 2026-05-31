# 🃏 Memory Card Builder

A browser-based tool to create printable memory card sheets (6×6 cm) with cut lines.

Upload your images, arrange the order, adjust card size and spacing, then print directly or save as PDF — each card gets a dashed cut line for easy scissor trimming.

## 🚀 Live Site

**[cschaf.github.io/memory-card-builder](https://cschaf.github.io/memory-card-builder/)**

## ✂️ Features

- **Multi-image upload** — select multiple images at once (JPEG, PNG, WebP)
- **Drag-free reordering** — move images up/down or delete them
- **Customizable layout** — card size, gap between cards, and page margin
- **Dashed cut lines** — toggle on/off, 2 mm inside each card edge
- **Auto-pagination** — 8 cards per A4 page (2 columns × 4 rows), new pages added automatically
- **Print / PDF export** — Ctrl+P → "Save as PDF" → set scale to "Actual size" (100 %)
- **HTML download** — save the entire tool for offline use

## 🖨️ Printing Tips

1. Adjust card size and spacing to your preference
2. Press **Ctrl+P** (Windows) or **Cmd+P** (Mac)
3. Set scale to **"Actual size"** / **100 %**
4. Choose **"Save as PDF"** or print directly
5. Cut along the dashed lines with scissors or a paper cutter

## 📦 Offline Use

Click **"💾 HTML-Datei herunterladen"** to save a self-contained HTML file — works offline in any browser.

## 🔧 Development

```bash
# Serve locally
npx serve .
# Or just open index.html in your browser
```

### Auto-deploy

Pushes to `main` trigger a GitHub Actions workflow that deploys to `gh-pages` via [peaceiris/actions-gh-pages](https://github.com/peaceiris/actions-gh-pages).

## 📄 License

MIT — see [LICENSE](LICENSE)
