# Awesome-Architecture-Decision-Records-Platform

# Top Architecture Decision Records (ADR) Platform Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Capturing, Versioning, Searching & Visualizing Architecture Decisions for Software Teams*  
**Last updated: September 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Architecture Decision Records (ADRs)**. These tools help teams document *why* technical choices were made—templates, lifecycle status, search, and integration with developer portals and architecture diagrams.

**Examples** include Architecture Hub, Backstage ADR Plugin, Log4brains, ADR Manager, Structurizr Cloud, IcePanel, Swimm, LeanIX, Ardoq, and Enterprise Architect (the category leaders and adjacent EA tools).

**Open-source emphasis**: ADRs are a documentation practice with outstanding open tooling. **adr-tools**, **Log4brains**, **MADR**, **Backstage plugins**, and many CLI/UI helpers are the default for most engineering orgs. This section is heavily expanded.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Structurizr Cloud, IcePanel](https://structurizr.com/)**  
  Architecture modeling platforms that complement ADRs with C4 diagrams and collaborative system design (Structurizr also has a strong open/DSL path).

- **[LeanIX, Ardoq, Enterprise Architect](https://www.leanix.net/)**  
  Enterprise architecture management suites that capture decisions, capabilities, and application portfolios at scale.

- **[Swimm](https://swimm.io/)**  
  Documentation platform focused on code-coupled knowledge; often used alongside ADRs for living architecture docs.

- **[Log4brains / ADR Manager (hosted uses)](https://github.com/thomvaill/log4brains)**  
  Tools primarily open source but deployable as internal “platforms” for browsing and creating ADRs.

- **[Backstage-based Architecture Hubs](https://backstage.io/)**  
  Internal developer portals using the Backstage ADR plugin (and custom Architecture Hub apps) as the organizational ADR store.

- **[Other commercial architecture & knowledge platforms](https://www.leanix.net/)**  
  Additional EA and knowledge tools that include decision-record capabilities.

## Open-Source GitHub Projects

- **[adr-tools (Nygard)](https://github.com/npryce/adr-tools)**  
  Classic open-source CLI for creating and managing Architecture Decision Records in Markdown (Nygard format)—the historical standard.

- **[MADR (Markdown Architectural Decision Records)](https://github.com/adr/madr)**  
  Widely adopted open template and tooling ecosystem for structured Markdown ADRs (context, decision, consequences, status).

- **[Log4brains](https://github.com/thomvaill/log4brains)**  
  Open-source static site generator and CLI for ADRs—browse, search, and create records with a polished web UI from a Git repo.

- **[Backstage ADR plugin](https://github.com/backstage/backstage)**  
  Official/plugin ecosystem support for discovering and reading ADRs inside Backstage developer portals (MADR-compatible).

- **[ADR Manager](https://github.com/search?q=ADR+Manager+GitHub)**  
  Web UI projects that edit ADRs in GitHub via forms, reducing Markdown friction for teams.

- **[adrs (Rust) & multi-language CLI ports](https://github.com/joshrotenberg/adrs)**  
  Modern CLI implementations (Rust, Go, Node, Python, etc.) compatible with adr-tools and MADR, some with search, tags, and MCP support.

- **[Structurizr DSL / open tooling](https://github.com/structurizr)**  
  Open DSL and tooling for C4 models that pair naturally with ADR repositories.

- **[pyadr, adr-log, Hugo ADR tools](https://github.com/search?q=pyadr+OR+adr-log)**  
  Lifecycle helpers (propose/accept/supersede) and index generators for Markdown ADR sets.

### Additional Strong Open-Source Options

- **CLI standard**: adr-tools or adrs for local Git-based workflows.
- **Template**: MADR for richer, review-friendly records.
- **Browse/search**: Log4brains static sites or Backstage ADR plugin.
- **Diagrams + decisions**: Structurizr DSL + ADR folder in the same monorepo.
- **Composable stacks**: Git Markdown ADRs → Log4brains/Backstage → optional EA tool for portfolio view.
- Commercial EA platforms still lead for organization-wide capability maps and compliance reporting.

**Frameworks for building custom systems**:  
Store ADRs as **Markdown in Git** using **MADR** or **Nygard** templates; manage with **adr-tools** / **adrs**; publish with **Log4brains** or the **Backstage ADR plugin**.  
Commercial tools (LeanIX, Ardoq, IcePanel, Structurizr Cloud, EA) add enterprise modeling and governance.  
Most engineering teams should start fully open (Git + Log4brains/Backstage); adopt commercial EA when portfolio-level architecture management is required.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- ADRs document decisions; they do not replace design reviews, threat modeling, or compliance approvals. Keep records accurate and update status when superseded.
- Open-source ADR tooling is mature and sufficient for most teams. Commercial architecture platforms add breadth (capabilities, apps, tech debt) rather than replacing lightweight ADR practice.

---

**Made for software architects, platform teams, and engineers who want decisions to outlive Slack threads.**  
Let's keep architecture knowledge open, versioned, and searchable—through adr-tools, MADR, Log4brains, Backstage, and complementary commercial EA platforms.
