# Graph Report - .  (2026-06-04)

## Corpus Check
- 60 files · ~120,820 words
- Verdict: corpus is large enough that graph structure adds value.

## Summary
- 167 nodes · 172 edges · 52 communities (23 shown, 29 thin omitted)
- Extraction: 91% EXTRACTED · 9% INFERRED · 0% AMBIGUOUS · INFERRED: 16 edges (avg confidence: 0.91)
- Token cost: 45,224 input · 12,330 output

## Community Hubs (Navigation)
- [[_COMMUNITY_Brand, AI Brief & Pricing|Brand, AI Brief & Pricing]]
- [[_COMMUNITY_Case Status Pipeline|Case Status Pipeline]]
- [[_COMMUNITY_Frontend Tech Stack|Frontend Tech Stack]]
- [[_COMMUNITY_Client History Dashboard|Client History Dashboard]]
- [[_COMMUNITY_Case Detail Modal|Case Detail Modal]]
- [[_COMMUNITY_Reference Files & AI Context|Reference Files & AI Context]]
- [[_COMMUNITY_AI Case Analysis & Disputes|AI Case Analysis & Disputes]]
- [[_COMMUNITY_Spanish CRM & AI Summary|Spanish CRM & AI Summary]]
- [[_COMMUNITY_Astro Page Components|Astro Page Components]]
- [[_COMMUNITY_Client Intake Link Flow|Client Intake Link Flow]]
- [[_COMMUNITY_EN Client Dashboard|EN Client Dashboard]]
- [[_COMMUNITY_Case Notes Empty State|Case Notes Empty State]]
- [[_COMMUNITY_Note Creation Form|Note Creation Form]]
- [[_COMMUNITY_Hierarchical Notes System|Hierarchical Notes System]]
- [[_COMMUNITY_IDE Settings|IDE Settings]]
- [[_COMMUNITY_Vendor Dispute Case|Vendor Dispute Case]]
- [[_COMMUNITY_Local Dev Config|Local Dev Config]]
- [[_COMMUNITY_ES Intake Link Flow|ES Intake Link Flow]]
- [[_COMMUNITY_Case Notes List|Case Notes List]]
- [[_COMMUNITY_Authentication UI|Authentication UI]]
- [[_COMMUNITY_Notes Detail View|Notes Detail View]]
- [[_COMMUNITY_TypeScript Config|TypeScript Config]]
- [[_COMMUNITY_Case Detail Screenshot|Case Detail Screenshot]]
- [[_COMMUNITY_Status Action Bar|Status Action Bar]]
- [[_COMMUNITY_Case In Review Screenshot|Case In Review Screenshot]]
- [[_COMMUNITY_Client Intake Brief|Client Intake Brief]]
- [[_COMMUNITY_Case UI Screenshot|Case UI Screenshot]]
- [[_COMMUNITY_Case Timeline Screenshot|Case Timeline Screenshot]]
- [[_COMMUNITY_ES Case En Revisión|ES Case En Revisión]]
- [[_COMMUNITY_ES Case Detail (a)|ES Case Detail (a)]]
- [[_COMMUNITY_ES Case Detail (b)|ES Case Detail (b)]]
- [[_COMMUNITY_ES Case Modal|ES Case Modal]]
- [[_COMMUNITY_ERP Dispute Screenshot|ERP Dispute Screenshot]]
- [[_COMMUNITY_ES ERP Case Detail|ES ERP Case Detail]]
- [[_COMMUNITY_Timeline Risk Summary|Timeline Risk Summary]]
- [[_COMMUNITY_Case Editor View|Case Editor View]]
- [[_COMMUNITY_ES Nuevo Cliente|ES Nuevo Cliente]]
- [[_COMMUNITY_ES Client History|ES Client History]]
- [[_COMMUNITY_ES Notes Screen|ES Notes Screen]]
- [[_COMMUNITY_ES Note Creation|ES Note Creation]]
- [[_COMMUNITY_ES Note Form|ES Note Form]]
- [[_COMMUNITY_ES Reference Files|ES Reference Files]]
- [[_COMMUNITY_ES Login Screenshot|ES Login Screenshot]]
- [[_COMMUNITY_ES Note Detail View|ES Note Detail View]]
- [[_COMMUNITY_ES Create Note Form|ES Create Note Form]]
- [[_COMMUNITY_ES Note Creation (b)|ES Note Creation (b)]]
- [[_COMMUNITY_Notes List (Case 6)|Notes List (Case #6)]]
- [[_COMMUNITY_Notes List Two Items|Notes List Two Items]]

## God Nodes (most connected - your core abstractions)
1. `Captio Brand Document` - 18 edges
2. `Nexo Commercial Distributors Corp.` - 11 edges
3. `Captio Landing Page (index.html)` - 11 edges
4. `Client Detail Modal Component` - 7 edges
5. `../../layouts/Layout.astro` - 6 edges
6. `AI Case Brief Generation (Claude/Anthropic)` - 6 edges
7. `scripts` - 5 edges
8. `Client History Page` - 5 edges
9. `Basic Information Block` - 5 edges
10. `Captio App - Reference Files Page (EN)` - 5 edges

## Surprising Connections (you probably didn't know these)
- `Captio Visual Identity and Color Palette` --rationale_for--> `Captio Landing Page (index.html)`  [INFERRED]
  CAPTIO_BRAND.md → index.html
- `Captio Brand Voice and Tone` --rationale_for--> `Captio Landing Page (index.html)`  [INFERRED]
  CAPTIO_BRAND.md → index.html
- `Captio Landing Page (index.html)` --references--> `Captio — Legal Intake & AI Brief Platform`  [EXTRACTED]
  index.html → CAPTIO_BRAND.md
- `Captio Pricing Model (Per Firm)` --implements--> `Annual Pricing Plan ($45/mo, $540/yr)`  [INFERRED]
  CAPTIO_BRAND.md → pricing/index.html
- `Captio Pricing Model (Per Firm)` --implements--> `Monthly Pricing Plan ($60/mo)`  [INFERRED]
  CAPTIO_BRAND.md → pricing/index.html

## Import Cycles
- None detected.

## Hyperedges (group relationships)
- **Legal Case Analysis: Nexo Commercial Distributors Corp. - Vendor Non-Performance** — case_screenshot_from_2026_06_04_14_46_55_client, case_screenshot_from_2026_06_04_14_46_55_case_analysis, case_screenshot_from_2026_06_04_14_46_55_damages [EXTRACTED 0.95]
- **Captio Core Workflow: Intake Link → Form → AI Brief** — intake_link_feature, client_intake_form, ai_brief_generation [EXTRACTED 1.00]
- **Captio WWW Pages Share Tailwind + Inter + Bilingual System** — captio_index, pricing_index, video_index [EXTRACTED 1.00]
- **Captio Case Management: Timeline + Notes + Status Workflow** — case_timeline, case_notes, case_status_workflow [INFERRED 0.85]

## Communities (52 total, 29 thin omitted)

### Community 0 - "Brand, AI Brief & Pricing"
Cohesion: 0.20
Nodes (22): AI Case Brief Generation (Claude/Anthropic), Annual Pricing Plan ($45/mo, $540/yr), Brief Editor with Inline Editing and Highlighting, Captio Brand Document, Captio Visual Identity and Color Palette, Captio Brand Voice and Tone, Captio Landing Page (index.html), Captio Pricing Model (Per Firm) (+14 more)

### Community 1 - "Case Status Pipeline"
Cohesion: 0.18
Nodes (17): Basic Information Block, Case Overview Section, Case Detail Modal - Nexo Commercial Distributors Corp., Case Status: In Review, Case Status Workflow: Invited > New > In Review > Consult Scheduled > Conflict Hold > Engaged > Declined > Closed, Case Type: Business / Contract, Client Answers Section, Client Email: legal@nexocommercial.com (+9 more)

### Community 2 - "Frontend Tech Stack"
Cohesion: 0.14
Nodes (13): dependencies, astro, @astrojs/tailwind, tailwindcss, name, scripts, build, dev (+5 more)

### Community 3 - "Client History Dashboard"
Cohesion: 0.36
Nodes (8): Captio Application, Client History Page, Client Status Summary (2 Total, 0 Engaged, 0 In Review, 1 New), Captio Client History Dashboard Screenshot, Nexo Commercial Distributors Corp. (Case #5), NovaSoft Systems LLC, Toledo Realtors (Case #1), toledolaw (Logged-in User)

### Community 4 - "Case Detail Modal"
Cohesion: 0.36
Nodes (8): Client Detail Modal - Case Management UI (Captio), Demo Client: Nexo Commercial Distributors Corp. (Business/Contract case type), Case Management Feature, Case Status Pipeline (Invited, New, In review, Consult scheduled, Conflict hold, Engaged, Declined, Closed), Case Timeline / Activity Log, Client Answers Section (Basic Information + Case Overview), Client Detail Modal Component, Generate Brief CTA Button (AI-powered brief generation)

### Community 5 - "Reference Files & AI Context"
Cohesion: 0.40
Nodes (6): Active Context Files Section, Captio Application (intake · brief · equipo), Files Navigation Item (Active), Request a Context File Form, Captio App - Reference Files Page (EN), User: toledolaw

### Community 6 - "AI Case Analysis & Disputes"
Cohesion: 0.50
Nodes (5): Nexo Commercial Distributors Corp. - Case Detail AI Analysis View, AI-Generated Case Analysis Document, Nexo Commercial Distributors Corp. (Client Entity), Documented Damages: $400,000 USD, Case Timeline - Nexo Client Created Event

### Community 7 - "Spanish CRM & AI Summary"
Cohesion: 0.50
Nodes (5): Captio CRM (ES) - Case Detail Modal: Distribuidora Nexo Comercial S.A.P.I. de C.V., Demo Client: Distribuidora Nexo Comercial S.A.P.I. de C.V., Feature: AI-powered Case Summary Generation (Generar resumen), Feature: Case Timeline / Activity Log, Case Status Workflow: Invitado → Nuevo → En revisión → Consulta agendada → Revisión de conflicto → Cliente aceptado / Rechazado / Cerrado

### Community 8 - "Astro Page Components"
Cohesion: 0.40
Nodes (4): ../components/Footer.astro, ../components/Nav.astro, ../../layouts/Layout.astro, observer

### Community 9 - "Client Intake Link Flow"
Cohesion: 0.40
Nodes (5): Captio App - New Client Page (EN, logged in as toledolaw), Language Toggle ES/EN (EN active), New Client Feature - Generate Intake Link (EN), Pending Links Section - Toledo Realtors, User: toledolaw (online)

### Community 10 - "EN Client Dashboard"
Cohesion: 0.40
Nodes (5): Captio App - Client History Dashboard (EN, toledolaw user), Client #4 - Distribuidora Nexo Comercial S.A.P.I. de C.V. (New), Client History Feature - Dashboard with Stats and Client Cards, Client #1 - Toledo Realtors (Invited), User: toledolaw

### Community 11 - "Case Notes Empty State"
Cohesion: 0.50
Nodes (4): Case #4 - Distribuidora Nexo Comercial S.A.P.I. de C.V., Case Notes Empty State Pattern, Case Notes Screen - Empty State with Write/Search Actions (EN), User: toledolaw

### Community 12 - "Note Creation Form"
Cohesion: 0.67
Nodes (4): Captio App - Case Notes Creation Form (English UI), Case #4 - Distribuidora Nexo Comercial S.A.P.I. de C.V., New Case Note Creation Form, User: toledolaw

### Community 13 - "Hierarchical Notes System"
Cohesion: 0.50
Nodes (4): Case Notes - Add Note UI (Nexo Commercial Distributors Corp.), Add Case Note Form, Case #6 - Nexo Commercial Distributors Corp. (Business/Contract), Parent Note Hierarchy Feature

### Community 15 - "Vendor Dispute Case"
Cohesion: 0.67
Nodes (3): Case Detail Modal - NovaSoft Defective Software (Engaged Status), NovaSoft Systems LLC (Defendant - Defective Software), Case Status: Engaged

### Community 17 - "ES Intake Link Flow"
Cohesion: 1.00
Nodes (3): Captio App - Nuevo Cliente Screen (Spanish UI, Link Generation Flow), Enlaces Pendientes - Pending Intake Links Tracker, Nuevo Cliente - Client Intake Link Generation Feature

### Community 18 - "Case Notes List"
Cohesion: 0.67
Nodes (3): Case Notes List View - Captio App (EN), Case #4 - Distribuidora Nexo Comercial S.A.P.I. de C.V. (Negocios / contrato), Case #1 - Toledo Realtors

### Community 19 - "Authentication UI"
Cohesion: 0.67
Nodes (3): Captio Login Page (EN) - Sign In UI Screenshot, Captio Authentication Feature, Language Switcher (ES/EN)

### Community 20 - "Notes Detail View"
Cohesion: 0.67
Nodes (3): Case Notes Detail View — Case Review Note for Nexo Commercial Distributors Corp., Note: About the files (child note of Case review), Note: Case review (independent, parent of 'About the files')

## Knowledge Gaps
- **77 isolated node(s):** `lastUpdateCheck`, `allow`, `name`, `type`, `version` (+72 more)
  These have ≤1 connection - possible missing edges or undocumented components.
- **29 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `Case Status Workflow: Invited > New > In Review > Consult Scheduled > Conflict Hold > Engaged > Declined > Closed` connect `Case Status Pipeline` to `Brand, AI Brief & Pricing`?**
  _High betweenness centrality (0.050) - this node is a cross-community bridge._
- **Why does `Tailwind CSS (CDN)` connect `Frontend Tech Stack` to `Brand, AI Brief & Pricing`?**
  _High betweenness centrality (0.044) - this node is a cross-community bridge._
- **Are the 2 inferred relationships involving `Nexo Commercial Distributors Corp.` (e.g. with `Generate Brief Button (AI-assisted action)` and `Timeline Event: Cliente demo generado (6/4/2026, 1:22:08 PM)`) actually correct?**
  _`Nexo Commercial Distributors Corp.` has 2 INFERRED edges - model-reasoned connections that need verification._
- **Are the 2 inferred relationships involving `Captio Landing Page (index.html)` (e.g. with `Captio Visual Identity and Color Palette` and `Captio Brand Voice and Tone`) actually correct?**
  _`Captio Landing Page (index.html)` has 2 INFERRED edges - model-reasoned connections that need verification._
- **What connects `lastUpdateCheck`, `allow`, `name` to the rest of the system?**
  _77 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `Frontend Tech Stack` be split into smaller, more focused modules?**
  _Cohesion score 0.14285714285714285 - nodes in this community are weakly interconnected._