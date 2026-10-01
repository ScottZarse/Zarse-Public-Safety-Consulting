# CLAUDE.md

## Project
Marketing website for **Zarse Public Safety Consulting, LLC** (CAD, RMS, P25 radio, identity
architecture, network infrastructure consulting). Owner: Scott Zarse, a fire battalion chief and
novice developer who reviews and directs rather than writes code. Explain anything new in plain
language and walk him through steps he must do himself.

## Stack and layout
- Plain static HTML/CSS in a single file: `index.html` (styles inline in `<style>`, design tokens
  as CSS variables in `:root`). No build step, no framework, no dependencies.
- `Zarse_Capability_Statement.pdf` is linked from the page; replace the file, keep the filename.
- Fonts from Google Fonts (Space Grotesk, IBM Plex Sans, IBM Plex Mono).
- Keep it simple: don't introduce a framework or build tooling unless Scott asks.

## Deploy
- GitHub repo: `https://github.com/ScottZarse/Zarse-Public-Safety-Consulting` (branch `main`).
- Hosted on Netlify, which redeploys automatically on every push to `main`. **Pushing to `main`
  changes the live public site**, so check the change locally first and tell Scott what is going live.
- Preview locally by opening `index.html` in a browser (or the Claude browser pane).

## Working style
- Small, clear commits with plain-English messages. Commit and push when Scott says it's ready.
- Don't claim a change looks right until it has been viewed (desktop and phone width).
- No secrets in the repo. Contact details already on the page (email, phone) are intentional.
- This is a separate project from Battalion 10; never mix the two repos.
