# Logic Horizon

Systems for document-aware agents — software we can instrument, constrain, and score when an agent plans, uses tools, and runs over a long horizon.

## Philosophy

Open work should be something you can run and inspect. We build the substrate for that: durable runs, typed domain actions, and evaluations that treat an agent as more than a chatbot.

## Projects

| Project | Stage | What it is |
| --- | --- | --- |
| canvas-agent | Private | Visual workflows, durable agent runs, and an AI-native canvas. |
| anyharness | Private | One tool named `harness`: the agent invents a JSON capability inside policy. |
| [aura](https://github.com/bunkernine/aura) | Beta | Taste memory for other AIs — linguistic, aesthetic, and behavioral profile over MCP. |
| [crm.sdk](https://github.com/bunkernine/crm.sdk) | Beta | Typed CRM for agents — contacts, companies, deals, search, reports. |

## Focus

- **Capability** — did the agent invent or select the right tool, not just call one?
- **Policy** — did it stay inside a closed world when the task was open-ended?
- **Taste and preference** — is “good” more than a gold string?
- **Durable work** — does the run still make sense after pause, resume, and tool I/O?
- **Domain tasks** — CRM-style actions with typed contracts, not free-form SQL.

Core maintainer: [Sheikh Sifat](https://github.com/bunkernine).
