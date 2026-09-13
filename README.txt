Karnataka Govt Exam — Master Study Tracker
Final PWA package

Files are wired for the same folder/root deployment:
- index.html        Main offline study tracker
- manifest.json     PWA manifest
- sw.js             Offline service worker
- study.png         Original supplied artwork
- icons/icon-192.png
- icons/icon-512.png

Deploy the complete folder to the root of a HTTPS site (for example GitHub Pages).
The app is local/private: study progress is stored in the browser's local storage/IndexedDB by the app and is not sent to a server.

For PWABuilder, enter the deployed root URL, for example:
https://girish1209.github.io/DP/

Do not rename or separate the files after deployment unless you also update the relative paths in index.html, manifest.json, and sw.js.
