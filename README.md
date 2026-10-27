# The Media I Live Through

A React + Vite presentation adapted from Vitria’s *Personal Media Ecology_FINAL.pdf*.

## Run locally

```sh
npm install
npm run dev
```

## Production

```sh
npm run build
npm run preview
```

17 slides, arrow-key / Space navigation, Home and End shortcuts, touch swipes, slide overview (G), fullscreen, deep links, and reduced-motion support. On small screens, slide content scrolls vertically.

Content lives in `src/main.jsx`; design and animation in `src/styles.css`. Diagrams use CSS/SVG, with original PDF platform logos and an AI-generated forest background. Fonts fall back to installed fonts when Google Fonts is unavailable. Bibliographic details are reproduced from the supplied PDF, not independently verified. Device totals are records, not exclusive elapsed time.

## Visual assets

Platform logos in `public/logos/` are extracted from page 6 of the supplied PDF, including the unlabeled blue infinity icon (kept as `source-platform.png` without assuming its brand).

The built-in image generation tool created `public/images/forest-greenery.png`. Prompt: “Use case: photorealistic-natural. Asset type: 16:9 background for an elegant academic React slide presentation about personal media ecology. Create a beautiful real-looking lush green forest with delicate ferns, moss, tall soft-focus trees, gentle morning light and natural atmospheric mist. Composition: foliage concentrated along the right edge and lower corners, left two thirds mostly luminous pale warm ivory mist with very subtle distant greenery, generous quiet negative space for dark text. Muted sage and olive greens, editorial photography, refined peaceful atmosphere, softly diffused light. No text, no logos, no people, no devices, no watermarks. Landscape wide image.”

## PDF-faithful revision

The six “Behind my devices” views now reproduce the source’s cumulative structure: original device image, ten platform logos, companies/platform power, data/transactions, technical infrastructure, and social/institutional environment. Each new ring preserves all inner rings. The expanded diagram provides a scrollable large-format view; Escape closes it.

`public/images/pdf/` contains visual extracts from the supplied PDF: the Nam June Paik installation, four screen-time captures, original devices, role tree, forest/feed collage, connected ecology illustration, media wall and circuit tree. Credits supplied in the PDF are retained on the presentation. The decision slide restores the four source pathways (travel, fashion/shopping, food/skincare, donation/help).
