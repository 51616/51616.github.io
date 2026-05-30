# Design System Document: Hacker News Research Index

## 1. Overview & Creative North Star

**Creative North Star: Fast research index.** The site should feel like a compact Hacker News page adapted for a personal academic archive: dense, link-rich, text-first, and quick to scan. It keeps the existing archival-paper attitude, but replaces the large editorial hero with a narrow utility document.

The main traits are an orange top bar, small utilitarian type, warm paper surfaces, blue links, black 1px strokes, dotted row separators, square thumbnails, and minimal chrome. The page should look like a fast hand-maintained index, not a portfolio template.

Reference artifact from the Codex design pass:

- `/tmp/pi-work/codex-image-gen/hn-personal-site/hn-academic-homepage-mockup.png`
- `/tmp/pi-work/codex-image-gen/hn-personal-site/DESIGN.md`

## 2. Colors & Surface Logic

- **Background:** `#f6f6ef`, a Hacker News-like paper field.
- **Surface:** `#fffaf0`, the main document sheet.
- **Muted surface:** `#f4f1e8`, used for footers, tags, and utility controls.
- **Ink:** `#000000`, used for text and hard borders.
- **Primary orange:** `#ff6600`, reserved for the top bar and compact emphasis badges.
- **Links:** `#0033aa`; visited links may use `#551a8b`; hover moves to orange.
- **Rules:** `#b8b3a7`, used for dotted separators and thumbnail borders.

Use solid colors only. Do not use gradients, glass effects, soft shadows, or rounded cards.

## 3. Typography

Use `Verdana, Arial, Helvetica, sans-serif` for the base UI. Use `Courier New, Courier, monospace` only for metadata such as dates, venues, labels, and tiny archive notes.

Keep the type compact: body around `13px`, metadata around `11px`, section titles around `15px`, and the name/title no larger than a modest page heading. Hierarchy should come from order, bold text, compact rules, and link density rather than display typography.

## 4. Layout

The page is a centered document with max width around `1100px`, a 1px black outline, and an orange header attached to the same width. The home page order is fixed:

1. about
2. selected publications with small thumbnails
3. talks/news
4. service
5. work experience
6. education
7. awards
8. earlier projects

Use compact rows instead of large cards. Publications use a fixed small thumbnail and dense text. Lower CV-style sections use two-column label/content rows where space allows and collapse to one column on narrow screens.

## 5. Components

### Header

Orange bar, black text, compact links separated by `|`. It should wrap on small screens rather than hide links behind a menu.

### Links and Buttons

Links are direct and visible. Buttons are small square controls with a 1px black border; primary buttons use orange fill. No pill shapes.

### Publication Rows

Each publication row has a small square thumbnail, venue/date metadata, blue title link, author line, and compact action links. Separate rows with a dotted rule.

### CV Lists

Use compact two-column rows: metadata/date on the left and content on the right. Separate entries with dotted rules.

### Project Grid

Earlier projects may use a two-column bordered grid, with small square thumbnails and direct links.

## 6. Do's and Don'ts

### Do

- Keep the page dense and fast to scan.
- Make links obvious and plentiful.
- Use real dates, venues, and compact metadata.
- Preserve square corners and hard 1px borders.
- Keep images functional, small, and aligned.

### Don't

- Do not use oversized hero marketing layout.
- Do not use glossy cards, gradients, soft shadows, rounded corners, or app chrome.
- Do not hide desktop navigation behind a menu.
- Do not introduce a JavaScript framework for this design.
