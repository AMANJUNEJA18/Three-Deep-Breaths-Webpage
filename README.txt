Three Deep Breaths — Homepage STATIC FINAL

Deploy ONLY:
- index.html

This is the intentionally simple homepage build.

IMPORTANT:
- Do NOT deploy sw.js from any previous homepage cache-fix package.
- This package contains no service worker.
- The one-time unregister code removes any previously installed homepage
  service worker from the visitor's browser.
- After this release, the homepage remains a plain static HTML page.

Homepage:
https://threedeepbreaths.in/

App:
https://app.threedeepbreaths.in/


NIGHT UPDATE
- Three Deep Breaths doorway remains unchanged.
- Added a second quiet Night doorway to https://app.threedeepbreaths.in/night
- Existing homepage service-worker unregister logic remains unchanged.
- Deploy index.html and keep the existing CNAME.
