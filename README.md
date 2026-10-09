# Favorite Movies Website

A small responsive, multi-page HTML/CSS portfolio project showcasing five personal movie picks with ratings, posters, synopses, and cast lists.

## Live demo

https://nitinfavmovies.netlify.app

If the hosted link is unavailable, run the project locally using the steps below.

## Pages

The Netlify publish directory is \`html/\` (configured in \`netlify.toml\`).

- Home: \`html/index.html\`
- F1: \`html/f1.html\`
- Batman Begins: \`html/batman.html\`
- Top Gun: Maverick: \`html/topg.html\`
- Avengers: Endgame: \`html/avengers.html\`
- The Shawshank Redemption: \`html/shawshank.html\`

Movie posters are stored under \`html/images/\`.

## Run locally

From the repository root, start a small static server:

\`\`\`bash
python3 -m http.server 8000
\`\`\`

Then open http://localhost:8000/html/ in your browser. You can also open \`html/index.html\` directly, but using a local server more closely resembles deployment.

## Tech stack

- HTML5 semantic markup
- CSS and responsive layout
- Netlify static hosting

## Current scope

This is a static showcase. Ratings are personal opinions, and there is no database, login, or live movie API. Poster files and relative links must remain inside the \`html/\` directory for the current page structure.

## Future improvements

- Add a shared stylesheet instead of page-specific markup styles
- Add keyboard-visible focus states to all detail pages
- Add a small automated link and image-path check
- Keep poster image rights and attribution in mind before redistributing assets

## Author

Nitin Yalamanchili
