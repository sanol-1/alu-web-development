# CSS Advanced: Smile School landing page

The styling step of the Smile School landing page. The structure comes from the previous project (`html_advanced`); here everything is done in `styles.css`, with no CSS framework.

![Full page screenshot](images/screenshot.png)

## Objectives

- Turn a designer mockup (Figma) into a pixel-careful web page.
- Center content in fixed-width containers and lay it out with Flexbox.
- Keep the CSS simple: short selectors, shared rules for shared styles.
- Style each section: header and banner, quote, videos list, membership, FAQ and footer.

## Design choices

| Element | Value |
|---|---|
| Main purple | `#552cb7` |
| Dark purple (quote) | `#3d1f8a` |
| Footer | `#2b1466` |
| Light purple (membership) | `#f3edff` |
| Font | Source Sans Pro, falling back to Arial |
| Content width | 960px, centered (1040px for the videos) |

## Sections

| Section | What is styled |
|---|---|
| Header | Logo on the left and 3 white links on the right, in a centered 960px container |
| Banner | Background image, centered `h1`, text and rounded button with shadow, then 4 round-photo teachers |
| Quote | Dark background, round photo on the left, quote on the right, bold name and italic title |
| Videos | Cards with rounded corners and shadow, play icon in the thumbnail, purple author names, stars on the left and duration on the right |
| Membership | Light background, 4 centered items with purple icons, purple rounded button |
| FAQ | 2x2 grid of questions in a centered container |
| Footer | Logo left, 3 social icons right, centered copyright |

## Files

```
css_advanced/
├── README.md
├── index.html
├── styles.css
└── images/   (logo, background, icons and placeholder photos)
```

## How to view it

Open `index.html` in a browser. Once GitHub Pages is on, the page is served from the repository.

## Notes

- The photos and icons in `images/` are placeholders. Replace them with the exports from the Figma file, keeping the same names.
- Colors and sizes were chosen to match the design as closely as possible; fine-tune them against the Figma values if needed.

## Author

Sano ([sanol-1](https://github.com/sanol-1))
