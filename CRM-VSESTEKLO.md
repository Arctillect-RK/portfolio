# Vsesteklo CRM / ERP — showcase

**Live (production):** https://crm.vsesteklo.ru/  
**Public site:** https://vsesteklo.ru/  
**Status:** in production, used by the business day-to-day.

> Demo credentials are **not** published here. Contact the author for a private walkthrough.

---

## What it is

Internal **CRM + operations console** for a glass / mirror manufacturing company (Всестекло).  
It connects the **public website**, **engineering calculator**, **price list on the site**, **lead intake**, **reviews**, and **competitor price monitoring** into one admin SPA.

Built as a modern SPA (Vue-based UI) with role-oriented screens for sales and production staff.

---

## Main modules (live menu)

### Management

| Module | What it does |
|--------|----------------|
| **Прайс-контроль** | Live control of **fixed site prices** for catalog products (mirrors & shower partitions). Search by name/SKU, filters (Все / Зеркала / Перегородки), edit «цена на сайте» / «новая цена», sync with public catalog. Dimension-based products (stairs etc.) stay in the **calculator**. |
| **Аналитика за м²** | Business analytics per square meter — margin / volume style KPIs for glass production sales. |
| **Отчёты парсера** | Dashboard for **automatic price parsers** (competitors / suppliers): run history, status, parsed catalogs for dynamic margin recalculation. |
| **Модерация отзывов** | Approve / reject customer reviews before they appear on vsesteklo.ru. |
| **Настройки** | System / company settings for the CRM. |
| **Калькулятор** | **Engineering quote calculator** — complex geometry, thickness, edge processing, cutouts, hardware; real-time cost for custom products (not only fixed SKUs). |

### Sales

| Module | What it does |
|--------|----------------|
| **Заявки с сайта** | Pipeline of **leads from the website** (forms, calculator orders): deals, follow-up, handoff to production specs. |

### Roles (UI views in product)

The SPA includes dedicated experiences for:

- **Manager** — deals, price control, client communication  
- **Engineer** — technical validation / production specs  
- **Measurer** — site measure workflow  
- **Admin** — full access (price list, parsers, reviews, settings)  
- Plus: **clients**, **chat**, **notifications**, **logs**

---

## Product flow (why it matters)

```
Website visitor
  → catalog fixed prices  OR  engineering calculator (custom sizes)
  → lead / order
  → CRM: «Заявки с сайта»
  → commercial proposal / production specification
  → price list & margin controlled in «Прайс-контроль»
  → competitor monitoring via «Отчёты парсера»
  → reviews moderated before public site
```

This is not a landing-page admin. It is the **operating system of the glass business**: sales + pricing + production inputs + market monitoring.

---

## Stack (high level)

- **Frontend CRM:** SPA (Vue), role-based views, responsive (desktop + mobile nav: Заявки / Отзывы / Прайс / Отчёты)  
- **Public site:** marketing + catalog + online calculation entry points  
- **Backend services:** API, database, parsers, notifications (Telegram), payment integrations on the public funnel  
- **Deployed production domains:** `vsesteklo.ru` + `crm.vsesteklo.ru`

---

## Portfolio highlights (for resume / GitHub)

1. Designed and shipped a **production CRM** still used in live operations.  
2. Unified **fixed catalog pricing** and **parametric calculator** in one business process.  
3. **Parser reports** for competitor/supplier prices → margin control.  
4. **Lead intake from website** into internal sales pipeline.  
5. **Review moderation** linked to public reputation.  
6. Multi-role UI (manager / engineer / measurer / admin).

---

## Related public code

- Repo: https://github.com/Arctillect-RK/vsesteklo  
- Portfolio index: https://github.com/Arctillect-RK/portfolio  

Secrets and production keys are scrubbed from the public mirror.
