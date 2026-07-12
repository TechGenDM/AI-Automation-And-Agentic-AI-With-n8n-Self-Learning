# 🤖 AI Automation & Agentic AI with n8n — Notes

<div align="center">

![n8n](https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)
![AI Agents](https://img.shields.io/badge/AI%20Agents-FF6F00?style=for-the-badge&logo=openai&logoColor=white)
![Status](https://img.shields.io/badge/status-still%20debugging%20a%20webhook-red?style=for-the-badge)
![Coffee](https://img.shields.io/badge/fueled%20by-coffee%20%E2%98%95-6F4E37?style=for-the-badge)

### *"It's not automation, it's Agentic AI" — me, coping after 3 failed workflows*

</div>

Personal notes, workflow breakdowns, and mild existential crises from the [**Complete AI Automation and Agentic AI Bootcamp with n8n**](https://www.udemy.com/course/complete-ai-automation-and-agentic-ai-bootcamp-with-n8n/) by **Mayank Aggarwal** & **KRISHAI Technologies**.

> 📌 This is my personal learning repo — notes, not a copy-paste of the course. Mistakes, half-understood diagrams, and "aha!" moments included at no extra charge.

---

## 🧠 Me Before vs After This Course

```
Before:  if (task == repetitive) { doItManually(); cry(); }
After:   n8n.trigger() -> agent.think() -> agent.act() -> me.relax();
```

<div align="center">

| Before n8n 😵 | After n8n 😎 |
|:---:|:---:|
| "I'll just do it manually one more time" | "Let the agent handle it" |
| 47 browser tabs open | 1 clean canvas, 47 nodes |
| Copy-pasting API responses at 2 AM | Webhooks doing it while I sleep |
| "What's a webhook?" | "Have you tried MCP?" |

</div>

---

## 📖 About the Course

| | |
|---|---|
| **Platform** | Udemy |
| **Instructors** | Mayank Aggarwal, KRISHAI Technologies Pvt. Ltd. |
| **Duration** | 28+ hours · 171 lectures · 45 sections (yes, I counted, yes, I regret nothing) |
| **Focus** | n8n automation, AI agents, multi-agent architectures, RAG, MCP, real-world projects |

---

## 🚀 Projects Covered

| Project | Key Concepts | Vibe Check |
|---|---|---|
| **Social Media Automation** | Idea generation, app connections, post generation | 🤖 "post it before I overthink it" |
| **GitHub PR Automation Agent** | Webhook triggers, workflow automation | 🔀 no more manually reviewing PRs at midnight |
| **AI Personal Assistant (Swarm Agents)** | Email, calendar & travel sub-agents, Telegram + voice control | 🧠🧠🧠 an actual Jarvis, kind of |
| **WhatsApp Agent** | Meta Business API, doctor-query use case | 📱 chatbot that doesn't say "I'm sorry, I don't understand" |
| **Video Creation with Gemini** | Nano Banana API, image/video generation pipeline | 🎬 director mode: on |
| **Voice Assistant with VAPI** | Voice-triggered n8n agent, appointment booking | 🎙️ "Hey, book that meeting for me" |
| **GitHub AI Technical Assistant** | End-to-end backend + answer flow | 🛠️ Stack Overflow, but it's my agent now |

---

## 🧩 Core Topics

- n8n fundamentals — nodes, canvas, JSON, workflows
- APIs — REST, auth, headers, pagination, error handling *(the 400/401/500 trauma arc)*
- AI Agents & Multi-Agent Systems — Chain of Thought, Parallel, Router/Controller, ReAct, Hierarchical
- Retrieval-Augmented Generation (RAG) — Supabase, Pinecone, self-hosted (Qdrant + Ollama)
- Model Context Protocol (MCP) — n8n Cloud & self-hosted
- Prompt Engineering — Data Extractor, Router, Critic-then-Revise patterns
- Scaling & Self-Hosting — Docker, VPS, queue mode, horizontal scaling
- OpenClaw — agent architecture, skills, security

---

## 🛠️ Tools Used

`n8n` · `OpenAI` · `Gemini` · `Supabase` · `Pinecone` · `Qdrant` · `Ollama` · `VAPI` · `WhatsApp Business API` · `Docker` · `ngrok`

---

## 💭 Quotes From My Debugging Sessions

> "It's not a bug, the agent is just being *creative*."

> "I added error handling. The error handling failed."

> "Why is the webhook not triggering — oh. It's not deployed. Classic."

> "Multi-agent architecture sounds cool until you're the one debugging which agent said what."

---

<div align="center">

### 🔥 Built with curiosity, broken with confidence, fixed with Stack Overflow and n8n docs.

*These notes reflect my own understanding while learning — may be incomplete, simplified, or contain personal interpretations. Refer to the original course for full accuracy.*

⭐ If future-me forgets any of this, past-me left notes. You're welcome.

</div>