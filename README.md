# India Hospitals: What Must Be True (Mindful Finance), revised edition

Static, zero-build site. One self-contained `index.html` (CSS, JS and model data inlined).

## Deploy
- Dashboard: vercel.com/new, drag this folder in. Framework preset **Other**, no build command, no output directory.
- CLI: `npm i -g vercel`, then `cd vercel-site && vercel --prod`.

## Notes
- Fonts (Inter, Manrope) load from Google Fonts with system-font fallbacks.
- Model data is inlined in `index.html` (search `const D=`). It comes from India_Hospitals_Financial_Model_Revised.xlsx.
- Deep-link to a slide with `/#2` (slide number). 15 slides.
- Educational research only. Not investment advice.
