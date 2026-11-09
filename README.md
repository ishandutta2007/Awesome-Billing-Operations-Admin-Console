# Awesome Billing Operations & Admin Consoles [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of billing operations platforms, subscription management admin consoles, invoicing portals, and self-hosted billing engines with administrative dashboards.

---

## Contents

- [Overview](#overview)
- [SaaS Billing Platforms](#saas-billing-platforms)
- [Open-Source Billing Platforms & Admin Consoles](#open-source-billing-platforms--admin-consoles)
- [Contributing](#contributing)

---

## Overview

Billing operations involve tracking subscriptions, invoicing, payment gateways, usage metering, and account collections. In the industry, billing tooling generally falls into two categories:

1. **SaaS Billing Platforms**: Commercial platforms where the admin console is the core operational interface for managing subscriptions and revenue.
2. **Open-Source Billing Platforms & Admin Consoles**: Self-hosted or community-driven engines with dedicated admin portals and dashboards for billing and subscription management.

---

## SaaS Billing Platforms

The following commercial billing platforms bundle administrative consoles as their primary operations UI:

| Platform | Admin Console / Operational Interface | Pricing |
|---|---|---|
| **[Stripe](https://stripe.com)** | Stripe Dashboard (payments, billing, invoicing, and subscription management) | **Free tier**: No fixed monthly fee (pay-as-you-go). **Pricing**: Billing is 0.70% of recurring volume; standard card processing is 2.9% + 30¢. Custom enterprise pricing available. |
| **[Chargebee](https://www.chargebee.com)** | Chargebee Admin Console (subscription management, billing workflows, and analytics) | **Free tier**: Starter / Launch tier available (free up to first $250k cumulative billing, or 0% / free up to specific transaction thresholds). **Pricing**: Flow tier at $0 + 0.80% or $99/mo + 0.65%; Performance plan from $599/mo; custom enterprise plans available. |
| **[Recurly](https://recurly.com)** | Recurly Admin Console (churn management, subscriber management, and analytics) | **Free tier**: No free tier; free trial available. **Pricing**: Starter plan begins at $249/mo + 0.9% of revenue; Professional and Enterprise tiers via custom quote. |
| **[Paddle](https://www.paddle.com)** | Paddle Vendor Dashboard (Merchant of Record, global tax compliance, and billing console) | **Free tier**: No monthly software subscription fee. **Pricing**: 5% + 50¢ per transaction across global sales, including MoR tax compliance. Custom enterprise pricing available. |
| **[Rebilly](https://www.rebilly.com)** | Rebilly Console (subscription automation, churn prevention, and payment orchestration) | **Free tier**: Sandbox / free trial available. **Pricing**: Pro plan starts at $125/mo + 1% of revenue; Enterprise pricing tailored to custom volume. |
| **[Zuora](https://www.zuora.com)** | Zuora Central Billing Console (enterprise quote-to-revenue operations) | **Free tier**: None. **Pricing**: Enterprise quote-only based on billing volume, features, and scale. |
| **[FastSpring](https://fastspring.com)** | FastSpring Operations Portal (digital commerce and SaaS subscription engine) | **Free tier**: None. **Pricing**: Revenue share model (percentage + transaction fee), typically starting around 8.9% or custom negotiated rates. |
| **[BillingPlatform](https://billingplatform.com)** | BillingPlatform Operations Console (dynamic usage-based and hybrid billing) | **Free tier**: None. **Pricing**: Enterprise quote-only based on usage volume and configuration. |
| **[Ordway](https://www.ordwaylabs.com)** | Ordway Admin Console (billing automation and revenue recognition) | **Free tier**: None. **Pricing**: Quote-based SaaS pricing tailored to mid-market and growth stage companies. |
| **[Maxio](https://www.maxio.com)** | Maxio Admin Console (formerly Chargify + SaaSOptics; B2B SaaS billing & metrics) | **Free tier**: None. **Pricing**: Starts at ~$599/mo based on annual recurring revenue (ARR); custom enterprise tiers available. |

---

## Open-Source Billing Platforms & Admin Consoles

Self-hosted billing systems, invoicing applications, and subscription engines featuring administrative consoles. Sorted descending by GitHub star count:

- **[Hyperswitch](https://github.com/juspay/hyperswitch)** [![Stars](https://img.shields.io/github/stars/juspay/hyperswitch?style=social&color=white)](https://github.com/juspay/hyperswitch/stargazers) — High-performance, open-source payment orchestration router with an admin dashboard to handle payments, routing, and refunds across multiple processors.
- **[Lago](https://github.com/getlago/lago)** [![Stars](https://img.shields.io/github/stars/getlago/lago?style=social&color=white)](https://github.com/getlago/lago/stargazers) — Open-source metering and usage-based subscription billing platform with an intuitive operational back-office console.
- **[Invoice Ninja](https://github.com/invoiceninja/invoiceninja)** [![Stars](https://img.shields.io/github/stars/invoiceninja/invoiceninja?style=social&color=white)](https://github.com/invoiceninja/invoiceninja/stargazers) — Leading open-source invoicing, billing, and client management platform with full administrative and client portals.
- **[Akaunting](https://github.com/akaunting/akaunting)** [![Stars](https://img.shields.io/github/stars/akaunting/akaunting?style=social&color=white)](https://github.com/akaunting/akaunting/stargazers) — Free and open-source accounting and billing software for small businesses with an extensible modular admin panel.
- **[Crater](https://github.com/crater-invoice-inc/crater)** [![Stars](https://img.shields.io/github/stars/crater-invoice-inc/crater?style=social&color=white)](https://github.com/crater-invoice-inc/crater/stargazers) — Open-source invoicing app for freelancers and small businesses with Vue.js/Laravel administration panels and companion mobile apps.
- **[Kill Bill](https://github.com/killbill/killbill)** [![Stars](https://img.shields.io/github/stars/killbill/killbill?style=social&color=white)](https://github.com/killbill/killbill/stargazers) — Robust open-source subscription billing and payments platform designed for enterprise scale. Includes administrative interfaces via the [Kill Bill Admin UI](https://github.com/killbill/killbill-admin-ui) [![Stars](https://img.shields.io/github/stars/killbill/killbill-admin-ui?style=social&color=white)](https://github.com/killbill/killbill-admin-ui/stargazers).
- **[InvoicePlane](https://github.com/InvoicePlane/InvoicePlane)** [![Stars](https://img.shields.io/github/stars/InvoicePlane/InvoicePlane?style=social&color=white)](https://github.com/InvoicePlane/InvoicePlane/stargazers) — Self-hosted open-source application for managing invoices, clients, quotes, and payment collections.
- **[Paymenter](https://github.com/Paymenter/Paymenter)** [![Stars](https://img.shields.io/github/stars/Paymenter/Paymenter?style=social&color=white)](https://github.com/Paymenter/Paymenter/stargazers) — Modern open-source gateway and billing platform tailored for hosting companies with built-in client and administration panels.
- **[OpenMeter](https://github.com/openmeterio/openmeter)** [![Stars](https://img.shields.io/github/stars/openmeterio/openmeter?style=social&color=white)](https://github.com/openmeterio/openmeter/stargazers) — Cloud-native usage metering and real-time event aggregation engine for usage-based AI and developer API billing.
- **[Meteroid](https://github.com/meteroid-oss/meteroid)** [![Stars](https://img.shields.io/github/stars/meteroid-oss/meteroid?style=social&color=white)](https://github.com/meteroid-oss/meteroid/stargazers) — Open-source pricing and billing infrastructure providing subscription management, invoicing, usage-based metering, and revenue analytics.
- **[ITFlow](https://github.com/itflow-org/itflow)** [![Stars](https://img.shields.io/github/stars/itflow-org/itflow?style=social&color=white)](https://github.com/itflow-org/itflow/stargazers) — Open-source IT documentation, ticketing, and billing platform with comprehensive client and invoice management.
- **[SolidInvoice](https://github.com/SolidInvoice/SolidInvoice)** [![Stars](https://img.shields.io/github/stars/SolidInvoice/SolidInvoice?style=social&color=white)](https://github.com/SolidInvoice/SolidInvoice/stargazers) — Simple, elegant open-source invoicing solution and automated billing management application with a web-based administrative console.
- **[Open Source Billing](https://github.com/vteams/open-source-billing)** [![Stars](https://img.shields.io/github/stars/vteams/open-source-billing?style=social&color=white)](https://github.com/vteams/open-source-billing/stargazers) — Clean, straightforward open-source portal for generating invoices, recurring payments, and collecting payments online.
- **[AgileBill](https://github.com/tony-landis/agilebill)** [![Stars](https://img.shields.io/github/stars/tony-landis/agilebill?style=social&color=white)](https://github.com/tony-landis/agilebill/stargazers) — Open-source billing engine and provisioning software with comprehensive administration tools.
- **[Faveo Invoicing](https://github.com/faveosuite/faveo-invoicing-community)** [![Stars](https://img.shields.io/github/stars/faveosuite/faveo-invoicing-community?style=social&color=white)](https://github.com/faveosuite/faveo-invoicing-community/stargazers) — Open-source platform for SaaS billing and software license management built on Laravel.
- **[UniBee](https://github.com/UniBee-Billing/unibee)** [![Stars](https://img.shields.io/github/stars/UniBee-Billing/unibee?style=social&color=white)](https://github.com/UniBee-Billing/unibee/stargazers) — Open-source recurring billing and subscription management platform with merchant and [Admin Portal](https://github.com/UniBee-Billing/unibee-admin-portal) [![Stars](https://img.shields.io/github/stars/UniBee-Billing/unibee-admin-portal?style=social&color=white)](https://github.com/UniBee-Billing/unibee-admin-portal/stargazers) front-ends.
- **[Jetstream Cashier Billing Portal](https://github.com/renoki-co/jetstream-cashier-billing-portal)** [![Stars](https://img.shields.io/github/stars/renoki-co/jetstream-cashier-billing-portal?style=social&color=white)](https://github.com/renoki-co/jetstream-cashier-billing-portal/stargazers) — Billing portal package for Laravel Jetstream tracking subscription quotas, plans, and seats.
- **[PNLCS](https://github.com/Panelica/pnlcs)** [![Stars](https://img.shields.io/github/stars/Panelica/pnlcs?style=social&color=white)](https://github.com/Panelica/pnlcs/stargazers) — Open-source hosting billing system and client portal alternative to WHMCS built on Laravel.
- **[Autumn (Summer)](https://github.com/useautumn/summer)** [![Stars](https://img.shields.io/github/stars/useautumn/summer?style=social&color=white)](https://github.com/useautumn/summer/stargazers) — Developer billing and usage-tracking toolkit designed to sit cleanly between Stripe and modern SaaS apps.
- **[BillKu](https://github.com/ribato22/BillKu)** [![Stars](https://img.shields.io/github/stars/ribato22/BillKu?style=social&color=white)](https://github.com/ribato22/BillKu/stargazers) — SME billing, invoicing, and operations management dashboard built on NestJS and Next.js.
- **[Liberu Billing](https://github.com/liberusoftware/project-billing-laravel-inertia-react)** [![Stars](https://img.shields.io/github/stars/liberusoftware/project-billing-laravel-inertia-react?style=social&color=white)](https://github.com/liberusoftware/project-billing-laravel-inertia-react/stargazers) — Modular billing and invoicing application built on Laravel, Inertia, and React.

---

## Contributing

Contributions are welcome! Please check out the [contribution guidelines](CONTRIBUTING.md) to add new tools or improve information.
