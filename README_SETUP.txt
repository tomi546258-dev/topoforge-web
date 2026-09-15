TOPOFORGE FPGA WEBSITE v0.8.5
=======================

Changes from v0.8.4
----------------
- The FormSubmit return address now points to the actual GitHub Pages project
  path, so a successful request opens thanks.html instead of a GitHub 404 page.
- Canonical, social, sitemap and form-source URLs now consistently use the
  /topoforge-web/ project path.

GoatCounter setting required
----------------------------
Keep this enabled:
  Allow adding visitor counts on your website

UPLOAD TO GITHUB
----------------
Replace/upload these files in the repository root:
  index.html
  styles.css
  README.md
  README_SETUP.txt
  FORM_SETUP.txt
  TopoForge_Evaluation_Request_Kit_0_1_TXT.zip
  SHA256SUMS.txt

thanks.html also changes in this revision and must be uploaded.

Then wait for GitHub Pages to redeploy and reload:
  https://tomi546258-dev.github.io/topoforge-web/

In Microsoft Edge use Ctrl+Shift+R for a hard reload. The public GoatCounter
result may be cached by the service for up to four hours.
