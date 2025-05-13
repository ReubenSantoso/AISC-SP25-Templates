# 🌀 Project Cycles Template Repository  
*AISC @ UW – Spring 2025*

> **A ready-to-fork starter kit for the 90 + students building AI agents in the first-ever **AISC Project Cycles** program.*

---

## 📚 What’s inside?

| Folder | Purpose |
|--------|---------|
| **`/Simple RAG Templates/`** | Minimal, self-contained notebooks that walk you through classic **Retrieval-Augmented Generation** pipelines. Each file is a “cookbook” experimenting with a different combination of **embedding model** (OpenAI *text-embedding-3*, Hugging Face *E5-small*, etc.) and **LLM back-end** (GPT-4o, Claude-3, Gemma 1.1, …). Clone, swap keys, run – perfect for first-week prototypes. |
| **`/Agentic RAG Templates/`** | Step-up examples that introduce **agent patterns**: <br>• **Single-agent** scripts that plan → retrieve → generate in one loop. <br>• **Manager-agent + specialist** set-ups where a router LLM delegates to tools (function-calling API) like SQL, Pandas, or vector search. <br><br>📝 *Highlight*: `university_rag_pipeline.ipynb` shows why numeric CSV columns don’t belong in a vector DB. It spins up a Pandas-helper agent for exact cost-of-attendance queries **and** a semantic agent for fuzzy “culture” questions—all in ~200 lines of plain Python (no LangChain). |
| **`/Program Resources/`** | PDFs, slides, and week-by-week deliverable checklists mirrored from the master Project Cycles Notion board. |

---

## 🗣️ About **Project Cycles**

Project Cycles is AISC’s quarterly build program where small squads spend **six weeks shipping an AI agent**—culminating in a live ✨ **Demo Day** ✨.  
*More context & the full curriculum:* <https://sp24-projectcycles.notion.site/?pvs=4>

### Why this repo matters

* **90 + students** need a safe launchpad ⇢ we give them plug-and-play templates.  
* Mixing **no-code → full-code** tracks means every skill level is welcome.  
* Agent techniques (RAG, function-calling, tool routing) so teams start with best practices, not boilerplate spaghetti.

---

## 🌱 Quick start

```bash
# clone your own copy
gh repo fork ReubenSantoso/AISC-SP25-Templates --clone
cd AISC-SP25-Templates
