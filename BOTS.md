# Bots of AI / Intelligence  (docx S5 candidate menu)

These are the **Major sub-functions** of AI / Intelligence from the spec. Each is a bot — a
child decision system that can be instantiated to do the actual work.

## Install flow (matches the Orientation Protocol)
1. **Orient** — the agent runs the Kojiki Orientation Protocol (name / industry /
   jurisdiction / siblings).
2. **Research** — the agent researches the field and decides which sub-functions this
   specific org needs.
3. **Install** — instantiate only the chosen bots:
   ```bash
   cd bots
   python3 install_bots.py brand growth performance-marketing
   ```
   (use the slugs listed below; omit args to install all). Each installed bot becomes a
   full decision system under `bots/<slug>/` with README + AGENT.md + schemas + a stub
   decision record, and registers under this department's group_id for handoffs.

Total candidates: 8.

- `ai-strategy` — **AI Strategy**  ·  titles: Chief AI Officer, VP AI, Head of AI, AI Director, AI Engineer, ML Engineer, Agent Engineer, Knowledge Engineer, AI Evaluation Lead
- `ai-engineering` — **AI Engineering**  ·  titles: Chief AI Officer, VP AI, Head of AI, AI Director, AI Engineer, ML Engineer, Agent Engineer, Knowledge Engineer, AI Evaluation Lead
- `agent-engineering` — **Agent Engineering**  ·  titles: Chief AI Officer, VP AI, Head of AI, AI Director, AI Engineer, ML Engineer, Agent Engineer, Knowledge Engineer, AI Evaluation Lead
- `automation` — **Automation**  ·  titles: Chief AI Officer, VP AI, Head of AI, AI Director, AI Engineer, ML Engineer, Agent Engineer, Knowledge Engineer, AI Evaluation Lead
- `knowledge-engineering` — **Knowledge Engineering**  ·  titles: Chief AI Officer, VP AI, Head of AI, AI Director, AI Engineer, ML Engineer, Agent Engineer, Knowledge Engineer, AI Evaluation Lead
- `evaluation` — **Evaluation**  ·  titles: Chief AI Officer, VP AI, Head of AI, AI Director, AI Engineer, ML Engineer, Agent Engineer, Knowledge Engineer, AI Evaluation Lead
- `ai-operations` — **AI Operations**  ·  titles: Chief AI Officer, VP AI, Head of AI, AI Director, AI Engineer, ML Engineer, Agent Engineer, Knowledge Engineer, AI Evaluation Lead
- `ai-governance` — **AI Governance**  ·  titles: Chief AI Officer, VP AI, Head of AI, AI Director, AI Engineer, ML Engineer, Agent Engineer, Knowledge Engineer, AI Evaluation Lead
