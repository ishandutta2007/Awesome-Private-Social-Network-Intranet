# Awesome-Private-Social-Network-Intranet

# Awesome Private Social Network & Intranet

> A curated list of top Private Social Network and Intranet platforms — both SaaS/Hosted commercial suites and open-source alternatives for building internal communities, company news feeds, and employee collaboration spaces.
> 🌟 Star this repo if you find it useful! 🌟

---

## 📋 Table of Contents

- [SaaS / Hosted Platforms](#-saas--hosted-platforms)
  - [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [Open-Source Software](#-open-source-software)
  - [Mastodon](#mastodon)
  - [Discourse](#discourse)
  - [Rocket.Chat](#rocketchat)
  - [Outline](#outline)
  - [Mattermost](#mattermost)
  - [Nextcloud Hub](#nextcloud-hub)
  - [Zulip](#zulip)
  - [NodeBB](#nodebb)
  - [HumHub](#humhub)
  - [Liferay Community Edition](#liferay-community-edition)
  - [Elgg](#elgg)
  - [Open Social](#open-social)
  - [eXo Platform](#exo-platform)
- [Comparison at a Glance](#-comparison-at-a-glance)
- [Contributing](#-contributing)

---

## 🟦 SaaS / Hosted Platforms

Commercial, cloud-hosted Private Social Network and Intranet platforms. These are not open-source but are included as reference points for feature comparison.

### Sector Overview & Market Dynamics
The global Social Intranet and Enterprise Social Network (ESN) market is valued at approximately **$7B to $14B** and is projected to expand toward **$25B to $40B+** over the next decade at a 12–18% CAGR, propelled by remote/hybrid digital workplace transformations. The sector exhibits a distinct two-tier structure: **highly concentrated at the foundation layer**, where tech mega-vendors (Microsoft Viva/SharePoint, Salesforce/Slack, Google Workspace) bundle collaboration tools into existing enterprise suites, yet **moderately-to-highly fragmented in the dedicated intranet/employee-experience layer**, where independent vendors compete through specialized employee engagement, internal communication workflows, and tailored UI integrations.

| Platform | Type / Focus | Company Size (Valuation / Revenue) | Starting Tier Pricing | Free Tier / Trial Limits |
|:---|:---|:---|:---|:---|
| **Microsoft Viva Engage** | Enterprise social network within Microsoft 365 | ~$3.1T Market Cap / ~$245B Annual Revenue (Microsoft) | Included in M365 Business Basic ($6.00/user/mo) or E1 ($10.00/user/mo); standalone/advanced Viva Suite at $12.00/user/mo | Core features included free for existing Microsoft 365 / Office 365 tenants; 30-day free trial for premium Viva Suite add-on |
| **Workplace from Meta** | Enterprise social network with feed, chat & groups | ~$1.5T Market Cap / ~$135B Annual Revenue (Meta) | Historically $4.00/user/mo (50% discount to $2.00/user/mo applied during sunset) | Deprecated/Shutting down (June 2026 final shutdown; read-only access mode Sept 2025 – May 2026 at no cost) |
| **LumApps** | Social intranet & employee communication platform | $650M Valuation (Bridgepoint acquisition, 2024) / ~$60M–$70M ARR | ~£2.60–£3.20/user/mo (~$3.30–$4.10/user/mo, G-Cloud baseline) or ~$8.00/user/mo entry tier | No self-service free tier or self-serve trial; custom guided proof-of-concept / demo upon request |
| **Simpplr** | AI-powered employee experience & intranet platform | ~$547M Valuation / Series D (~$70M raised) | £4.00/user/mo (~$5.10/user/mo, G-Cloud Simpplr One baseline; min. 500-user enterprise tiers) | 14-day free trial (sales-assisted upon qualification; no permanent free tier) |
| **Igloo Software** | Digital workplace & modern intranet platform | ~$30M–$36M Annual Revenue (Acquired by Appspace, 2025) | ~$8.00/user/mo (standard baseline packages typically starting at $599/mo block minimum) | No self-service free tier or trial; guided demo / proof-of-concept upon sales qualification |

---

## 🟩 Open-Source Software

Self-hosted, community-driven Private Social Network and Intranet tools. Ranked below in descending order by GitHub stargazers.

### Mastodon [![GitHub stars](https://img.shields.io/github/stars/mastodon/mastodon?style=social&color=white)](https://github.com/mastodon/mastodon/stargazers)
**Stack:** Ruby on Rails / Node.js / PostgreSQL / Redis | **License:** AGPL-3.0  
Mastodon is the leading decentralized, microblogging social network platform. For organizations and private networks, Mastodon can be deployed in private/authorized-fetch mode where registrations are invite-only or gated via OAuth/SAML, turning it into an internal corporate microblogging feed akin to Yammer or Twitter.  
**Best for:** Organizations wanting a private corporate microblogging feed, executive broadcast stream, or decentralized community network with native mobile app support.

### Discourse [![GitHub stars](https://img.shields.io/github/stars/discourse/discourse?style=social&color=white)](https://github.com/discourse/discourse/stargazers)
**Stack:** Ruby on Rails / PostgreSQL / Redis | **License:** GPL-2.0  
Discourse is a modern open-source discussion platform that organizes posts into categories and searchable threads. Positioned as the premier open-source tool for **durable knowledge sharing, internal town halls, and asynchronous team discussions**, it replaces noisy chat or ephemeral feeds with structured, searchable conversations.  
**Best for:** Organizations wanting structured long-form discussions, internal company Q&A, and policy/announcement repositories.

### Rocket.Chat [![GitHub stars](https://img.shields.io/github/stars/RocketChat/Rocket.Chat?style=social&color=white)](https://github.com/RocketChat/Rocket.Chat/stargazers)
**Stack:** TypeScript / Node.js / MongoDB | **License:** MIT / Open Core  
Rocket.Chat is a comprehensive open-source team communications hub featuring real-time messaging, audio/video conferencing, channels, omnichannel customer routing, and Matrix federation. It provides private communication channels, team broadcast rooms, and deep compliance features for high-security intranets.  
**Best for:** Enterprises needing a privacy-first, on-premises collaboration and real-time team communication hub.

### Outline [![GitHub stars](https://img.shields.io/github/stars/outline/outline?style=social&color=white)](https://github.com/outline/outline/stargazers)
**Stack:** TypeScript / Node.js / React / PostgreSQL / Redis | **License:** BSL 1.1 / Community  
Outline is a fast, collaborative team knowledge base and intranet wiki. Built for modern teams, it provides markdown-first documentation, real-time co-editing, robust search, and granular access controls for building internal knowledge hubs and company handbooks.  
**Best for:** Teams building an internal documentation intranet, company handbook, and centralized operational knowledge base.

### Mattermost [![GitHub stars](https://img.shields.io/github/stars/mattermost/mattermost?style=social&color=white)](https://github.com/mattermost/mattermost/stargazers)
**Stack:** Go / React / PostgreSQL | **License:** MIT (Team Edition) / Open Core  
Mattermost is an enterprise-grade secure collaboration platform that combines real-time channels, structured playbooks, and audio calling. Positioned as a self-hosted alternative to Slack and Workplace Chat, it integrates seamlessly into corporate intranets requiring high data sovereignty and private cloud deployment.  
**Best for:** Technical and regulated organizations seeking self-hosted team communication with integrated operational playbooks.

### Nextcloud Hub [![GitHub stars](https://img.shields.io/github/stars/nextcloud/server?style=social&color=white)](https://github.com/nextcloud/server/stargazers)
**Stack:** PHP / Vue.js / MariaDB / PostgreSQL | **License:** AGPL-3.0  
Nextcloud Hub is a comprehensive self-hosted productivity and intranet suite that unifies file sharing (Nextcloud Files), chat/video calls (Nextcloud Talk), groupware (Mail, Calendar, Contacts), and office document editing into a single digital workplace portal.  
**Best for:** Organizations needing an all-in-one private cloud intranet combining document storage, calendar, chat, and collaborative office tools.

### Zulip [![GitHub stars](https://img.shields.io/github/stars/zulip/zulip?style=social&color=white)](https://github.com/zulip/zulip/stargazers)
**Stack:** Python / Django / TypeScript / PostgreSQL | **License:** Apache-2.0  
Zulip is an open-source team collaboration tool that combines the immediacy of real-time chat with the asynchronous structure of email threading. Every message belongs to a specific topic within a stream, eliminating context switching and keeping conversations focused.  
**Best for:** Distributed teams and companies seeking structured, topic-threaded communication that prevents information overload.

### NodeBB [![GitHub stars](https://img.shields.io/github/stars/NodeBB/NodeBB?style=social&color=white)](https://github.com/NodeBB/NodeBB/stargazers)
**Stack:** Node.js / MongoDB / Redis | **License:** GPL-3.0  
NodeBB is a fast, responsive modern forum engine built with web sockets for real-time interactions, streaming notifications, and mobile readiness. It is widely used to power internal employee communities, knowledge-sharing hubs, and private customer forums.  
**Best for:** Teams looking for a modern, real-time community forum with extensive plugin support and seamless SSO.

### HumHub [![GitHub stars](https://img.shields.io/github/stars/humhub/humhub?style=social&color=white)](https://github.com/humhub/humhub/stargazers)
**Stack:** PHP / Yii2 / MySQL | **License:** AGPL-3.0 (open core)  
HumHub is the premier open-source social intranet platform and the closest analog to Workplace from Meta. It features user profiles, Spaces (groups) with individual walls, a network-wide social activity stream, wikis, tasks, shared calendars, files, and mobile apps. It supports LDAP and SAML for enterprise identity federation.  
**Best for:** Organizations and member communities wanting a turnkey self-hosted social intranet with a social news feed, team spaces, and internal wikis.

### Liferay Community Edition [![GitHub stars](https://img.shields.io/github/stars/liferay/liferay-portal?style=social&color=white)](https://github.com/liferay/liferay-portal/stargazers)
**Stack:** Java | **License:** LGPL-2.1  
Liferay is an enterprise portal and digital experience platform designed for building complex, multi-site corporate intranets. It features drag-and-drop widget composition, role-based content personalization, document management, forms, and deep enterprise identity integration.  
**Best for:** Large enterprise organizations needing a highly customizable, portal-based corporate intranet with granular delegated administration.

### Elgg [![GitHub stars](https://img.shields.io/github/stars/Elgg/Elgg?style=social&color=white)](https://github.com/Elgg/Elgg/stargazers)
**Stack:** PHP / MySQL | **License:** GPL-2.0 / MIT  
Elgg is a flexible open-source social engine framework built on an entity-relationship data model. Everything from blogs and activity feeds to user groups is handled via its modular plugin architecture, enabling developers to build bespoke social networking platforms.  
**Best for:** Developers and technical teams wanting to architect a custom internal social network from an extensible engine.

### Open Social [![GitHub stars](https://img.shields.io/github/stars/goalgorilla/open_social?style=social&color=white)](https://github.com/goalgorilla/open_social/stargazers)
**Stack:** PHP / Drupal | **License:** GPL-2.0 (open core)  
Open Social is a community and intranet distribution built on Drupal. Designed as an alternative to Facebook Groups and Workplace, it provides social activity feeds, group management, event coordination, and discussion modules, leveraging Drupal's rich content-management ecosystem.  
**Best for:** Organizations already using Drupal or seeking a community intranet with robust content modeling.

### eXo Platform [![GitHub stars](https://img.shields.io/github/stars/exoplatform/platform?style=social&color=white)](https://github.com/exoplatform/platform/stargazers)
**Stack:** Java | **License:** AGPL-3.0 (Community Edition)  
eXo Platform is an open-source digital workplace solution combining enterprise social networking, team collaboration spaces, document management, wikis, task boards, and gamification rewards in a unified web portal.  
**Best for:** Mid-market to enterprise companies looking for an all-in-one digital workplace and social collaboration suite.

---

## 📊 Comparison at a Glance

| Software | License | Stack | Social Feed | Spaces/Groups | Chat | Self-Hosted | Best For |
|:---|:---|:---|:---:|:---:|:---:|:---:|:---|
| **Viva Engage** | Proprietary | Cloud | ✅ | ✅ Communities | (Teams) | ❌ | Microsoft 365 enterprises |
| **Workplace** | Proprietary | Cloud | ✅ | ✅ Groups | ✅ | ❌ | (Shutting down) |
| **Simpplr** | Proprietary | Cloud | ✅ | (Check) | ❌ | ❌ | AI-powered employee experience |
| **Mastodon** | AGPL-3.0 | Ruby/Rails | ✅ | ❌ (Hashtags) | ❌ | ✅ | Private corporate microblogging |
| **Discourse** | GPL-2.0 | Ruby/Rails | ❌ (Forum) | ✅ Categories | ❌ | ✅ | Structured discussion & Q&A |
| **Rocket.Chat** | MIT / Open Core | TS/Node | ❌ | ✅ Channels | ✅ | ✅ | Privacy-first team communication |
| **Outline** | BSL 1.1 / Open | TS/Node | ❌ | ✅ Collections | ❌ | ✅ | Modern team knowledge base/wiki |
| **Mattermost** | MIT / Open Core | Go/Postgres | ❌ | ✅ Channels | ✅ | ✅ | Self-hosted secure team chat |
| **Nextcloud Hub**| AGPL-3.0 | PHP/Vue | ✅ (Activity) | ✅ Circles | ✅ (Talk) | ✅ | All-in-one private cloud intranet |
| **Zulip** | Apache-2.0 | Python/Django | ❌ | ✅ Streams | ✅ (Threaded) | ✅ | Asynchronous topic-threaded chat |
| **NodeBB** | GPL-3.0 | Node.js | ❌ | ✅ Categories | ❌ | ✅ | Real-time community forum |
| **HumHub** | AGPL-3.0 | PHP/Yii2 | ✅ | ✅ Spaces | ❌ (Not chat) | ✅ | Social intranet + team spaces |
| **Liferay CE** | LGPL-2.1 | Java | (Portlets) | ✅ Sites | ❌ | ✅ | Multi-site portal intranet |
| **Elgg** | GPL-2.0 / MIT | PHP/MySQL | ✅ (Custom) | ✅ (Plugins) | ❌ | ✅ | Custom social networks |
| **Open Social** | GPL-2.0 | PHP/Drupal | ✅ | ✅ Groups | ❌ | ✅ | Drupal community platform |
| **eXo Platform**| AGPL-3.0 | Java | ✅ | ✅ Spaces | (Chat) | ✅ | Digital workplace portal |

---

## 🤝 Contributing

Contributions are welcome! If you know of an open-source Private Social Network or Intranet tool that should be listed here, please open a pull request with:

- Project name and URL
- Brief description (1–2 sentences)
- Stack and license
- Why it stands out

Please ensure the project is actively maintained (releases within the last 12 months) and genuinely open-source. Note that the open-source ecosystem **splits** between **social intranet platforms** (HumHub, Open Social) that replicate Workplace's feed-and-groups model, **custom social engines** (Elgg) for bespoke builds, **portal-based intranets** (Liferay, eXo) for enterprise multi-site deployments, and **specialized tools** (Discourse for forums, Mattermost for chat) that are often assembled into a stack rather than replacing a single product. **HumHub** is the closest open-source analog to Workplace's social intranet, with Spaces, profiles, and a network-wide feed [citation:11]. Since Workplace is shutting down, teams migrating away should map their actual usage—if it was mostly the feed, HumHub alone covers most of it; if chat was the main use, Mattermost is the replacement; if discussion threads mattered, Discourse covers that [citation:11].

---

## 📄 License

This list is released under CC0 1.0 Universal (Public Domain). The software projects listed retain their respective licenses.

---

⭐ **If this list helped you discover a useful tool, please star the repo!** ⭐
