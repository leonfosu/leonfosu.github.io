# leonfosu.github.io

Personal portfolio: engineering projects & finance case studies.

## Structure

```
index.html              homepage
style.css               shared styling
projects/
  volex-lbo.html        Volex plc IC case study page
assets/
  pdfs/                  PDF exports (embedded inline on project pages)
```


1. Copy `projects/volex-lbo.html` and rename it (e.g. `dcf-valuation.html`).
2. Update the title, summary bullets, and the `<iframe>` src to point at the new PDF.
3. Drop the PDF export into `assets/pdfs/`.
4. Add a card for it in `index.html` under the `#projects` section, and change its
   `tag` from `soon` to `live` once the page is ready.

## Notes

- `volex-ic-memo-sample.pdf` is a placeholder — replace it with the real IC memo
  exported to PDF once it's finished. Everything else stays the same.
- To add Excel/PowerPoint downloads, drop the files under `assets/` and add a link
  in the `.downloads` block on the project page.
