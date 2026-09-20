$BIRDDOG landing page
=====================

Static site — no build step. Open index.html in a browser, or upload the whole
folder to any static host (Netlify, Vercel, GitHub Pages, Cloudflare Pages, etc).

Files
  index.html                   the page (all CSS + JS inline)
  assets/birddog.webp          duck head (transparent)
  assets/stonkfun.webp         stonkfun logo (transparent)
  assets/boysclub-birddog.webp Boy's Club #4 page used in the Origin section

Fonts load from Google Fonts (Shrikhand, Rubik, Space Mono) — needs internet.

Launch day
  1. Contract address: in index.html find  id="caAddr"  and add
       data-ca="0xYOUR_CONTRACT_ADDRESS"
     The scramble stops, the real CA shows, and the Copy button unlocks.
  2. X handle: replace every  https://x.com/search?q=%24BIRDDOG  with your
     profile URL (4 places: nav, hero button, X card button).
