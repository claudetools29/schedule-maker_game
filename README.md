<p align="center"><img src="logo.svg" alt="Schedule Quest logo" width="110"></p>

<h1 align="center">Schedule Quest</h1>

<p align="center">A daily schedule maker that turns your day into a game.<br>Plan a printable poster, then tick tasks to earn points, level up, unlock badges and spend your points on rewards.</p>

<p align="center"><img src="docs/quest.png" alt="Schedule Quest with the checklist, points and level" width="860"></p>

**No build step, no dependencies, no server.** The whole app is `index.html`, and your data stays in your own browser.

## Features

- **Schedule poster**: add, edit, drag, sort and colour time blocks. A4, Letter or A3 paper, with several looks (black & white by default).
- **Start Quest**: a full-screen poster with a big checkbox beside every task.
- **Points and levels**: longer blocks give more points, finishing everything gives a Perfect Day bonus, and you level up as you go.
- **Rewards shop**: add your own rewards and spend points on them.
- **Achievements**: 15 badges to unlock.
- **Calendar**: every day fills in as you finish tasks, with perfect days marked.
- **Save as PDF** (direct download) and **Print** as separate buttons.
- **Export / Import** your schedule and progress as a small `.json` file.
- **Phone app layout**: bottom tab bar, big touch targets, and it fits any screen size.
- **Installable and works offline** as an app on your phone or computer.

## On your phone

On phones it turns into an app: a bottom tab bar (**Quest, Calendar, Poster, Edit, More**), a top bar with your points and streak, big touch-friendly buttons, and a vibration tap when you tick a task or level up (on devices that support it). Install it from your browser and it opens full screen like any other app.

<p align="center"><img src="docs/mobile.png" alt="Schedule Quest on a phone: Quest, Calendar, Poster and Settings screens" width="900"></p>

| Calendar | Full-screen quest |
|---|---|
| <img src="docs/calendar.png" alt="Calendar tab"> | <img src="docs/fullscreen.png" alt="Full-screen quest mode"> |

## Use it

Open `index.html` in any modern browser, or use the live page once it is published (see below).

### Install as an app

Once it is on GitHub Pages, open the page and use your browser's **Install** option (Chrome / Edge: the install icon in the address bar; Android: menu → *Install app*; iPhone: Share → *Add to Home Screen*). After the first visit it also works offline.

## Publish with GitHub Pages

1. Create a new repository on GitHub (for example `schedule-quest`).
2. Upload **all the files in this folder** (keep `docs/` as a folder) with **Add file → Upload files**, then commit.
3. Go to **Settings → Pages**. Under **Build and deployment**, set **Source** to **Deploy from a branch**, choose branch **main** and folder **/ (root)**, then **Save**.
4. After a minute or two your site is live at `https://YOUR-USERNAME.github.io/REPO-NAME/`.
5. Optional: in **Settings → General → Social preview**, upload `docs/social-preview.png` so links to your repo show a nice image.

## Files

| File | What it is |
|---|---|
| `index.html` | The whole app |
| `manifest.webmanifest`, `sw.js` | Make it installable and available offline |
| `logo.svg`, `favicon.svg` | Logo and browser tab icon |
| `icon-192.png`, `icon-512.png`, `icon-maskable-512.png`, `apple-touch-icon.png` | App icons |
| `docs/` | Screenshots for this README and the social preview image |
| `.nojekyll` | Tells GitHub Pages to serve the files as they are |

## Notes

- Progress is stored per browser and per web address, so the published version starts empty. **Export** from your old copy and **Import** into the new one to bring your schedule and progress across.
- Full screen may not be available on iPhone Safari; Start Quest then fills the browser window instead.
- If you change `index.html` after publishing, the app picks up the new version on the next online visit.
