TOPOFORGE WEBSITE v0.7
=======================

Change from v0.6
----------------
- Removed the GoatCounter embedded visitor-counter rendering that could show
  an Error 403 / embedded page in the footer.
- Visitor count is now read from GoatCounter's public .json counter endpoint.
- Footer displays only plain text, for example:
    Visitors: 1
- GoatCounter count.js remains in place for normal page tracking.
- Contact email, use-case section, FormSubmit request flow, and thanks page
  are unchanged.

GoatCounter setting required
----------------------------
Keep this enabled:
  Allow adding visitor counts on your website

UPLOAD TO GITHUB
----------------
Replace/upload these files in the repository root:
  index.html
  styles.css

thanks.html does not need to change for this visitor-counter fix.

Then wait for GitHub Pages to redeploy and reload:
  https://tomi546258-dev.github.io/topoforge-web/

Use Ctrl+F5 if the old version is cached.
