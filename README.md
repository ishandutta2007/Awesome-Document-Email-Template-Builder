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
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|-------------|-------------------|--------------------------|
| **[Beefree (RGE Studio)](https://beefree.io/)** | Email and landing page design suite (formerly Beefree, now RGE Studio). Drag-and-drop editor with export to ESPs. **Starter plan is completely free**; Professional adds collaboration and merge tag controls . | Starter: **$0** (free forever); Professional: **$30/month** or $300/year; Business: **$160/month** or $1,600/year  | **Free (Starter)**: full editor with some feature limits (export count capped, no collaboration); **15-day Professional trial** without credit card . |
| **[Stripo](https://stripo.email/)** | Email template builder with export to 80+ ESPs. **Free plan is always free** with 2 members, 4 exports/month, and 10 saved emails. Paid tiers scale export limits and team seats . | Free: **$0**; Basic: **$20/month** (50 exports); Medium: **$45** (300 exports); Pro: **$95** (4,000 exports)  | **Free (forever)**: 2 members, 4 exports/month, 5 test emails/day, 10 saved emails. **No credit card required** . |
| **[Unlayer](https://unlayer.com/)** | Embeddable email, page, popup, and document builder **SDK for developers**. White-label editor that integrates into your own product. **Free tier: forever free** with basic builders. Paid plans priced by export volume . | Free: **$0** (forever); Launch: **$250/month** (5,000 exports); Scale: **$750/month**; Optimize: **$2,000/month**  | **Free**: basic email/page/popup/document builders, no credit card; **14-day free trial** on paid plans (full feature access) . |
| **[Chamaileon](https://chamaileon.io/)** | Collaborative email builder SDK for embedding. **Entry pricing signals vary**: Chamaileon's own comparison lists SDK at **$0 entry** with ~$200/month estimated for 500 MAU; third-party review lists custom pricing from **$400** . | SDK: **$0 entry** (~$200/month at 500 MAU); Custom from **$400**  | **14-day free trial** available; free plan exists for basic use . |
| **[PandaDoc](https://www.pandadoc.com/)** | Document workflow platform with **drag-and-drop document editor and templates**. Free eSign plan includes 5 documents/month and up to 5 reusable templates . | Free: **$0** (5 docs/month); Starter: **$19/seat/month** (annual); Business: **$49/seat/month**  | **Free**: 5 documents/month, 5 templates, limited API access, AI assistants (beta) . **14-day free trial** . |
| **[Dyspatch](https://www.dyspatch.io/)** | Enterprise email production and collaboration platform. Purpose-built for email teams with approval workflows and modular templates . | List (mid-tier, 50K contacts): **$2,000–$3,000/month**; Negotiated: **$1,500–$2,500/month**; Onboarding: **$1,000–$5,000+** . | **No free tier**; demo via sales. Annual contract minimum **12 months** . |
| **[MailerLite](https://www.mailerlite.com/)** | Email marketing platform with **drag-and-drop template builder** and automation. Free plan supports up to 1,000 subscribers with 12,000 monthly emails . | Free: **$0** (1,000 subscribers); Growing Business: **from €9/month**; Advanced: **from €19/month**  | **Free**: up to 1,000 subscribers, 12,000 emails/month, 1 user, drag-and-drop editor, 10 landing pages . |
| **[Mailchimp](https://mailchimp.com/)** | Email marketing platform with **professionally designed templates** and a customizable builder. Free plan available with limited sends; Standard plan includes custom-coded templates . | Standard: **from $20/month** (14-day free trial); Free plan available  | **Free plan**: limited monthly sends; **14-day Standard trial** (up to 24x ROI claim) . |

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
