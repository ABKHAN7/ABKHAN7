# Abdul Basit

**Odoo ERP & Python Developer** · Islamabad, Pakistan

I build and maintain Odoo implementations end-to-end: custom modules, version migrations, database recovery, third-party integrations, and reporting. Production experience across Odoo 14–19 (Community and Enterprise) in Python, OWL.js, XML, and QWeb.

[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:abdulbasit.workofficial@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/abdul-basit-3166b3232)
[![Upwork](https://img.shields.io/badge/Upwork-6FDA44?style=flat-square&logo=upwork&logoColor=white)](https://www.upwork.com/freelancers/~01824b2703ca5619a9)
[![Portfolio](https://img.shields.io/badge/Portfolio-111827?style=flat-square&logo=githubpages&logoColor=white)](https://abdulbasit.workofficial.com)

---

## What I do

- **Custom Odoo module development** — Python backend, OWL.js frontend, XML views, QWeb reports
- **Version migrations** — Enterprise ↔ Community conversions and major-version upgrades using OpenUpgrade
- **Database administration and recovery** — backup restoration, constraint resolution, Studio field reconstruction, admin reset via passlib
- **Third-party integrations** — PrestaShop, eCommerce platforms, payment gateways, accounting systems
- **Custom reports** — QWeb PDFs, the Odoo 17 / 18 / 19 accounting reports framework, POS receipts
- **Process automation** — workflow rules, scheduled actions, custom approval chains, pricelist change tracking

---

## Selected work

**Aegis (Canadian-American industrial company) — Odoo Developer · Part-time**
Sole developer on a production Odoo deployment of 124 custom modules across procurement, inventory, sales, and accounting.

- **Led the v17 → v19 production migration solo** — zero data loss across all 124 modules, including Enterprise → Community conversion and the OpenUpgrade v18 intermediate step.
- **Built the Sales Analysis Report (SAR) QWeb engine** — product image embedding via `image_data_uri()` with `bin_size=False`, UTF-8 currency encoding fix in `wkhtmltopdf`, A4 landscape pagination with fixed row heights, and invoice sequence aggregation across `sale_order_line → sale_order_line_invoice_rel → account_move_line → account_move` to handle Odoo 17's removal of the stored M2M junction table.

**Rastgar — Junior Odoo Developer · Full-time (current)**
Maintain a production Odoo deployment with custom module development across procurement, inventory, sales, and accounting. Performed live database restoration from a corrupted backup into `rastgar_restored`, resolving PostgreSQL authentication errors, custom-module indentation failures, duplicate-key constraints, and missing Studio-generated columns; admin reset via passlib. Ongoing feature development and system administration.

**Odoo v17 Community → v18 Enterprise migration — Upwork (Nov 2025)**
Solo execution of a cross-version, cross-edition production database migration as a fixed-price contract. Delivered with a 5.0 / 5.0 client rating.

**Custom financial report — Odoo 18 accounting framework**
Built the `impetus_project_invoicing` report inside Odoo 18's accounting reports framework. Switched from native formula format to `code.expression_label` syntax (e.g., `PROJ_REV.balance`) to resolve a runtime formula-expansion error.

**FoodieHub (solo project)**
End-to-end restaurant tender management system covering procurement workflow, supplier management, and order tracking.

**Green Agrimall — Odoo 17 implementation**
ERP rollout for agricultural trading: product catalog, inventory, sales pipeline, and custom procurement modules.

---

## Stack

**Core:** Python · PostgreSQL · Odoo 14–19 · OWL.js · XML · QWeb

**Tooling:** Git · PyCharm · VS Code · Ubuntu Linux · OpenUpgrade · passlib · wkhtmltopdf

**Adjacent:** JavaScript · HTML / CSS · REST APIs · webhooks · PrestaShop integration

---

## Education

**B.Sc. Computer Science** — Kohat University of Science & Technology · 2021–2025

---

## Activity

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=ABKHAN7&theme=github-dark&hide_border=true&background=0D1117&stroke=58A6FF&ring=58A6FF&fire=58A6FF&currStreakLabel=58A6FF" alt="GitHub Streak" />
</p>

---

*Open to senior Odoo development roles, complex integration work, and ERP migration projects. Reach out via email or LinkedIn.*
