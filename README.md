# Elspeth Taylor Coaching — website code

A static, multi-page website. No build step, no framework. Just open or host the files.

## Files
- `index.html` — Home
- `life.html`, `sport.html`, `work.html` — the three ways in (Work includes Women in Flux)
- `how-i-coach.html`, `ways-to-work.html`, `about.html`, `lets-talk.html`
- `privacy.html`, `terms.html` — legal placeholders (replace the placeholder text)
- `styles.css` — all styling (brand palette, type, layout)
- `script.js` — mobile menu, active-nav highlight, scroll reveal

## Preview locally
Open `index.html` in a browser. (If links behave oddly from a file path, run a tiny local server: `python3 -m http.server` in this folder, then visit `http://localhost:8000`.)

## Host it
Drag this folder onto Netlify, Vercel, Cloudflare Pages or GitHub Pages. Point your domain at it. Done.

## Images
The pages now reference real `<img>` tags. Create a folder called `images` inside this `site` folder and save your photos with these exact names (lowercase, no spaces):

- `hero-ridge-walk.jpg` — Home hero
- `home-reflection-mug.jpg` — Home, Life door
- `home-racket-movement.jpg` — Home, Sport door
- `home-notebook-ideas.jpg` — Home, Work door
- `home-elspeth-outdoors.jpg` — Home, About teaser
- `sport-court-kit.jpg` — Sport page
- `about-elspeth-portrait.jpg` — About portrait
- `about-lakes-reset.jpg` — About, outdoors

Before uploading: resize so the longest edge is ~2000px and compress (squoosh.app) to under ~300KB each. Prefer `.webp` if you can export it (then update the file extensions in the HTML). Until the files exist, each slot shows a warm taupe block rather than a broken icon.

## What still needs doing
1. **Photography.** Save the eight images above into the `images` folder. Keep the `alt` text already written into each `<img>`.
2. **The ET. logo.** The mark is set in type as a stand-in. Drop in the finished logo artwork when you have it.
3. **The enquiry form.** It's front-end only. Connect it to an email service (Formspree, Netlify Forms, etc.) via the `<form action>`.
4. **Booking.** The "Book a discovery call" button is a placeholder — link it to your scheduler (Calendly, etc.).
5. **Legal.** Fill in `privacy.html` and `terms.html`.
6. **Fonts.** Loads Inter Tight + Newsreader from Google Fonts. Swap for the licensed display face from the brief if you buy one.

## Colours
Ivory `#F4F0E6` · Deep olive `#3E463D` · Copper `#A84227` · Burnt orange `#D76A27` · Ochre `#D9A02E` · Warm taupe `#A2947D`
