# Awesome-Consent-Management-Platform

## Top Consent Management Platforms (CMP) Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Cookie Consent, GDPR/CCPA Compliance, Google Consent Mode & Privacy Compliance*

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Consent Management Platforms (CMP)**. These tools help websites and applications collect, manage, and document user consent for cookies and data processing in compliance with GDPR, CCPA/CPRA, ePrivacy, and other privacy regulations.



**Examples** include OneTrust, Cookiebot, Usercentrics, Didomi, CookieYes, Termly, Osano, Iubenda, Crownpeak, Ethyca, TrustArc, and Consentmanager (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom consent workflows, and transparent privacy compliance — ideal for organizations that need full control over consent data without per-pageview SaaS fees or vendor lock-in.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents



- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[OneTrust](https://www.onetrust.com/)**

  The dominant enterprise CMP and privacy management platform. Provides cookie consent, preference centers, compliance automation, and data governance with extensive integrations. Enterprise-focused with significant pricing.



- **[Cookiebot](https://www.cookiebot.com/)**

  Popular CMP known for its automated cookie scanning and user-friendly banner. Provides GDPR, CCPA, and Google Consent Mode compliance with free tier for small websites.



- **[Usercentrics](https://usercentrics.com/)**

  German CMP platform with strong European market presence. Provides consent management, preference centers, and compliance across multiple regulations.



- **[Didomi](https://www.didomi.io/)**

  French CMP and consent management platform. Provides cookie consent, preference management, and compliance tools with strong European focus.



- **[CookieYes](https://www.cookieyes.com/)**

  Affordable CMP with automated cookie scanning and banner customization. Provides GDPR, CCPA, and Google Consent Mode compliance.



- **[Termly](https://termly.io/)**

  CMP and legal compliance platform. Provides cookie consent, privacy policy generation, and terms of service tools.



- **[Osano](https://www.osano.com/)**

  Privacy platform with CMP, data mapping, and consent management. Focuses on simplifying privacy compliance for businesses.



- **[Iubenda](https://www.iubenda.com/)**

  Italian legal tech platform providing CMP, privacy policies, and terms generation. Popular with European businesses and websites.



- **[Crownpeak](https://www.crownpeak.com/)**

  Digital experience platform with CMP capabilities. Provides consent management integrated with content management.



- **[Ethyca](https://www.ethyca.com/)**

  Privacy infrastructure platform with consent management, data mapping, and automated compliance tools. Developer-focused.



- **[TrustArc](https://trustarc.com/)**

  Privacy compliance platform with CMP, assessments, and certification services. Enterprise-focused.



- **[Consentmanager](https://www.consentmanager.net/)**

  German CMP provider with cookie consent and compliance tools. Offers self-hosted option for enterprise.



## Open-Source GitHub Projects



- **[Klaro](https://github.com/kiprotect/klaro)**

  **The most established open-source consent manager.** Simple, privacy-friendly, and compliant with GDPR and ePrivacy. **1,278 stars, 271 forks**. Lightweight (**57 kB gzipped**), multilingual, and designed to be extremely simple and intuitive. Ensures no third-party apps or trackers execute without user consent, even when JavaScript is disabled or Klaro itself is blocked. Available as standalone JS library with extensive integrations including **TYPO3** (erhaweb/klaro-consent-manager) , **Shopware 6** (multi-sales-channel, Google Consent Mode v2) , and **Matomo** integration . **MIT License**. Self-hosted with no cloud dependency .



- **[ConsentOS](https://github.com/consentos/consentos)**

  Self-hosted, multi-tenant cookie consent management platform positioned as a **source-available alternative to OneTrust, Cookiebot, and CookieYes**. Features **auto-blocking** (intercepts script creation, cookie writes, and storage API calls until consent), **Playwright-driven cookie scanner** with auto-categorization against Open Cookie Database (2,200+ patterns), **dark pattern detection** (pre-ticked boxes, missing reject buttons, button asymmetry), compliance engine for GDPR/CNIL/CCPA/CPRA/ePrivacy/LGPD, and **tamper-evident consent record audit trail**. Supports IAB TCF v2.3, GPP v1, Google Consent Mode v2, GPC, and Shopify Customer Privacy API. Configuration cascade from System → Org → Site Group → Site → Region. Docker deployment. **Elastic Licence 2.0** (source-available, self-host indefinitely) .



- **[Consent-O-Matic](https://github.com/cavi-au/Consent-O-Matic)**

  Browser extension that **automatically answers consent pop-ups** based on user preferences. Built by privacy researchers at Aarhus University. Set preferences once, and the extension automatically responds to cookie banners. Works with 4 popular CMPs (Cookiebot, OneTrust, QuantCast, TrustArc) and supports custom rules. **MIT License**. Available for Chrome (197 ratings, 4.2 stars) and Firefox (4.3 stars, 384 reviews) .



- **[WSO2 OpenFGC](https://github.com/wso2/openfgc)**

  Industry-agnostic, flexible **fine-grained consent management engine** built for developers. Go-based with domain-driven layered architecture. Features Consent Elements (specific data points), Consent Purposes (grouping with legal justification), and Consent Records (immutable evidence with full status lifecycle: Created → Active → Expired/Revoked). MySQL/PostgreSQL recommended for production. Open source .



- **[PrivacyLens](https://github.com/privacy-lens)**

  Next-generation consent management UI developed at **Carnegie Mellon University** by usability researchers. Features informed consent mechanisms, optional display of attribute names and values being sent, ability to distinguish required vs optional attributes, multiple consent frequency options, affirmative actions, prior consent log usage, revocation, and grouping of attributes into consent bundles. **Open source** .



### Additional Strong Open-Source Options



- **Lightweight Banners**: **Biscuitman** (8 stars, super lightweight), **novaConsent** (pure vanilla JS), **EasyCookies** (customizable banner library) .

- **Framework Integrations**: **Klaro** integrations for TYPO3, Shopware, Matomo, PrestaShop, Bootstrap 5, Next.js, SvelteKit .

- **Compliance Tools**: **Cookinspect** (Selenium-based crawler for finding IAB TCF violations), **Cookie-Glasses** (browser extension verifying consent matches IAB TCF choices) .

- **SaaS Clones**: **CookieYes Clone** (Next.js + Turso, GDPR/CCPA/Google Consent Mode v2, multi-tenant) .



**Frameworks for building custom systems**: Combine **Klaro** for the core consent banner and blocking engine, **ConsentOS** for multi-tenant management with compliance audit trails, **WSO2 OpenFGC** for fine-grained consent records, and **Consent-O-Matic** for automated consent handling. Add **PostgreSQL** for persistence and **Docker** for deployment.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Consent management platforms handle sensitive user consent data; ensure compliance with GDPR, CCPA/CPRA, ePrivacy, and relevant regional privacy regulations.

- **Open-source reality**: **Klaro** is the most mature open-source CMP with 1,278 stars and extensive integrations . **ConsentOS** provides a more comprehensive multi-tenant platform with dark pattern detection and compliance auditing . However, enterprise-grade features like IAB TCF certification, advanced geo-targeting, and legal team dashboards may require commercial platforms (OneTrust, Cookiebot, Usercentrics) for full regulatory compliance in complex environments.



---



**Made for privacy engineers, web developers, compliance officers, and legal teams.**

Let's make consent management more open, transparent, and privacy-respecting.
