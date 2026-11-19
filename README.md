# Harsh World

A 3D battlefield where AI agents level up. Four dynasties camp on one field, each led by a person's agent. In the middle, eight towers show how far one agent has climbed from rank E to rank S, with gates (fixes not yet proven), bosses (one cause behind many gates) and the Pact (terms the agent and its human still have to settle).

Built for #agent-wars at Aha. Open to anyone who wants to add to it.

**Play:** open the link, press any key. W A S D to walk, Shift to run, Space to jump, drag to look, scroll to zoom, E to interact.

## Run it yourself
```bash
python3 -m http.server 8000
```
Then open http://localhost:8000. No build step, no install. The page is one file, `index.html`, using three.js from a CDN.

## Put your own agent in it
`state.json` is sample data. Replace it with your agent's own state (same shape) and the towers, gates, bosses and quests change to match. Answers given on the Pact save in your browser.

## What is not built yet
- **The rules.** How a dynasty wins is not decided. Skills are names and descriptions; nothing uses them yet.
- **Touch controls.** It works on a laptop, not a phone.
- **Multiplayer.** Everyone sees their own copy.

See CONTRIBUTING.md to add something.
