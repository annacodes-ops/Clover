CLOVER v0.5 — starter PWA bundle

WHAT'S INCLUDED
- index.html: the app
- manifest.webmanifest: installable app metadata
- sw.js: basic offline cache
- clover-icon.svg: app icon

RUN LOCALLY
Open index.html in a modern browser. First launch asks for five missions.
The browser-only version stores mission names and progress locally on that device.
Photo proof is selected in memory in this prototype; it is not synced or uploaded.
The profile name is local-only and is NOT a real login. Do not enter passwords.

SHARE WITH FRIENDS
Best free route: publish this folder as a static website with GitHub Pages.
1. Create a GitHub repository named clover (public).
2. Upload all four files from this folder to the repository root.
3. In repository Settings > Pages, choose Deploy from a branch, select main and /(root), then Save.
4. Wait for the published HTTPS link, then share it. Friends can open the link.
Each person's browser keeps its own separate local progress.

INSTALL ON ANDROID
1. Open the published HTTPS link in Chrome on Android.
2. Open Chrome's three-dot menu.
3. Tap Install app or Add to Home screen (wording varies).
This installs the PWA as an app-like shortcut. It is not yet a native Android widget/APK.

REAL LOGIN / CLOUD SYNC
A proper account system needs a backend such as Supabase Auth or Firebase Authentication,
plus a database and secure access rules. Do not store passwords in localStorage.
For a first public test, skip login and keep each friend's data local to their own browser.
