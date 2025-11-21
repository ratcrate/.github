

<p align="center">  <img width="500" height="500" alt="ratcrate-vector" src="https://github.com/user-attachments/assets/01f61be3-4a7c-4bac-a125-01a9f03269e5" /> </p>
          
#  Ratcrate
> A curated registry of **ratatui** - powered terminal applications

Ratcrate is your go-to resource for discovering terminal user interface (TUI) applications built with [Ratatui](https://github.com/ratatui-org/ratatui). I maintain an up-to-date catalog of ratatui-based projects to help developers find inspiration and users discover powerful terminal applications.


# Overview

**Ratcrate** is a discovery platform for Rust crates in the Ratatui ecosystem. It consists of:
- `ratcrate-core`: Data fetching and JSON generation
- `ratcrate-web`: ReactJS based web interface (Future - Convert to Dioxus Rust)
- `ratcrate-cli`: Command-line interface
- `ratcrate-tui`: Terminal UI with Ratatui

```markdown

ratcrate-core (data pipeline - Private Repo) 
          ↓ 
     ratcrate.json
          ↓ 
  ┌───────┴┬────────┐
  ↓        ↓        ↓
 web      cli      tui

```

## 📦 Browse the Registry

Visit [ratcrate.github.io](https://ratcrate.github.io) to explore the full catalog of ratatui applications.

## 🛠️ Tools & Projects

- **[ratcrate-web](https://github.com/ratcrate/ratcrate-web)** - Web interface for browsing the registry. Updated every 24 hours
- **[ratcrate-cli](https://github.com/ratcrate/ratcrate-cli)** - Command-line tool for searching and discovering ratatui apps
- **[ratcrate-tui](https://github.com/ratcrate/ratcrate-tui)** - Terminal user interface for exploring the registry (built with ratatui, naturally!)

## 🎯 Why Ratcrate?

Ratatui is powering a new generation of terminal applications, and I want to make it easy to:
- Discover quality TUI applications
- Find libraries and tools built with ratatui
- Get inspired by what's possible with terminal interfaces
- Contribute to the ratatui ecosystem

## 🤝 Contributing

Found a ratatui project that's not in the registry? Want to improve our tools? Contributions are welcome across all our repositories!

---

*Powered by the [Ratatui](https://github.com/ratatui-org/ratatui) ecosystem* 🐀
