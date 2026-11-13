EXIT TICKET SYSTEM - iPhone app (PWA)
=====================================
A PWA must be served over HTTPS (it cannot be installed from a file on the phone).
Pick ONE free host, upload everything in this folder:

  A) Netlify Drop (easiest):  go to app.netlify.com/drop, drag this whole folder in.
  B) GitHub Pages:  put the files in a repo, Settings > Pages > deploy from branch.
  C) Cloudflare Pages: Create project > Direct Upload.

Then on the iPhone (use SAFARI, not Chrome):
  1. Open your site's address.
  2. Tap Share > "Add to Home Screen" > Add.
  3. Open it ONCE from the home-screen icon while online (this stores PDF tools and fonts).
  After that it works offline.

Data: stored privately on that iPhone (separate from the Windows app).
  - Sidebar > "Export backup" saves/shares a .json file (Files, AirDrop, email).
  - "Import backup" restores it, on the same or a new device.
  - Please export a backup regularly: deleting the home-screen icon or clearing
    Safari data erases the records.
PDF: "Share PDF" opens the iOS share sheet (Save to Files, AirDrop, Mail, Print).
Updates: when you change files, edit VERSION in sw.js (e.g. ets-v2) and re-upload.
