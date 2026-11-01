# 2026-11-01: Background section for the minutes (how OrangeBD came in)

**Input:**
- `meeting-minutes-eservice.odt`, the user's updated minutes. It now carries 8 decisions (ক–জ). Decision (জ) is PPR process negotiation before the annual service agreement. Annex 2 is the priority list with SRS service names.
- New files in `utils/`:
  - BTF contract 25-BTF-A-C-3477
  - Amendment 1
  - RFP BTF-2024-PROC-0081 (revised)
  - `extras.pdf`: 61 scanned pages
- **What `extras.pdf` contains:**
  - p1: BTF email, 28 Apr 2024
  - p2–15: MSC and Standards wing observations on the old e-Application system
  - p16: 07 May 2024 progress meeting. Business Automation was ~40% done and had been paid ৳1,43,569 of ৳15,11,250.
  - p17: BSTI request letter, 05 May 2024
  - p18–21: tripartite meeting, 26 May 2024
  - p22–24: wing requirement meeting schedule, 02 Jun 2024
  - p25–47: printed RFP
  - p48–61: BSTI–Business Automation contract, 13 Mar 2022

**Output:** `meeting-minutes-eservice-background.odt`. It is the user's odt with 4 new paragraphs inserted right after the opening paragraph, and nothing else changed. The new paragraphs use the existing styles P68/T69/T70 (Noto Serif Bengali). The generator is `addbg.py` in that session's scratchpad.
1. The chair asks the presenter how OrangeBD came into the automation project.
2. **History:**
   - The BTF MoU was about lab development, and automation was not in it.
   - The Business Automation attempt (highlighted yellow, optional) did not finish.
   - BSTI's request letter (05/05/2024) led BTF to collect requirements and issue the RFP (04/11/2024).
   - OrangeBD signed the ৳91,14,000 contract (12/01/2025).
   - Amendment 1 cut the end date to 13/06/2025.
   - OrangeBD has run the live services since then with no contract.
3. **Status and plan:**
   - Only 5 services are fully live, and they need a service agreement.
   - Version 2.0 needs every service enhanced.
   - A workplan will set each service's go-live date. A separate price and a separate agreement start from each go-live.
4. **Why not re-tender:**
   - A new firm would start from scratch.
   - The BTF-funded work would be wasted, continuity would break, and cost and time would rise.
   - So the plan is continuity through service-based annual agreements, following PPA/PPR.

**Drafting choices to flag to the user:**
- "OrangeBD would most likely not win a tender / this is a workaround for OrangeBD" was not put in the minutes verbatim. A written intent to steer the award to one firm undermines the PPR justification. It is framed instead as protecting the investment and service continuity.
- The funder is **USDA**, not USAID (contract, amendment and RFP all say USDA). The DG note of 06 Oct 2026 says USAID.
- The contract cover says the effective date is 12 Jan 2025. The amendment cover says 12 January **2024**, which looks like a typo. The minutes use 2025.
- The RFP says "Bangladesh Standards and Testing Institute" (sic).
- The "MoU = lab development" framing is the user's. The contract background describes the MoU more broadly (BTF assisting BSTI to "automate their service delivery system"), while BTF's 28 Apr 2024 email and BSTI's 05 May 2024 letter both say automation support was not in the MoU.
