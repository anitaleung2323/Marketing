# Project instructions

## Serenett marketing context

Before performing any Serenett marketing-related task, read `.agents/product-marketing.md` in full, then read and use the smallest set of relevant skills from `.agents/skills/`. This includes product marketing, positioning, messaging, brand voice, copywriting, content, SEO, merchandising, lifecycle, email, social, paid media, campaigns, landing pages, growth, partnerships, and marketing analysis.

Treat `.agents/product-marketing.md` as the project's default Serenett marketing context. Follow its source hierarchy and claims guardrails. Direct user instructions take precedence. Verify dynamic website facts before publishing or relying on them, and update the context file when the user provides new approved long-lived marketing or business information.

For SEO, content performance, acquisition, engagement, landing-page, funnel, or conversion analysis, use the GSC/GA4 Google Sheet registered in the context as the primary quantitative source. Read it live, check sync freshness and date coverage, and apply the data-quality rules in the context before drawing conclusions.

For product classification, category naming or codes, catalog structure, product feeds, collection mapping, merchandising, taxonomy SEO, breadcrumbs, or category-level reporting, read the live `L1&L2&L3&L4(EN)-2026` tab in the product taxonomy Google Sheet registered in the context. It changes periodically, so do not treat a previously copied category list as authoritative. Distinguish the internal L1-L4 taxonomy from the current customer-facing website navigation.

## Skill routing

Use Marketing Skills only when the task matches their stated trigger or the user explicitly names one. Choose the smallest relevant set and read each selected `SKILL.md` in full before acting.

For non-marketing work such as general coding, Shopify implementation, file management, finance, or operations, use the relevant non-marketing workflow. Do not invoke Marketing Skills unless the task also has a marketing objective.

For cross-functional tasks, combine only the necessary workflows. Examples include SEO plus Google Sheets and data-quality analysis for GSC work, copywriting or CRO plus Shopify for storefront copy changes, and taxonomy analysis plus SEO only when classification affects search or customer-facing discovery.
