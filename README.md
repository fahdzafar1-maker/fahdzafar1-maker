# Fahd Zafar

**AI Automation Engineer** — multi-agent systems, RAG pipelines, and workflow automation.

I build AI systems that run real business operations, not demos. Most of my work
sits where an LLM meets a database, an API, and someone's actual money — so I spend
most of my time on the part that decides what happens when the model is wrong.

---

### What I work on

- **Multi-agent orchestration** — supervisor/specialist architectures with bounded
  autonomy, explicit escalation paths, and an audit trail for every decision
- **RAG** — pgvector retrieval with tenant isolation and relevance floors, so an
  agent answers from the customer's own documents or says it doesn't know
- **Guardrails** — allowlisted data access, parameterised queries, least-privilege
  database roles, prompt-injection handling, dedup, retries, and cost ceilings
- **Integrations** — webhooks, REST APIs, WhatsApp Business, voice agents, CRMs

---

### Featured

**[tradedesk-ai](https://github.com/fahdzafar1-maker/tradedesk-ai)** — a multi-agent
AI front desk for home-service contractors.

A supervisor routes each inbound call or message to one of four specialists; RAG
answers from the contractor's own documents; a price tool reads through an allowlist;
anything dangerous goes to a human immediately. Every agent decision is logged and
surfaced on a FastAPI dashboard.

The security design is the part worth reading: the agent cannot write SQL at all —
it calls a typed tool, a validator enforces an allowlist, the query is a fixed
template with bound parameters, and the database role only has SELECT.
I build with Claude as my primary development assistant.

---

### Stack

`n8n` · `PostgreSQL` · `pgvector` · `OpenAI` · `Docker` · `Railway` . 'anthropic'

---

### Contact

I work asynchronously and in writing — it is how I do my clearest work.

- Email — fahdzafar1@gmail.com
- LinkedIn — [linkedin.com/in/fahd-z-b57b283a9](https://www.linkedin.com/in/fahd-z-b57b283a9)
