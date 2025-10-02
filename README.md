# Link-in-Bio (GitHub Pages)

A minimal, fast, and fully self-hosted link-in-bio site.

## Quick Start
1. **Create a repo** named `USERNAME.github.io` (replace USERNAME).
2. Upload these files to the repo root (or push via git).
3. Go to **Settings → Pages**, set **Source** to `Deploy from a branch`, and choose the `main` branch and `/` (root).
4. Wait a minute and open `https://USERNAME.github.io`.

## Customise
- Edit `index.html`:
  - Replace **Your Name**, bio, and link URLs.
  - Update Open Graph tags (`og:url` and `og:image`) if you have a custom domain/preview.
  - Swap the inline avatar with `<img src="your-photo.jpg" alt="Your Name">` if desired.
- Edit `styles.css` for colours, spacing, and fonts.

## Optional
- **Custom domain**: Add a new file named `CNAME` with just your domain inside (e.g. `links.yourdomain.com`). Then add a `CNAME` DNS record pointing to `USERNAME.github.io`.
- **Analytics**: Add your Plausible/GA script to `index.html`. The page also appends basic UTM tags to outbound links.
- **Favicon/OG Image**: Replace `favicon.svg` and set a proper `og:image` hosted on your domain.
- **No Jekyll**: `.nojekyll` is included so GitHub Pages won't process files.

## Local Preview
Just open `index.html` in your browser. No build step needed.

## Notes
- This works without frameworks; just static HTML/CSS/JS.
- Light/dark mode respects the user's system setting.
- Accessible: keyboard focus states, labelled sections, readable contrast.

Generated on 2025-10-02.
