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

## Open points

- Importer/Exporter (marked * in serial.docx) is included as the last priority. Set Include = N to drop it.
- Metrology dealer licence is not in serial.docx and is not costed.
- Confirm the VAT rate, and whether the cap is measured including VAT.
