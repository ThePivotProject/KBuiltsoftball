 KBuilt - single-file static site
 This folder has ONE file that matters: index.html (everything is inside it - video, photos, all 4 pages).
 Cart + Team Rentals form save to the visitor browser (localStorage) - no server needed.

 DEPLOY - pick ONE (no build, no npm, no folder upload):
 1) Netlify Drop (easiest): go to app.netlify.com/drop, drag index.html onto the page. Done - you get a live link.
 2) Cloudflare Pages: dash.cloudflare.com -> Pages -> Upload assets -> drag index.html.
 3) GitHub Pages single file: create a repo, click Add file -> Upload files, upload ONLY index.html, then Settings -> Pages -> Source: Deploy from a branch, Branch: main, Folder: / (root). Wait 1-2 min.
 4) Any host (GoDaddy, Bluehost, etc.): upload index.html to your public_html / www folder.

 You do NOT need to upload a folder. One file is the whole site.
