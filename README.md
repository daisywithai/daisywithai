# Daisy Grace Thomas

### Agentic AI Lead Consultant · AI Mentor · Founder, DaisyWithAI

[![Typing hook](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=800&color=6E40C9&center=true&vCenter=true&width=720&lines=Most+AI+projects+die+as+demos.;I+build+agents+that+reach+production.;Webhooks+in.+Decisions+made.+Work+done.;Agentic+AI+for+regulated+enterprises.)](https://linkedin.com/in/daisywithai)

**Your team doesn't need another chatbot. It needs AI agents that plan, call tools, and finish the job.** I design them, ship them, and train your people to run them.

[![](https://img.shields.io/badge/Book_a_Discovery_Call-6E40C9?style=for-the-badge&logo=googlecalendar&logoColor=white)](mailto:daisywithai@gmail.com) [![](https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/daisywithai) [![](https://img.shields.io/badge/Get_Mentored-0F9D58?style=for-the-badge&logo=bookstack&logoColor=white)](mailto:daisywithai@gmail.com?subject=AI%20Mentorship)

---

## ⚡ Why companies call me

> 80% of enterprise AI pilots never make it past the demo stage. The model is rarely the problem. Integration, control and trust are.

That gap is where I work. 10+ years turning business problems into production systems across **Healthcare, Aerospace, EdTech and IT**. Engineering roots at **Rolls Royce** and **Boeing**. Now I build agentic AI that survives audits, edge cases and real users.

| Business pain | What I deliver |
| --- | --- |
| "We have AI pilots, nothing in production" | Production-grade agent architecture with guardrails and rollout plan |
| "Our teams drown in tickets and manual requests" | Agents that triage, route and fulfil inside ServiceNow and your stack |
| "We're regulated. We can't risk a rogue AI" | Human-in-the-loop controls, audit trails, GAMP5-aware validation |
| "Our people don't know how to use AI" | Hands-on AI enablement programs that turn non-coders into builders |

---

## 🏗 Agent architecture I build

```mermaid
flowchart LR
    A[Event Sources<br>WhatsApp · Email · ServiceNow · Slack · API] -->|Webhook / REST| B[Ingress Layer<br>Auth · Signature check · Dedup]
    B --> C[Orchestrator<br>LangGraph · n8n · Python]
    C --> D{Planner LLM<br>Claude · GPT · Gemini}
    D -->|Function calling / MCP| E[Tool Layer<br>APIs · ServiceNow · DBs · Search]
    D <-->|Retrieve / Store| F[(Memory<br>Vector DB · Session state)]
    E --> D
    D --> G{Guardrails<br>Policy · PII · Confidence}
    G -->|Risky / Low confidence| H[Human Approval]
    G -->|Safe| I[Action + Response]
    H --> I
    I --> J[Observability<br>Traces · Evals · Cost]
    J -.->|Feedback loop| C
```

---

## 🧰 Agentic AI tech stack

| Layer | Tools & techniques |
| --- | --- |
| **Foundation Models** | Claude, GPT, Gemini, Llama, Mistral, open models via Hugging Face |
| **Agent Frameworks** | LangChain, LangGraph, CrewAI, AutoGen, OpenAI Agents SDK, Claude Agent SDK |
| **Agent Protocols** | MCP (Model Context Protocol), A2A, function calling, JSON Schema tools, structured outputs |
| **Workflow Automation** | n8n, Make, Zapier, Power Automate, ServiceNow Flow Designer & IntegrationHub |
| **Triggers & Integration** | Webhooks, signature verification, REST APIs, OAuth 2.0, Meta WhatsApp Cloud API, Gmail & Google Workspace APIs |
| **Memory & RAG** | Embeddings, chunking strategies, LlamaIndex, Pinecone, ChromaDB, pgvector, hybrid search |
| **Reasoning Patterns** | ReAct, planner/executor, reflection, multi-agent handoffs, tool routing |
| **Safety & Governance** | Guardrails, PII masking, prompt injection defence, HITL approvals, audit logging, GAMP5 validation |
| **Evals & Observability** | LangSmith, Langfuse, Promptfoo, Ragas, golden datasets, regression evals, tool-call accuracy |
| **Deploy & Ops** | Python, FastAPI, Docker, GitHub Actions, Cloudflare, self-hosted n8n, secrets management |
| **AI Dev Tools** | Claude Code, Cursor, GitHub Copilot, ChatGPT, Gemini, Perplexity, NotebookLM |

![](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white) ![](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white) ![](https://img.shields.io/badge/ServiceNow-62D84E?style=flat-square&logo=servicenow&logoColor=white) ![](https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=anthropic&logoColor=white) ![](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white) ![](https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white) ![](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black) ![](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![](https://img.shields.io/badge/WhatsApp_API-25D366?style=flat-square&logo=whatsapp&logoColor=white) ![](https://img.shields.io/badge/Webhooks-000000?style=flat-square&logo=webhooks&logoColor=white) ![](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white) ![](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) ![](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white) ![](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white) ![](https://img.shields.io/badge/Cursor-000000?style=flat-square&logo=cursor&logoColor=white) ![](https://img.shields.io/badge/Copilot-000000?style=flat-square&logo=githubcopilot&logoColor=white)

---

## 🚀 Featured builds

| Project | What it does | Under the hood |
| --- | --- | --- |
| **CareerAgent** | Agentic AI that analyses profiles, matches roles and drafts outreach for job seekers | Python, LLM tool calling, RAG, structured outputs |
| **Daisy AI Agent** | WhatsApp agent that handles conversations end to end, 24/7 | Meta webhook ingress, n8n orchestration, Gemini, session memory, Cloudflare Tunnel |
| **ServiceNow Agentic Workflows** | AI-driven triage, routing and fulfilment for enterprise ITSM | ServiceNow Flow Designer, Scripted REST, LLM classification |
| **Agent Testing Framework** | Validates agent decisions, tool calls and failure handling before go-live | Python, eval datasets, adversarial test suites |

---

## 🔁 The DaisyWithAI delivery method

```
01 DISCOVER  →  Business outcome, risk, ROI. Which jobs should an agent own?
02 DESIGN    →  Tools, schemas, auth, memory, guardrails. Architecture on paper first.
03 BUILD     →  Orchestration, tool calling, integrations, webhooks.
04 CONTROL   →  Confidence gates, human approvals, audit trails.
05 PROVE     →  Evals, edge cases, adversarial tests, API failure drills.
06 SCALE     →  Observability, cost tuning, team enablement, handover.
```

---

## 💼 Work with me

| 🧭 AI Strategy Sprint   For leaders who need clarity.   Identify your top agent use cases, ROI and risk. Leave with a roadmap and architecture you can fund. | 🏗 Agent Build & Advisory   For teams ready to ship.   I lead design and delivery of production agents integrated with your systems. Guardrails and evals included. | 🎓 AI Mentorship & Training   For people and teams leveling up.   1:1 mentoring and corporate workshops on AI automation and agentic AI. Built for non-coders and career pivoters. |
| --- | --- | --- |

---

## 🎓 Credentials

**MSc Data Science**, Deakin University **Generative AI**, IIT Patna **10+ years** across ServiceNow, enterprise integration and data Aeronautical engineering foundation · Rolls Royce · Boeing

---

## 📬 Let's build your first production agent

**Have an AI idea stuck in pilot? A process your team hates? A team that needs to get AI-ready?** Send me one line about it. I reply within 24 hours.

[![](https://img.shields.io/badge/Email_Me-daisywithai@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:daisywithai@gmail.com?subject=Agentic%20AI%20Consulting%20Enquiry) [![](https://img.shields.io/badge/DM_on_LinkedIn-@daisywithai-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/daisywithai)

\


![](https://github-readme-stats.vercel.app/api?username=daisywithai&show_icons=true&hide_border=true&title_color=6E40C9&icon_color=6E40C9) 

*Agents that don't just answer. Agents that deliver.*

📍 Chennai, India · Working with clients globally
