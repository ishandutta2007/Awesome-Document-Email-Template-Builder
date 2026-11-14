# Awesome-Document-Email-Template-Builder

## Top Document & Email Template Builder Ecosystem

**Curated List of SaaS Platforms & Open-Source GitHub Projects**  
*Focused on Drag-and-Drop Email Design, Document Templating & White-Label Embedding*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Document & Email Template Builders**. These tools help teams design responsive emails, create reusable document templates, and embed drag-and-drop editors into their own products—covering everything from standalone email builders to white-label SDKs for SaaS applications.

**Examples** include Beefree (RGE Studio), Stripo, Unlayer, Chamaileon, Dyspatch, MailerLite, PandaDoc, and open-source alternatives like Mosaico and Licensor (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted email template design, open-source document templating, and community-driven builders—ideal for organizations seeking to avoid per-export fees and white-label SDK pricing. The open-source landscape is genuinely thin for **drag-and-drop email builders** (most commercial SDKs are proprietary), but functional for **document templating and rendering**: **Mosaico** provides a self-hosted email template editor , and **Licensor** offers a desktop document template engine with variable substitution .

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saas-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The global email marketing software and document generation markets represent a combined market size of approximately **$6.5B to $7.2B** (with email marketing software valued at ~$2.5B–$2.8B growing at ~11.5% CAGR, and document generation software reaching ~$4.1B–$4.4B growing at ~9.7% CAGR). 

The sector exhibits **moderate fragmentation with high concentration at the macro suite level**: while broad marketing and workflow suites (e.g., Mailchimp/Intuit, PandaDoc) capture the bulk of total market revenue through winner-take-most distribution and SMB lock-in, specialized drag-and-drop template builders and embeddable SDKs (e.g., Beefree, Stripo, Unlayer) maintain a highly fragmented, vibrant niche serving bespoke developer integration and multi-ESP workflows.

## SaaS Platforms

| Product | Company Scale (Valuation / Revenue) | Description | Pricing (Starting Tier) | Free Tier / Free Trial Limits |
|---------|------------------------------------|-------------|-------------------------|-------------------------------|
| **[Mailchimp](https://mailchimp.com/)** | **$12B acquisition** (~$800M+ ARR) | Flagship email marketing and automation platform featuring rich email template libraries and visual builder. | Standard: **$20/month** (500 contacts) | **Free forever plan**: max 250 contacts, 500 email sends/month (daily cap of 250 sends); **14-day Standard trial** available. |
| **[PandaDoc](https://www.pandadoc.com/)** | **$1B valuation** (~$100M+ ARR) | Document workflow and automation platform offering drag-and-drop proposal, contract, and document template design. | Starter: **$19/user/month** (annual) or $35/month | **Free forever plan**: 5 documents/month, 5 templates, eSignatures only; **14-day free trial** of Business plan (capped at 5 test documents, no credit card required). |
| **[MailerLite](https://www.mailerlite.com/)** | **~$90M (€84M) acquisition** (~$18M ARR) | Email marketing and landing page platform with intuitive drag-and-drop builder and automation tools. | Growing Business: **€9/month** (~$10/month, 500 subscribers) | **Free forever plan**: up to 1,000 subscribers, 12,000 emails/month, 1 user seat, 10 landing pages; **30-day free trial** of premium features. |
| **[Beefree (RGE Studio)](https://beefree.io/)** | **~$26M (€24M) parent market cap** ($18.7M ARR) | Standalone and embeddable visual design suite for responsive emails, popups, and pages (subsidiary of publicly traded Growens). | Professional: **$30/month** (or $300/year billed annually) | **Free forever (Starter) plan**: max 6 exports/month, 10 stored designs/pages, includes Beefree badge; **15-day Professional free trial** (no credit card required). |
| **[Stripo](https://stripo.email/)** | **Bootstrapped** (~$4.5M–$4.8M ARR) | Specialized email template design tool featuring modular email blocks, AMP components, and direct export to 80+ ESPs. | Basic: **$20/month** (or $180/year; 50 exports/month) | **Free forever plan**: 2 user seats, 4 exports/month, 5 test emails/day, 10 saved emails (no credit card required). |
| **[Unlayer](https://unlayer.com/)** | **Seed-funded / YC** (~$5M ARR) | Embeddable drag-and-drop builder SDK and web editor for emails, web pages, popups, and documents. | Launch: **$250/month** (5,000 cloud API exports) | **Free forever plan**: $0 for basic web builders on 1 domain (no white-labeling, cloud export limits apply); **14-day free trial** for paid plans. |
| **[Dyspatch](https://www.dyspatch.io/)** | **~$13.4M funded** (~$2.5M ARR) | Enterprise-focused email production environment and modular template builder with approval workflows and localization. | Starter: **$149/month** (or $134.10/month billed annually) | **No standard self-serve free plan**; **Trial / demo evaluation sandbox**: 100 email client render previews provided upon request via sales demo. |
| **[Chamaileon](https://chamaileon.io/)** | **Bootstrapped** (~$660K ARR) | Collaborative email design platform and embeddable SDK with reusable module libraries and real-time co-editing. | Premium Team: **$400/month** (or ~$4,000/year billed annually) | **No standard self-serve free plan**; Guided evaluation sandbox access provided via consultation / product demo call. |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Mosaico](https://github.com/voidlabs/mosaico)** | [![Stars](https://img.shields.io/github/stars/voidlabs/mosaico?style=social&color=white)](https://github.com/voidlabs/mosaico/stargazers) | **The most mature open-source email template editor.** Self-hosted, browser-based drag-and-drop builder for responsive email templates. Generates clean, table-based HTML compatible with major email clients. **Free and open-source** (check repository license). Best for teams wanting a **self-hosted Beefree/Stripo alternative** without per-export fees . |
| **[Licensor](https://github.com/clxrityy/Licensor)** | [![Stars](https://img.shields.io/github/stars/clxrityy/Licensor?style=social&color=white)](https://github.com/clxrityy/Licensor/stargazers) | **Desktop document template manager with variable substitution and rendering.** GNU GPLv3. Templates stored as **Markdown files with YAML front matter** defining name, description, and variables (text, textarea, number, date). **Double-curly-brace variable substitution** (`{{variable_name}}`). Search across templates/documents. **Export rendered documents as `.md` or `.txt`, or as `.zip` with metadata/files**. **Best for generating personalized documents from Markdown templates** without a SaaS dependency . |

### Additional Strong Open-Source Options

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Mosaico (Wikidata entry)](https://www.wikidata.org/wiki/Q114457596)** | — | Wikidata entry confirming Mosaico as an **open-source tool for creating email templates** with source code at `github.com/voidlabs/mosaico` . Use as a reference for the project's open-source status. |

**Frameworks for building custom systems**: Choose **Mosaico** for a self-hosted email template editor (the closest open-source equivalent to Beefree/Stripo) , and **Licensor** for Markdown-based document templating with variable substitution and export . **For embedding a white-label builder into your own product**, the commercial SDKs (Unlayer, Chamaileon, Beefree SDK) remain the only mature options—no open-source equivalent provides the same embeddable, white-label experience.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Template builders may handle customer data in merge tags and personalized content; enforce data minimization and compliance with applicable privacy regulations when using variable substitution.
- **Open-source email builders are scarce; document templating is more viable.** Mosaico is the primary open-source email template editor, but it lacks the polished UX and ESP integrations of Beefree or Stripo . Licensor provides document templating but is a desktop app with Markdown-based templates—not a drag-and-drop visual builder . **Commercial SDK pricing varies dramatically and hidden costs are common**: Unlayer's free tier is genuinely forever-free but paid plans jump to **$250/month** ; Chamaileon's entry signals range from **$0 to $400** depending on source and usage ; Dyspatch is enterprise-only with **$18,000–$30,000 annual TCO** for 50K contacts and **$1,000–$5,000+ onboarding fees** . **Free tiers have meaningful limits**: Stripo caps exports at **4/month** on free, Beefree restricts export counts, and PandaDoc limits documents to **5/month** . Validate export limits and feature gates against your actual production volume before committing.

---

**Made for email marketers, developers, and operations teams building template infrastructure.**  
Let's make document and email template building more open, accessible, and cost-predictable.
