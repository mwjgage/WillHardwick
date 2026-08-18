# Will Hardwick — Author Website

This is a standalone rebuild of willhardwick.com using the real content extracted from your
live Google Sites page — same white-background, click-through-to-detail-page design as the
sample I built earlier, populated with your actual book covers, taglines, blurbs, content
notes, and buy links.

## Files

- `index.html` — homepage grid of all 8 books
- `about-the-author.html` — your bio page
- One page per book: `opening-the-lords-cabinet.html`, `dirty-habits.html`,
  `seven-days-hard-work.html`, `lessons-in-the-greek-style.html`, `special-delivery.html`,
  `conquering-the-roman.html`, `forbidden-trails.html`, `executive-pleasure.html`
- `style.css` — all styling
- `images/` — the 10 covers/photos captured from the live site

## Preview

Double-click `index.html` to open it in your browser — no server needed.

## What's carried over as-is

- All nav links, page titles, and taglines
- Full blurb text for every book, word for word
- Content notes / warnings where the live site had one
- Buy links for the 4 books that had one: Opening the Lord's Cabinet, Special Delivery,
  Conquering the Roman, Forbidden Trails
- The spice-level rating shown on Opening the Lord's Cabinet (the only page that had one)

## Two things worth fixing before this goes live anywhere

1. **Cover typo:** the "Conquering the Roman" cover image itself has "WILL HARDING" printed
   on it instead of "Hardwick." That's baked into the image, so it needs a new export from
   whatever tool generated the cover — I can't edit text inside the image file itself.
2. **Missing buy links:** Dirty Habits, Seven Day's Hard Work, and Lessons in the Greek Style
   don't have a retailer link on the live site, so their pages here say "Not yet available
   from retailers." Send me the URLs whenever they're ready and I'll wire up the buttons.

## Image quality note

The cover images are screenshots taken from the live site (the original Google-hosted files
are session-locked and couldn't be downloaded directly), captured at roughly 305×488px. If you
have the original higher-resolution cover files from wherever they were generated, swap those
into `images/` for a sharper result — just keep the filenames the same, or update the `src`
paths in the HTML.

## Publishing it

Static site, so GitHub Pages, Netlify, or a regular web host all work — happy to help with
that step whenever you're ready to move off Google Sites.
