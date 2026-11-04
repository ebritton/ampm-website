# ampm-website
AMPM Mcgill Music Union

## Languages

- `index.html`: English (Canada), the default landing page.
- `fr.html`: French (Quebec / Canada).
- `styles.css`: the shared design for both pages.

Use the English / Français links in the header to switch languages. Both pages
are plain HTML and work with JavaScript disabled, including under a GitHub Pages
project path. Each page includes language metadata, translated accessibility
labels, and links to the alternate language.

When updating content, edit the matching section in both HTML files. Keep section
IDs the same in each language. The existing AMPM logo is retained; the French
association name in the page copy is a translation of the English name.

## Local preview

From this directory, run `python -m http.server 8000`, then open
`http://localhost:8000` or `http://localhost:8000/fr.html`.

Resource links and the contact email remain placeholders from the original site.
Replace them in both languages when the official documents and address are ready.
