# Session 5: Revised financial structure (work-volume based, ≤ 2 crore per approval)

**Date:** 19 October 2026
**Inputs:** `serial.docx` (BSTI priority list, 20 groups + footnote items), Financial Proposal V4, `BSTI 2.0.pptx` feature counts
**Output:** `BSTI 2.0 - Revised Financial Structure.xlsx` (formula-driven; build script kept in the session scratchpad)

## Brief from the user

- Keep the rollout cost the same (৳11,16,65,000).
- Split it by volume of work, following the priority in `serial.docx`.
- BSTI can approve at most ৳2 crore at a time.
- Set a time limit for the development schedule.

## Method

- **Volume:** feature count for each service, from deck slides 14–46. Where serial.docx splits a deck service into sub-types (Verification ×4, Tank ×2, Storage Tank ×5, Surveillance ×2), the features are split equally.
- **Weight:** New = 1.0; Variant (renewal, brand, scope inclusion) = 0.5; Live in v1 (HRM, Payroll, BDS sale, CM new, PCR new) = 0.5. All factors are editable inputs.
- **BSTI estimates (no SRS scope):** common platform 60, BDS sale 40, suspension/cancellation 30, MSC scope inclusion 50, BSW API 30 features.
- **WP0:** the Aug–Dec 2026 O&M (৳16.25 lakh) is a separate package. The other ৳11.004 cr is allocated by work units (1,809 units ≈ ৳60,829 per unit).
- **Payment milestones:** 20% design sign-off / 30% UAT / 40% go-live / 10% after 3-month stabilisation.

## Result (excl. VAT; cap tested incl. 15% VAT)

| Package | Priorities | Value (lakh) | Start | Go-live deadline |
|---|---|---|---|---|
| WP0 Interim O&M | live 5 | 16.25 | Aug 2026 | Dec 2026 |
| WP1 Platform, HRM, Payroll, BDS, Accounts | 1–2 | 123.79 | Jan 2027 | Jun 2027 |
| WP2 CM licence + suspension/cancellation | 3 | 161.20 | Apr 2027 | Dec 2027 |
| WP3 Labs + PCR | 4–7 | 170.63 | Oct 2027 | Jun 2028 |
| WP4 Mobile court … Storage tank | 8–13 | 173.36 | Apr 2028 | Dec 2028 |
| WP5 MSC | 14 | 162.41 | Oct 2028 | Jun 2029 |
| WP6 Halal, LPG, Case mgmt | 15–17 | 173.67 | Jan 2029 | Sep 2029 |
| WP7 NML, Building, BSW API, Importer/Exporter | 18–21 | 135.34 | Apr 2029 | Dec 2029 |

- **Largest approval:** ৳1.997 cr including VAT (WP6).
- **Maintenance:** unchanged at ৳7.524 cr, in 8 quarterly tranches of ৳94.05 lakh.
- **Cash flow vs the proposal:** 2027 is about ৳98 lakh higher (payment is delivery-based), 2028–29 lower. ৳13.5 lakh of WP7 retention falls in Mar 2030.

## Revision 1 (same day): user instructions

- **Number format:** money now shows lakh/crore grouping (11,16,65,000). The year-wise difference column is now in lakh, because Excel's conditional formats can't group negative crore values.
- **Lab testing can't be delayed.** CM + PCR + labs + Accounts must be fully running within December 2027. The schedule changes to:
  - WP1 (incl. Accounts): Jan–Jun 2027, unchanged
  - WP3 (labs + PCR): starts Feb 2027, 10 months, go-live 30 Nov 2027
  - WP2 (CM): starts Mar 2027, 9 months, go-live 30 Nov 2027
  - WP1–WP3 run in parallel Mar–Jun 2027
  - WP4–WP7 unchanged
- **Approvals:** needed by 30 Nov 2026 (WP1), 31 Dec 2026 (WP3) and 31 Jan 2027 (WP2), one per month and each under 2 crore.
- **Cash flow effect:** 2027 is now ৳4.22 cr against the proposal's ৳2.05 cr (+৳2.17 cr); 2028 is ৳1.78 cr lower. The revenue budget for 2027 has to provide for this.
- A new Summary check (Inputs B15) flags if WP1–WP3 go-live slips past 31 Dec 2027.

