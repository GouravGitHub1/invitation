# Akshay & Priyal — Wedding Invitation

A polished, mobile-first static wedding invitation built with plain HTML, CSS and JavaScript.

## Included

- Minimal Indian floral visual style
- Responsive mobile and desktop layout
- Intro loading animation
- Scroll-reveal animations
- Floating petals
- Gentle floral/parallax movement
- Scroll progress indicator
- Mobile navigation
- Animated countdown to 26 January 2027
- Haldi, Sangeet and Wedding sections
- Venue section with Google Maps link
- Accessibility support for reduced-motion users
- No framework and no backend

## Files

- `index.html`
- `styles.css`
- `script.js`

## Add your couple photo

In `index.html`, find the `<img>` inside `.photo-inner`.

Couple photo is configured at:

```html
<img src="./new_image.jpeg" alt="Akshay and Priyal">
```

Recommended image:
- Portrait orientation
- Around 1000–1600px wide
- JPG or WebP
- Keep the file reasonably compressed for fast mobile loading

## Venue

The "View Location" button opens Google Maps for:

Harsh Resort, Bhilwara (https://maps.app.goo.gl/npdphEhvf1tN3DoR8)

## Run locally

Open `index.html` directly, or use:

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## GitHub Pages

1. Create a GitHub repository.
2. Upload all files and the `assets` folder.
3. Go to Settings → Pages.
4. Choose "Deploy from a branch".
5. Select your main branch and the root folder.
6. Save.

Because this is a static website, GitHub Pages can host it for free.

## Important

The site intentionally does not show event times because the wedding details supplied so far only include dates. Add the times later if you want them displayed.
