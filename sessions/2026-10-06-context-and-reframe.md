# Session 2: User's answers and a revised view of OrangeBD's offer

**Date:** 6 October 2026
**Builds on:** `2026-10-05-initial-analysis.md`

## User's answers to the open questions

1. **Live services (5):**
   - CM (new registration only)
   - HR
   - Standards sale
   - Payroll
   - PCR
2. **Source code and servers:** held by OrangeBD.
3. **Offices:** 23 in total, including head office. All of them are already added, but they run under the head office organogram. Restructuring now would disrupt the live services, so the plan is a phase 2 build with the current data migrated into it later.
4. **Budget and history (user's account):**
   - v1 was USAID money through BTF. BTF paid OrangeBD the full ~৳91 lakh before the work was finished, because USAID was closing and the money would otherwise have gone back to the US.
   - BTF and OrangeBD made a gentleman's agreement: OrangeBD would finish on its own and deal with BSTI directly from then on. BTF then closed.
   - Working directly with BSTI, OrangeBD found the real scope was far larger. On the BSTI administration's order, it collected requirements from every wing and wrote the 303-page SRS so that v1's failure wouldn't repeat.
   - OrangeBD is still supporting BSTI in good faith with limited staff. It can't staff the full scope without being paid, hence the service-based proposal.
   - The 13 Jun 2025 contract amendment in the forwarding letter may be related; not yet confirmed.

## What this changes in session 1's analysis

- **OrangeBD is acting in good faith, not opportunistically.** v1 was underpriced and the vendor absorbed the loss. Treat the negotiation as a fair deal with a partner, not as a contest.
- **The SRS's role:** it was written at BSTI's direction to capture scope, and it does that well. It is still not a spec you can build or accept work against (no non-functional requirements, forms, fee rules or acceptance criteria). The "written after development started" criticism is softened.
- **Aug–Dec 2026 at ৳65k per service per month** is effectively O&M for the 5 live services since BTF ended. That is reasonable, so the "billing for already-built services" finding is withdrawn for this period.
- **From 2027, live services are billed at development rates.** The 5 live services move to ৳180k, then ৳155k, then ৳130k per month, against a maintenance rate of ৳95k. The extra over the maintenance rate:
  - 2027: (180−95) × 5 × 12 = ৳51 lakh
  - 2028–29: (60+35) × 5 × 12 = ৳57 lakh
  - Total ≈ ৳1.08 crore for these 5 services alone.
  - This works as progress-linked financing of the development team, so judge it on the total rather than per service.
- **Unchanged:**
  - Total price compared with OrangeBD's own benchmarks (myGov ৳12 cr, RDCD ৳11.44 cr)
  - Billing per variant (33 services vs ~21 families)
  - Missing contract terms
  - PPR compliance
  - CM–lab and regional-office gaps in the SRS
- **New, top risk: BSTI has no contract with OrangeBD at all.** OrangeBD holds the code and servers, and live HR and Payroll (salaries) run on them without an SLA, without defined data custody and without an exit plan. Fix this first, separately from the ৳18.69 cr decision.
- **Standards sale** is live but isn't among the 33 SRS services. It is unclear whether it is counted in the "5 live" billing and where it sits in maintenance.

## Proposed approach (for discussion)

Split the offer into three parts:

1. **Interim O&M contract, starting now:**
   - Covers the 5 live services at a fair monthly fee.
   - Requires source code and database deposits, hosting and credential disclosure, a basic SLA and data ownership by BSTI.
   - It is small and quick to sign.
2. **v1 residual:** whatever the BTF contract (as amended) covered and paid for. Use it as goodwill credit in the negotiation, not as a hard demand, since the vendor is already out of pocket. This needs the contract documents.
3. **Phase 2 build:**
   - Platform plus workflow families, paid on milestones and acceptance.
   - Office (HQ / divisional / regional) is a data dimension from day one.
   - Migration of current data is explicitly in scope. OrangeBD should document the current data model now.

**Phase 2 funding:** USAID money is gone, so a source is needed before procurement (BSTI revenue budget or an ADP/TAPP project). The procurement method for a direct award to the incumbent needs a PPR justification and approval at the right level.

## Open questions

- Does BSTI have:
  - the BTF–OrangeBD contract
  - the 13 Jun 2025 amendment
  - the v1 deliverables list
  - anything in writing about the gentleman's agreement (letter, email, minutes)?
- Where are the systems hosted (OrangeBD cloud, BCC or the National Data Center), and who pays for hosting now?
- Is standards sale counted in the 5 billed live services?
- What is the funding source for phase 2?

## Round 2: user's answers

1. **Contract:** nothing after the 13 Jun 2025 amendment. The gentleman's agreement is not written down, so the v1 residual has no legal footing and can only be goodwill. Since Aug 2026 OrangeBD has been running the live services with no contract at all. The Aug–Dec 2026 lump sum (৳16.25 lakh) would be partly a payment for past work and needs a basis for approval.
2. **Hosting:** BCC. The infrastructure is in government hands. Confirm whose name the BCC allocation is in (BSTI, BTF or OrangeBD), get BSTI admin access and backups, and check whether BCC bills hosting to BSTI. Hosting isn't in OrangeBD's price.
3. **Service swaps:**
   - Service 22 (Registered Importer/Exporter Certificate) becomes the **Metrology dealer licence**.
   - Service 23 (Importer/Exporter Renewal) becomes **Standards sale**.
   - The count stays at 33, but **neither replacement appears in the SRS or the deck**. A grep for "dealer" returns nothing, and Standards sale is absent. The documented scope of slides 35–36 (12 modules and 53/55 features each) no longer applies, so two of the 33 billed services have no written scope.
   - Standards sale is already live (built in v1 with BTF money). As service 23 it needs a defined new deliverable: move it into the unified portal and SSO, link standards purchase to the CM application, and use the shared payment engine. Otherwise BSTI pays rollout rates for something that already exists.
   - The Metrology dealer licence is probably in the same family as Metrology Licence Issue/Renewal (24/25), so it is likely mostly configuration. To be confirmed.
4. **Phase 2 funding:** BSTI revenue. The full PPR applies, with no donor cover. A multi-year commitment needs an annual budget allocation and a clause making each year's payment subject to that allocation. Yearly cash flow as proposed:

   | Year | Amount (excl. VAT) |
   |---|---|
   | 2026 | ৳0.16 cr |
   | 2027 | ৳2.05 cr |
   | 2028 | ৳4.00 cr |
   | 2029 | ৳4.95 cr |
   | 2030 | ৳3.76 cr |
   | 2031 | ৳3.76 cr |

   Consider a direct award for the interim O&M (continuity is a strong justification) and a separate procurement decision for phase 2. Confirm the method with BSTI's procurement and legal cell.

**Next:** draft the interim O&M term sheet.
