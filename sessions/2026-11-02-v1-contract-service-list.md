# 2026-11-02 (2): How many services did OrangeBD's v1 contract cover? List of 27

**Question:** When OrangeBD got the work, how many services were agreed?

**Answer:**
- Contract 25-BTF-A-C-3477 never states a service count. Its Scope of Work (Section C §4.2, PDF pp. 26–35) lists the processes wing by wing, and payment was tied to 10 milestone deliverables, not to services. Amendment 1 changed only the deliverables and dates.
- Counting what the Scope of Work lists gives **25**:
  - CM: 8
  - Chemical & Physical: 3
  - MSC: 2
  - Metrology: 7
  - Standards e-commerce: 1
  - Admin: 4 (HRM/Leave, Payroll, Finance & Accounts, Case Management)
- The Admin dashboard and the Customer portal are platform components, not services.
- "17 → 27 services" (26 May 2024 meeting, `kb/scanned/extras.md`) refers to **Business Automation**, not OrangeBD. The wing-wise status page of the BA system (extras p15) actually adds up to 30.

**Output:** `notes/2026-11-02-list-of-27-services-v1-scope.docx` (English, Arial, A4). It lists the 25 contract items plus 2 that the Metrology wing said were missing from OrangeBD's v1 SRS (note para ৪৯, 05 May 2025):
- Verification of weights & measuring instruments
- Import clearance & verification

The user chose this definition of "27". The generator is `list27.js` in that session's scratchpad; it reuses the `docx` node_modules from the 70d4d28b scratchpad. The table also maps each item to its 2026 SRS service number and to live status in v1.

**Flags in the doc:**
- CM Clearance Certificate and Import Clearance & Verification are not among the 33 services in the 2026 SRS, and neither is Standards sale.
- Two Metrology mappings are inferred and need confirming with the wing: Metrology Registration → Service-27/28 (LPG/fuel station) and Import Registration → Service-22/23.
- It is not known which CM licence type "CM new registration" (live) covers.
