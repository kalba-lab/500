# 500

**Minimalist link dump for macOS**

A bucket for all your links. Drag from any browser, find later, open anywhere.

🌐 Website: [500links.online](https://500links.online)

## Problem

You find something interesting. An article, a tool, a video. "I'll check this later."

So you keep the tab open. Or save it to bookmarks. Or send yourself an email.

A week later you have 47 tabs and zero idea what any of them were about.

And if you use multiple browsers? Safari bookmarks here, Chrome bookmarks there, Firefox somewhere else. No simple way to collect links from everywhere and open them wherever you need.

## Solution

500 is a small window at the edge of your screen. See something interesting? Drag the link and drop it in. Done.

Later, when you need it, just search. One click to edit the name, double-click to open in any browser you want.

No folders. No tags. No accounts. Just throw it in, find it later.

Five hundred links, five thousand, whatever. Just dump them in.

## How it works

1. Drag URL from any browser
2. Drop it into 500
3. Search, edit, open whenever you need

```
500 window:
┌─────────────────────────┐
│ 🔍 Search...            │
├─────────────────────────┤
│ 🌐 Article about AI     │
│ 🌐 Cool design tool     │
│ 🌐 Recipe for tonight   │
│ 🌐 GitHub repo          │
└─────────────────────────┘
```

## Features

- 🔗 **Drag & Drop** - from any browser, just drag the URL
- 🔍 **Instant search** - find links as you type
- 🌐 **Browser choice** - open each link in Safari, Chrome, Firefox, whatever
- ✏️ **Quick rename** - click to edit, double-click to open
- 🗑️ **Delete mode** - toggle for quick cleanup
- 📤 **Export** - HTML bookmarks, JSON, or Markdown
- 🎨 **Adjustable font** - make it comfortable

## Install

1. [Download DMG](https://github.com/kalba-lab/500/releases/latest)
2. Drag 500.app to Applications
3. Open and start dropping links

Requires macOS 13+, Universal (Intel + Apple Silicon).

**App won't open?** macOS blocks apps from developers who don't pay Apple $100/year. I don't. To open:

1. Try to open 500.app (it will be blocked)
2. Go to System Settings → Privacy & Security
3. Scroll down to Security - you'll see "500 was blocked"
4. Click Open Anyway

You only need to do this once.

## Keyboard shortcuts

- `⌘+` - larger font
- `⌘-` - smaller font
- `⌘0` - reset font
- `Esc` - cancel editing
- `Enter` - save edit

## Data

Links stored locally:
```
~/Library/Application Support/500/links.json
```

## Tech

Swift, SwiftUI

## License

Free to use

---

📦 [Download](https://github.com/kalba-lab/500/releases/latest) · ✉️ [min@kalba.dev](mailto:min@kalba.dev?subject=500) · [Kalba Lab](https://kalba.dev)
