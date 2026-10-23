<p align="center"><b>🇬🇧 English</b> · <a href="README.nl.md">🇳🇱 Nederlands</a></p>

<p align="center">
  <img src="docs/banner.png" alt="Arrow, a browser for the Mac" width="100%">
</p>

<p align="center"><img src="docs/icon.png" width="96" alt="Arrow logo"></p>
<h1 align="center">Arrow</h1>

<p align="center"><b>Aim. Release. Arrive.</b><br>A calm, fast browser for the Mac.</p>

<p align="center">
  <a href="https://github.com/matthiasmannx/arrow-releases/releases/latest/download/Arrow.dmg"><img src="https://img.shields.io/badge/Download-Arrow.dmg-6D3DF5?style=for-the-badge&logo=apple&logoColor=white" alt="Download Arrow.dmg"></a>
  <a href="https://github.com/matthiasmannx/arrow-releases/releases/latest/download/Arrow.pkg"><img src="https://img.shields.io/badge/Installer-Arrow.pkg-3b2f63?style=for-the-badge&logo=apple&logoColor=white" alt="Download Arrow.pkg"></a>
</p>

<p align="center">
  <img src="https://img.shields.io/github/v/release/matthiasmannx/arrow-releases?label=version&color=7b55f0" alt="version">
  <img src="https://img.shields.io/badge/macOS-Apple%20Silicon%20%26%20Intel-1d1640" alt="macOS Apple Silicon and Intel">
  <img src="https://img.shields.io/badge/Chromium-156-1d1640" alt="Chromium 156">
  <img src="https://img.shields.io/badge/Apple-notarised-2fb457" alt="Notarised by Apple">
  <img src="https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Fmatthiasmannx%2Farrow-releases%2Fmain%2Fdocs%2Finstalls.json&label=installs&cacheSeconds=3600" alt="installs">
  <img src="https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Fmatthiasmannx%2Farrow-releases%2Fmain%2Fdocs%2Factive.json&label=active%20Arrows&cacheSeconds=3600" alt="active Arrows">
</p>

---

## What is Arrow?

Arrow is a browser for the Mac, built around how you actually work. Work and personal never mix, your go-to sites are one click away, and tabs tidy themselves up. Under the hood runs Chromium, the same engine as Chrome, so every site and every Chrome extension just works.

## Install

| | |
|---|---|
| **.dmg** | Open the file and drag **Arrow** to **Applications**. |
| **.pkg** | Double-click and follow the steps; Arrow ends up in Applications by itself. |

On first launch a short welcome gets you going. You can import your bookmarks, history and passwords from **Chrome, Safari, Firefox, Edge** or **Brave** right there.

> Arrow is signed with an Apple Developer ID and notarised by Apple, so you won't see a warning when you open it.

## Features

| | |
|---|---|
| 🪐 **Spaces** | Separate worlds for work and personal, each with its own logins, cookies and extensions. Switch with the dots at the bottom, a swipe or your mouse thumb buttons. |
| ⚡ **Command bar** | Press **⌘T**: search, type an address or jump to an open tab. It completes as you type, does sums (`12*7`), converts units and currencies (`50 usd in eur`) and runs actions (`qr`, `dark`, `pipette`). |
| ⭐ **Favorites and folders** | Your go-to sites as tiles, with your own name, emoji or picture. |
| 🪟 **Split view and Peek** | Two sites side by side, or let a link float in front of you without losing your tab. |
| 🕶️ **Private window** | **⇧⌘N**: nothing is saved, everything is gone when you close it. Closed a tab by accident? **⇧⌘T** brings it back. |
| 🐣 **Little Arrow** | Links from Outlook, Teams or Slack open in a small separate window. |
| 💼 **Work and personal mode** | One click opens your start set. Per mode you decide which sites may disturb you and which are paused. |
| 🔐 **Passwords, addresses and cards** | Save, fill and suggest strong passwords. Addresses and payment cards fill with one click; cards only after Touch ID, and the CVC is never stored. |
| 🌐 **Translate** | **⌥⌘T** translates the page with macOS's own translation, so the text never leaves your Mac. |
| 📖 **Reader view** | **⌥⌘R**: just the article, in a calm layout with your font size and light, sepia or dark. |
| 🕘 **History** | **⌘Y**: search everything you visited, and clear a page, a day or a whole site. |
| 📸 **Screenshots and recordings** | Just like macOS, with an editor to annotate, crop or trim a video. |
| 🧩 **Every Chrome extension** | From the Chrome Web Store, with a side panel like Chrome's, and a developer mode for your own extensions. |
| 🧭 **Per-site settings** | Click the padlock to set dark mode, cookie banners, auto reload and permissions for that site; all of them together in *Settings → Sites*. |
| 🏁 **Start pages** | Choose which sites open when Arrow starts. |
| 🎨 **Your style** | Six themes, three tile styles, English or Dutch. |

