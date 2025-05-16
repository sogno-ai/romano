# ROMANO — The Autonomous MCP Agent

**Retrieval Orchestration for MCP Automation, Navigation & Operations**

ROMANO is a self-hosted AI automation agent powered by the MCP protocol.  
It executes complex browser and system tasks using structured prompts and real-time orchestration.

---

## 🧠 Key Concepts

- **MCP-native**: Compatible with tools like Playwright-MCP, shell commands, and more.
- **LLM-assisted**: Supports prompt-based reasoning to plan and execute actions.
- **Modular**: Clean separation between orchestrator (client) and executor (server).
- **Self-hosted**: Built for privacy, control, and data sovereignty.

---

## 🛠️ Architecture

- **Client**: sends user intents, receives updates and results
- **Server**: interprets, orchestrates and executes tasks

---

## ✨ Features

- Web automation (click, snapshot, navigation, extraction)
- Shell command execution
- Decision-making via prompt injection
- Scenario playback and scheduling (coming soon)
- Real-time updates via SSE/WebSocket

---

## 🧰 Tech Stack

| Component | Language | Notes |
|----------|----------|-------|
| MVP      | Java (Quarkus/langchain4j) | Fast prototyping |
| Core     | Rust       | Performance, binary deployment |
| LLM      | Any API / `candle`, `llm` | Modular inference |
| UI       | CLI / Next.js / TUI        | Optional |

---
