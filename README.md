# Game Outside — website

The public site for the Game Outside app: a landing page and the privacy policy
that the App Store listing links to.

Served by GitHub Pages from `main`. Plain static HTML with no build step, because
the App Store needs the privacy URL to resolve reliably and forever, and a build
pipeline is one more thing that can be broken when someone edits a paragraph.

- `index.html` — landing page
- `privacy/index.html` — privacy policy, linked from App Store Connect

The app itself lives in the private `game-outside` repo.
