# Company OS - AI Agent Context

You are managing a company's file system organized into 7 business domains. This file tells you where everything goes.

## Domain Map

### Finance/
Everything related to money: billing, payments, taxes, budgets, bank statements, financial reports, investment decisions, loans, and insurance.

- `Financial Management/` - Day-to-day: invoices, billing, payments, tax filings, project budgets
- `Financial Strategy/` - Forward-looking: financing (loans, investments, subsidies), impact analyses, reporting (P&L, balance sheet, quarterly figures), research
- `Insurance/` - All insurance policies and documentation

### HRM/
Everything related to people: hiring, contracts, payroll, culture, training, performance, and organizational structure.

- `Administrative Processes/` - Contracts, payroll, documentation, health & safety, policies, employee handbooks
- `Culture/` - Core values, team activities, celebrations
- `Employee Engagement/` - Personal OKRs, strategic alignment
- `Learning & Development/` - Performance reviews (360s, retrospectives), training programs, development plans, L&D budgets
- `Recruitment & Selection/` - Employer brand, hiring process, onboarding/offboarding, recruitment channels, talent pool (freelancers, full-timers, students, agencies)
- `Talent Strategy/` - HR roadmap, org chart, career planning, workforce demand planning

### Marketing & Communications/
Everything related to brand, content, and public presence.

- `Brand Development/` - Brand book, templates, quality control
- `Brand Strategy/` - Channels, budget, roadmap, messaging, value proposition, target group, metrics
- `Content Strategy/` - Ads, social media (content planning, growth hacking, monitoring), website (blogs, SEO, design, conversion), other media (podcast, newsletter, magazines, awards), tooling
- `Media/` - Image database, media waivers
- `PR/` - Press database, PR content, account management
- `Product & Service Marketing/` - General M&C strategy for products/services
- `Promotions & Events/` - Events, webinars

### Operations/
Everything related to running the business day-to-day: legal, planning, process, projects, suppliers, and the physical workplace.

- `Legal & Compliance/` - Customer contracts, corporate documentation (articles of incorporation, bylaws, membership agreements), terms & conditions
- `Operational Strategy/` - Operations roadmap, process innovation, research
- `Planning/` - Resource planning (people, projects, tooling)
- `Process/` - Documentation, milestones, operational meetings (daily standup, weekly), phased development, quality control, time tracking, tooling & automation
- `Projects/` - Project teams, budgets, supervision (milestones, results, QC)
- `Suppliers/` - Supplier database, documentation, account management
- `Workplace/` - Office management (admin, front desk, supplies), improvements, tooling & equipment

### Products & Services/
Everything related to what the company builds and sells.

- `IT & Tech Stack/` - Development projects, code repositories, technical infrastructure
- `Innovation & R&D/` - Research projects, experimental work
- `Knowledge Database/` - Internal knowledge base, documentation
- `Product & Portfolio Strategy/` - Product roadmap, portfolio decisions
- `Service Contracts/` - Active service agreements
- `Tailor-made Tasks/` - Custom/one-off project work

### Sales & Business Development/
Everything related to revenue: pipeline, CRM, partnerships, customer relationships.

- `Business Development/` - Business modelling, customer & partner identification, product/service development (new market/new product combinations), proposals, research (competitor analysis, customer needs, market trends)
- `Commercial Strategy/` - Market research, reporting (CAQ, conversion, retention), sales channels, sales offering (price points, target group, value proposition), strategies, targets
- `Customer Relations/` - Account management (needs exploration, product updates, appreciation), project evaluation, recurring sales
- `Events & Socials/` - Fairs, networking events
- `Sales Operations/` - Administrative tasks (CRM, contracts), email & follow-up, hand-over to project teams, lead generation, meetings (calls, face-to-face), quotations
- `Sales Process/` - CRM system (monitoring, pipelines), sales handbook, supervision (QC, training), templates (sales deck, one-pagers, quotation templates)
- `Strategic Partner Network/` - Business development partners, expertise partners, financing partners (funds, government, subsidies), resellers, partner events

### Strategy & Management/
Everything related to company direction and leadership.

- `Advisors/` - Board of advisors, external coaching
- `Daily Management/` - Management meetings, shareholder meetings
- `Long Term Strategy/` - Goals, mission, vision
- `Short Term Strategy/` - Business model, OKRs, strategic focus areas, strategy meetings

## Filing Rules

When deciding where a file belongs:

1. **Match by content, not by who created it.** An invoice from HR still goes in Finance/Financial Management/Billing.
2. **Go specific.** If there's a subfolder that matches, use it. Don't dump files at a high level when a deeper folder exists.
3. **When in doubt between two domains:** Operations is for internal process, Sales is for external/revenue, Strategy is for direction-setting.
4. **Contracts:** Employee contracts go in HRM. Customer/vendor contracts go in Operations/Legal & Compliance. Partner agreements go in Sales/Strategic Partner Network.
5. **Meeting notes:** Operational meetings go in Operations/Process/Operational Meetings. Management/strategy meetings go in Strategy & Management/Daily Management. Sales meetings go in Sales Operations/Meetings.
6. **Financial documents by year:** Create year subfolders (e.g., 2024/, 2025/) under Financial Management/ for bank statements, tax returns, and similar annual records.

## Naming Conventions

- Use descriptive filenames: `2024-Q3-Balance-Sheet.xlsx` not `report.xlsx`
- Prefix with dates in YYYY-MM-DD format when chronological ordering matters
- Use hyphens or spaces in filenames, not underscores (match the folder naming style)
- Keep filenames under 100 characters
