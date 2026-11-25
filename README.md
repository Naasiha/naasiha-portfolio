# Naasiha Nazar – Marketing Portfolio

A one-file portfolio website. Everything (pages, images, fonts, CV PDF) is inside `index.html`.

## Publish with Claude Code

Open this folder in Claude Code and say:

> Put this folder on my GitHub repository Naasiha/naasiha-portfolio (it already exists and is empty), then deploy it to Vercel as a static site and give me the live link.

What Claude Code will do:
1. `git init`, add `index.html` and `README.md`, commit, and push to `https://github.com/Naasiha/naasiha-portfolio` (branch `main`). You may be asked to sign in to GitHub in your browser.
2. Deploy to Vercel, either by importing the GitHub repository at vercel.com/new or with the Vercel CLI (`npx vercel --prod`). You may be asked to sign in to Vercel.
3. No build step and no framework are needed: Vercel serves `index.html` as it is.

## Updating the site later

Replace `index.html` with the new version, then ask Claude Code to commit and push. Vercel redeploys automatically.
