# WebSetu Review Helpers — GitHub Pages

Account: Shubham18112001
Site after setup: https://shubham18112001.github.io/

## Upload once
1. GitHub > + (top right) > New repository
2. Repository name: Shubham18112001.github.io
3. Public, Add a README file, Create repository
4. Add file > Upload files > upload ALL files from this folder
5. Settings > Pages > Build and deployment > Branch: main, Folder: / (root) > Save
6. Wait 1-2 minutes, then open https://shubham18112001.github.io/

## Files
- index.html — list of helpers
- sunrise-review.html — Sunrise Coaching Center, already filled with its Google review link
- card01.html to card05.html — blank reusable cards (SHOP_NAME / REVIEW_LINK not set yet)
- review-helper-template.html — master template, copy it for card06 onwards

## Assign a card to a new client
1. Open the card file on GitHub, click the pencil icon (Edit this file).
2. Change ONLY these two lines near the top of the script:
   var SHOP_NAME = '...';
   var REVIEW_LINK = 'https://g.page/...';
3. Commit changes. No reprint, no NFC rewrite needed — the card's QR/NFC already points at this page.
4. Test the page on a phone that has NOT had its DNS changed.

## NFC / QR link to write on the card
- Sunrise: https://shubham18112001.github.io/sunrise-review.html
- Card 01: https://shubham18112001.github.io/card01.html
- Card 02: https://shubham18112001.github.io/card02.html
(and so on — replace the file name only)
