# Marine Mavericks '19 — Personality of the Day Form

A static HTML form that emails every submission to **isaacben484@gmail.com**.

## Files
- `index.html` — the form itself.

## How it works
The form is wired to [Formspree](https://formspree.io), a free service that forwards form submissions to your email — no server or backend needed. Each field has a labelled `name`, so responses arrive clearly organised, and photo uploads are included.

## Setup (one-time, ~2 minutes)

1. Go to [formspree.io](https://formspree.io) and sign up using **isaacben484@gmail.com**.
2. Click **New Form**, name it (e.g. "Marine Mavericks"), and set the recipient email to **isaacben484@gmail.com**.
3. Formspree gives you an endpoint like `https://formspree.io/f/abcdwxyz`. Copy the ID part (the `abcdwxyz`).
4. Open `index.html`, find this line, and replace `YOUR_FORM_ID` with your ID:

   ```html
   <form action="https://formspree.io/f/YOUR_FORM_ID" method="POST" enctype="multipart/form-data">
   ```

5. Save the file. Done.

## Going live
Upload `index.html` to any web host so people can fill it out. Free options:
- **GitHub Pages** — push the file to a repo, enable Pages in settings.
- **Netlify** — drag and drop the file at [netlify.com](https://netlify.com).
- **Vercel** — deploy from a folder or repo.

## First submission
Formspree sends a one-time confirmation email to **isaacben484@gmail.com** after the very first submission. Click the link in that email to activate forwarding — after that, every response lands in the inbox automatically.

## Limits & alternatives
- Formspree's free tier allows **50 submissions/month**.
- For unlimited free responses, a **Google Apps Script** version can be set up instead — ask if you'd like that.

## Fields collected
Full Name, Nickname, Date of Birth, Instagram Handle, Favourite Lecturer, Favourite Department, Faculty Crush, Most Traumatic Level, Best Level, If Not Fisheries Then What, Favourite Course Mates, Parting Words, Favourite Quote, and Photo upload.

---
*CATCH KNOWLEDGE. CULTIVATE FUTURE.*
