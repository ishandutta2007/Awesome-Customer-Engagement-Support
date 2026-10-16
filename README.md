# Awesome-Customer-Engagement-Support

## Top Customer Engagement & Support Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Omnichannel Inboxes, Ticket Management & AI-Assisted Support*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Customer Engagement & Support**. These tools enable organizations to manage customer conversations across email, live chat, social messaging, and voice—from shared inboxes optimized for collaborative email replies to full-featured ticketing systems with SLA tracking, automation, and AI assistance.



**Examples** include Intercom, Zendesk, Freshdesk, Salesforce Service Cloud, Help Scout, Drift, Front, Kustomer, HubSpot Service Hub, and Gladly (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, omnichannel support, and open ticketing infrastructure—ideal for support teams, platform engineers, and organizations seeking transparent, vendor-independent customer engagement.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **Zendesk**  

  The legacy ticketing heavyweight. **Comprehensive ticketing system** optimized for **state transitions** (New → Open → Pending → Solved) with SLAs, prioritization, and queue management . **The enterprise standard** for complex, formal support workflows. Pricing starts around **$55 per agent per month**, which many teams under 15 agents find overkill .



- **Intercom**  

  Several products in one: **website chat widget, shared inbox, help center, product tours, campaigns, and AI support agent** . **The conversational support standard**—best for teams whose support is more chat-driven than email-driven. Cloud-hosted only.



- **Freshdesk**  

  **Omnichannel support platform** with ticketing, automation, self-service portal, and multi-channel support. Known for ease of use and affordability. **A common recommendation for teams in the 5-15 agent range** switching from Zendesk .



- **Help Scout**  

  **Email-first shared inbox** with a clean UI, conversation threading, customer profiles, and a knowledge base. **The benchmark FreeScout was designed to replace** . Best for teams where email is the primary support channel.



- **Drift**  

  **Conversational marketing platform** with AI chatbot, meeting scheduling, and pipeline acceleration. **The enterprise standard for B2B conversational marketing** rather than traditional support.



- **Front**  

  **Collaborative shared inbox** optimized for **multiple humans, one customer thread**—internal comments, snooze, assignment . Best for teams that live in email and need "who is replying to this?" clarity.



- **Kustomer**  

  **CRM-powered customer service platform** focused on conversational support. Features **unified customer timeline** and AI-powered automation.



- **HubSpot Service Hub**  

  **Customer service software** integrated with HubSpot CRM. Features ticketing, shared inbox, knowledge base, and customer feedback tools.



- **Gladly**  

  **Customer service platform** built around a unified customer conversation view across channels. Focuses on reducing agent context-switching.



## Open-Source GitHub Projects



- **[Chatwoot](https://github.com/chatwoot/chatwoot)**  

  **Open-source customer engagement suite—an alternative to Intercom, Zendesk, Salesforce Service Cloud** (MIT) . **The most adopted open-source customer engagement platform** with **37,000+ GitHub stars** . **Omnichannel shared inbox** centralizes **live chat, email, WhatsApp, Facebook, Instagram, Twitter, Telegram, Line, SMS** into one queue . **AI Captain** for automated responses and triage . Features **private notes and @mentions, labels, canned responses, auto-assignment, business hours, auto-responders, contact management, CSAT reports, and Slack/Shopify/Dialogflow integrations** . **Self-hostable or Chatwoot Cloud ($19+/agent)** . **Note**: Knowledge base is **basic compared to Zendesk**; SLA tracking exists but is **less mature**; self-hosting needs **Redis, Postgres, Sidekiq** (real DevOps lift) . **The reference implementation for omnichannel open-source support**.



- **[Zammad](https://github.com/zammad/zammad)**  

  **Web-based open-source helpdesk/customer support system** (AGPL-3.0) . **The closest open-source equivalent to Zendesk**—**full-featured ticketing with SLA tracking, knowledge base, customer portal, role-based access, audit logging, and telephony via Asterisk** . **Multi-channel inbox** covers **email, chat, phone, Twitter, Facebook, Telegram, WhatsApp, SMS** . **Elasticsearch-powered full-text search** is instant and covers everything . **Every feature ships in the open-source version—no paid add-ons** . **The cleanest OSS interface**—"the UI is the closest of any open-source helpdesk to a commercial SaaS product" . **Trade-offs**: **Ruby on Rails stack** (DevOps lift if your team is JS-only), **resource heavy** (4-8 GB RAM minimum, Elasticsearch is the main consumer), **slow boot times (60-90 seconds)** . **Best for**: growing teams (5-50+ agents) needing multi-channel support, powerful search, and enterprise features .



- **[FreeScout](https://github.com/freescout-help-desk/freescout)**  

  **Free self-hosted Zendesk & Help Scout alternative** (AGPL-3.0) . **The super lightweight and powerful free open source help desk and shared inbox** built with **PHP (Laravel framework)** . **The lightest-weight serious option**—runs on **1-2 GB RAM** and even **shared hosting** . **No limitations on users, tickets, or mailboxes** . Features **omnichannel** (email, WhatsApp, Telegram, Facebook, Slack, Live Chat), **100% mobile-friendly, multilingual (33 languages), seamless email integration, OAuth for Microsoft 365 and Google Workspace, collision detection, push notifications, internal notes, auto-reply, open tracking, powerful search** . **Modules marketplace** for advanced features (SLA, automation, satisfaction surveys) at **$50 one-time each**—pay only for what you need . **Best for**: solo founders and small support teams (1-5 agents) who want a clean email-first help desk and don't need omnichannel .



- **[LibreDesk](https://github.com/libredesk/libredesk)**  

  **Open-source customer support desk** (AGPL-3.0) . **Email, website live chat, and WhatsApp in one inbox, plus help center, automation rules, SLAs, and CSAT** . **Ships as a single binary backed by Postgres and Redis**—**the lightest full inbox to run** . **~3,000 GitHub stars** and actively maintained . **Best for**: teams wanting a lighter alternative to Chatwoot that still covers email, chat, and WhatsApp.



- **[osTicket](https://github.com/osTicket/osTicket)**  

  **The oldest established open-source support ticket system** (GPLv2) . **First GitHub release in 2013, deployed widely in production for over a decade** . Features **custom fields, ticket filters, agent collaboration, knowledge base, customer portal, multi-language** . **The feature set has been proven in production**—fewer surprise breaking changes than newer projects . **Runs as 2 containers** (app + MariaDB), installs in **~5 minutes**, and runs comfortably on a **Raspberry Pi 4 or $5/month VPS** . **Interface looks dated** versus Zammad/Chatwoot . **Best for**: small teams (1-5 agents) who primarily handle email-based tickets, want stability, and have minimal hardware .



- **[GLPI](https://github.com/glpi-project/glpi)**  

  **Open-source IT Service Management software** (GPL-3.0) . **The best default for internal IT support**—**asset management plus helpdesk** . Features **ITIL-compliant Helpdesk, automatic inventory, software deployment, knowledge base, Problem/Incident/Request/Change/Release management, Asset Management** . **Best for**: internal IT teams needing asset management and ITSM rather than customer-facing support.



- **[Frappe Helpdesk](https://github.com/frappe/helpdesk)**  

  **100% open-source Ticket Management tool** (AGPL-3.0) . **Modern, streamlined ticket management built on Frappe Framework** with **Vue-based UI** . Features **dual portals for agents and customers, customizable SLAs, assignment rules based on priority/issue type/workload, knowledge base with advanced search, canned responses, production-ready Docker deployment** . **Setup in approximately 5 minutes** via easy-install script . **Integrates with the broader Frappe/ERPNext ecosystem** . **Best for**: teams already using Frappe/ERPNext or wanting a modern, Python-based helpdesk.



- **[Helpy](https://github.com/helpyio/helpy)**  

  **Modern, open source helpdesk customer support application** (MIT) . Features **knowledgebase, community discussions, and support tickets integrated with email** . **Best for**: teams wanting community forums alongside traditional ticketing.



- **[Tiledesk](https://github.com/Tiledesk/tiledesk)**  

  **Open-source conversational platform** (MIT) . **A chat widget and agent dashboard with a visual design studio for chatbot flows that hand conversations to human agents** . **Best for**: teams wanting bots to answer first and hand off to people . **Note**: Stack runs several services and MongoDB; some Docker images are Enterprise-only .



- **[Live Helper Chat](https://github.com/LiveHelperChat/livehelperchat)**  

  **Long-running live chat system** (Apache-2.0) . Features **web and mobile agent apps, a bot builder that can call third-party AI services, and a REST API** . **Best for**: teams that only need a website chat widget—email ticketing, campaigns, and product tours need other tools .



### Additional Strong Open-Source Options



- **[Peppermint](https://github.com/Peppermint-Lab/peppermint)** — Open-source ticket management (AGPL-3.0) . **Note**: Still appears in comparisons but **less maintained than Chatwoot, Zammad, or FreeScout** .

- **[Erxes](https://github.com/erxes/erxes)** — Open-source experience operating system (XOS) with omnichannel engagement and AI support  . **Plugin-based architecture** with inbox, CRM, and knowledge base modules.

- **[Chaskiq](https://github.com/chaskiq/chaskiq)** — **Source-available (not open source)** — license adds **Commons Clause to AGPL-3.0**, restricting selling services built on it  . **The license badge shows "Other"**—read the LICENSE file itself .

- **[Papercups](https://github.com/papercups-io/papercups)** — **No commits since February 2024**  . **Not recommended for new deployments**.

- **[KestrelDesk](https://github.com/Swhshd/kestreldesk)** — Self-hosted AI customer support and real-time collaboration platform built with Go (open-source)  . **AI-native with Qdrant vector storage, workflow editor, and OpenAI-compatible model integration**  . **The most AI-forward open-source helpdesk** .

- Community **n8n** workflows for helpdesk-to-CRM synchronization and SLA breach alerting .



**Frameworks for building custom systems**: Combine **Chatwoot** for omnichannel live chat and social messaging with **Zammad** for full-featured ticketing and SLA management, **FreeScout** for lightweight email-first shared inbox, **Frappe Helpdesk** for Frappe ecosystem integration, and **KestrelDesk** for AI-native support—creating a comprehensive customer engagement platform.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Customer engagement platforms handling customer data must comply with data protection regulations (GDPR, CCPA, etc.) and implement appropriate access controls and audit logging.

- **Open-source customer support is mature and production-ready.** Chatwoot is the most adopted open-source customer engagement platform with **37,000+ GitHub stars** and omnichannel support  . Zammad is the **closest open-source equivalent to Zendesk** with full-featured ticketing and enterprise features  . FreeScout is the **lightest-weight serious option**, running on 1-2 GB RAM  . **These are genuine alternatives to commercial platforms.**

- **The shared inbox vs. ticketing system distinction is critical.** **Shared inboxes** (Front, Help Scout, FreeScout) are optimized for **collaborative email replies**—multiple humans, one customer thread, internal comments, snooze, assignment  . **Ticketing systems** (Zendesk, Zammad) are optimized for **state transitions**—New → Open → Pending → Solved, with SLAs, prioritization, and queue management  . **Chatwoot is a shared inbox with ticketing bolted on; Zammad is both, configurable per mailbox**  . **Pick based on whether your team is email-first or queue-first.**

- **Resource footprint varies dramatically.** **FreeScout runs on 1-2 GB RAM** and even shared hosting  . **osTicket runs comfortably on a Raspberry Pi 4**  . **Zammad needs 4-8 GB RAM** with Elasticsearch as the main consumer  . **If you're on a $5/month VPS, FreeScout or osTicket are your options; Zammad needs a dedicated server.**

- **The license distinction matters.** **Chatwoot is MIT** (permissive)  . **Zammad and FreeScout are AGPL-3.0** (copyleft)  . **Chaskiq is source-available, not open source**—it adds a Commons Clause restricting selling services built on it  . **Read the LICENSE file, not the marketing page.**

- **The hidden cost is not the license.** It is **hosting, upgrades, backups, and the person who owns all three**—budget a few hours a month at minimum, and more in the first quarter  . **Most teams under 15 agents are over-paying Zendesk for features they barely touch**  .



---



**Made for support teams, customer experience managers, and organizations building transparent customer engagement solutions.**  

Let's make Customer Engagement & Support more open, data-driven, and omnichannel.
