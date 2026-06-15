# Mobaco Landing Page

A static English landing page for Mobaco World, focused on Patreon-powered alpha testing.

## Files

- `index.html` - page structure and English copy
- `styles.css` - complete responsive visual design
- `script.js` - small header/year enhancement
- `assets/mobaco-hero.png` - generated hero artwork
- `assets/mobaco-world-header.jpg` - optimized hero/header artwork used on the live page
- `assets/mobaco-world-header.png` - original source version of the header artwork
- `assets/screenshots/` - compressed gameplay screenshots used throughout the page

## Deploy on Cloudflare Pages

1. Create a GitHub repository and add these files.
2. In Cloudflare, go to `Workers & Pages`.
3. Choose `Create application` and then `Pages`.
4. Connect the GitHub repository.
5. Use these settings:
   - Framework preset: `None`
   - Build command: leave empty
   - Build output directory: `/`
6. Deploy.
7. Add your custom domain in the Pages project settings.

## Things to customize

- Patreon alpha links point to `https://www.patreon.com/cw/cgmasterclass`.
- Replace `hello@mobacoworld.com` with your real contact address when available.
- Replace the FAQ answers once the alpha rules and sharing policy are final.
- Replace or add files in `assets/screenshots/` when newer gameplay screenshots are available.
