# Starter workspaces

Importable workspace templates for getting started with Lorah. Each `.json`
file in this directory is a Lorah workspace export — open Lorah, choose
**Settings → Workspaces → Import workspace**, and select the file. The
import creates a new workspace pre-populated with goals, teammates,
shared memory, and rules tuned for a specific use case.

## Available templates

| File | Use case | Workspace name in Lorah |
|---|---|---|
| [`Sample_Product_R_D_AtlasFlow.json`](Sample_Product_R_D_AtlasFlow.json) | Product & R&D team building a product (uses a fictional "AtlasFlow" product as the worked example) | Sample — Product & R&D: AtlasFlow |
| [`Sample_GTM_Launch_SignalNest.json`](Sample_GTM_Launch_SignalNest.json) | Go-to-market launch team running a launch (fictional "SignalNest" product) | Sample — GTM Launch: SignalNest |
| [`Sample_Personal_Board_of_Directors.json`](Sample_Personal_Board_of_Directors.json) | Personal board of directors — a panel of specialist teammates that challenge you on career, financial, strategic, and life-decision questions | Sample — Personal Board of Directors |

> **Note on the Personal Board template.** Earlier drafts of this directory
> planned an "investment research team" template. That was replaced with the
> Personal Board of Directors shape — broader in scope (career + financial +
> strategic decisions, not just investments), and a better fit for Lorah's
> "persistent specialists that hold context across sessions" design.

## What's in each export

Lorah's workspace export bundle (the JSON file) includes:

- **Workspace** — name, goals, constraints, principles, priorities
- **Teammates** — name, personality, role, responsibilities, deliverable format, rules
- **Memory** — decisions, facts, glossary, project context already curated for the use case
- **Documents** — pinned reference docs (worked-example artifacts; you can replace with your own)
- **Recipes** — shared workflows / multi-teammate routines
- **Meetings** — sample meeting structures
- **Syncs + handoffs** — operational scaffolding

Each export is **structure + curated context only**. No conversation
history, no LLM usage data, no provider keys. After import, connect
your own provider keys in Lorah's **Settings → Providers**.

## Import flow

1. Open Lorah on your machine (see [`../docs/install-windows.md`](../docs/install-windows.md) / [`../docs/install-macos.md`](../docs/install-macos.md) if you're not installed yet)
2. **Settings → Workspaces → Import workspace**
3. Pick the `.json` file
4. Lorah opens the new workspace, ready to use

If you've never run Lorah before, complete the
[first-run setup](../docs/first-run.md) first (workspace, provider key,
license code), then import the template afterward into a fresh workspace.

## Worked examples

The fictional products (AtlasFlow, SignalNest) and the Personal Board's
sample decisions are deliberately concrete so you can see what real Lorah
usage looks like before adapting the templates to your own work. Treat
them as **scaffolding to learn from** — clone the structure, replace the
content with yours.

---

Stuck? Email [support@lorah.ai](mailto:support@lorah.ai).
