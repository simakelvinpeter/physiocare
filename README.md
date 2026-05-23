# PhysioCare

A standalone physiotherapy companion app — **zero installation required**. Open a single HTML file in any browser and it works.

> Built with React 18, Tailwind CSS, and Babel — all loaded from CDN. No build step, no server, no dependencies to install.

---

## Screenshots

| Splash | Login | Register |
|--------|-------|----------|
| ![Splash](screenshots/01-splash.png) | ![Login](screenshots/02-login.png) | ![Register](screenshots/03-register.png) |

| Dashboard | Dashboard (scrolled) |
|-----------|----------------------|
| ![Dashboard](screenshots/04-dashboard.png) | ![Dashboard scrolled](screenshots/04b-dashboard-scrolled.png) |

| Exercises List | Exercises (scrolled) |
|----------------|----------------------|
| ![Exercises](screenshots/05-exercises-list.png) | ![Exercises scrolled](screenshots/05b-exercises-list-scrolled.png) |

| Exercise Detail | Exercise Detail |
|-----------------|-----------------|
| ![Exercise detail](screenshots/06-exercise-detail.png) | ![Exercise detail 2](screenshots/06b-exercise-detail-glute.png) |

| Progress | Reminders | Profile |
|----------|-----------|---------|
| ![Progress](screenshots/07-progress.png) | ![Reminders](screenshots/08-reminders.png) | ![Profile](screenshots/09-profile.png) |

---

## Features

- **15 guided exercises** with video demonstrations, step-by-step instructions, and difficulty labels
- **Progress tracking** — streak counter, weekly activity bars, session count, and adherence percentage
- **Achievements** — unlocked dynamically as you hit milestones (first session, 7-day streak, 10 exercises)
- **Reminders** — browser notification alerts with custom time picker; add and delete reminders per user
- **User accounts** — register / login stored in `localStorage`; each user has isolated progress data
- **Assessment flow** — condition/goal selection on sign-up personalises the dashboard
- **Consultation booking** — upcoming appointment card on dashboard
- **Fully offline** — works from `file://` with no internet after first load of CDN resources

---

## How to Run

1. Download `PhysioCare App standalone.html`
2. Open it in any modern browser (Chrome, Edge, Firefox, Safari)
3. That's it — no install, no server needed

---

## How to Share

| Method | Steps |
|--------|-------|
| **Email** | Attach the `.html` file — recipient opens it directly |
| **Netlify Drop** | Drag the file to [netlify.com/drop](https://netlify.com/drop) → instant public URL |
| **WhatsApp / Telegram** | Send as a file attachment |
| **Google Drive** | Upload → Share link → recipient downloads and opens |
| **GitHub Pages** | Push to repo → Settings → Pages → free public URL |

---

## Tech Stack

| Layer | Technology |
|-------|-----------|
| UI framework | React 18.3.1 (UMD via unpkg) |
| Styling | Tailwind CSS (CDN with custom teal config) |
| JSX transform | Babel Standalone 7.29.0 |
| Storage | Browser `localStorage` |
| Notifications | Web Notifications API |
| Videos | HTML5 `<video>` (Pixabay CDN) |
| Thumbnails | Pexels CDN |

---

## Project Structure

```
PhysioCare/
├── PhysioCare App standalone.html   ← entire app in one file
├── screenshots/                     ← app preview images
│   ├── 01-splash.png
│   ├── 02-login.png
│   ├── 03-register.png
│   ├── 04-dashboard.png
│   ├── 05-exercises-list.png
│   ├── 06-exercise-detail.png
│   ├── 07-progress.png
│   ├── 08-reminders.png
│   └── 09-profile.png
└── README.md
```

---

## Built by Micy
