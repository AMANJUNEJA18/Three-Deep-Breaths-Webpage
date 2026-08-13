Three Deep Breaths — Homepage Cache Fix

Deploy the contents of this ZIP to the existing homepage repository for:
https://threedeepbreaths.in/

The visual homepage is unchanged.

This adds a service worker specifically to prevent stale homepage HTML:
- HTML/navigation is always network-first.
- updateViaCache is disabled.
- the service worker is versioned.
- old service-worker caches are removed.
- the new worker activates immediately.
- the page reloads once when the new worker takes control.

Future homepage deployments should therefore fetch the newest index.html
without requiring Private Browsing or repeated manual cache clearing.

Do not deploy this package to the app repository.
