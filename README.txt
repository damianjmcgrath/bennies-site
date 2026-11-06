BENNIES WEBSITE REDESIGN — 6 NOVEMBER 2026

Deploy the CONTENTS of this folder to the root of your existing website hosting / GitHub Pages repository. Do not upload the folder itself one level deeper.

Files: index.html, styles.css, privacy.html, terms.html, delete-account.html, email-confirmed.html, Download/index.html, assets/ plus the future download template.

IMPORTANT: The supplied ZIP of site files contained GitHub webpage HTML rather than actual raw HTML. I recovered the real site source and kept the original legal text and deletion JavaScript. The new styling is shared across all pages.

Do not replace your domain's CNAME or DNS settings. If your website uses GitHub Pages, retain its existing CNAME file.

The Download page currently has NO store links, because the app is still in testing. Update Download/index.html using the template only after both public store listing URLs are known; replace placeholders with real verified links and approved badge assets.

After deploy test: /, /Download/, /privacy.html, /terms.html, /delete-account.html, /email-confirmed.html. Test account deletion verification on a test account before relying on it, and confirm the Supabase redirect URL is still allowed.

Local preview: from inside this folder run python -m http.server 8000 and open http://localhost:8000/ . Root-relative links require web hosting, not opening individual HTML files directly.

No build tools, external fonts, or JavaScript frameworks are required for the redesigned public pages. The existing Supabase JS is preserved only for the deletion functionality.
