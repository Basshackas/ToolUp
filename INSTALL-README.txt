TOOLUP - INSTALL ON YOUR PHONE

Why this is needed: Android only lets a web app be installed when it is opened from a web address that starts with https://.
A file opened from your phone's storage cannot be installed. This kit lets you put the app on a free web address once.
The app has NO data in it. Your purchases and sales stay on each phone. Putting the app online does not put your data online.

EASIEST WAY (about 3 minutes, free):
1. On a computer, open  https://app.netlify.com/drop
2. Drag this whole "toolup-install-kit" folder onto the page.
3. After a few seconds you get a web address. Open it in Chrome on your phone.
4. In Chrome tap the menu (the three dots) and choose "Install app" (or "Add to Home screen"). The ToolUp icon appears on your home screen.
5. Open ToolUp from the home screen. Set your PIN and Access Code.
6. In the app: gear icon > Export, Backup, Import > Import from Excel, and choose your workbook.

Other free places that work the same way: GitHub Pages, Cloudflare Pages.
Keep the folder together: index.html, manifest.webmanifest, sw.js and the three icon files must stay in the same place.

NOTES
- The app works offline after the first time it opens. Excel import/export needs internet once to download its helper library, then it is remembered.
- The installed app and a file opened from storage keep their data separately. To move data between them, use Save locked backup file and Restore.
- Anyone who has your web address can open the empty app, but cannot see your data. Your data is only on your phone, behind your PIN.
