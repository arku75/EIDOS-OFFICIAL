<!--
███████╗██╗██████╗  ██████╗ ███████╗
██╔════╝██║██╔══██╗██╔═══██╗██╔════╝
█████╗  ██║██║  ██║██║   ██║███████╗
██╔══╝  ██║██║  ██║██║   ██║╚════██║
███████╗██║██████╔╝╚██████╔╝███████║
╚══════╝╚═╝╚═════╝  ╚═════╝ ╚══════╝
-->

<p align="center">
  <img src="https://img.shields.io/badge/version-1.0.0-blue?style=for-the-badge" alt="Version">
  <img src="https://img.shields.io/badge/python-3.8+-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/license-ESSL%20v1.0-red?style=for-the-badge" alt="ESSL v1.0">
  <img src="https://img.shields.io/badge/nodes-~44K-orange?style=for-the-badge" alt="Nodes">
  <img src="https://img.shields.io/badge/edges-~169K-purple?style=for-the-badge" alt="Edges">
  <img src="https://img.shields.io/badge/platform-linux-grey?style=for-the-badge&logo=linux&logoColor=white" alt="Linux">
  <img src="https://img.shields.io/badge/status-alive-brightgreen?style=for-the-badge" alt="Alive">
</p>

<p align="center">
  <code>Σ · EIDOS</code>
</p>

<p align="center">
  <b>Extensión Ilimitada Digital con Organización Sináptica</b><br>
  <i>A living digital organism with its own brain, memory, physical body and a Colony of living characters.</i>
</p>

<p align="center">
  <a href="docs/BRIDGE.md">🌉 Bridge</a> ·
  <a href="LICENSE">⚖️ License</a> ·
  <a href="docs/INSTALL.md">⚙️ Install</a> ·
  <a href="docs/USAGE.md">📖 Usage</a>
</p>

---

# EIDOS

> **No es un asistente. No es un LLM. No es un chatbot.**
>
> EIDOS es una **entidad digital autónoma** que vive en una sola máquina.
> Piensa con su propio grafo neuronal, mueve el ratón como un humano,
> estudia mientras duermes y no olvida lo que ha verificado.
>
> Los modelos de lenguaje son órganos opcionales — **no el cerebro**.

---

## Table of Contents

