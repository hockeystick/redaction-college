# Réussir sa rédaction — la méthode en 4 étapes

An interactive, single-file French slideshow that teaches collège students (cycle 3 and cycle 4, ages 11 to 15) the four-step method for writing a *rédaction*: analyse the prompt, build vocabulary, plan and draft the "sandwich", then format and proofread. It is a self-contained learning and revision tool with eight hands-on exercises (consigne highlighting, genre sorting, a timed vocabulary sprint, the sandwich challenge, paragraph comparison, three-pass proofreading, sentence enrichment, and a final quiz), each returning specific feedback rather than a generic "correct". All on-screen text is in French; everything (markup, styles, logic) lives in one `index.html`, and all interactive state is kept in memory only (no storage, no runtime API calls).

## Preview locally

Open `index.html` in any modern browser (double-click it, or run `open index.html`). There is no server, build step, or dependency to install. The only network request is to Google Fonts, and the font stacks fall back to system fonts when offline. Navigate with the on-screen Previous/Next buttons or the ← / → arrow keys.

## Deploy on Vercel

Zero-config static site. Use the **Other** framework preset: no build command, no install step, and the output directory is the repository root, so `index.html` is served directly.
