LIFTLOG V2 — INSTALL NOTES

This folder is a static Progressive Web App (PWA). To install it as a Home Screen app on iPhone, publish the contents of this folder to an HTTPS web host. The workout data itself is stored in localStorage on the iPhone/browser origin; the host serves the app files and does not receive workout records.

After deployment, open the HTTPS site in Safari on iPhone, tap Share (square with upward arrow), scroll and choose Add to Home Screen, edit the name to LiftLog if desired, then tap Add. Launch from the new Home Screen icon.

Keep using the same deployed URL and same Safari profile to retain the same local workout data. Export JSON backups from the History tab. Clearing Safari website data or changing the app URL can make the old local data inaccessible.
