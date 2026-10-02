## How to Use

Getting started is super easy! Just download the `index.html` file, open it in your browser, and you're good to go. No installation or account needed! Your data stays saved in your browser and isn't sent to any server. Just remember not to share your backups or screenshots if they contain personal information. And if you're using a shared device, keep in mind that others might be able to access your data!
# Daylight ☀️

A lightweight, offline-first personal dashboard for organizing your day, building habits, taking notes, and tracking focus sessions.

Daylight runs as a **single HTML file**. It does not require a server, account, build tools, or installation.

## Features

- **Dashboard** — a home view with a live clock, greeting, and configurable widgets.
- **Tasks** — create and manage tasks with priorities, due dates, notes, and completion status.
- **Habits** — create habits, choose their colors, and record daily progress.
- **Focus timer** — Pomodoro-style focus and break sessions with configurable durations and optional sound.
- **Notes** — write and manage quick notes.
- **Statistics** — review task, habit, and focus-session activity.
- **Personalization** — change the app name, display name, light/dark theme, accent color, and dashboard widgets.
- **Local data** — changes are saved automatically in your browser's local storage.
- **Import and export** — back up or restore your data as JSON.

## Getting started

1. Download or clone this repository.
2. Open the HTML file in a modern browser.
3. Start adding tasks, habits, notes, or focus sessions.

No build step or package installation is required.

> Tip: You can also host the HTML file as a static page. Because Daylight stores data in browser local storage, each browser/device has its own separate data unless you export and import a backup.

## Data and privacy

Daylight is designed to keep your information on your device. The app saves its state in the browser's `localStorage` under the key `daylight.v1`; it does not require a backend or account.

- Use **Settings → Export JSON** to create a backup.
- Use **Settings → Import JSON** to restore a backup.
- **Reset all data** removes the app's saved data from the current browser. Export a backup first if you want to keep it.

Clearing browser data, using a different browser/profile, or opening the app in a different browser context may make your saved data unavailable. Keep regular backups of anything important.

## Technology

- HTML
- CSS
- Vanilla JavaScript
- Browser `localStorage`

There are no external frameworks or dependencies required to run the app.

## Project structure

```text
.
├── index.html   # The complete Daylight application
└── README.md   # Project documentation
```

If your HTML file has a different name, you can keep that name or rename it to `index.html` for convenience when hosting.

## Browser support

Use a modern browser with JavaScript and local storage enabled. The layout is responsive and includes a mobile navigation bar.

## Limitations

- Data is stored per browser/device; there is no built-in cloud sync.
- The focus timer runs in the browser, so background-tab or device power behavior may affect timing and notifications.
- JSON export is the recommended way to move or back up your data.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
