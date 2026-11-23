# v1r3s.github.io 🌸

My personal link page, live at **[v1r3s.github.io](https://v1r3s.github.io)**.
One place for all my socials, plus my latest YouTube video, updated automatically.

## Features
- 🔗 Links to YouTube, TikTok, Instagram, X, Twitch and GitHub
- ▶️ **Auto-updating "latest video" card**: a GitHub Action checks my YouTube feed every 6 hours and updates the page
- 🎨 Custom scrapbook design: blurred banner background, falling petal animation, press-down buttons
- 📱 Responsive: built mobile-first, works on any screen
- ♿ Respects "reduced motion" settings

## How it works
| File | What it does |
|---|---|
| `index.html` | The whole page: HTML, CSS and JavaScript in one file |
| `bg.png`, `avatar.png` | Background banner and profile picture |
| `latest.json` | My newest video ID, written by the GitHub Action |
| `.github/workflows/latest-video.yml` | The Action: reads my channel's RSS feed and commits `latest.json` when there's a new video |

The page reads `latest.json` on load and shows the matching thumbnail and link.

## Built with
HTML · CSS · JavaScript · GitHub Pages · GitHub Actions · Python

## Run it locally
Clone the repo and open `index.html` in a browser. That's it, no build step.

---
Made with ♡ by [Khaled Alkhawaldeh](https://github.com/V1R3S) (v1r3s)
