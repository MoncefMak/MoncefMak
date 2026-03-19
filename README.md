# Hi, I'm Moncef Makti — Full-Stack Software Engineer

- 🚀 I build scalable web apps, ERPs, and healthcare platforms that solve real business problems
- 💻 6+ years shipping production software across **Python/Django**, **TypeScript/NestJS**, **Vue.js/Nuxt**, and **C#**
- 🏥 Started in **healthcare tech** — teleconsultation, clinical systems, DICOM imaging, pharmacy inventory
- 🎪 Built an **event management SaaS** — payments, WhatsApp API, QR ticketing, multi-tenant architecture
- 🏢 Developed a **facilities management ERP** — accounting, sales pipeline, inventory, e-invoicing
- 📊 1,500+ commits · 900K+ lines of production code across 3 companies
- 🌍 Based in Algeria, experienced working with Saudi Arabia-based teams
- 💼 Experience:
  - **Full-Stack Developer at Azzam** — Event Management SaaS (Python/Django)
  - **Full-Stack Developer at Atqan** — Facilities Management ERP (NestJS/Vue.js) & Internal Platform (Django/Docker)
  - **Full-Stack Developer at Ibn Hamza S & M** — Healthcare Solutions (Django/Java 8/C#)

### 🛠 Tech Stack

`Python` `Django` `TypeScript` `NestJS` `Vue.js` `Nuxt` `C#` `Java` `PostgreSQL` `Redis` `Celery` `Docker` `Tailwind CSS` `HTMX` `Cloudflare R2`

### 📫 Let's connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/moncef-makti-3549b9138/)
[![WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://wa.me/213775647192)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/MoncefMak)

---

<!-- DETAILED VERSION BELOW — for reference, not displayed on profile -->
<!-- You can keep or remove everything below this line -->

<details>
<summary>📄 Click for detailed experience breakdown</summary>

## Azzam — Event Management SaaS | Core Developer
**Oct 2023 – Present** · Python/Django · Celery · PostgreSQL · Redis · Cloudflare R2

Multi-tenant platform for workshops, ticketing, payments, and communications in Saudi Arabia. I own 45% of the codebase.

- Migrated payments through **3 providers** (PayLink → Moyasar → MyFatoorah) — idempotent webhook
- Built a full **WhatsApp Cloud API** integration: template management with Meta auto-sync, real-time inbox, message history, rate limiting
- Eliminated **N+1 queries across 15+ views** — reduced critical page queries from ~40 to ~1
- Designed **multi-tenant isolation** with RBAC permissions, company-scoped data, and safe user-merge across tenants
- Migrated media storage to **Cloudflare R2** with signed URLs and presigned uploads
- Built **QR ticketing** with UUID-encrypted tokens, row-level locking for concurrent scans
- Led **Django 5.2 upgrade**, removed 20+ dead modules, consolidated 3 messaging apps into one
- Architected **Celery task routing** with dedicated queues and memory-optimized workers

`1,094 commits · 710K+ lines · 196K Python · 43K HTML`

---

## Atqan — Facilities Management ERP | Full-Stack Developer
**May 2024 – Feb 2026** · TypeScript/NestJS · Vue.js/Nuxt 4 · TypeORM · PostgreSQL · Docker

**Phase 1 — Backend & Infrastructure** *(May 2024 – Apr 2025)*
- Containerized the project with **Docker**
- Built **OTP authentication** with vacation/entry-period access control
- Designed a **granular permissions system** on top of Django models
- Integrated **Huawei OBS** and **CSV/Excel data import** pipelines

**Phase 2 — Facilities Management ERP** *(May 2025 – Feb 2026)*
- Built the complete **sales pipeline**: quotations → orders → invoices → returns (100+ commits)
- Developed the **accounting engine**: journal entries, notices, approval workflows
- Created **financial reports** with PDF export: account statements, income statements, cash flow
- Implemented **inventory flows**: assembly/disassembly, stock tracking, adjustment reports
- Built **property & HR modules**: employee contracts, heir tracking, soft-delete patterns
- Integrated **Saudi e-invoicing** compliance
- Full **Arabic i18n** with Hijri date support and RTL forms

`445 commits · 190K+ lines · 67K TypeScript · 47K Vue.js`

---

## Ibn Hamza S & M — Healthcare Solutions | Full-Stack Developer
**Aug 2019 – Sep 2023** · Django · Java 8 · C# · JavaScript · Bootstrap

- **Teleconsultation** — remote patient consultation platform
- **Clinical web app** — patient records, care management, **DICOM** imaging, pharmacy inventory
- **Financial modules** (web + desktop) — payments, debt coverage, secure partial payment tokens, invoicing
- **Desktop clinical solution (C#)** — diagnostics for medical specialties, custom installer
- **Online conferences** — for medical professionals

</details>

---

*Every number on this page is backed by actual git history.*
