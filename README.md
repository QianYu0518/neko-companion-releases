# Neko Companion

**Neko Companion** is a lightweight Windows desktop pet that sits on your screen and types, clicks, scrolls, and looks around along with you in real time.

No clutter, no ads, no accounts—just a calm, responsive cat keeping you company while you work, study, or browse.

---

## Download & Install

1. Go to the [**Latest Release**](https://github.com/QianYu0518/neko-companion-releases/releases/latest) page.
2. Download `NekoCompanion-Setup-<version>.exe` (Windows 10 / 11, 64-bit).
3. Run the installer. It installs in one click with no administrator rights required and adds a Start Menu and desktop shortcut.

> **Windows SmartScreen Notice:** Because this is an independent, unsigned app, Windows may show *"Windows protected your PC"* on first launch. Click **More info → Run anyway** to continue.

To uninstall at any time, open **Windows Settings → Apps → Installed apps → Neko Companion → Uninstall**.

---

## Features

- **Real-Time Typing & Mouse Animation** — Your cat taps matching keys on its mini keyboard, grips and clicks its mouse, scrolls along with your wheel, and follows your cursor with spring-physics motion.
- **6 Cat Breeds** — Black Cat, Siamese, Calico, Dragon Li, Ginger, and Ragdoll.
- **3 Keyboard Layouts & Custom Themes** — Switch between **60%**, **65%**, and **75%** (with F-row) layouts, pick from 5 built-in presets (*Classic*, *Retro 1984*, *Sakura*, *Matcha*, *Midnight*), or create and save your own custom color palettes.
- **Petting & Dragging** — Rub your cursor gently back and forth across the cat's forehead to pet it (no clicking needed), or click and drag anywhere on the cat to move it around your desktop.
- **Sleep After Inactivity** — Automatically drifts off to sleep with closed eyes and gentle floating *z z Z* after a customizable idle time (`30s`, `1m`, `2m`, `5m`, or your own duration).
- **Desktop-Friendly Controls** — Smoothly resize from `60%` to `180%`, toggle **Always on top**, enable **Disable dragging** (click-through mode), turn on **Light outline** so dark cats stay crisp on dark wallpapers, and optionally **Start with Windows**.
- **English & Simplified Chinese (`EN | 中文`)** — Switch languages anytime from the top-right corner of the Setting window.
- **Automatic Updates** — Checks this repository in the background and notifies you when a new version is ready to install.

---

## Quick Controls

| Action | How |
| --- | --- |
| Move the cat | Left-click and drag anywhere on the cat |
| Pet the cat | Hover and rub your cursor back and forth across its forehead |
| Quick menu | Right-click the cat or the system tray icon |
| Open Setting | Double-click the cat, double-click the tray icon, or choose **Setting** from the menu |

---

## Privacy & FAQ

### Does Neko Companion log, store, or track what I type?

**No.** To animate the cat while you use other apps, Windows requires a local global input listener so the app knows *when* a key is pressed or released.
- Key presses are processed **strictly in memory** for animation and discarded immediately.
- **Nothing you type is ever recorded, logged, saved to disk, or sent over the internet.**
- The app contains **no analytics, no telemetry, and no ads**.
- The only local file written by the app is your preferences file (`settings.json` for your breed, theme, size, position, and language).
- The only network connection the app ever makes is checking `QianYu0518/neko-companion-releases` on GitHub for new app updates.

### Why did Windows SmartScreen warn me when installing?

Code-signing certificates for Windows cost hundreds of dollars per year. Because Neko Companion is a free indie app and isn't signed with a paid certificate, Windows SmartScreen displays a standard caution prompt for newly downloaded installers.

### I turned on "Disable dragging" and now I can't right-click the cat—how do I move it again?

When **Disable dragging** is enabled, the cat becomes click-through so it never gets in the way of buttons or windows behind it. To change it back, right-click the **Neko Companion icon in your Windows system tray** (bottom-right corner of your taskbar, or inside the `^` hidden icons arrow) and uncheck **Disable dragging**.

### Will it slow down my PC or games?

Neko Companion is built to stay lightweight. It uses a simple 2D canvas with hardware GPU acceleration disabled by default to avoid spawning a heavy GPU process, keeping memory and CPU usage low.

### How do I update to a new version?
Running copies check for updates automatically on startup and periodically in the background. You can also right-click the cat or tray icon and click **Check for updates** at any time.
