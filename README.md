# Awesome-Private-Social-Network-Intranet

# Awesome Private Social Network & Intranet

> A curated list of top Private Social Network and Intranet platforms — both SaaS/Hosted commercial suites and open-source alternatives for building internal communities, company news feeds, and employee collaboration spaces.
> 🌟 Star this repo if you find it useful! 🌟

---

## 📋 Table of Contents

- [SaaS / Hosted Platforms](#-saas--hosted-platforms)
  - [Microsoft Viva Engage (Yammer)](#microsoft-viva-engage-yammer)
  - [Workplace from Meta](#workplace-from-meta)
  - [Simpplr](#simpplr)
  - [LumApps](#lumapps)
  - [Igloo Software](#igloo-software)
- [Open-Source Software](#-open-source-software)
  - [HumHub](#humhub)
  - [Elgg](#elgg)
  - [Open Social](#open-social)
  - [eXo Platform](#exo-platform)
  - [Liferay Community Edition](#liferay-community-edition)
  - [Discourse](#discourse)
  - [Mattermost](#mattermost)
- [Comparison at a Glance](#-comparison-at-a-glance)
- [Contributing](#-contributing)

---

## 🟦 SaaS / Hosted Platforms

Commercial, cloud-hosted Private Social Network and Intranet platforms. These are not open-source but are included as reference points for feature comparison.

### Microsoft Viva Engage (Yammer)
**Type:** Enterprise social network within Microsoft 365
Viva Engage (formerly Yammer) provides a familiar social feed, communities, and conversations integrated directly into Microsoft Teams and the broader Microsoft 365 ecosystem. It is the default choice for organizations already standardized on Microsoft, with data governed by the tenant's compliance and retention policies.

### Workplace from Meta
**Type:** Enterprise social network with feed, chat, and groups
Workplace combined a social news feed, team chat, and knowledge groups in a single platform. **Important status:** Meta announced Workplace's shutdown, with the service being discontinued. Organizations still on Workplace must plan migration to alternatives, and there is **no official importer** for HumHub, Mattermost, or Discourse [citation:11].

### Simpplr
**Type:** AI-powered employee experience and intranet platform
Simpplr is an AI-powered employee experience platform that transforms workplace engagement, offering a seamless digital experience fostering connection, recognition, and productivity [citation:5]. It is positioned for enterprises wanting a modern, personalized intranet experience.

### LumApps
**Type:** Social intranet and employee communication platform
LumApps provides a social intranet with personalized content, social feeds, and integration with Google Workspace and Microsoft 365. It is positioned for mid-market to enterprise organizations wanting a modern intranet experience.

### Igloo Software
**Type:** Digital workplace and intranet platform
Igloo Software provides a digital workplace with news, blogs, wikis, forums, and file sharing. It is positioned for organizations wanting a comprehensive intranet with social collaboration features.

---

## 🟩 Open-Source Software

Self-hosted, community-driven Private Social Network and Intranet tools. The open-source ecosystem is **anchored by HumHub** for social intranets, with complementary platforms for forums, chat, and portal-based intranets.

### HumHub
**Stack:** PHP / Yii2 / MySQL | **License:** AGPL (open core)
HumHub is the closest open-source analog to Workplace's social feed and the leading open-source social intranet for private organizational networks [citation:2][citation:11]. Key features include **profiles, Spaces (groups) with their own walls and modules, a network-wide activity stream (dashboard), wiki, tasks, calendar, files, messaging, and a mobile app** [citation:3][citation:7]. It is designed for organizations, member communities, associations, and schools—not as a pure chat tool, but as a social network where announcements, documents, and discussions live together [citation:3][citation:15]. **Important licensing note:** HumHub has a dual license model with a free open-source edition and paid editions/apps available alongside the open code [citation:2]. It supports LDAP and SAML sign-on for enterprise identity integration [citation:2].  
**Best for:** Organizations and member communities wanting a self-hosted social intranet with a familiar Facebook-style feed, Spaces for teams, and a wiki for durable knowledge, accepting the operational overhead of running a PHP/Yii2 stack.

### Elgg
**Stack:** PHP / MySQL | **License:** Open Source
Elgg is an open-source social engine framework known for its **extreme flexibility and plugin-based architecture**, where everything from blogs to groups is a plugin [citation:6]. Its data model is built around entities, relationships, metadata, and annotations, enabling highly dynamic social applications [citation:6]. It is positioned for developers wanting to build **custom social environments** rather than deploy a ready-made intranet [citation:2][citation:10]. **Trade-off:** The learning curve is steep, and the flexibility comes at the cost of needing significant development effort to assemble a complete intranet.  
**Best for:** Developers and technical teams wanting to build a bespoke private social network from a flexible engine, accepting that significant customization is required.

### Open Social
**Stack:** PHP / Drupal | **License:** GPL (open core)
Open Social is a Drupal-based community platform positioned as an open-source alternative to Facebook Groups and Workplace [citation:3]. It is the natural choice for organizations **already running Drupal** or wanting a platform that leverages Drupal's content modeling and module ecosystem [citation:2]. It provides profiles, groups, feeds, and discussion features.  
**Best for:** Drupal shops and organizations wanting a community platform built on a proven CMS foundation, particularly those with existing Drupal expertise.

### eXo Platform
**Stack:** Java | **License:** AGPL (Community Edition)
eXo Platform is a digital workplace solution that allows businesses to connect, engage, empower, and reward teams, available on-premise and on the cloud [citation:5]. It combines social collaboration with document management, wikis, and calendars. It is positioned for mid-market to enterprise organizations wanting a comprehensive digital workplace.  
**Best for:** Organizations wanting a full-featured digital workplace with social collaboration and document management, accepting a Java-based deployment.

### Liferay Community Edition
**Stack:** Java | **License:** LGPL (Community Edition)
Liferay is a portal platform that lets organizations build intranet pages by dragging and dropping widgets—documents, wikis, message boards, forms, and custom applications [citation:13]. It is designed for enterprises needing **multi-site intranets with delegated administration**, personalized dashboards, and complex authentication requirements (SAML, OAuth, LDAP) [citation:13]. **Trade-off:** It is resource-heavy and has a steeper learning curve, requiring Java and portal development skills for a polished intranet [citation:13].  
**Best for:** Large organizations needing a highly customizable, portal-based intranet with multiple departmental sites and strong enterprise features.

### Discourse
**Stack:** Ruby on Rails / PostgreSQL / Redis | **License:** GPL
Discourse is an open-source forum platform that organizes posts into topics and categories, positioned as the open-source replacement for **durable discussion and announcements** rather than social feeds or chat [citation:11]. It is often paired with HumHub in a stack: HumHub for the social intranet feed, Discourse for structured long-form discussion, and Mattermost for chat [citation:11].  
**Best for:** Teams wanting a structured, searchable discussion forum for announcements and knowledge sharing, often used alongside a social intranet.

### Mattermost
**Stack:** Go / React / PostgreSQL | **License:** MIT (Team Edition) / Open Core
Mattermost is an open-source team chat platform designed for secure, self-hosted communication, positioned as a Slack alternative for organizations that cannot put data in a public cloud [citation:3]. **Important distinction:** It is a **chat tool**, not a social intranet—it replaces the chat function of Workplace or Teams, not the news feed or groups [citation:11][citation:15]. The Team Edition is free for up to 250 activated users with unlimited message history, though free mobile push notifications route through the Test Push Notification Service (TPNS), which is not recommended for production [citation:15].  
**Best for:** Technical teams needing self-hosted team chat, often deployed alongside HumHub and Discourse to cover the full Workplace feature set.

---

## 📊 Comparison at a Glance

| Software | License | Stack | Social Feed | Spaces/Groups | Chat | Self-Hosted | Best For |
|----------|---------|-------|-------------|---------------|------|-------------|----------|
| **Viva Engage** | Proprietary | Cloud | ✅ | ✅ Communities | (Teams) | ❌ | Microsoft 365 enterprises |
| **Workplace** | Proprietary | Cloud | ✅ | ✅ Groups | ✅ | ❌ | (Shutting down) |
| **Simpplr** | Proprietary | Cloud | ✅ | (Check) | ❌ | ❌ | AI-powered employee experience |
| **HumHub** | AGPL (open core) | PHP/Yii2 | ✅ | ✅ Spaces | ❌ (Not chat) | ✅ | Social intranet + wiki |
| **Elgg** | Open Source | PHP/MySQL | ✅ (Custom) | ✅ (Plugins) | ❌ | ✅ | Custom social networks |
| **Open Social** | GPL (open core) | PHP/Drupal | ✅ | ✅ Groups | ❌ | ✅ | Drupal community platform |
| **eXo Platform** | AGPL (Community) | Java | ✅ | ✅ Spaces | (Chat) | ✅ | Digital workplace |
| **Liferay CE** | LGPL (Community) | Java | (Portlets) | ✅ Sites | ❌ | ✅ | Multi-site portal intranet |
| **Discourse** | GPL | Ruby/Rails | ❌ (Forum) | ✅ Categories | ❌ | ✅ | Structured discussion |
| **Mattermost** | MIT (Team) | Go/Postgres | ❌ | ✅ Channels | ✅ | ✅ | Self-hosted team chat |

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
