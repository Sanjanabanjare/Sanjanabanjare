# Publish — Sanjana Banjare GitHub Profile README

## What this is

A burgundy-themed upgrade for your **existing** profile repository — the public
repo named exactly `Sanjanabanjare` (github.com/Sanjanabanjare). Light rich
colour version: ivory-blush background (#FFF9F6 / #FDECEF), deep burgundy
#701A3D, rose #C77B9B and a gold accent #C9A227.

Do **not** create a duplicate repository. This folder is the content to copy
into that repo.

## Files in this folder

- `README.md` — the new profile README (interactive / 3D-style version)
- `assets/sanjana-hero-3d.svg` — animated 3D hero banner (floating isometric cubes)
- `assets/sanjana-hero.svg` — earlier light hero banner (kept as a spare)
- `assets/sanjana-footer.svg` — minimal animated footer
- `.github/workflows/profile-3d.yml` — generates the 3D contribution graph
- `.github/workflows/snake.yml` — generates the contribution snake
- `PUBLISH.md` — this file

## How to publish with GitHub Desktop

1. Open GitHub Desktop and open your local clone of the `Sanjanabanjare`
   repository. If it is not cloned yet, clone `https://github.com/Sanjanabanjare/Sanjanabanjare.git`.
2. Copy `README.md`, the whole `assets/` folder and the whole `.github/`
   folder from this folder into the root of that repository, replacing the
   old `README.md`. Do not copy `PUBLISH.md` into the repo.
3. In GitHub Desktop, inspect every changed file. Confirm no phone number,
   token or secret was added.
4. Commit with the message `Upgrade profile README`, then **Push origin**.
5. Open https://github.com/Sanjanabanjare and check the README, hero and
   stats cards render as expected.
6. **Activate the 3D graph and snake:** open the repo on GitHub, go to
   **Actions**, run **Generate 3D Contribution Graph** and **Generate
   Snake** once, wait for them to finish, then refresh your profile.
   They generate `profile-3d-contrib/profile-season-animate.svg` and the
   snake on the `output` branch — they do not appear instantly on push.

## Honest note about "interactive 3D" on GitHub

GitHub sanitises README HTML and does not run JavaScript or custom CSS,
so a profile README cannot have a real interactive 3D scene. This version
does the closest GitHub allows, in the same style as the reference profile
you sent: an animated 3D-style SVG hero, a typing animation, live stats
cards, pinned repo cards, a 3D contribution graph and a contribution snake
— all generated from your real GitHub data. No content was copied from
the reference profile (Joshua Thadi / MASTERJUDAH): his ASP.NET, .NET,
Data Science and other details are not yours, so none of them appear
here. Only the layout idea was used, with your verified details.

## Preview before publishing

- GitHub preview: after pushing to a branch, open the README on github.com
  and use Preview — that is the only reliable preview, because GitHub
  sanitises some SVG animation.
- Local check: open `assets/sanjana-hero.svg` directly in a browser to see
  the animation. The design is made to look good as a static image too,
  if GitHub restricts motion.

## What was verified — and what was NOT used

Verified against your uploaded CV (`sanjana_cv.pdf`) and your live GitHub
profile on 2026-11-10:

- Name: **Sanjana Banjare**, GitHub **Sanjanabanjare**, LinkedIn
  `in/sanjana-banjare`, location Bilaspur, Chhattisgarh
- Education: B.Tech CSE, Lovely Professional University, CGPA 7.09;
  Intermediate 70%; Matriculation 97%
- Projects: **GymPro** — https://github.com/Sanjanabanjare/gympro and
  **Indisky** — https://github.com/Sanjanabanjare/indisky (both live repos)
- Achievements: Top 3 College Hackathon, Nov 2024 (200+ participants);
  AWS & AI Skill Development, May 2025
- Internships and all six certificates as listed in the README

**Important — the reference guide was for a different person.** The pasted
guide named Sri Sushmita Dasari, B.Tech AI/ML at Aditya Engineering College,
CGPA 9.10, Flipkart GRiD 7.0 and Myntra WeForShe HackerRamp 2026. None of
that appears in this README, because it does not match your CV. Only the
burgundy design, layout and structure from the guide were used.

## Privacy check

- Your phone number does **not** appear in any file here.
- No API token or secret is included.
- Your email and LinkedIn are included because they are on your CV and
  public GitHub profile. Remove the email badge / line from `README.md`
  if you would rather not show it publicly.

## If a stats card breaks

The stats, streak and activity graph are live images from external
services using your real username `Sanjanabanjare`. If one fails to load,
delete that image line from `README.md` — do not replace it with
invented numbers.
