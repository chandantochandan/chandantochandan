<div align="center">
  <h1>Chandan</h1>
  <p><strong>Building Vidurai - it remembers context so you don't have to.</strong></p>
</div>

---

**Vidurai** is a universal context and memory layer that sits between your real work (files, terminal, browser) and whatever AI assistant you use.

Instead of dumping raw logs into a model, Vidurai:

- watches your workflow locally (editor, terminal, files, browser)
- extracts the **gist** instead of the noise  
- compresses and prioritizes with reinforcement learning  
- sends a clean, minimal context to the AI only when needed  

The goal is simple:  
less copy-paste, fewer tokens, clearer answers.

---

## Vidurai Ecosystem

Core projects:

- 🧠 **[vidurai](https://github.com/chandantochandan/vidurai)** – RL-powered memory + strategic forgetting engine (Python)  
- 🛰 **[vidurai-daemon](https://github.com/chandantochandan/vidurai-daemon)** – local context daemon (files, terminal, process awareness)  
- 🔌 **[vidurai-proxy](https://github.com/chandantochandan/vidurai-proxy)** – universal AI proxy / context layer  
- 🌐 **[vidurai-website](https://github.com/chandantochandan/vidurai-website)** – marketing site ([vidurai.ai](https://vidurai.ai))  
- 📖 **[vidurai-docs](https://github.com/chandantochandan/vidurai-docs)** – documentation ([docs.vidurai.ai](https://docs.vidurai.ai))

Docs and research:

- 📚 **Docs:** https://docs.vidurai.ai  
- 🔬 **Research note:** [VIDURAI_RESEARCH.md](https://github.com/chandantochandan/vidurai/blob/main/research/VIDURAI_RESEARCH.md)  
  - fuzzy-trace theory  
  - strategic forgetting  
  - reinforcement-learning based compression

---

## Themes I Work On

- Memory architectures for LLM-based systems  
- Reinforcement learning for compression and retention  
- “Forgetting as a feature”, not a bug  
- Local-first, privacy-preserving developer tools  
- Human–AI mediation: making context legible to both sides  
- Reducing token waste and cognitive overload

---

## Current Focus

- Evolving Vidurai from “library” to **full workflow layer**  
- Tightening the loop between:
  - daemon → context mediator → browser / IDE extension → AI  
- Improving research-backed heuristics for:
  - when to forget  
  - what to keep verbatim  
  - what to reduce to gist  

---

## Tech Stack

Main tools I work with:

- **Languages:** Python, TypeScript  
- **AI / Infra:** OpenAI / Claude APIs, RL, embeddings, vector search  
- **Backend:** FastAPI, WebSockets, SQLite / file-based stores  
- **Tooling:** VS Code extensions, browser extensions, Docker, Git  


<div align="center">
  <p>Building Vidurai in public.<br/>
  Exploring how intelligent forgetting can make AI — and developers — more effective.</p>
</div>
