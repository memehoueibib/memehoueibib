<div align="center">

<img src="https://img.shields.io/badge/-%20-0D1117?style=flat-square" height="1" width="1" alt="" />

# Meme Houeibib

**Senior Full-Stack Engineer · PrestaShop Architect · E-commerce, ERP & AI Automation**

📍 Chambéry, France · 🇫🇷 

[![Portfolio](https://img.shields.io/badge/Portfolio-memehoueibib.com-00E5B0?style=for-the-badge&logoColor=white)](https://memehoueibib.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-memehoueibib-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/memehoueibib/)
[![Email](https://img.shields.io/badge/Email-contact@memehoueibib.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:contact@memehoueibib.com)

<br/>

<table>
  <tr>
    <td align="center"><h3>300+</h3>PrestaShop modules<br/>in production</td>
    <td align="center"><h3>5+</h3>years building<br/>production systems</td>
    <td align="center"><h3>10+</h3>marketplaces<br/>integrated</td>
    <td align="center"><h3>3</h3>PrestaShop 9<br/>migrations led</td>
    <td align="center"><h3>24/7</h3>AI agents running<br/>in production</td>
  </tr>
</table>

</div>

---

### About

I build the software that keeps e-commerce businesses running: storefronts, back-offices, ERPs, marketplace connectors, shipping pipelines and, increasingly, autonomous AI agents that handle real customer conversations.

Most of my work lives in **PrestaShop** (1.7 → 8 → 9), where I have shipped **300+ custom modules** covering pretty much every part of a shop: catalog, pricing, checkout, shipping, invoicing, returns, SEO, marketplaces and warehouse operations. Around it I build full-stack products in **NestJS / Next.js / React / TypeScript** and wire everything together with **OpenAI, Claude and n8n**.

I care about code that goes to production in one pass, stays maintainable, and can be operated by non-technical teams from the back-office.

**What I bring to the table**

- **PrestaShop at scale** · 300+ modules, overrides, hooks, page-builder widgets, theme work (Hummingbird / Classic), multi-version compatibility (1.7, 8, 9)
- **Platform migrations** · end-to-end PrestaShop 9 migrations (fresh install + ETL, module audit, override diffing, smoke tests, 301 plans, zero-downtime cut-over)
- **Marketplace engineering** · Amazon, Cdiscount, Rakuten, ManoMano, Leroy Merlin, Home24, BUT, eBay, Leboncoin via BeezUP, Sellermania, Mirakl API and direct integrations
- **AI in production** · OCR + automatic grading for refurbished goods, AI customer-support agents on Leboncoin / eBay / email, AI-assisted listings, translation pipelines
- **Logistics automation** · Packlink / Mondial Relay / Colissimo, label generation, connected scales, barcode scanning, warehouse PWA
- **Tracking & growth** · Meta CAPI, GTM server-side, GA4 enhanced e-commerce, Google Ads enhanced conversions, AEO / SEO (JSON-LD, llms.txt)
- **Business software** · ERP, invoicing (Factur-X / EN 16931), HR & payroll, accounting, scheduling, fleet management

---

### Experience

| Period | Role | Scope |
|--------|------|-------|
| **2025 → today** | **Full-Stack Engineer · MAXDEAL** (refurbished appliances, maxdeal.fr) | Led the PrestaShop 9 migration and premium storefront rebuild. Built **Comptoir** (AI marketplace inbox), **MaxDeal Go** (warehouse PWA), the reconditioning ERP, Leboncoin / eBay direct integrations, shipping automation. Run a permanent Claude Code agent on the production server for traceable, Git-backed operations. |
| **2021 → today** | **Freelance Lead Developer · Belhome & Meubletmoi** (furniture e-commerce) | Technical owner of two PrestaShop stores (1.7 & 8): custom modules, marketplace feeds, Mirakl connectors, Doofinder search, Google / Meta tracking, server incident response, PS9 migration planning, AI assistant for the storefront. |
| **Freelance** | **Web & product projects** | Medical sports center website (Next.js / NestJS), hotel cleaning-team management PWA, interim-worker payroll app, n8n-based ATS, food-delivery mobile app for the Mauritanian market. |

**Education** · MSc Web & Mobile Development (Lyon) · BSc Computer Science (Université Savoie Mont Blanc)

---

### Featured Work

| Project | What it does | Stack |
|---------|--------------|-------|
| **Comptoir** · AI marketplace inbox | Unified inbox for Leboncoin, eBay and email. Chrome extension intercepting Leboncoin conversations, AI-suggested and fully autonomous replies, Telegram-connected mail agent, team of specialised AI agents with a supervisor and a real-time control room. Connected to the PrestaShop catalog (price, stock, listings). | NestJS, Next.js, MySQL, BullMQ, OpenAI, Chrome Extension |
| **PrestaShop 9 migration & premium storefront** | Full migration of a 16 000-product store from PS 1.7 to PS 9: fresh install + ETL, module-by-module compatibility fixes, Hummingbird theme rebuild with page-builder widgets, conditional warranty rules, transactional email theme, SEO redirect plan, deploy runbook. Live since Sept 2026. | PrestaShop 9, PHP 8.3, Symfony, Creative Elements, Git |
| **MH Audit Modules** · migration cockpit | Audits a source shop (local or remote via tokenised connector), classifies 120+ modules and 30+ overrides, copies / installs / packages them in batches, diffs overrides, runs smoke tests, tracks what is done / tested / configured, and exports untranslated strings for AI translation. | PHP, PrestaShop 1.7 → 9 |
| **MaxDeal Go** · warehouse PWA | Order preparation, picking lists, box selection, issue reporting and shipping label generation from a phone, with Packlink API, connected scale and barcode scanning. Replaces a fully manual 30–60 parcels/day workflow. | PrestaShop module, PWA, Packlink API |
| **AI Refurbishment Platform** | Automatic grading of refurbished products: OCR scanning, defect detection, AI-generated titles and descriptions, dynamic pricing, direct eBay OAuth publication with watermarked photos. | Python, OpenAI, OCR, React, Supabase |
| **Marketplace connectors** | Direct Mirakl integrations (Home24, BUT invoices), Leboncoin API (Cognito auth, category mapping, dry-run), eBay API, Sellermania patches for PS9, BeezUP feed rules for Meta Ads. | PHP, REST, OAuth2, Mirakl, BeezUP |
| **Reconditioning ERP** · AppMaxdeal Hub | Stock, reconditioning workflow, Reconomia API (OpenID Connect / Keycloak) for regulatory reuse reporting, eBay listing module. | NestJS, Next.js, MariaDB |
| **Talabat Tewssil** · delivery app | Voice-first food-delivery app for Nouakchott with a courier network, local payment integrations, App Store / Play Store release. | Turborepo, NestJS, Expo React Native |
| **EfficaOrga** · hotel cleaning management | Multi-role PWA: intelligent scheduling, drag-and-drop team seating, vehicle fleet, intervention snapshots, automated SMS / email. | React, TypeScript, Supabase |
| **AlpesInterface** · ATS & dispatch | n8n-powered email processing, CV parsing, Telegram notifications, driver / vehicle / seat management with Brevo transactional emails. | n8n, Supabase, Railway, Brevo |
| **HR & Payroll app** | Interim-worker management: gross / net calculations, coefficient-based pay by affiliation, PDF / Excel exports, bank reconciliation. | React, Node.js, PostgreSQL |

---

### PrestaShop Module Ecosystem (selection)

300+ modules shipped across production stores. A few representative ones:

| Domain | Modules |
|--------|---------|
| **Marketplaces** | `mhhome24` (Mirakl), `mhmiraklinvoice` (BUT), `mhleboncoinapi`, `mhtosellerpush`, Sellermania PS9 patches |
| **Orders & logistics** | `customorderslist` (picking PDF), `mhcolis`, `mhtracking`, `mhexportlisting` (mobile stock-taking), MaxDeal Go PWA |
| **Pricing & promotions** | `mhpercentshipping` (tiered % shipping), `mhsmartpromo`, `mhupdateprices` (bulk CSV), cart-tier promo display, `mhvatnumber` (EU VAT exemption) |
| **Customer experience** | `mhluckywheel` (in-store QR contest), `mhavisproduct`, `mhshortcodeminiatureinfo`, delivery-delay shortcodes, `retractationform`, `mhexportrefund` |
| **Storefront & SEO** | `mxhomewidgets` (page-builder widgets), `mhmailtheme`, `mhenrichedproductschema` (JSON-LD), Doofinder search, faceted-search fixes |
| **Migration & tooling** | `mhauditmodules` + `mhauditconnector`, translation workshop, override diffing, smoke tests |

---

### Tech Stack

**Core**

![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![Symfony](https://img.shields.io/badge/Symfony-000?style=flat-square&logo=symfony&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white)

**E-commerce & Marketplaces**

![PrestaShop](https://img.shields.io/badge/PrestaShop_1.7_|_8_|_9-DF0067?style=flat-square&logo=prestashop&logoColor=white)
![Mirakl](https://img.shields.io/badge/Mirakl-1A1A1A?style=flat-square)
![BeezUP](https://img.shields.io/badge/BeezUP-FF6F00?style=flat-square)
![Sellermania](https://img.shields.io/badge/Sellermania-2E7D32?style=flat-square)
![eBay](https://img.shields.io/badge/eBay-E53238?style=flat-square&logo=ebay&logoColor=white)
![Leboncoin](https://img.shields.io/badge/Leboncoin-EC5A13?style=flat-square)
![Packlink](https://img.shields.io/badge/Packlink-0052CC?style=flat-square)
![Stripe](https://img.shields.io/badge/Stripe-635BFF?style=flat-square&logo=stripe&logoColor=white)

**Marketing & Tracking**

![Google Ads](https://img.shields.io/badge/Google_Ads-4285F4?style=flat-square&logo=googleads&logoColor=white)
![Meta](https://img.shields.io/badge/Meta_Ads_+_CAPI-0081FB?style=flat-square&logo=meta&logoColor=white)
![GTM](https://img.shields.io/badge/GTM_Server--side-246FDB?style=flat-square&logo=googletagmanager&logoColor=white)
![GA4](https://img.shields.io/badge/GA4-E37400?style=flat-square&logo=googleanalytics&logoColor=white)
![Search Console](https://img.shields.io/badge/Search_Console-458CF5?style=flat-square&logo=googlesearchconsole&logoColor=white)

**AI & Automation**

![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Anthropic](https://img.shields.io/badge/Claude_API-D4A27F?style=flat-square&logo=anthropic&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude_Code-D4A27F?style=flat-square&logo=anthropic&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000?style=flat-square&logo=ollama&logoColor=white)
![Telegram](https://img.shields.io/badge/Telegram_Bots-26A5E4?style=flat-square&logo=telegram&logoColor=white)

**Mobile**

![React Native](https://img.shields.io/badge/React_Native_/_Expo-61DAFB?style=flat-square&logo=react&logoColor=black)
![PWA](https://img.shields.io/badge/PWA-5A0FC8?style=flat-square&logo=pwa&logoColor=white)
![Swift](https://img.shields.io/badge/SwiftUI-F05138?style=flat-square&logo=swift&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)

**Infrastructure & Data**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![Plesk](https://img.shields.io/badge/Plesk-52BBE6?style=flat-square&logo=plesk&logoColor=white)
![Railway](https://img.shields.io/badge/Railway-0B0D0E?style=flat-square&logo=railway&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL_/_MariaDB-4479A1?style=flat-square&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![Redis](https://img.shields.io/badge/Redis_/_BullMQ-DC382D?style=flat-square&logo=redis&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)

---

### How I work

- **Production-first** · code is written to ship in one pass, with Git traceability, database dumps before and after, and a rollback path.
- **Operable by the business** · storefronts, widgets and rules are editable from the back-office by non-technical teams; no hard-coded text.
- **AI as a teammate** · I run Claude Code agents directly on servers (tmux, remote control) to map, implement and verify changes, with every commit under my name.
- **Incident-ready** · I have handled MySQL crashes during bot attacks, full-disk outages, corrupted category trees, 30 000 lost product images recovered from backups.

---

### Currently

- 🤖 Rebuilding **Comptoir** around a team of specialised AI agents with a live control room
- 🚚 Automating order preparation end-to-end (scan → weigh → label → tracking pushed to every marketplace)
- 🛒 Turning the Home24 connector into a multi-marketplace engine to replace third-party feed tools
- 📡 Monitoring & alerting stack for e-commerce stores (uptime, attacks, performance)

---

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=memehoueibib&show_icons=true&theme=github_dark&hide_border=true&include_all_commits=true&count_private=true" height="165" alt="GitHub stats" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=memehoueibib&layout=compact&theme=github_dark&hide_border=true" height="165" alt="Top languages" />

<br/><br/>

**Open to new opportunities** · CDI, freelance, consulting

PrestaShop · E-commerce platforms · Marketplace integrations · AI agents · Server-side tracking

[![Portfolio](https://img.shields.io/badge/memehoueibib.com-00E5B0?style=flat-square)](https://memehoueibib.com)
[![CV FR](https://img.shields.io/badge/CV_Français-111827?style=flat-square)](https://memehoueibib.com/cv/fr/)
[![CV EN](https://img.shields.io/badge/Resume_EN-111827?style=flat-square)](https://memehoueibib.com/cv/en/)

</div>
