# College Attendance Calculator

A **single-file**, zero-dependency attendance calculator with a polished dark UI. Track attended/total classes, see live percentage with an animated progress ring, plan holidays, and find out exactly how many classes you can bunk while still hitting your target.

## ✨ Features

- **Live attendance %** — entered classes vs attended, instant percentage ring
- **Required % target** — batao kitna chahiye, app batayega kitna aur attend karna padega
- **Bunk calculator** — "kitni classes bunk kar sakta hoon?" without dropping below target
- **Future planner** — upcoming classes add karo aur projected % dekho
- **Holiday tracker** — add/remove holidays, attendance me adjust hota hai
- **Theme toggle** — dark/light mode with persistence
- **Auto-save** — sab kuch `localStorage` me save hota hai (restore on reload)
- **PWA-ready** — service worker registration for installable/offline use
- **Responsive** — mobile se desktop tak sab par clean

## 🛠️ Tech

- **Vanilla HTML + CSS + JS** — single `attendance-calculator.html` file, koi build step nahi
- Fonts: Plus Jakarta Sans + Fira Code (Google Fonts)
- Custom properties for theming · SVG progress ring · toast notifications

## ▶️ Run

File kholo bas:

```bash
# double-click attendance-calculator.html
# ya local server:
npx serve .
```

Koi dependency install karne ki zaroorat nahi.

## 📁 Structure

```
attendance-calculator.html   # complete app (HTML + CSS + JS)
```

---

*B.Tech CSE (Cybersecurity) · Parul University*
