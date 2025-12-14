```markdown
# Tristan Rader — 90s Athletic Static Site

This repository contains a simple multi-page static site styled in a 1990s athletic theme. It's designed to be hosted on GitHub Pages or any static file host.

Included files:
- index.html — Home (hero, CTA)
- about.html — Biography
- issues.html — Platform and priorities
- events.html — Events table
- donate.html — Donate guidance and link
- contact.html — Contact / volunteer form (Formspree example)
- styles.css — Theme and layout

Quick preview
- Open `index.html` locally in your browser to preview.

Exact steps to publish (copy & paste these commands)
1. Create a GitHub repository (example: twrader/rader).
2. On your computer, in the project folder:
   - git init
   - git add .
   - git commit -m "Initial retro athletic site for Tristan Rader"
   - git branch -M main
   - git remote add origin git@github.com:<your-github-username>/<repo-name>.git
   - git push -u origin main

3. Enable GitHub Pages:
   - Go to the repository on GitHub → Settings → Pages.
   - Under "Source" choose branch: main, folder: / (root). Save.
   - Wait a few minutes; your site will be live at https://<your-github-username>.github.io/<repo-name>/ (or at your custom domain if configured).

What you must update BEFORE going live
1. Replace placeholder text:
   - Treasurer: replace [TREASURER NAME — UPDATE] in all pages.
   - Contact email: confirm the email in contact.html (mailto:info@tristanrader.com).
2. Donate link:
   - Replace the donate button URL in donate.html with the campaign’s secure processor (ActBlue, WinRed, Stripe, etc.).
3. Form endpoint:
   - If you want contact form submissions, sign up for Formspree (or Netlify Forms) and replace the form action URL in contact.html.
4. Social links:
   - Replace the placeholders for Twitter/Facebook in index.html footer.
5. Events:
   - Update events in events.html or embed a live calendar.

Optional but recommended
- Add a CNAME file if you want TristanRader.com to point to GitHub Pages (see GitHub docs).
- Add a privacy policy / cookies notice if you enable analytics or donation tracking.
- Add a small analytics snippet (Plausible or Matomo recommended for privacy).
- Consult campaign counsel to verify compliance language for donations/disclaimer.

Need help?
- If you want, I can:
  - Create the GitHub repo and push these files (I’ll need the repo owner/name and permission).
  - Replace placeholders (treasurer, email, donate URL) — provide the exact text or URLs.
  - Embed a donation widget (give me the processor and widget snippet).
  - Convert your full blog / archived pages into this theme.

```