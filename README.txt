MY HOME LIBRARY — VERSION 1

Files:
- index.html: the app
- manifest.webmanifest: Android home-screen app settings
- sw.js: offline caching

IMPORTANT:
The app stores books and cover images in the browser's local database on the device.
Use the Backup button regularly. The backup JSON includes the book records and cover images.

TO TRY IT:
1. Upload these files to a static HTTPS host (for example, a private GitHub Pages repository/site or another static web host).
2. Open the HTTPS address in Chrome on your Android phone.
3. In Chrome, open the three-dot menu and choose "Add to Home screen" or "Install app".
4. Open the app from its new home-screen icon.

The app does not currently sync between devices. Restoring a backup merges its books into the current collection.
Barcode/ISBN lookup is reserved for a later version.