## Revision 2 (same day): phase 1 = maintenance + restructuring, no overlap

**User instructions:**
- Maintenance of the 5 live services goes inside the BSTI 2.0 transformation package.
- That phase is a total restructuring; new development comes after it.
- Package timelines must not overlap.
- Keep the existing package table, and add a sub-level price breakdown beside it.

**User decisions (asked):**
- Keep the Dec 2027 deadline and compress the schedule.
- Move CM new and PCR new into phase 1.

**Changes:**
- **WP0 is gone.** The ৳16.25 lakh Aug–Dec 2026 O&M is now a lump-sum line inside WP1, paid on signing (31 Dec 2026). WP1's milestones apply to its development part only.
- **The cap forced a reshuffle.** Accounts moves to WP2 with labs, and PCR renewal and brand inclusion stay in WP1 with PCR new. Accounts in WP2 together with PCR variants would have been ৳2.19 cr incl. VAT. PCR variants in WP3 alongside CM would have been ৳2.02 cr.
- **Schedule.** Packages run one at a time; only stabilisation/warranty runs alongside the next package. Gantt row 12 must stay ≤ 1, and Summary has a new check (C46).

| Package | Scope | Value (lakh) | Incl. VAT (cr) | Start | Go-live | Approval by |
|---|---|---|---|---|---|---|
| WP1 | O&M of 5 live + platform + HRM, Payroll, BDS, CM new, PCR (new/renewal/brand) | 162.24 | 1.866 | Jan 2027 | 30 Apr 2027 | 30 Nov 2026 |
| WP2 | Accounts + Chemical, Physical, Energy Meter labs | 162.41 | 1.868 | May 2027 | 31 Aug 2027 | 31 Mar 2027 |
| WP3 | CM variants + scope + suspension/cancellation | 147.21 | 1.693 | Sep 2027 | 30 Nov 2027 | 31 Jul 2027 |
| WP4 | Mobile court … storage tank | 173.36 | 1.994 | Jan 2028 | 30 Jun 2028 | 30 Nov 2027 |
| WP5 | MSC | 162.41 | 1.868 | Jul 2028 | 31 Dec 2028 | 31 May 2028 |
| WP6 | Halal, LPG, Case mgmt | 173.67 | 1.997 | Jan 2029 | 30 Jun 2029 | 30 Nov 2028 |
| WP7 | NML, Building, BSW API, Importer/Exporter | 135.35 | 1.557 | Jul 2029 | 31 Dec 2029 | 31 May 2029 |

- **Timing.** WP1–WP3 get 1-month design, build and UAT windows (4 + 4 + 3 months). CM goes live in its UAT month. This is a delivery risk (Notes item 19), and OrangeBD has to confirm resourcing.
- **Cash flow (excl. VAT).** 2027 is ৳4.41 cr against the proposal's ৳2.05 cr (+235.7 lakh). 2028 is ৳3.34 cr (−65.7 lakh), and 2029 is ৳3.12 cr (−183.6 lakh). WP7 retention of ৳13.5 lakh falls in Mar 2030.
- **New table** on Summary J11:R70: a price breakdown by sub-level (48 Work Volume rows + the O&M line). Each line is its work share rounded to ৳1,000, the last line in each block balances to the package value, and each package has a subtotal. A block check shows MOVED if a row is reassigned on Work Volume. Summary check C47.
- **How it was built:** Python wasn't available this session, so Node + exceljs was used to edit the workbook and HyperFormula to recalculate it. All 11 Summary checks are OK, and cached values are written into the file.

## Open points

- Importer/Exporter (marked * in serial.docx) is included as the last priority. Set Include = N to drop it.
- Metrology dealer licence is not in serial.docx and is not costed.
- Confirm the VAT rate, and whether the cap is measured including VAT.
