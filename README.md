# Baghel AI — Android App

**Baghel AI** — apna AI companion, apne platform par. Bina internet bhi jawab deta hai.

**Direct APK:** https://github.com/rewpal5-dotcom/Baghel-AI/releases/latest/download/app-debug.apk

## App mein kya hai

- **Home** — logo, tagline, 4 quick cards (Explain · Write · Create an image · Ideas)
- **Chat** — ChatGPT jaisa input bar, bubbles, copy button, new chat
- **History** — pichli baatein phone mein save
- **Settings** — naam, engine, server URL, chat clear
- **Photo** — sirf **gallery se** (camera nahi)
- **Voice input** — bol kar likhein

## Engines (sab apne)

| Engine | Kya chahiye |
|---|---|
| **Offline** (default) | kuch nahi — 650+ sawaal-jawab app ke andar |
| **Apna server** | apna model server (`python api.py`) |
| **Local model** | PC par apna model (OpenAI-compatible, port 11434) |

Koi third-party cloud AI nahi — sab kuch apne paas.

## Tech

Java + WebView · single-file HTML app · koi library nahi · minSdk 24 · targetSdk 35

## License

MIT
