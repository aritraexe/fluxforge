[README.md](https://github.com/user-attachments/files/34651846/README.md)
# FluxForge

Free, private file tools that run entirely in the browser. No uploads, no accounts, no tracking.

- **PDF:** merge, split, compress, PDF to images, images to PDF, organize, page numbers, watermark, PDF to text, Word to HTML/text, Markdown and HTML, text to PDF, spreadsheet converter, JSON/YAML
- **Images:** compress, upscale, remove background, resize, crop, rotate, convert, HTML to image, watermark, blur face
- **Audio and video:** convert, extract, trim, merge, speed/volume/fades, recorder, video to GIF, trim, compress, mute, capture frame, screen recorder
- **Utilities:** QR codes, unit converter, text tools, password generator

## Deploy on GitHub Pages

1. Create a repository and upload `index.html` and this README.
2. Open **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
3. Your site appears at `https://<username>.github.io/<repository>/`.

No build step is needed. It is a single static file.

## Notes

- Libraries load from cdnjs and jsDelivr at pinned versions: pdf-lib, pdf.js, JSZip, qrcode-generator, mammoth, marked, turndown, SheetJS, js-yaml and lamejs.
- Replace the placeholder logo: search `index.html` for `LOGO:` and swap the inline SVG for your own.
- Video trim, compress and mute are re-recorded in real time in the browser.
- Microphone and screen recording need HTTPS (GitHub Pages provides it) and browser permission.
