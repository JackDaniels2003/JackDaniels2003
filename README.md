<!-- ╔══════════════════════════════════════════════════════════════╗ -->
<!-- ║  Daniel Teodoro · Profile README · dark / blue design system   ║ -->
<!-- ╚══════════════════════════════════════════════════════════════╝ -->

<p align="center">
  <img src="./assets/banner.svg" alt="Daniel Teodoro — Software Engineer" width="100%"/>
</p>

<p align="center">
  <a href="./README.md"><b>English</b></a>
  &nbsp;·&nbsp;
  <a href="./README_pt.md">Português</a>
</p>

<p align="center">
  <code>Software Engineer</code> &nbsp;•&nbsp;
  <code>Business Systems</code> &nbsp;•&nbsp;
  <code>Financial Technology</code> &nbsp;•&nbsp;
  <code>Automation</code>
</p>

<img src="./assets/divider.svg" width="100%"/>

## &nbsp; The short version

I build the internal software a retail company actually runs on — financial platforms, business dashboards, warehouse and automation tools that people open every morning to make decisions and move money.

I'm not the kind of engineer who waits for a finished spec. I sit in the results meetings, I talk to the finance, logistics and management teams, I understand *why* a number matters before I model the table that stores it. Then I ship it to production and keep improving it.

<br/>

## &nbsp; What I do

<table>
<tr>
<td width="50%" valign="top">

**Financial Management**
Projected income statements, cash flow, accounts receivable and the indicators leadership reviews.

**Business Intelligence**
Dashboards and KPIs that replace fragile spreadsheets with live, queryable data.

**Automation**
Document extraction, ETL pipelines and routines that remove manual, repetitive work.

</td>
<td width="50%" valign="top">

**Internal Platforms**
Operational systems used daily across departments, behind authentication and role-based access.

**Data Integration**
Bridging legacy ERP data (DBF / TOTVS) into modern PostgreSQL-backed applications.

**Operational Systems**
Warehouse requests, scheduling and internal communication workflows.

</td>
</tr>
</table>

<img src="./assets/divider.svg" width="100%"/>

## &nbsp; Current mission

> **Building software that improves how a company operates.**
>
> Replacing spreadsheets with web applications.
> Turning raw ERP exports into decisions managers can trust.
> Giving leadership real numbers, in real time, instead of week-old reports.

<br/>

## &nbsp; How I work

<p align="center">
  <img src="./assets/workflow.svg" alt="Engineering workflow" width="100%"/>
</p>

<p align="center">
  <sub>
    Business Problem → Requirements → Architecture → AI-assisted Development → Testing → Deployment → Continuous Improvement
  </sub>
</p>

<img src="./assets/divider.svg" width="100%"/>

## &nbsp; Featured platforms

<sub>Built for production use. Repositories are kept **private** because the code belongs to the company.</sub>

<br/>

<table>
<tr>
<td colspan="2" valign="top">

### ▣ &nbsp;Integrated Management Platform &nbsp;<sub>· flagship</sub>

What started as a financial DRE grew into the company's internal operations hub — one platform, many departments, all running on the same live data.

| Module | What it does |
|--------|--------------|
| **Financial** | Projected & realized income statement (DRE) with back-testing, cash-flow calendar, accounts receivable, indicators |
| **HR** | Digital time clock, hour-bank tracking, payroll summary |
| **Purchasing** | Purchase orders, budgeting and their impact on the financials |
| **Logistics** | Monetary inventory control and distribution-center reporting |
| **Data** | Automated ETL importing legacy ERP data (DBF / TOTVS) into PostgreSQL every few minutes |

`Node.js` · `Express` · `PostgreSQL` · `Python ETL` · `Docker` · `Nginx`

<sub>Private · production · used across departments every day</sub>

</td>
</tr>
<tr>
<td width="50%" valign="top">

### ◆ &nbsp;Field Lead Capture Platform

Turns the sales team into a prospecting network out in the field.

- Consultants register construction sites & prospects on location
- Photos (auto-compressed) and GPS geolocation per lead
- Interactive map of every captured opportunity
- Lead distribution and follow-up tracking
- Single sign-on with the main platform (HMAC)

`Python` · `Flask` · `SQLite` · `Pandas`

<sub>Private · production · used daily</sub>

</td>
<td width="50%" valign="top">

### ▦ &nbsp;Warehouse Addressing Platform

Maps and manages every storage position in the warehouse.

- Each pallet position, aisle and slot fully mapped
- Drag-and-drop pallet control
- End-to-end movement management
- Registered-product management
- Same architecture as the main platform — Python + SQLite, no Docker

`Python` · `SQLite` · `Drag & Drop UI`

<sub>Private · production · used daily</sub>

</td>
</tr>
<tr>
<td width="50%" valign="top">

