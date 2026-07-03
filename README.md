# Awesome AI Lead Generation [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of AI-powered tools, frameworks, and resources for automated lead generation, prospecting, and sales intelligence.

Lead generation is being transformed by AI. This list covers everything from AI-powered scrapers and enrichment tools to predictive scoring engines and autonomous outreach agents.

**Why this list?** The intersection of AI and lead generation is the fastest-growing segment in sales tech, yet there was no comprehensive awesome list covering it. This fills that gap.

---

## Contents

- [AI Scraping & Data Extraction](#ai-scraping--data-extraction)
- [Lead Enrichment & Verification](#lead-enrichment--verification)
- [AI Sales Agents & Outreach](#ai-sales-agents--outreach)
- [Predictive Lead Scoring](#predictive-lead-scoring)
- [Intent Data & Buyer Signals](#intent-data--buyer-signals)
- [CRM Intelligence](#crm-intelligence)
- [Email Finding & Verification](#email-finding--verification)
- [Social Selling & LinkedIn](#social-selling--linkedin)
- [Conversational AI & Chatbots](#conversational-ai--chatbots)
- [Data Providers & Databases](#data-providers--databases)
- [Workflow Automation](#workflow-automation)
- [Analytics & Attribution](#analytics--attribution)
- [Open Source Tools](#open-source-tools)
- [Frameworks & Libraries](#frameworks--libraries)
- [Benchmarks & Research](#benchmarks--research)
- [Learning Resources](#learning-resources)

---

## AI Scraping & Data Extraction

*Tools that use AI to extract structured lead data from the web.*

- [Crawl4AI](https://github.com/unclecode/crawl4ai) - Open-source AI-powered web scraper optimized for LLM extraction. Produces clean Markdown with contact info. `Python` `Free`
- [Spider](https://github.com/spider-rs/spider) - Blazing fast web crawler in Rust (11MB RAM). Structured JSONL output with links and metadata. `Rust` `Free`
- [Crawlee](https://github.com/apify/crawlee) - Web scraping and browser automation library with anti-blocking, proxy rotation, and auto-retry. `TypeScript` `Free`
- [Stagehand](https://github.com/browserbase/stagehand) - AI browser automation framework. Control browsers with natural language for dynamic lead extraction. `TypeScript` `Free`
- [Maxun](https://github.com/getmaxun/maxun) - No-code web scraping platform with AI data extraction. Turn any website into structured data. `TypeScript` `Free`
- [Scrapegraph-AI](https://github.com/VinciGit00/Scrapegraph-ai) - LLM-based scraper using graph logic for complex multi-page extraction. `Python` `Free`
- [Firecrawl](https://github.com/mendableai/firecrawl) - Turn entire websites into LLM-ready markdown. API-first with batch crawling. `TypeScript` `Freemium`
- [Colly](https://github.com/gocolly/colly) - Elegant, fast scraper framework for Go. 0.47s/page, 20MB RAM. Best for bulk HTTP scraping. `Go` `Free`
- [Browser Use](https://github.com/browser-use/browser-use) - AI agent that controls browsers using natural language. Extract data from any page with prompts. `Python` `Free`
- [Apify](https://apify.com/) - Cloud platform for web scraping and automation. 1,500+ ready-made scrapers. `SaaS` `Freemium`
- [Instant Data Scraper](https://github.com/nicola/instant-data-scraper) - Chrome extension that uses AI to detect tabular data on any webpage. `JavaScript` `Free`
- [Webclaw](https://github.com/0xMassi/webclaw) - Fast, local-first web content extraction for LLMs with MCP server integration. `Rust` `Free`

## Lead Enrichment & Verification

*AI tools that enrich raw leads with company data, technographics, and contact verification.*

- [Clay](https://www.clay.com/) - AI-powered data enrichment platform. Waterfall enrichment across 100+ data providers. Finds emails, phones, tech stacks. `SaaS` `Paid`
- [Clearbit](https://clearbit.com/) - Real-time company and contact enrichment API. Firmographics, technographics, intent. Now part of HubSpot. `API` `Freemium`
- [Apollo.io](https://www.apollo.io/) - Sales intelligence with 275M+ contacts. AI-powered enrichment, scoring, and sequencing. `SaaS` `Freemium`
- [Lusha](https://www.lusha.com/) - B2B contact and company data platform with browser extension. GDPR-compliant. `SaaS` `Freemium`
- [FullEnrich](https://www.fullenrich.com/) - Waterfall enrichment aggregating 15+ providers. "The Clay for enrichment." `SaaS` `Paid`
- [Dropcontact](https://www.dropcontact.com/) - GDPR-compliant email finder and enrichment. No database — enriches in real-time. `SaaS` `Paid`
- [Snov.io](https://snov.io/) - Email finder, verifier, and drip campaign tool. Chrome extension for LinkedIn. `SaaS` `Freemium`
- [Hunter.io](https://hunter.io/) - Domain search and email verification. Find anyone's email from their company domain. `API` `Freemium`
- [Proxycurl](https://nubela.co/proxycurl/) - LinkedIn data API. Pull structured profiles, companies, and job postings. `API` `Paid`
- [People Data Labs](https://www.peopledatalabs.com/) - Developer-first person and company data API. 3B+ records. `API` `Paid`

## AI Sales Agents & Outreach

*Autonomous AI agents that prospect, write emails, and manage outreach campaigns.*

- [11x.ai](https://www.11x.ai/) - AI SDR "Alice" that autonomously prospects, writes personalized emails, and books meetings. `SaaS` `Paid`
- [Artisan AI](https://www.artisan.co/) - AI sales agent "Ava" that handles end-to-end outbound: research, personalization, sending, follow-ups. `SaaS` `Paid`
- [Hermes](https://www.buildwithhermes.com/) - AI voice agent platform for phone-based lead qualification. Agents make and answer calls, qualify leads, and book meetings, white-labeled per client workspace. `SaaS` `Paid`
- [Regie.ai](https://www.regie.ai/) - AI-powered sales engagement. Auto-generates personalized sequences using prospect research. `SaaS` `Paid`
- [Lavender](https://www.lavender.ai/) - AI email coaching. Scores emails in real-time, suggests improvements, learns your voice. `SaaS` `Freemium`
- [Instantly.ai](https://instantly.ai/) - Cold email at scale. Unlimited email accounts, warmup, AI personalization. `SaaS` `Paid`
- [Smartlead](https://www.smartlead.ai/) - Cold email infrastructure with unlimited mailboxes, AI warmup, and subsequences. `SaaS` `Paid`
- [Lemlist](https://www.lemlist.com/) - Multichannel outreach (email + LinkedIn + calls) with AI personalization and image embedding. `SaaS` `Paid`
- [Woodpecker](https://woodpecker.co/) - Cold email automation with AI follow-up detection and deliverability tools. `SaaS` `Paid`
- [CrewAI](https://github.com/crewAIInc/crewAI) - Open-source multi-agent framework. Build custom AI SDR teams with role-based agents. `Python` `Free`
- [AutoGen](https://github.com/microsoft/autogen) - Microsoft's multi-agent framework for building conversational AI sales agents. `Python` `Free`

## Predictive Lead Scoring

*AI/ML systems that predict which leads are most likely to convert.*

- [MadKudu](https://www.madkudu.com/) - Predictive lead scoring using product usage, firmographics, and intent signals. `SaaS` `Paid`
- [Breadcrumbs](https://www.breadcrumbs.io/) - Revenue acceleration with co-dynamic lead scoring. Combines fit + activity data. `SaaS` `Freemium`
- [Infer](https://www.infer.com/) - Predictive analytics for B2B. Scores leads based on 1000+ signals. `SaaS` `Paid`
- [6sense](https://6sense.com/) - Account-based orchestration with AI-powered intent prediction and buyer journey mapping. `SaaS` `Paid`
- [Leadspace](https://www.leadspace.com/) - B2B customer data platform with AI scoring across intent, fit, and engagement. `SaaS` `Paid`
- [scikit-learn](https://scikit-learn.org/) - Open-source ML library. Build custom lead scoring models with classification algorithms. `Python` `Free`
- [XGBoost](https://github.com/dmlc/xgboost) - Gradient boosting library. State-of-the-art for tabular lead scoring problems. `Python/R/C++` `Free`
- [LightGBM](https://github.com/microsoft/LightGBM) - Fast gradient boosting by Microsoft. Handles large-scale lead datasets efficiently. `Python/C++` `Free`

## Intent Data & Buyer Signals

*Tools that detect buying intent from behavioral signals.*

- [Bombora](https://bombora.com/) - B2B intent data from a co-op of 5,000+ websites. Know which companies are researching your category. `SaaS` `Paid`
- [G2](https://sell.g2.com/) - Buyer intent from G2 software reviews. Know when prospects compare your category. `SaaS` `Paid`
- [TechTarget](https://www.techtarget.com/products/priority-engine/) - Purchase intent data from 150M+ registered technology buyers. `SaaS` `Paid`
- [Cognism](https://www.cognism.com/) - Sales intelligence with intent data, direct dials, and verified emails. GDPR-compliant. `SaaS` `Paid`
- [ZoomInfo](https://www.zoominfo.com/) - The largest B2B data platform. Intent signals, org charts, technographics, 100M+ contacts. `SaaS` `Paid`
- [Demandbase](https://www.demandbase.com/) - Account-based marketing with AI-powered intent scoring and account identification. `SaaS` `Paid`
- [CommonRoom](https://www.commonroom.io/) - AI-powered customer intelligence. Captures signals from community, social, product, and CRM. `SaaS` `Freemium`
- [Warmly](https://www.warmly.ai/) - Identifies anonymous website visitors and reveals buying intent in real-time. `SaaS` `Freemium`

## CRM Intelligence

*AI layers on top of CRMs that automate data entry, surface insights, and predict outcomes.*

- [HubSpot AI](https://www.hubspot.com/artificial-intelligence) - Built-in AI for content generation, lead scoring, forecasting, and chatbots. `SaaS` `Freemium`
- [Salesforce Einstein](https://www.salesforce.com/einstein/) - AI layer for Salesforce. Predictive scoring, opportunity insights, automated data capture. `SaaS` `Paid`
- [Clari](https://www.clari.com/) - Revenue intelligence platform. AI-powered forecasting and pipeline inspection. `SaaS` `Paid`
- [Gong](https://www.gong.io/) - Revenue intelligence from call recordings. AI analyzes conversations for deal risks and coaching. `SaaS` `Paid`
- [People.ai](https://people.ai/) - Automatically captures contact and activity data from email, calendar, phone into CRM. `SaaS` `Paid`
- [Twenty](https://github.com/twentyhq/twenty) - Open-source CRM. Modern alternative to Salesforce with API-first architecture. `TypeScript` `Free`
- [ERPNext](https://github.com/frappe/erpnext) - Open-source ERP with built-in CRM, lead management, and workflow automation. `Python` `Free`

## Email Finding & Verification

*Tools specifically for finding and validating email addresses at scale.*

- [Hunter.io](https://hunter.io/) - Find professional email addresses. Domain search, email finder, and bulk verification. `API` `Freemium`
- [Snov.io](https://snov.io/) - Email finder with 7-tier verification. LinkedIn integration and drip campaigns. `SaaS` `Freemium`
- [Findymail](https://www.findymail.com/) - Email finder with 97%+ accuracy. Specializes in finding verified B2B emails. `SaaS` `Paid`
- [Voila Norbert](https://www.voilanorbert.com/) - Email finder and verification. Find anyone's corporate email with name + domain. `API` `Freemium`
- [ZeroBounce](https://www.zerobounce.net/) - Email verification, scoring, and deliverability toolkit. 99%+ accuracy. `API` `Freemium`
- [MillionVerifier](https://www.millionverifier.com/) - Bulk email verification. $0.50 per 1,000 emails. Industry-lowest pricing. `SaaS` `Paid`
- [Reacher](https://github.com/reacherhq/check-if-email-exists) - Open-source email verification library. Check if an email exists without sending. `Rust` `Free`
- [Truemail](https://github.com/truemail-rb/truemail) - Configurable email validator. MX, SMTP, regex checks. `Ruby` `Free`

## Social Selling & LinkedIn

*AI tools for LinkedIn prospecting, content, and relationship building.*

- [LinkedIn Sales Navigator](https://business.linkedin.com/sales-solutions) - Advanced lead and company search with AI-recommended leads and InMail. `SaaS` `Paid`
- [Expandi](https://expandi.io/) - LinkedIn automation. Safe cloud-based outreach with personalization and smart sequences. `SaaS` `Paid`
- [Dripify](https://dripify.io/) - LinkedIn automation with sales funnel builder. Drip campaigns, auto-connect, auto-endorse. `SaaS` `Paid`
- [Taplio](https://taplio.com/) - AI-powered LinkedIn personal branding. Content generation, scheduling, analytics. `SaaS` `Paid`
- [Phantombuster](https://phantombuster.com/) - Cloud-based automation for LinkedIn, Twitter, Instagram. Extract profiles, auto-connect, scrape data. `SaaS` `Freemium`
- [Octopus CRM](https://octopuscrm.io/) - LinkedIn automation for connection requests, messaging, profile visits, and endorsements. `SaaS` `Paid`
- [Linked Helper](https://www.linkedhelper.com/) - Desktop LinkedIn automation. Auto-invite, message, endorse with CRM integration. `Desktop` `Paid`
- [Shield](https://www.shieldapp.ai/) - LinkedIn analytics dashboard. Track content performance, follower growth, engagement. `SaaS` `Paid`

## Conversational AI & Chatbots

*AI chatbots that qualify leads and book meetings on your website.*

- [Drift](https://www.drift.com/) - Conversational marketing platform. AI chatbot qualifies visitors and books meetings in real-time. `SaaS` `Paid`
- [Intercom Fin](https://www.intercom.com/fin) - AI agent that resolves and qualifies leads using your knowledge base. 50%+ resolution rate. `SaaS` `Paid`
- [Qualified](https://www.qualified.com/) - Conversational sales for Salesforce users. AI identifies high-value visitors in real-time. `SaaS` `Paid`
- [Tidio](https://www.tidio.com/) - AI chatbot + live chat + helpdesk. Lyro AI agent handles customer conversations. `SaaS` `Freemium`
- [Landbot](https://landbot.io/) - No-code chatbot builder for lead generation. WhatsApp, web, and Messenger bots. `SaaS` `Freemium`
- [Botpress](https://github.com/botpress/botpress) - Open-source chatbot platform with built-in NLU. Self-hosted lead qualification bots. `TypeScript` `Free`
- [Typebot](https://github.com/baptisteArno/typebot.io) - Open-source conversational form builder. Beautiful lead capture with conditional logic. `TypeScript` `Free`

## Data Providers & Databases

*Large-scale B2B data providers for bulk lead sourcing.*

- [ZoomInfo](https://www.zoominfo.com/) - 100M+ business contacts. Intent data, org charts, technographics. Industry standard. `SaaS` `Paid`
- [Apollo.io](https://www.apollo.io/) - 275M+ contacts with free tier. Built-in sequencing and dialer. Best value. `SaaS` `Freemium`
- [Cognism](https://www.cognism.com/) - Phone-verified mobile numbers. Diamond Data for direct dials. GDPR-first. `SaaS` `Paid`
- [Kaspr](https://www.kaspr.io/) - LinkedIn-focused data provider. Real-time email and phone extraction. `SaaS` `Freemium`
- [RocketReach](https://rocketreach.co/) - 700M+ professionals, 35M+ companies. Email and phone lookup. `SaaS` `Freemium`
- [Lead411](https://www.lead411.com/) - Growth intent data + verified contacts. Trigger-based prospecting. `SaaS` `Paid`
- [UpLead](https://www.uplead.com/) - 155M+ contacts with 95% data accuracy guarantee. Real-time email verification. `SaaS` `Paid`
- [Seamless.AI](https://seamless.ai/) - AI-powered search engine for B2B contacts. Real-time data verification. `SaaS` `Freemium`

## Workflow Automation

*Tools that automate multi-step lead generation workflows.*

- [Clay](https://www.clay.com/) - Build lead gen workflows with 100+ integrations. AI enrichment, scoring, and personalization in one table. `SaaS` `Paid`
- [Make](https://www.make.com/) - Visual automation platform. Connect lead gen tools with 1,500+ app integrations. `SaaS` `Freemium`
- [Activepieces](https://github.com/activepieces/activepieces) - Open-source automation with 400+ integrations and MCP server support. `TypeScript` `Free`
- [Zapier](https://zapier.com/) - Connect 6,000+ apps. Automate lead routing, enrichment triggers, CRM sync. `SaaS` `Freemium`
- [Temporal](https://github.com/temporalio/temporal) - Open-source workflow orchestration. Build reliable, long-running lead gen pipelines. `Go` `Free`
- [Windmill](https://github.com/windmill-labs/windmill) - Open-source workflow engine. Scripts in Python/TypeScript/Go with UI builder. `Rust/TypeScript` `Free`
- [Pipedream](https://pipedream.com/) - Developer-first automation. Run Node.js/Python code triggered by any event. `SaaS` `Freemium`

## Analytics & Attribution

*Track where leads come from and which channels convert.*

- [Plausible](https://github.com/plausible/analytics) - Open-source, privacy-friendly analytics. Lightweight alternative to Google Analytics. `Elixir` `Free`
- [PostHog](https://github.com/PostHog/posthog) - Open-source product analytics, session recording, feature flags, A/B testing. `TypeScript` `Free`
- [Matomo](https://github.com/matomo-org/matomo) - Open-source web analytics. Full Google Analytics replacement with data ownership. `PHP` `Free`
- [Mixpanel](https://mixpanel.com/) - Product analytics for conversion funnels, retention, and user segmentation. `SaaS` `Freemium`
- [Segment](https://segment.com/) - Customer data platform. Collect, clean, and route lead data to any tool. `SaaS` `Freemium`
- [Dreamdata](https://www.dreamdata.io/) - B2B revenue attribution. Multi-touch attribution across the entire buyer journey. `SaaS` `Paid`
- [HockeyStack](https://www.hockeystack.com/) - No-code B2B attribution and analytics. Unified view of marketing and sales impact. `SaaS` `Paid`
- [Umami](https://github.com/umami-software/umami) - Simple, fast, privacy-focused open-source analytics. `TypeScript` `Free`

## Open Source Tools

*Self-hosted, open-source tools for building your own lead gen stack.*

- [Crawl4AI](https://github.com/unclecode/crawl4ai) - AI web scraper that outputs LLM-ready markdown with contact extraction. 45K+ stars. `Python`
- [Twenty](https://github.com/twentyhq/twenty) - Modern open-source CRM with GraphQL API, email sync, and workflow automation. `TypeScript`
- [Mautic](https://github.com/mautic/mautic) - Open-source marketing automation. Email campaigns, lead scoring, landing pages. `PHP`
- [Erxes](https://github.com/erxes/erxes) - Open-source experience management. CRM, marketing, sales, and support in one platform. `TypeScript`
- [Chatwoot](https://github.com/chatwoot/chatwoot) - Open-source customer engagement. Live chat + chatbot + omnichannel inbox. `Ruby`
- [Listmonk](https://github.com/knadh/listmonk) - High-performance self-hosted newsletter and mailing list manager. `Go`
- [Cal.com](https://github.com/calcom/cal.com) - Open-source Calendly alternative. Embed scheduling links for lead conversion. `TypeScript`
- [Formbricks](https://github.com/formbricks/formbricks) - Open-source survey platform. In-app surveys, website forms, lead qualification. `TypeScript`
- [Dub.co](https://github.com/dubinc/dub) - Open-source link management. Track clicks, conversions, and referral attribution. `TypeScript`
- [Reacher](https://github.com/reacherhq/check-if-email-exists) - Open-source email verification in Rust. Self-hosted, privacy-first. `Rust`

## Frameworks & Libraries

*Developer tools for building custom lead generation systems.*

- [LangChain](https://github.com/langchain-ai/langchain) - LLM orchestration framework. Build AI agents for research, extraction, and outreach. `Python`
- [CrewAI](https://github.com/crewAIInc/crewAI) - Multi-agent framework with role-based AI teams. Build SDR/researcher/writer agent crews. `Python`
- [Colly](https://github.com/gocolly/colly) - Fast and elegant scraping framework for Go. Concurrent, rate-limited, robots.txt aware. `Go`
- [Spider](https://github.com/spider-rs/spider) - Fastest web crawler. 11MB memory, structured JSONL, full-site crawl. `Rust`
- [Playwright](https://github.com/microsoft/playwright) - Cross-browser automation. Test and scrape JS-heavy sites. `TypeScript`
- [wreq](https://github.com/0x676e67/wreq) - HTTP client with TLS fingerprint impersonation. Anti-detection for scraping. `Rust`
- [Claude Agent SDK](https://github.com/anthropics/claude-code) - Build AI agents with Claude. Orchestrate multi-step lead gen workflows. `TypeScript/Python`
- [Scrapy](https://github.com/scrapy/scrapy) - Industrial-strength web crawling framework. Middlewares, pipelines, extensions. `Python`

## Benchmarks & Research

*Performance comparisons and research papers on AI lead generation.*

### Scraper Performance (M4 Max, 10 pages)

| Tool | Language | Time | Memory | Output Quality |
|------|----------|------|--------|----------------|
| Colly | Go | **4.65s** | **20.9 MB** | Raw text + links |
| Spider | Rust | 5.97s | **11.1 MB** | Structured JSONL |
| Stagehand | TypeScript | 12.73s | 151 MB | DOM innerText |
| Crawl4ai | Python | 14.68s | 117 MB | **Clean Markdown** |

### Key Research

- [The State of AI-Powered Sales (2025)](https://www.salesforce.com/resources/research-reports/state-of-sales/) - Salesforce research on AI adoption in sales teams.
- [Google DORA Report 2025](https://dora.dev/) - Found 90% AI adoption correlates with 9% bug increase — relevant for AI-generated outreach quality.
- [Gartner: AI SDR Market Guide](https://www.gartner.com/) - Projects 80% of orgs will use AI agents for outbound by 2028.

## Learning Resources

### Courses & Guides

- [Clay University](https://www.clay.com/university) - Free courses on building AI-powered lead gen workflows.
- [Apollo Academy](https://www.apollo.io/academy) - Sales engagement and prospecting best practices.
- [Cold Email Mastery](https://www.instantly.ai/blog) - Instantly.ai's blog on deliverability, copywriting, and automation.

### Communities

- [r/sales](https://www.reddit.com/r/sales/) - Reddit community for sales professionals (500K+ members).
- [r/coldemail](https://www.reddit.com/r/coldemail/) - Cold email strategies, tools, and results.
- [SalesHacker](https://www.saleshacker.com/) - B2B sales community with webinars, articles, and forums.
- [RevGenius](https://www.revgenius.com/) - Community of revenue professionals sharing playbooks and strategies.

### Newsletters

- [The AI Sales Brief](https://theaisalesbrief.com/) - Weekly newsletter on AI tools for sales.
- [Predictable Revenue](https://predictablerevenue.com/) - Outbound sales methodology and AI adoption insights.

---

## Selection Criteria

Tools are evaluated on:

- **AI Integration** - Does it use AI/ML for intelligence, not just automation?
- **Data Quality** - Accuracy, freshness, and compliance (GDPR/CCPA).
- **Developer-Friendliness** - API availability, open-source options, extensibility.
- **Performance** - Speed, memory efficiency, scalability.
- **Value** - Free/open-source options prioritized alongside commercial tools.

## Contributing

Contributions welcome! Please read the [contributing guidelines](CONTRIBUTING.md) first.

- Add tools in alphabetical order within their category
- Include a brief description, language/platform tag, and pricing model
- Verify all links are working
- One tool per pull request for easier review

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

This list is released under CC0. You can copy, modify, and distribute it, even for commercial purposes, without asking permission.
