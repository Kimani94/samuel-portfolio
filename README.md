# Samuel Munyua — Portfolio

Personal portfolio site for **Samuel Kimani Munyua**, Senior QA Reviewer & AI Data Quality Specialist (image, video, text, and 3D LiDAR annotation).

**Live site:** add your GitHub Pages URL here once deployed, e.g. `https://<username>.github.io/<repo>/`

## What's in here

A single-page site covering:
- Hero + recruiter snapshot (5+ years, 98% peak accuracy, 25% project completion lift)
- What I Solve (value proposition by problem area)
- Case studies — DDD (LiDAR/AV), Humans in the Loop (training & pilots), CloudFactory (ops & QA), Atlas Capture (LLM/video evaluation)
- Work in Action — real annotation/QA screenshots (client identifiers redacted for NDA compliance)
- How I Work (the quality loop: requirements → annotate → review → correct → validate → deliver)
- Certifications, grouped by relevance
- Tools & technologies
- Full experience timeline
- About, quality philosophy, and contact

## Structure

```
samuel-portfolio-site/
├── index.html          # everything — single-file site (HTML/CSS/JS)
├── assets/
│   └── images/          # profile photo + work-sample screenshots
└── README.md
```

## Deploying to GitHub Pages

1. Create a new GitHub repository (e.g. `portfolio` or `<username>.github.io` for a root-domain site).
2. Push these files to the repository:
   ```
   git init
   git add .
   git commit -m "Initial portfolio"
   git branch -M main
   git remote add origin https://github.com/<username>/<repo>.git
   git push -u origin main
   ```
3. In the repo, go to **Settings → Pages**, set the source to the `main` branch, root folder.
4. Your site will be live at `https://<username>.github.io/<repo>/` within a few minutes.

## Updating content

Everything is in `index.html` — text content is in plain HTML in each `<section>`, styles are in the `<style>` block at the top, and the point-cloud hero animation is in the `<script>` block at the bottom. No build step required — edit and push.

## Contact

- Email: samuelkymani@gmail.com
- Phone: +254 701 008 165
- LinkedIn: linkedin.com/in/samuel-munyua-966ba9a4
