# The Career Adventure Map

A one-page interactive illustrated career map, ready for GitHub Pages. No frameworks, build step, tracking, or external packages required.

## Publish

1. Create a public GitHub repository (e.g. `career-adventure-map`).
2. Upload `index.html` and `career-map.png` to the repository root.
3. In repository **Settings → Pages**, choose **Deploy from a branch**, `main`, `/ (root)`, then save.
4. Your site will appear at `https://YOUR-USERNAME.github.io/career-adventure-map/` after GitHub Pages deploys it.
5. Put the resulting link in your LinkedIn post. LinkedIn supports linking to the live page rather than embedding its JavaScript directly in a post.

## Customize

- Edit the `towns` object inside `index.html` to revise descriptions and accomplishments.
- The LinkedIn links in `index.html` now point to `https://www.linkedin.com/in/dpjgreen/` — update them only if your profile URL changes.
- Adjust each `.hotspot` button's `left` and `top` percentages to move the clickable towns.
- Keep `career-map.png` beside `index.html`.

## Features

- Clickable career towns with an accessible details panel
- Desktop and mobile layouts
- Scroll to zoom, drag to pan, + / − / Fit controls
- Guided tour of seven stops (six career towns + next adventure)
- No hosting service needed beyond GitHub Pages

The accompanying illustration remains unchanged.


## Included CTA update

The **Next Adventure** panel now includes a stronger invitation: **Help build my next town**. This is meant to make the experience feel less like a résumé and more like an invitation to start a conversation.
