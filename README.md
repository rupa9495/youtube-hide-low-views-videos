# YouTube Hide Low Views Videos

A lightweight userscript that **automatically hides low views videos** from YouTube's homepage.

---

## Features

- Hides **"Members only"** and **"Members first"** videos
- Works dynamically with YouTube's modern **Single Page Application (SPA)** behavior
- Reacts to scrolling and content updates automatically
- 100% client‑side — no API calls, no external dependencies

---

## Installation

### Option 1. Using Tampermonkey (Recommended)

1. Install **[Tampermonkey](https://www.tampermonkey.net/)** for your browser.
2. Click **Create a new script**.
3. Paste the contents of [`hide-low-views-videos.user.js`](./hide-low-views-videos.user.js).
4. Save the script and refresh **YouTube**.

### Option 2. Using AdGuard

If you are using **AdGuard for Windows, macOS, or the browser extension**, you can also import the userscript directly.

1. Open AdGuard settings.
2. Navigate to **Extensions → Userscripts** (or **Filters → Custom** if using the extension).
3. Click **Add userscript**.
4. Enter the direct URL to the script: [`https://github.com/umbertoragone/youtube-hide-low-views-videos/raw/main/hide-low-views-videos.user.js`](https://github.com/umbertoragone/youtube-hide-low-views-videos/raw/main/hide-low-views-videos.user.js)
5. AdGuard will download and manage the script automatically.
7. Refresh YouTube to activate it.

## Contributing

Pull requests are welcome. If YouTube changes its layout (again), please open an issue including an HTML snippet showing the updated badge element so the selectors can be updated quickly.
