# Awesome-Embedded-Lending-Platform

# Top Embedded Lending Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on API-First Lending Infrastructure, Automated Underwriting, White-Label Capital & Platform-Embedded Credit*
**Last updated: September 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Embedded Lending**. These tools help platforms, marketplaces, and fintechs offer capital to their business customers directly inside the software they already use—removing friction from traditional loan applications and enabling underwriting based on real-time platform data.

**Examples** include Taktile, Upstart, Amount, Finastra, Blend, Newgen Lending, Decimal Technologies, TurnKey Lender, LendAPI, Nucleus Software, Pipe, Parafin, Kanmon, Treasury Prime, Unit, Capchase, Wayflyer, Fundbox, Settle, and Zilch Business (the category leaders).

**Open-source emphasis**: Embedded lending is a commercially consolidated category, but **powerful open-source foundations exist** for building lending infrastructure. The standout is **Frappe Lending**—a production-ready, 100% open-source Loan Management System built on the Frappe Framework and ERPNext, already handling tens of thousands of live loans. Apache Fineract and Mifos X provide battle-tested core banking with lending modules. This section documents every major open-source path, from full LMS platforms to core banking engines with lending capabilities.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Taktile](https://taktile.com/)**
  Decision-making platform for automated lending and risk assessment. Enables lenders to build, test, and deploy underwriting decisions with a visual builder and API-first architecture.

- **[Upstart](https://www.upstart.com/)**
  AI lending marketplace connecting borrowers with bank partners. Uses machine learning for credit decisioning that considers education and employment history alongside traditional credit data.

- **[Amount](https://www.amount.com/)**
  Digital lending infrastructure for banks and credit unions. Provides white-label loan origination, decisioning, and account opening with deep core banking integrations.

- **[Finastra](https://www.finastra.com/)**
  Global financial software provider with comprehensive lending solutions spanning commercial, corporate, and retail lending. Offers API-first lending platforms for banks and financial institutions.

- **[Blend](https://blend.com/)**
  Digital lending platform for banks and mortgage lenders. Streamlines loan applications, verification, and closing with a focus on consumer experience.

- **[Newgen Lending](https://newgensoft.com/)**
  Digital lending platform covering loan origination, underwriting, and servicing. Part of Newgen's broader banking and financial services suite.

- **[Decimal Technologies](https://decimaltech.com/)**
  Digital lending and onboarding platform for financial institutions. Provides loan origination, credit decisioning, and customer onboarding with deep India market expertise.

- **[TurnKey Lender](https://turnkey-lender.com/)**
  End-to-end lending automation platform. Provides loan origination, decisioning, servicing, and collections for banks, credit unions, and alternative lenders.

- **[LendAPI](https://lendapi.com/)**
  API-first lending infrastructure platform. Enables any platform to embed lending products via a unified API, handling origination, underwriting, and capital management.

- **[Nucleus Software](https://www.nucleussoftware.com/)**
  Financial technology provider with lending and transaction banking solutions. Offers loan management, origination, and collections platforms for financial institutions.

- **[Pipe](https://pipe.com/)**
  Embedded capital platform for SaaS companies. Provides revenue-based financing that integrates directly into SaaS platforms, using platform data for underwriting.

- **[Parafin](https://www.parafin.com/)**
  Embedded financing infrastructure for marketplaces, vertical SaaS, and payment processors. Powers capital programs for Amazon, DoorDash, Walmart, and Mindbody. Handles underwriting, compliance, servicing, and capital markets. Extends over $25 billion in offers . Offers Term (fixed-term loan) and Flex (revenue-based financing) products, with no-code, low-code, and custom integration paths .

- **[Kanmon](https://kanmon.com/)**
  Embedded lending platform for vertical SaaS and fintechs. Provides white-label loan origination, underwriting, and servicing with API-first integration.

- **[Treasury Prime](https://treasuryprime.com/)**
  Banking-as-a-Service platform with embedded lending capabilities. Provides APIs for account opening, money movement, and credit products.

- **[Unit](https://unit.co/)**
  Banking-as-a-Service platform with lending products. Enables platforms to offer credit and charge cards, and lending through a unified API.

- **[Capchase](https://capchase.com/)**
  Revenue-based financing for SaaS and subscription businesses. Provides non-dilutive capital tied to recurring revenue.

- **[Wayflyer](https://wayflyer.com/)**
  Revenue-based financing for e-commerce brands. Provides capital for inventory and marketing spend, repaid as a percentage of sales.

- **[Fundbox](https://fundbox.com/)**
  Small business financing platform. Provides lines of credit and term loans with fast underwriting based on business data.

- **[Settle](https://settle.co/)**
  Bill pay and financing platform for startups. Combines accounts payable automation with embedded credit.

- **[Zilch Business](https://zilch.com/)**
  Buy-now-pay-later and credit platform for businesses. Provides embedded financing at point of sale.

## Open-Source GitHub Projects

- **[Frappe Lending](https://github.com/frappe/lending)**
  The most mature open-source Loan Management System (LMS) available. Built on ERPNext and the Frappe Framework, it provides end-to-end loan lifecycle management: loan origination, disbursement, repayment scheduling, interest accrual, collections, collateral management, co-lending, and credit bureau file generation. **100% open source and API-first**—every feature is REST API compatible . Already running in production at institutions managing tens of thousands of live loans and disbursing hundreds daily . Handles loan booking, portfolio management, DPD tracking, NPA classification, and regulatory reporting . Python/JavaScript stack with role-based access, audit logs, and document versioning . **Open source**. 

- **[Apache Fineract](https://github.com/apache/fineract)**
  The Apache Software Foundation's open-source core banking system designed for digital financial services. Version 1.11.0 (March 2025) includes lending capabilities alongside savings, deposits, and client management . Fineract is the backend engine for Mifos X, providing the common functionalities for creating customers, managing wallets, savings and loan accounts, and maintaining financial ledgers . **Apache-2.0**. 

- **[Mifos X](https://github.com/openMF/mifos-x)**
  A Digital Public Good recognized by the Digital Public Goods Alliance. Full core banking suite including the Fineract backend, web UI, reporting plugin, mobile field operations app (Kotlin), and customer mobile banking app . Used by financial inclusion organizations worldwide. **Open source (Mozilla Public License)**. 

- **[Open Source Bank](https://github.com/ishanperera/opensourcebank)**
  API-first core banking engine with a double-entry ledger, transaction processing, and compliance tooling. Explicitly designed so developers can **build a lending platform on top of it** . Features idempotent transactions, JWT + API keys auth, RBAC, PII encryption, audit logging, fraud detection engine, Plaid sandbox, and Stripe test mode integration. Python FastAPI + Next.js stack, PostgreSQL, Docker Compose deployment. **Open source**. 

- **[FinAegis Core Banking Prototype](https://github.com/FinAegis/core-banking-prototype-laravel)**
  Laravel-based core banking prototype with **modular lending domain**. Install only the domains you need: `php artisan domain:install lending` . Features P2P loans, credit scoring, and risk assessment within the lending module. Includes event sourcing with Redis Streams, multi-asset accounts, governance, and compliance domains. PHP 8.4+, PostgreSQL, Redis. Demo mode runs without external dependencies. **Open source**. 

- **[FinCoreX](https://github.com/Vignesh-R-G/FinCoreX)**
  Lightweight core banking system with **loan processing and repayment modules**. Spring Boot, Spring Security, Spring Batch for automated repayments, AOP, and PostgreSQL. Handles CASA accounts, fixed deposits, loan creation, disbursement, and repayment scheduling. **Open source**. 

- **[XRPL Permissioned Lending Framework](https://github.com/VS1-Finance/xrpl-lending)**
  Open-source reference application for **compliant, permissioned lending on the XRP Ledger**, developed by the XRPL Foundation and VS1 Finance . Uses native XRPL components (Credentials, Permissioned Domains, Single Asset Vaults, Lending Protocol) instead of external smart contracts—reducing security risks and enabling KYC/AML-gated liquidity pools . Designed for institutional credit with automated term lending and asset allocation. Lessons incorporated from the National Bank of Georgia regulatory sandbox. **Open source**. 

### Additional Strong Open-Source Options

- **Full LMS Platforms**: **Frappe Lending** (production-ready, ERPNext-based, API-first) .
- **Core Banking with Lending**: **Apache Fineract** (Apache-2.0, used by Mifos), **Mifos X** (Digital Public Good), **Open Source Bank** (API-first, double-entry ledger) .
- **Modular Banking Frameworks**: **FinAegis** (Laravel, install lending domain separately), **FinCoreX** (Spring Boot, loan processing) .
- **Blockchain Lending**: **XRPL Lending Framework** (institutional-grade, permissioned, compliance-ready) .

**Frameworks for building custom systems**: Combine **Frappe Lending** for the complete loan lifecycle management, **Apache Fineract** or **Open Source Bank** for core banking ledger and account infrastructure, **FinAegis** for modular domain-based architecture, and **XRPL Lending Framework** for permissioned on-chain lending. Add **PostgreSQL** for persistence and **Docker** for deployment.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Embedded lending platforms handle sensitive financial and personal data; ensure compliance with lending regulations, KYC/AML requirements, and data protection laws.
- **Open-source reality**: **Frappe Lending** is the standout open-source LMS—production-ready, actively maintained, and already processing tens of thousands of loans . **Apache Fineract** and **Mifos X** provide mature core banking foundations with lending modules . However, embedded lending *programs* (underwriting engines, capital markets access, platform-native UX) still require significant integration work or commercial partners like **Parafin** .

---

**Made for fintech builders, platform product managers, embedded finance developers, and lending infrastructure teams.**
Let's make embedded lending more open, transparent, and accessible.
