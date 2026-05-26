# Starter workspaces

Importable workspace templates for getting started with Bond. Each `.json`
file in this directory is a Bond workspace export — open Bond, choose
**Import workspace**, and select the file. The import creates a new
workspace pre-populated with goals, teammates, and rules tuned for a
specific use case.

Planned templates:

| File | Use case |
|---|---|
| `sample-product-rd.json` | Product R&D team |
| `sample-gtm-launch.json` | Go-to-market launch team |
| `sample-investment-research.json` | Investment research team |

Each template is structure-only — project context, teammate definitions
(name, personality, role, responsibilities, deliverable format), and
rules. No conversation history, no LLM cost data, no provider keys.
After import, you connect your own LLM provider keys in Bond's settings.

_Templates land in this directory once the alpha cohort starts inviting
contributors and we have real-world starter shapes worth shipping. Until
then this is a placeholder — the import flow exists in the desktop app
(Settings → Workspaces → Import workspace) and is exercised regularly,
so when templates land they will work out of the box._
