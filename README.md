# Awesome-Utility-Customer-Information-System

# Top Utility Customer Information System (CIS) Platforms Ecosystem
**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Utility Billing, Customer Care, Meter-to-Cash, Rate Management, Account Management & Regulatory Compliance for Electric, Water & Gas Utilities*
**Last updated: August 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Utility Customer Information Systems (CIS)**. These systems manage customer accounts, metering data, billing, payments, service orders, and customer care for electric, water, gas, and multi-utility providers.

**Examples** include Oracle Utilities CC&B, Hansen CIS, Cayenta, Harris CIS, Milsoft CIS, Gentrack, Advanced Utility Systems, NorthStar Utilities, VertexOne, Fluentgrid, Oracle Utilities CIS, Harris Customer CIS, Kraken Technologies, SilverBlaze, and Utilismart (the category leaders).

**Open-source emphasis**: Fully featured open-source utility CIS platforms remain rare due to the complexity of regulated billing and meter-to-cash processes. This section is expanded with the strongest available open-source billing engines, usage-based rating systems, ERPNext utility modules, and related projects that utilities or developers can adapt for customer information and billing needs.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms
- **[Oracle Utilities Customer Care & Billing (CC&B) / Customer Cloud Service](https://www.oracle.com/utilities/)**  
  Enterprise-grade CIS and meter-to-cash platform used by large investor-owned utilities, supporting complex rates, multi-commodity billing, and high transaction volumes.

- **[Hansen CIS](https://www.hansencx.com/)**  
  Modern SaaS customer information system focused on digital customer experience, AI-enabled service, and cloud delivery for water, electric, and multi-utility providers.

- **[Cayenta (Harris)](https://www.harriscomputer.com/)**  
  Integrated CIS and utility suite from Harris Computer, popular with municipal and mid-market utilities for billing, customer care, and field operations.

- **[Harris CIS / Customer Solutions](https://www.harriscomputer.com/)**  
  Suite of customer information and billing solutions serving municipal, cooperative, and mid-to-large utilities.

- **[Milsoft CIS](https://www.milsoft.com/)**  
  Utility software including customer information and related operational systems, often used by electric cooperatives and municipal utilities.

- **[Gentrack](https://www.gentrack.com/)**  
  Customer and billing platforms for utilities and energy retailers, with strong capabilities in complex market and retail environments.

- **[Advanced Utility Systems](https://www.advancedutility.com/)**  
  CIS and utility management solutions focused on billing, customer service, and operational efficiency.

- **[NorthStar Utilities](https://www.northstarutilities.com/)**  
  Customer information and billing systems tailored for utilities seeking integrated meter-to-cash functionality.

- **[VertexOne](https://www.vertexone.com/)**  
  Cloud-oriented CIS and utility customer platform serving mid-to-large utilities with billing and engagement capabilities.

- **[Fluentgrid](https://www.fluentgrid.com/)**  
  Utility software including CIS, billing, and smart-grid related customer systems.

- **[Kraken Technologies](https://kraken.tech/)**  
  Modern energy and utility customer platform known for flexible billing, real-time data, and digital-first customer experiences (widely used by energy retailers).

- **[SilverBlaze](https://www.silverblaze.com/)**  
  Customer engagement and CIS-related solutions for utilities focused on digital channels and self-service.

- **[Utilismart](https://www.utilismart.com/)**  
  Utility customer and billing software supporting account management and related services.

## Open-Source GitHub Projects
- **[BillRun](https://github.com/BillRun/system)**  
  Open-source enterprise billing and fraud-detection system designed for telecom and usage-based businesses; adaptable for high-volume utility or multi-service rating and invoicing.

- **[FOSSBilling](https://github.com/FOSSBilling/FOSSBilling)**  
  Free and open-source billing and client management system originally popular with hosting providers; useful foundation for subscription and usage-based utility-style billing.

- **[CitrusDB](https://github.com/paulyasi/citrusdb)**  
  Classic open-source customer database and billing software for managing accounts, invoices, and basic customer service workflows.

- **[ABillS (AsmodeuS Billing)](https://github.com/)**  
  Mature open-source billing system with prepaid/postpaid support, payments, and service management capabilities that can be extended for utility use cases.

- **[ERPNext Utility Billing modules](https://github.com/navariltd/utility-billing)**  
  Open-source utility billing and property management extension for ERPNext, supporting meter readings, tariffs, mass billing, and service workflows for municipal and multi-tenant scenarios.

- **[Flexprice](https://github.com/flexprice/flexprice)**  
  Open-source usage-based pricing and billing engine with real-time metering, credits, and self-hosting options — relevant for modern consumption-based utility models.

- **[General open billing and rating engines](https://github.com/)**  
  Community projects for mediation, rating, and invoicing that can form the core of a custom CIS billing layer.

- **[Open meter data and MDM prototypes](https://github.com/)**  
  Research and open tools for handling interval meter data that can integrate with billing systems.

- **[Self-hosted CRM + billing stacks](https://github.com/)**  
  Combinations of open CRM (e.g., CiviCRM or similar) with billing modules adapted for account and payment management.

- **[Payment gateway and invoice open libraries](https://github.com/)**  
  Supporting open-source components for payment processing, PDF invoicing, and customer notifications.

### Additional Strong Open-Source Options
- Odoo or ERPNext community modules for utilities and property billing.
- Usage metering and event-based rating libraries.
- Open data models for customer, premise, and service point entities.
- Custom portals built on open web frameworks for self-service account access.
- Reporting and analytics layers using Metabase, Superset, or similar for CIS data.

**Frameworks for building custom systems**: For smaller or municipal utilities, combine **ERPNext + utility billing modules** or a mature open billing engine (**BillRun**, **FOSSBilling**, or **ABillS**) with a self-hosted CRM and meter-data ingestion pipeline. Add open payment gateways, a customer portal, and regulatory reporting scripts. This approach provides full data ownership and avoids proprietary lock-in, though it requires significant configuration and domain expertise to meet utility-grade rate complexity, compliance, and high-availability needs. Large regulated utilities typically still rely on proven commercial CIS platforms.

## How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- Utility CIS systems handle regulated billing, customer data, and financial transactions. Open-source solutions offer transparency and cost advantages but generally lack the out-of-the-box depth, certification, and support required for large regulated utilities. Thorough testing, legal review, rate-engine validation, and operational readiness are essential before any production deployment.
- Always ensure compliance with local utility regulations, data privacy laws, and financial controls.

---
**Made for utility IT leaders, billing managers, and organizations exploring open approaches to customer information and meter-to-cash systems.**
Let's make utility customer systems more transparent, adaptable, and community-supported where feasible.
