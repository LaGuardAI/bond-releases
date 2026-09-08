# Starter workspaces

Importable workspace templates for getting started with Lorah. Each `.json`
file in this directory is a Lorah workspace export — open Lorah, go to
**Settings → Workspace → Transfer → Import workspace**, click
**Choose file…**, and select the file. The import creates a new workspace
pre-populated with goals, teammates, shared memory, and rules tuned for a
specific use case.

## Available templates

| File | Use case | Workspace name in Lorah |
|---|---|---|
| [`Sample_Product_R_D_AtlasFlow.json`](Sample_Product_R_D_AtlasFlow.json) | Product & R&D team building a product (uses a fictional "AtlasFlow" product as the worked example) | Sample — Product & R&D: AtlasFlow |
| [`Sample_GTM_Launch_SignalNest.json`](Sample_GTM_Launch_SignalNest.json) | Go-to-market launch team running a launch (fictional "SignalNest" product) | Sample — GTM Launch: SignalNest |
| [`Sample_Personal_Board_of_Directors.json`](Sample_Personal_Board_of_Directors.json) | Personal board of directors — a panel of specialist teammates that challenge you on career, financial, strategic, and life-decision questions | Sample — Personal Board of Directors |

## What's in each export

Lorah's workspace export bundle (the JSON file) includes:

- **Workspace** — name, goals, constraints, principles, priorities
- **Teammates** — name, personality, role, responsibilities, deliverable format, rules, and each teammate's sample conversation from the worked example
- **Memory** — the Memory included in these templates belongs to the worked example. It is not knowledge captured or approved from your own project. Review, replace or remove it before relying on it
- **Documents** — pinned reference docs (worked-example artifacts; you can replace with your own)
- **Sync records** — sample sync runs from the worked example, including their example token and cost figures

Provider keys and other credentials are stripped from each export, and
workspace and teammate cost totals are reset. The sample conversations,
sync records and their token and cost figures belong to the worked example
and describe no usage of yours. These templates are configured for
Anthropic models. Before sending a message, connect the required Anthropic
API access in **Settings → API Keys**, or change the Specialist to another
supported model and configure its access.

## Import flow

1. Open Lorah on your machine (see [`../docs/install-windows.md`](../docs/install-windows.md) / [`../docs/install-macos.md`](../docs/install-macos.md) if you're not installed yet)
2. **Settings → Workspace → Transfer → Import workspace**
3. Click **Choose file…** and pick the `.json` file
4. The import creates a new project containing the worked example. Review
   and confirm each Specialist's imported instructions before using that
   Specialist. Imported Memory is not automatically accepted as your project
   knowledge. Review the items you want to keep; leave the rest pending or
   reject them.

If you've never run Lorah before, complete the
[first-run setup](../docs/first-run.md) first (a project and model access
through a supported setup path), then import the template afterward into a
fresh workspace. No beta invitation or license code is needed to start.

## Worked examples

The fictional products (AtlasFlow, SignalNest) and the Personal Board's
sample decisions are deliberately concrete so you can see what real Lorah
usage looks like before adapting the templates to your own work. Treat
them as **scaffolding to learn from** — clone the structure, replace the
content with yours.

---

Stuck? Email [support@lorah.ai](mailto:support@lorah.ai).
