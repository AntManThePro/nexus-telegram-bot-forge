# NEXUS Telegram Bot Forge

**Interactive neon particle pipeline that turns BotFather + a live JS kernel into a production-ready Telegraf starter.**

Built by **DoubleA / AntManThePro** — Field Operations & QA · Hardware/Software bridge · godmode2025.net

---

## What this is

A single-file, 60fps Canvas + Tailwind experience that visualizes the entire Telegram bot creation flow as a live hardware-software dataflow:

- **Node graph**: INTENT → BOTFATHER → TOKEN → KERNEL → API BRIDGE → DEPLOY
- **Particle dataflow** carrying commands and state
- **Live kernel editor** with hot-reload (`new Function` sandboxed)
- **Token vault** that arms the pipeline
- **One-click compile** that emits a clean Node + Telegraf starter payload you can drop straight into production

This is not a tutorial page.  
This is a working systems visualizer that also happens to generate real code.

---

## Quick Start

1. Open [`index.html`](./index.html) in any modern browser (mobile + desktop)
2. Follow the **BOTFATHER SEQUENCE** panel on the right
3. Paste your real BotFather token into the **TOKEN VAULT** and hit **ARM TOKEN**
4. Edit the live kernel if you want custom command logic
5. Hit **HOT RELOAD** then **COMPILE STARTER PAYLOAD**
6. Copy the generated `bot.js` and run it with Telegraf

```bash
npm init -y
npm i telegraf
# paste the compiled payload into bot.js
node bot.js
```

---

## Why it exists

Recruiters and clients should look at this and think:

> “There’s no way he thought of that.”

It demonstrates:

- Real Canvas particle systems with object pooling mindset
- Live code injection / hot-reload patterns
- Hardware-software bridge thinking (nodes as sensors/compute/memory/actuators)
- Clean production code generation
- Mobile + desktop responsive neon UI
- Field-ops style observability (throughput, stability metrics)

---

## Tech

- Vanilla JS + Canvas 2D
- Tailwind Play CDN
- No build step
- Single file
- Works offline after first load

---

## License

MIT — do whatever you want with it. Credit appreciated but not required.

---

**AntManThePro**  
Operations & QA · Building tools that make work clearer and measurable  
[godmode2025.net](https://godmode2025.net)
