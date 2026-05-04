# 🌌 Orion — Project Notes & Roadmap

## What is Orion?
Orion is a personal open brain / memory system built to capture, search, and recall thoughts, ideas, and knowledge across sessions using MCP (Model Context Protocol).

---

## 🧠 Core Concepts
- **Thoughts** are the atomic unit — a single idea, reflection, or piece of information.
- **Topics** group thoughts thematically.
- **People** link thoughts to individuals in your life or network.
- **Search by meaning** (semantic search) lets you find related thoughts even without exact keywords.

---

## 🗺️ Roadmap

### ✅ Done
- [ ] Basic thought capture (`capture_thought`)
- [ ] Semantic search (`search`, `search_thoughts`)
- [ ] Fetch by ID (`fetch`)
- [ ] List recent thoughts with filters (`list_thoughts`)
- [ ] Thought stats overview (`thought_stats`)

### 🔄 In Progress
- [ ] Tagging system for cross-topic linking
- [ ] Recurring review prompts (weekly reflection)

### 🚀 Planned
- [ ] Export thoughts to Markdown / PDF
- [ ] Daily digest summary via Claude
- [ ] Web UI for browsing the brain
- [ ] Notion / Obsidian sync
- [ ] Voice-to-thought capture

---

## 📋 Usage Tips
- **Be specific** when capturing thoughts — include context (date, project, mood).
- **Use topics consistently** so filters and stats are meaningful.
- **Search before capturing** to avoid duplicates.
- Review `thought_stats` weekly to see patterns in what you're thinking about.

---

## 🔗 Integrations
- Claude (via MCP at `open-brain-mcp`)
- Supabase (backend storage)

---

## 📅 Last Updated
<!-- Update this when you make changes -->
May 2026