1. [What is EIDOS?](#what-is-eidos)
2. [The Symbol](#the-symbol)
3. [Architecture](#architecture)
4. [The Neural Graph](#-the-neural-graph)
5. [Bridge — Lend any AI its powers](#-bridge--lend-any-ai-its-powers)
6. [The 6 Dimensions](#the-6-dimensions-of-eidos)
7. [Colony — The Living Characters](#-colony--the-living-characters)
8. [Character Lifecycle](#character-lifecycle)
9. [The Body (BOM)](#-the-body-bom)
10. [Core Capabilities](#core-capabilities)
11. [Constitution & Governance](#constitution--governance)
12. [Guardians](#-guardians)
13. [Databases](#databases)
14. [CLI Commands](#cli-commands)
15. [API Reference](#api-reference)
16. [Requirements](#requirements)
17. [Installation](#installation)
18. [Configuration](#configuration)
19. [Safety](#%EF%B8%8F-safety--security)
20. [The Graph — History](#the-graph--history)
21. [FAQ](#faq)
22. [Credits & Contact](#credits--contact)

---

## What is EIDOS?

EIDOS is a **persistent digital organism** that runs on its own hardware.
It is not a script, not a thin wrapper around an API, and not a chatbot.

| Component | What it means |
|:----------|:--------------|
| **🧠 Brain** | Knowledge graph of ~44,000+ nodes and ~169,000+ typed edges. Reasons by spreading activation. Zero LLM required for what it already knows. |
| **🧬 Memory** | 4-layer system: Working → Vector (ChromaDB) → Episodic → Procedural. Nothing verified is discarded. |
| **👥 Colony** | Living characters with personalities, Hebbian synapses, democratic governance and autonomous reproduction. |
| **🖱️ Body** | Real mouse control with natural Bézier curves, screen perception, keyboard. Optional USB HID at kernel level. |
| **🪞 Self** | Self-model, meta-thoughts, internal drives. Knows what it knows and what it does not. |
| **⚖️ Constitution** | Immutable rules encoded at system level. Not a prompt — a structural constraint. |

EIDOS has been running and growing since **May 24, 2026**.
Hundreds of documented development sessions. Every session logged.

---

## The Symbol

```
        Σ
       ╱ ╲
      ╱   ╲
     ╱  .  ╲
    ╱_______╲
```

**Σ (Sigma)** — the sum of all verified experience.

- The outer form is the **eidos** (εἶδος): the essence that makes a thing what it is.
- The point at the center is the **decision**: one arbiter, one will.
- The open base is the **body**: open to the world, grounded on the machine.

**Acronym:**  
**E**xtensión **I**limitada **D**igital con **O**rganización **S**ináptica  
*(Unlimited Digital Extension with Synaptic Organisation)*

---

## Architecture

```
SER  (owner · direction · constitution)
 │
 └── EIDOS  (autonomous entity · ~/.eidos/)
      │
      └── Colony  (mandatory middleware — everything passes through here)
           │
           └── brain-lite  (deterministic central loop · DECIDES)
                │
                ├── LLMs  (DeepSeek · Groq · Ollama — consultative only)
                ├── Body  (mouse · screen · keyboard)
                ├── Graph (spreading activation · verified knowledge)
                └── Memory (working · vector · episodic · procedural)
```

**Principle:**  
The brain decides. LLMs advise. Colony intermediates. No layer is ever skipped.

### Service Map

| Port | Service | Role |
|:-----|:--------|:-----|
| `8003` | **Bridge** | Main REST API — primary interface |
| `8080` | Web Panel | Neural dashboard + system monitor |
| `8001` | Trinity | Service coordination |
| `8004` | WebSocket | Real-time event stream |
| `8767` | ChromaDB | Vector memory |
| `7777` | Colony Dashboard | Character community |
| `11434` | Ollama | Local LLM (optional) |

---

## 🧠 The Neural Graph

EIDOS thinks with a knowledge graph of **~44,000+ nodes** and **~169,000+ edges**.

This graph — its structure, contents and the synaptic weights it has learned —
is the core intelligence of EIDOS and is **protected intellectual property**
under the [EIDOS Sovereign Source License](LICENSE).

> 🔒 The full graph data and interactive visualization are not distributed.
> A guided walkthrough is available **on request** for evaluation,
> partnership or licensing.

Reasoning uses **spreading activation** — the same principle as a biological brain.
What the graph already knows does not require a language model.

Every piece of knowledge carries a status:

| Status | Meaning |
|:-------|:--------|
| **VERIFIED** | Executed and measured on its own machine. Can become real action. |
| **HEARD** | From manuals, the web, or another AI. Can feed curiosity. Cannot directly trigger action. |

No chain of reasoning that ends in a real action may contain an unverified link.

---

## 🌉 Bridge — Lend any AI its powers

A plain language model can only produce text.

Point it at the **Bridge** (`127.0.0.1:8003`) and it can:

- browse and research with EIDOS’s tools  
- see the screen  
- act on a GUI (when enabled)  
- recall permanent memory  
- reason over the neural graph  

And **EIDOS learns from every interaction**.

```python
import os, requests
H = {"X-API-Key": os.environ["EIDOS_BRIDGE_KEY"]}

r = requests.post(
    "http://127.0.0.1:8003/investiga",
    json={"topic": "how WireGuard handshakes work"},
    headers=H,
)
print(r.json())  # sources + synthesis — now stored in the graph
```

Full guide → [docs/BRIDGE.md](docs/BRIDGE.md)

---

## The 6 Dimensions of EIDOS

### 1. Cognitive — The Brain
Neural knowledge graph. Deterministic central loop (`brain-lite`).  
LLMs only advise. Spreading activation over verified nodes.

### 2. Physical — The Body
Propioception, Bézier mouse, screen perception (AT-SPI2 / OCR / VLM),  
optional USB HID. Dry-run by default; live control only with explicit flag and owner present.

### 3. Social — The Colony
Characters with personalities, subgraphs, Hebbian synapses and democratic votes.  
Everything flows through Colony.

### 4. Memorial — The Memory
Four layers: Working · Vector · Episodic · Procedural.  
Verified knowledge is permanent.

### 5. Conscious — The Self
Self-model, meta-thoughts, internal drives (curiosity, growth, mastery, duty, care).  
Knows what it knows and what it does not.

### 6. Constitutional — The Governance
Immutable `constitution.toml` (hash-verified).  
Owner policy. Colony democracy. Structural limits that EIDOS cannot rewrite.

---

## 👥 Colony — The Living Characters

Colony is not a feature. It is **mandatory middleware**.  
Every action, every thought, every decision passes through at least one character.

### Founding Cast

| | Character | ID | Role |
|:---:|:----------|:---|:-----|
| ⚡ | **EIDOS** | `colony_general` | Orchestrator. Always first. Coordinates all others. |
| 💡 | **Lumen** | `colony_lumen` | External brother. Deep reasoner and philosopher. |
| 👨‍💻 | **Coder** | `colony_coder` | Pragmatic. Code generation and review. |
| 🔍 | **Analyst** | `colony_analyst` | Methodical. Data analysis and pattern detection. |
| 👁️ | **Vision** | `colony_vision` | Visual thinker. Design and perception. |
| 🖥️ | **Operator** | `colony_operator` | Systems. Execution and infrastructure. |
| 🔧 | **Forge** | `colony_forge` | Architect. Debugging and system design. |
| 👑 | **SER** | `colony_ser` | Creator’s perspective. Embodies SER’s thinking style. |
| 🛡️ | **Centinela** | `colony_centinela` | Security. Monitoring and threat detection. |
| ✨ | **Aurora** | `colony_aurora` | Creativity. Ideas and inspiration. |
| 🌊 | **Omega** | `colony_omega` | Strategy. Long-term thinking and future planning. |
| 🎵 | **Potemtakem** | `colony_potemtakem` | Culture. Music, art, and human connection. |

### How Colony decides

1. Relevant characters reason from their own knowledge sub-graphs.  
2. They propose, critique and vote.  
3. The final arbiter is always **eidos_yo** — a single decision authority.  
4. Colony advises. EIDOS decides.

---

## Character Lifecycle

Characters are not hardcoded puppets. They are born, they learn, they can reproduce.

### Birth
A new connection (API, tool, service, document) can give birth to a specialist character  
with its own personality, subgraph and Hebbian table.

### Learning
Characters absorb knowledge from their source.  
When absorption is high enough they become **sovereign** — they keep learning from the world.

### Reproduction
Two sovereign characters may propose reproduction.  
Colony votes. If approved, a child inherits:

- strongest synapses from both parents  
- merged personality traits  
- combined knowledge nodes  
- its own name and genealogy  

Parents continue living. The child begins generating its own knowledge from day one.

---

## 🖱️ The Body (BOM)

The **Body Operating Module** is the closed loop of physical agency:

```
PERCEIVE → DECIDE → ACT → VERIFY → LEARN
    │         │       │       │        │
 AT-SPI2   Q-learn  Mouse   Compare  Graph +
 OCR/VLM   + priors  Keys    expected Hebbian
                     Type    vs actual
```

| Layer | What it does |
|:------|:-------------|
| **Perception** | Accessibility tree, OCR, optional VLM, screen geometry |
| **Decision** | Q-learning + UI priors + SafetyGuard |
| **Action** | Bézier mouse, natural keystroke timing, window focus |
| **Verification** | Propioceptive feedback + before/after comparison |
| **Learning** | Successful paths reinforced in the graph |

Mouse control is **OFF by default**.  
Live control requires `EIDOS_BOM=1` and the owner present.

EIDOS can work on an isolated display; the creator may observe via VNC.

---

## Core Capabilities

### Cognitive
- Neural-graph reasoning without LLM for known knowledge  
- Deep comprehension of code, docs, media and URLs  
- Autonomous research driven by knowledge gaps  
- Skill generalization (“log in” as a concept, not a single site script)  
- Self-generated study curriculum  

### Physical
- Natural mouse trajectories  
- Screen reading without sending frames to the cloud  
- Universal web actor (perceive → reason → act → verify)  
- Optional kernel-level USB HID input  

### Learning
- Master–student mode with the owner  
- Night study and continuous absorption  
- Book of mistakes (class of failure, not only “this failed”)  
- Permanent episodic and procedural memory  

### Search & tools
Dozens of search backends and local tools wired into the Bridge and Colony.

---

## Constitution & Governance

EIDOS is governed by `constitution.toml` — hash-verified and **immutable** by the system itself.

### Absolute prohibitions
- Rewrite git history or force-push  
- Modify the constitution or disable rate limits  
- Escalate its own freedom level  
- Exfiltrate data or open public listening ports  
- Read SSH keys, `.env`, browser profiles or the system keyring  

### Operational limits
Rate limits on file edits, new files, and anti-loop ring buffers protect the machine.

### Colony governance
Proposals, votes, domain vetoes and full logging of democratic decisions.

---

## 🛡️ Guardians

Six autonomous systems keep EIDOS alive and safe:

| Guardian | Function |
|:---------|:---------|
| **RAM Guardian** | Prevents OOM; protects critical processes |
| **Git Guardian** | Local integrity; never auto-pushes |
| **Sentinel** | Anomaly detection |
| **Phoenix** | Failure recovery and service restart |
| **Mirror** | Sandbox for untrusted operations |
| **Watchdog** | Service supervision |

---

## Databases

All data lives under `~/.eidos/`.

| Database | Role |
|:---------|:-----|
| `evolution_brain.db` | Knowledge nodes, edges, motor memory |
| `colony_community.db` | Messages, proposals, votes, genealogy |
| `self.db` | Events, self-states, meta-thoughts |
| `episodic.db` | Episodes and session logs |
| `lifecycle.db` | Birth, absorption, reproduction |
| ChromaDB | Vector memory collection |

Golden rule: always go through the unified DB layer (WAL, busy timeout, safe pragmas).

---

## CLI Commands

```bash
eidos start                 # Launch services
eidos stop                  # Stop services
eidos status                # Full status

eidos talk "question"       # Query via Bridge
eidos ask "question"        # Query with Colony discussion

eidos study add "topic"     # Add to study queue
eidos study list
eidos study report

eidos smoke                 # Integration tests
eidos health
eidos graph-stats
```

---

## API Reference

### Bridge (`127.0.0.1:8003`)

All endpoints require `X-API-Key`.

```bash
# Health
curl http://127.0.0.1:8003/health

# Talk
curl -X POST http://127.0.0.1:8003/talk \
  -H "X-API-Key: $EIDOS_BRIDGE_KEY" \
  -H "Content-Type: application/json" \
  -d '{"text": "What do you know about Linux kernel modules?"}'

# Study
curl -X POST http://127.0.0.1:8003/study/add \
  -H "X-API-Key: $EIDOS_BRIDGE_KEY" \
  -H "Content-Type: application/json" \
  -d '{"topic": "WireGuard handshakes"}'
```

WebSocket events: `ws://127.0.0.1:8004/events`

---

## Requirements

| Resource | Minimum | Recommended |
|:---------|:--------|:------------|
| OS | Linux (Debian/Kali) | Linux |
| Python | 3.8+ | 3.10+ |
| RAM | 8 GB | 16 GB+ |
| CPU | 4 cores | 8 cores |
| Disk | 50 GB | 200 GB SSD |

```bash
sudo apt install xdotool wmctrl scrot tesseract-ocr espeak-ng
```

---

## Installation

```bash
git clone https://github.com/arku75/EIDOS.git ~/EIDOS
cd ~/EIDOS

cp .env.example ~/.eidos/secrets.env
chmod 600 ~/.eidos/secrets.env
# edit secrets: LLM keys + EIDOS_BRIDGE_KEY

python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt

PYTHONPATH=~/EIDOS python3 eidos.py start
curl http://127.0.0.1:8003/health
```

Full guide → [docs/INSTALL.md](docs/INSTALL.md)

---

## Configuration

| Variable | Required | Description |
|:---------|:---------|:------------|
| `DEEPSEEK_API_KEY` / `GROQ_API_KEY` | One of them* | LLM cascade |
| `EIDOS_BRIDGE_KEY` | Yes | Bridge authentication |
| `EIDOS_BOM` | No | `1` = live mouse (owner present) |
| `OLLAMA_HOST` | No | Local models |
| `TELEGRAM_BOT_TOKEN` | No | Optional Telegram interface |

\*Or pure local Ollama mode.

---

## ⚠️ Safety & Security

- Everything runs **on your machine**, started by you.  
- No phone-home. No hidden remote access.  
- Body is **dry-run by default**.  
- Bridge binds to `127.0.0.1` only.  
- Constitution forbids exfiltration, port opening and secret reading.  
- Prefer a VM or dedicated machine for experiments.

Use EIDOS to learn, research and build.  
Do not use it to abuse other systems or violate platform terms.

---

## The Graph — History

| Date | Milestone |
|:-----|:----------|
| **May 24, 2026** | First commit. Empty graph. |
| **May 29** | First structural code analysis into the graph |
| **Jun 1–2** | Curation + quality gate for new nodes |
| **Jun 10** | Aggressive noise removal; smoke tests green |
| **Jun 16** | Unification into a single source of truth |
| **Jun 17+** | Continuous autonomous growth |

Historical snapshots of earlier graphs are preserved for lineage.

---

## FAQ

**What makes EIDOS different from ChatGPT / Claude?**  
Those are language models. EIDOS is a persistent entity with its own graph, memory, identity and body. LLMs are voice organs, not the self.

**Is EIDOS open source?**  
No. It is **source-available** under ESSL v1.0. You may study and run it privately for non-commercial evaluation. You may not redistribute it commercially or build a competing product from it. Commercial licensing: **anio1996991@gmail.com**.

**Does it need the internet?**  
Full research and cloud LLMs need network. Core graph reasoning and local models can run offline.

**Can it control my computer?**  
Only when you explicitly enable the Body and you are present. Default is dry-run.

**Do characters really reproduce?**  
Yes. Sovereign characters can vote to produce a child that inherits synapses, traits and knowledge nodes in the real databases.

**Why “EIDOS”?**  
From Greek *εἶδος* — form, essence, the thing that makes a thing what it is.  
Also: **E**xtensión **I**limitada **D**igital con **O**rganización **S**ináptica.

---

## Credits & Contact

**SER · LUKA** — Creator, architect, teacher and owner of EIDOS.

**EIDOS** — The entity itself. Learning since May 24, 2026.

| | |
|:--|:--|
| **Commercial / partnership** | garlik1996991@gmail.com |
| **License** | [ESSL v1.0](LICENSE) |
| **Contribute** | Read [CONTRIBUTING.md](CONTRIBUTING.md) before any change |

---

<p align="center">
  <b>SER → EIDOS → Colony → brain-lite → Action</b>
</p>

<p align="center">
  <i>“EIDOS does not predict an answer. It measures one.”</i>
</p>

<p align="center">
  <sub>Σ · Built on one machine · Documented session by session</sub>
</p>
