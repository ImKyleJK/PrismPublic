# PrismPublic
✨ Prism is your ultimate server styling bot! Customize channels with 🎨 emojis, 💬 cool text styles, and apply full layouts instantly. Browse community-made templates, preview styles before applying, and set up new servers in one click with themed presets 🚀 — all through our synced web dashboard 🌐.

# 📦 Prism Changelog

All notable changes to this project will be documented in this file.

---

## [1.0.0] - 2025-05-05
### v1.0.0 — Initial Public Release
Version: v1.0.0
Release Date: 2025-05-05
Codename: "Style Sync"

### 🎯 Overview
Prism is a modern Discord bot and companion dashboard focused on styling, structuring, and streamlining Discord servers with elegant layouts, emoji-enhanced channel naming, and full template-based customization. This v1.0.0 release includes a robust modular bot with full web dashboard support, Discord OAuth2 login, Redis-backed template system, and slash command interface.
The first public release of **Prism**, a modular Discord bot and modern web dashboard for styling and managing Discord servers using templates, emojis, and layout presets.

---

### ✨ Added

#### 🤖 Discord Bot Core (Modular)
- Built with `discord.js` v14
- Modular slash command system
- Redis-based template storage and caching

#### 🧩 Template System
- Add, preview, and apply server style templates
- Includes metadata: name, tags, creator, timestamp, usage count
- Sorted by newest or most popular

#### 📊 Template Stats & Metadata
- Live usage count tracked
- Applied timestamp recorded
- Creator info and searchable IDs

#### 🧠 Redis Integration
- Stores templates and layout metadata
- Optimized for fast template lookup and sorting

#### 🌐 Web Dashboard (React + Tailwind)
- Vite-powered React dashboard
- Styled with Tailwind CSS
- Discord OAuth2 login to view & manage your servers
- Server list UI with style button
- Upload form to add community templates
- Preview and apply templates visually

#### ⚙️ Slash Commands
- `/ping` – Bot latency
- `/status` – Shows bot/Redis/template stats
- `/template list` – Show all available templates
- `/template info <id>` – Show full metadata of template
- `/template preview <id>` – Show preview embed of layout
- `/template apply <id>` – Apply template to current server

#### 🧾 Logs & Analytics
- Logs when and where templates are applied
- Useful for audit tracking, rate limits, and analytics

#### 🔐 OAuth2 Integration
- Sign in with Discord to view and manage your servers
- Scopes: `identify`, `guilds`, `applications.commands`, `bot`
