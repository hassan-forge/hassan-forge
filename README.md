## Hi, I'm Hassan

I'm a forward deployed AI engineer. I work with a team on a real process, find the manual steps that slow it down, and replace them with AI agents, RAG assistants and automations that run inside the tools the team already uses.

Before moving fully into AI work I spent 4+ years building production software: API integrations, real-time data sync, auth, testing and CI/CD for startup and enterprise clients.

### What I build

- **AI agents** that read, decide and act across a CRM, inbox, documents and internal APIs, with a person approving the steps that touch customers or money
- **RAG assistants** that answer from a company's own documents and data, with a source on every answer and an honest "I don't know" when the answer isn't there
- **MCP servers** that let Claude, ChatGPT or a custom agent use internal systems, with clear permissions and an audit log
- **Workflow automation** in n8n, Make or Zapier, and Python or Node.js services when a workflow tool isn't enough

### Client work

| Project | What it is |
|---|---|
| [AI Study-Abroad Counselor](case-studies/study-abroad-ai-counselor.md) | Multi-agent RAG counselor for a study-abroad consultancy. Answers student questions from the consultancy's own data and qualifies leads for sales. **Live in production, serving students across 23 countries.** LangGraph, Qdrant, OpenAI, FastAPI, Next.js, AWS |
| [Admitly](case-studies/admitly.md) | 8 AI agents running the student journey across 13 automated stages, from first inquiry to post-arrival follow-up, with a dashboard for the team. In final testing. Gemini 2.5 Flash, FastAPI, Gmail automation, Flutter Web, AWS |
| SparkEngine | Backend for a no-code agentic automation platform: multi-agent orchestration, tool calls, RAG, and one LLM layer that switches between OpenAI, Llama and DeepSeek. Python, FastAPI, NestJS, Supabase, Redis, Kubernetes |
| AI Lawyer | Retrieval pipelines and context management for a legal assistant, so answers come from the user's own contracts and policies and hold context across long conversations |
| Digbi Health (at Devsinc) | AI meal ratings and an AI coaching chat in a live health app, on the OpenAI API with structured outputs, retries and rate-limit handling |

Client code stays private; the links above are case studies with the architecture and results.

### Open-source projects

| Project | What it shows |
|---|---|
| [study-abroad-counselor-demo](https://github.com/hassan-forge/study-abroad-counselor-demo) | Public rebuild of the AI Study-Abroad Counselor with sample data: 7 LangGraph agents, Qdrant RAG with citations, rule-based lead scoring and CRM handoff, FastAPI with streaming, a Next.js chat, 30 tests and CI |
| [ai-support-agent](https://github.com/hassan-forge/ai-support-agent) | FastAPI support agent: RAG over docs with citations, tool calls (order lookup, ticket creation), a human approval queue for risky actions, evals and tests |
| [crm-mcp-server](https://github.com/hassan-forge/crm-mcp-server) | TypeScript MCP server that gives an AI model safe access to CRM data: read and write tools, a permission allowlist and an audit log |

These are reference projects I built to show how I structure client work. They run locally with no API key (an offline model is included) and switch to a real model with one setting.

### How I work

1. Start from one process and the number it should move: hours saved, response time or errors
2. Ship a working version on real data in 1 to 2 weeks
3. Add the production parts: error handling, logging, cost limits, evals and a handoff to a person
4. Deploy in the client's own accounts and hand over code, docs and a walkthrough

### Stack

- **AI:** Claude API · OpenAI API · Google Gemini · LangGraph · LangChain · multi-agent systems · RAG · Qdrant · Model Context Protocol · Claude Code
- **Backend:** Python · FastAPI · Node.js · TypeScript · PostgreSQL · Supabase · Firebase
- **Automation:** n8n · Make · Zapier · REST APIs and webhooks
- **Delivery:** Docker · GitHub Actions · AWS

### Work with me

Available for AI agent, RAG and automation projects through [Upwork](https://www.upwork.com/freelancers/~01ce9cdccec9e1b9da).
