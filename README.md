# Archipelago Cowork Template

A complete company folder structure designed to be managed by AI agents. 307 directories across 7 business domains, organized so that an AI assistant can file, retrieve, and manage your company's entire knowledge base without ambiguity.

## Why this exists

Traditional company file structures are a mess. Documents end up in random folders, naming conventions drift, and nobody can find anything. The usual fix is hiring someone to organize it, writing documentation nobody reads, or just giving up and searching for everything.

AI agents change this equation. Tools like Claude, Cursor, and Copilot can now manage files, but they need a structure they can reason about. If your folders are inconsistent or ambiguous, the AI doesn't know where to put things either.

This template gives your AI agent a clear, comprehensive map of your entire business. Every department, every function, every process has a place. The folder names are self-documenting. The hierarchy is logical. An AI agent can look at a document and know exactly where it belongs.

One person with an AI agent can now do what used to require an ops team, an office manager, and a shared drive admin.

## The 7 Domains

| Domain | What it covers |
|--------|---------------|
| **Finance** | Financial management, strategy, reporting, taxes, insurance |
| **HRM** | Hiring, onboarding, contracts, culture, learning & development |
| **Marketing & Communications** | Brand, content strategy, social media, PR, events |
| **Operations** | Legal, planning, process, projects, suppliers, workplace |
| **Products & Services** | Tech stack, R&D, knowledge base, service contracts |
| **Sales & Business Development** | Pipeline, CRM, partnerships, business development |
| **Strategy & Management** | Vision, OKRs, advisors, management meetings |

## Structure

```
archipelago-cowork-template/
├── Finance/
│   ├── Financial Management/
│   │   ├── Billing/
│   │   ├── Financial Tooling/
│   │   ├── Organisational Performance/
│   │   ├── Payments/
│   │   ├── Project Budgets/
│   │   └── Taxes & Surcharges/
│   ├── Financial Strategy/
│   │   ├── Financing/
│   │   ├── Impact Analyses/
│   │   ├── Reporting/
│   │   └── Research/
│   └── Insurance/
├── HRM/
│   ├── Administrative Processes/
│   ├── Culture/
│   ├── Employee Engagement/
│   ├── Learning & Development/
│   ├── Recruitment & Selection/
│   └── Talent Strategy/
├── Marketing & Communications/
│   ├── Brand Development/
│   ├── Brand Strategy/
│   ├── Content Strategy/
│   ├── Media/
│   ├── PR/
│   ├── Product & Service Marketing/
│   └── Promotions & Events/
├── Operations/
│   ├── Legal & Compliance/
│   ├── Operational Strategy/
│   ├── Planning/
│   ├── Process/
│   ├── Projects/
│   ├── Suppliers/
│   └── Workplace/
├── Products & Services/
│   ├── IT & Tech Stack/
│   ├── Innovation & R&D/
│   ├── Knowledge Database/
│   ├── Product & Portfolio Strategy/
│   ├── Service Contracts/
│   └── Tailor-made Tasks/
├── Sales & Business Development/
│   ├── Business Development/
│   ├── Commercial Strategy/
│   ├── Customer Relations/
│   ├── Events & Socials/
│   ├── Sales Operations/
│   ├── Sales Process/
│   └── Strategic Partner Network/
└── Strategy & Management/
    ├── Advisors/
    ├── Daily Management/
    ├── Long Term Strategy/
    └── Short Term Strategy/
```

Each of these expands 3-5 levels deep. 307 directories total. See the full tree in [STRUCTURE.md](STRUCTURE.md).

## Getting Started

### Quick setup

```bash
git clone https://github.com/archipelagoaec/archipelago-cowork-template.git
cp -r archipelago-cowork-template/Finance ~/your-company/
cp -r archipelago-cowork-template/HRM ~/your-company/
# ... or just copy the whole thing
```

### With an AI agent

Drop this into your workspace and point your AI agent at the `CLAUDE.md` file. It contains a complete map of the structure and filing rules so the agent knows where everything goes.

If you're using Claude Desktop (Cowork mode), Claude Code, Cursor, or any AI tool that reads project context files, the agent will automatically pick up the structure and start filing things correctly.

### Adapt it

This is a starting point. Your company might not need every folder, or you might need extras. Prune what you don't need, extend what you do.

## How AI agents use this

The included `CLAUDE.md` file tells AI agents:

- What each top-level domain contains
- How to decide where a file belongs
- Naming conventions to follow
- How to handle files that could fit multiple locations

When you ask your AI agent to "file this invoice" or "save these meeting notes," it doesn't have to guess. The structure makes the answer obvious.

## Origin

This template is based on the [Business Mindmap: Activity Radar](https://miro.com/miroverse/business-mindmap-activity-radar/) by [Kristel Thieme](mailto:kristel@raccoon.games) of Raccoon Games. The Activity Radar maps out every function a company needs, from strategy down to office supplies. We extracted the full node hierarchy from the Miro mind map and converted it into a 307-directory folder structure using Claude in Cowork mode.

The idea: if AI agents are going to manage your company's files, give them a structure that's comprehensive enough that nothing falls through the cracks, and unambiguous enough that filing decisions are deterministic.

## Credits

- **Folder structure**: Based on the Business Mindmap: Activity Radar by Kristel Thieme ([@raccoon.games](mailto:kristel@raccoon.games))
- **AI adaptation**: [Archipelago](https://archipelagoaec.com) with Claude

## License

MIT. Use it however you want, adapt it to your company, share it with your team.