### ◇ &nbsp;Invoice Processing Platform

Removes manual data entry from the finance routine.

- PDF extraction · XML (NF-e) parsing
- Automated reconciliation into the database

`Python` · `Automation` · `PostgreSQL`

<sub>Private · production</sub>

</td>
<td width="50%" valign="top">

### ◷ &nbsp;Warehouse Request Platform

Coordinates the flow between sales and the distribution center.

- Inventory confirmation & structured request workflow
- Status tracking and internal communication

`Node.js` · `PostgreSQL` · `EJS`

<sub>Private · production</sub>

</td>
</tr>
</table>

<img src="./assets/divider.svg" width="100%"/>

## &nbsp; Tech stack

<table>
<tr>
<td align="center" width="16.6%"><img src="./assets/icons/backend.svg" width="92"/></td>
<td align="center" width="16.6%"><img src="./assets/icons/frontend.svg" width="92"/></td>
<td align="center" width="16.6%"><img src="./assets/icons/database.svg" width="92"/></td>
<td align="center" width="16.6%"><img src="./assets/icons/business.svg" width="92"/></td>
<td align="center" width="16.6%"><img src="./assets/icons/infra.svg" width="92"/></td>
<td align="center" width="16.6%"><img src="./assets/icons/ai.svg" width="92"/></td>
</tr>
<tr>
<td align="center"><sub>Python · Flask<br/>Node.js · Express</sub></td>
<td align="center"><sub>JavaScript<br/>HTML · CSS</sub></td>
<td align="center"><sub>PostgreSQL<br/>SQLite · SQL</sub></td>
<td align="center"><sub>Power BI<br/>Power Apps</sub></td>
<td align="center"><sub>Docker · Nginx<br/>Git</sub></td>
<td align="center"><sub>AI-assisted<br/>engineering</sub></td>
</tr>
</table>

<img src="./assets/divider.svg" width="100%"/>

## &nbsp; AI in my engineering workflow

<table>
<tr>
<td width="62%" valign="top">

AI is part of how I build — not a gimmick and not a replacement for engineering.

I use it to move faster through implementation: scaffolding, boilerplate, refactors, edge-case discovery and documentation. It compresses the distance between a decision and working code.

**The decisions stay mine.** Architecture, data modeling, security boundaries, trade-offs and what *correct* means for the business — those come from understanding the problem, not from a prompt. AI accelerates the typing; engineering is still the thinking.

</td>
<td width="38%" valign="top">

<img src="./assets/terminal.svg" alt="terminal" width="100%"/>

</td>
</tr>
</table>

<img src="./assets/divider.svg" width="100%"/>

## &nbsp; GitHub activity

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=JackDaniels2003&show_icons=true&hide_border=true&bg_color=020617&title_color=60A5FA&icon_color=3B82F6&text_color=94A3B8&ring_color=2563EB" alt="stats"/>
  &nbsp;
  <img height="170" src="https://streak-stats.demolab.com?user=JackDaniels2003&hide_border=true&background=020617&stroke=1E3A8A&ring=2563EB&fire=60A5FA&currStreakLabel=60A5FA&sideLabels=94A3B8&dates=475569&currStreakNum=E2E8F0&sideNums=E2E8F0" alt="streak"/>
</p>

<p align="center">
  <img width="49%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=JackDaniels2003&layout=compact&hide_border=true&bg_color=020617&title_color=60A5FA&text_color=94A3B8&langs_count=8" alt="top languages"/>
</p>

<p align="center">
  <img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=JackDaniels2003&bg_color=020617&color=60A5FA&line=2563EB&point=FFFFFF&area=true&area_color=1E3A8A&hide_border=true&custom_title=Contribution%20Graph" alt="activity graph"/>
</p>

<p align="center">
  <img width="100%" src="https://raw.githubusercontent.com/JackDaniels2003/JackDaniels2003/output/github-snake-dark.svg" alt="contribution snake"/>
</p>

<img src="./assets/divider.svg" width="100%"/>

## &nbsp; Contact

<p align="center">
  <a href="mailto:danielteodoro1003@gmail.com">
    <img src="https://img.shields.io/badge/Email-danielteodoro1003@gmail.com-020617?style=for-the-badge&logo=gmail&logoColor=60A5FA&labelColor=0F172A" alt="email"/>
  </a>
  &nbsp;
  <a href="https://wa.me/5524999261431">
    <img src="https://img.shields.io/badge/WhatsApp-(24)%2099926--1431-020617?style=for-the-badge&logo=whatsapp&logoColor=60A5FA&labelColor=0F172A" alt="whatsapp"/>
  </a>
</p>

<p align="center">
  <sub>Brazil · building production software that solves real business problems.</sub>
</p>

<img src="./assets/divider.svg" width="100%"/>
