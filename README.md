# The Reading Room

A personal reading tracker with a dark academia aesthetic and modern glassmorphism design. Built as a single HTML file with zero dependencies.

**[Live Demo](https://luxilla8.github.io/reading-room/)**

## Features

- **Track your reading** — Add books, update page progress, and add notes as you go
- **Mark complete** — Rate books (1-5 stars) and write a brief reflection
- **Mark DNF** — Record why you set a book down, guilt-free
- **Reading stats** — Books and pages per month/year, average finish time, completion rate
- **Persistent storage** — All data saved to localStorage (no account needed)
- **Sample library** — Ships with 6 curated books so you can explore the interface immediately

## Design

- Dark academia color palette with warm ivory text on deep black-brown
- Glassmorphic cards with `backdrop-filter` blur and luminous borders
- Unsplash library background photo with slow Ken Burns drift animation
- Floating ambient particles (gold and ivory dust motes)
- Staggered card entrance animations with spring easing
- Rotating literary quotes from Borges, Gaiman, Cicero, Harper Lee, and more
- Typography: Playfair Display (headings) + Cormorant Garamond (body)
- Fully responsive down to mobile

## Tech

- Single `index.html` file — no build step, no frameworks, no dependencies
- Vanilla HTML, CSS, and JavaScript
- localStorage for data persistence
- Google Fonts loaded via `<link>` tags
- Background image from [Unsplash](https://unsplash.com)

## Usage

Open `index.html` in any modern browser. That's it.

Or visit the [live demo](https://luxilla8.github.io/reading-room/) hosted on GitHub Pages.

## How GitHub Pages Works

This site is hosted for free using [GitHub Pages](https://pages.github.com/). Here's what's happening:

1. **Source**: GitHub Pages serves the contents of the `main` branch at the `/` root
2. **URL pattern**: Your repo at `github.com/<user>/<repo>` becomes `<user>.github.io/<repo>/`
3. **index.html**: Pages looks for an `index.html` file and serves it as the homepage
4. **Automatic deploys**: Every push to `main` triggers a rebuild — changes go live in ~60 seconds
5. **Free HTTPS**: GitHub provides SSL certificates automatically

To set up Pages on your own repo: **Settings > Pages > Source > Deploy from a branch > `main` / `/ (root)`**

## License

MIT
