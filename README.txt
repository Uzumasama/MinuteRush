MinuteRush — English mobile-ready prototype
===========================================

Files
-----
- index.html: game home page and all three mini-games
- about.html: About page
- contact.html: Contact page (configure a real email address before launch)
- privacy.html: Privacy Policy
- README.txt: this file

Run locally
-----------
Open index.html in a modern browser. No build tools or external libraries are required.

Publish with GitHub + Cloudflare Pages
--------------------------------------
1. Upload all four HTML/TXT files to the ROOT of your GitHub repository.
2. In Cloudflare Pages, create a project and connect the GitHub repository.
3. For this plain static HTML site, leave the build command empty. If a build output directory is required, use / (the repository root) or the platform's recommended root setting.
4. Deploy and open the public URL to test every page and game.

Before public launch
--------------------
- Replace REPLACE-WITH-YOUR-REAL-EMAIL@example.com in contact.html with a real address you control.
- Review the Privacy Policy and adapt it to any services you actually add.
- Test the website on multiple mobile browsers and screen sizes.
- Add analytics or ads only after reviewing the relevant provider's policies and updating the privacy notice.

Gameplay notes
--------------
- Quick Tap: 60-second tap counter.
- Memory Grid: memorize highlighted tiles, then select each tile once; wrong picks cost one point.
- Number Rush: select five numbers in ascending order; wrong picks cost one point.
- Personal bests and game counts are stored in localStorage on the current browser/device, not in a shared leaderboard.
- The games use client-side JavaScript only. No backend or account is required.

This is a starter project, not a guarantee of hosting availability, advertising approval, or revenue.
