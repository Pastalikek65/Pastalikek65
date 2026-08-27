# Hi, I'm Pastalikek65 👋

Systems programmer who rebuilds infrastructure primitives from scratch — now mostly on my phone in Termux.

I learn by reimplementing core systems with zero deps. Lately I've been building offline-first tools that run on a phone, single binary, no Docker.

## 🧪 What I build — Termux Station + primitives

**New — Termux-friendly, built on my phone:**

| Project | What it is | Stack |
|---|---|---|
| [gh-starview](https://github.com/Pastalikek65/gh-starview) | `gh repo list` as sortable TUI with offline SQLite cache | Go 1.25, bubbletea, 13M |
| [txs](https://github.com/Pastalikek65/txs) | Single-binary TUI dashboard — github + jobs + db + sys + files | Go, 5 panels, 9.9M |
| [habit](https://github.com/Pastalikek65/habit) | Habit tracker with streaks | Go, SQLite WAL, 6.8M |
| [passman](https://github.com/Pastalikek65/passman) | Age-encrypted password manager | Go, age scrypt, 7.1M |
| [dotman](https://github.com/Pastalikek65/dotman) | Dotfiles manager — git sync + TUI | Go, 5M |
| [pytermq](https://github.com/Pastalikek65/pytermq) | Ultra-light job queue — SQLite WAL, 30MB | Python, 7 tests |
| [termux-portfolio](https://pastalikek65.github.io/termux-portfolio/) | My portfolio — single HTML, no build, fetches GitHub API | JS, Tailwind CDN |
| [sqlite-tui](https://github.com/Pastalikek65/sqlite-tui) | SQLite viewer — tables, rows, WAL | Go, 8.5M |

**Core primitives (from scratch, zero deps where possible):**

| Project | What it is |
|---|---|
| [termtunnel](https://github.com/Pastalikek65/termtunnel) | P2P TCP/HTTP tunnel over WebRTC + Noise — ngrok for Termux |
| [goredis](https://github.com/Pastalikek65/goredis) | Redis-compatible KV from scratch — RESP, sharded, RDB/AOF |
| [gotorrent](https://github.com/Pastalikek65/gotorrent) | BitTorrent client — bencode, tracker BEP 12, peer wire |
| [cronping](https://github.com/Pastalikek65/cronping) | Tiny cron daemon — alerts via Telegram/Discord/ntfy |
| [sqlite-backups](https://github.com/Pastalikek65/sqlite-backups) | Hot-backups of live SQLite — Online Backup API, LZ4, S3 |
| [edgewasm-runtime](https://github.com/Pastalikek65/edgewasm-runtime) | WASM runtime in Rust |

## 🌐 Open-source contributions

I contribute upstream to **rclone**, **freeCodeCamp**, **anacrolix/torrent**, **helm**, **alecthomas/participle** — 27 PRs, many merged.

## 🛠️ Tools

Go · Rust · C++ · Python · TypeScript · SQLite · Linux · bubbletea · age · WebRTC · Docker

## 📬

- Built 8 repos on my phone in Termux — `CGO_ENABLED=0`, `modernc.org/sqlite`, `android-arm64` goreleaser
- Open to systems discussions — `gh-starview` `txs` `habit` all have `demo.gif`
- Portfolio: https://pastalikek65.github.io/termux-portfolio/