## Fundamentals

The things you'd normally install an extension for are built in. They live in the **Fundamentals** menu and under the puzzle piece in the sidebar, which also shows whether each one works on the page you're on. They only run when you use them, so Arrow stays light.

| | |
|---|---|
| 🍪 **Cookie banners** | Rejected automatically ("Reject all" / "Only necessary"), with a per-site choice. |
| 🌙 **Dark mode for sites** | Light sites turn dark; sites with their own dark theme are left alone. **⇧⌘D** per site. |
| ⏩ **Video speed and volume** | Any video faster or slower (**⌃.** / **⌃,**) and a volume per tab, also from the mini player. |
| ↻ **Auto reload** | Reload a tab every 30 seconds to an hour, or your own time. Never while you're typing. |
| 🎨 **Colour picker** | **⇧⌘I**: point at any colour on the page, the hex code is on your clipboard. |
| 📱 **QR code** | Send the page to your phone, made on your own Mac. |
| 📝 **Markdown link** | **⌥⇧⌘C**: `[title](url)`, or a clickable link when you paste in Notion, Mail or Word. |
| 📜 **Full-page screenshot** | The whole page, sharp on Retina, including images that load as you scroll. |
| `{}` **JSON viewer** | JSON addresses as a collapsible tree with search and copy. |

## Safe and private

Arrow has no account, no telemetry and no advertising ID. Everything Arrow checks, it checks on your own Mac.

- **Phishing and malware protection** using open lists (URLhaus, Phishing Army, OpenPhish), compared locally. Not a single address of yours leaves your Mac.
- **Always HTTPS.** Plain http addresses open securely; if that fails, you get a clear warning.
- **Encrypted on disk.** Logins and passwords are encrypted, with keys only Arrow itself can read.
- **Permissions on request.** A site can't read your clipboard, open other apps or use your camera without asking first.
- **Sealed.** Arrow's own windows never load a website, and the app checks itself for tampering.
- **Isolated.** Every site runs in its own process and sandbox, and Arrow itself runs with the macOS hardened runtime.

## Fast

- Arrow starts connecting to a site as soon as you hover over a bookmark, so the page appears sooner.
- Tabs you haven't looked at for an hour give their memory back and stay right where they are in the sidebar.
- Large downloads come in several parts at once.

## Updates

You never have to download anything yourself. Arrow checks for a new version every 3 hours and installs it when you quit. **Security updates** always install, **new features** as you choose in *Settings → Updates*. Every update must be signed with the same Developer ID, or Arrow refuses it, and Arrow never goes back to an older version.

## Handy shortcuts

| Key | What |
|---|---|
| **⌘T** | New tab or jump to an open tab |
| **⌘D** | Pin or unpin a tab |
| **⌃1 … ⌃9** | Go to space 1 to 9 |
| **⌃⇧=** | Split view with the previous tab |
| **⇧⌘N** | New private window |
| **⇧⌘T** | Reopen closed tab |
| **⇧⌘2** / **⇧⌘5** | Screenshot / screen recording |
| **⇧⌘D** | Dark mode for this site |
| **⌥⌘R** / **⌥⌘T** | Reader view / translate |
| **⌘Y** | History |
| **⌃.** / **⌃,** | Video faster / slower |
| **⌘/** | All shortcuts (and change them) |

## Questions

<details><summary><b>Does Arrow work on an Intel Mac?</b></summary><br>Yes. One download works on both Apple Silicon and Intel Macs (macOS 12 or newer). Translating with macOS's own translation needs macOS 26.</details>
<details><summary><b>Can I bring my passwords?</b></summary><br>Yes. From Chrome, Edge and Brave directly while importing; from Safari, Firefox or 1Password through a CSV export in <i>Settings → Passwords → Import</i>.</details>
<details><summary><b>Where is the source code?</b></summary><br>This page only contains the signed releases of Arrow, not the source code.</details>

---

<p align="center"><sub>Designed &amp; Developed by <b>Matthias Mann</b> · tips or questions: matthiasmann175@gmail.com</sub></p>
