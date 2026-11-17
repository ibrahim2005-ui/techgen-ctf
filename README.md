# TechGen CTF — Operation Hidden Flag

Mobile-friendly, beginner-level, three-flag cybersecurity classroom game.

## Run
Publish this repository with **GitHub Pages**, from the `main` branch at the root. Visit `https://ibrahim2005-ui.github.io/techgen-ctf/`.

## Challenges
- Source Detective (30 points): open the homepage's View Source helper or HTML source, find the hidden directory.
- Robots Secret (30 points): follow the link to `robots.txt` and visit the training-only path it discloses.
- Change The ID (40 points): visit `profile.html?user=1`, change `user` to `2`, and collect the simulated access-control flag.

The game works on mobile browsers. Scores are stored locally on each device; there is no backend or live leaderboard. Source and flags are public, so it is not a secure exam platform.

## GitHub Pages notes
The homepage uses relative links, and `robots.txt` describes the correct project path `/techgen-ctf/no-bots/`. GitHub Pages project websites are hosted under a subpath rather than the domain root. On the published site, `https://ibrahim2005-ui.github.io/techgen-ctf/robots.txt` must return this file.

GitHub Pages must be enabled in repository Settings > Pages > Deploy from a branch > main / (root).
