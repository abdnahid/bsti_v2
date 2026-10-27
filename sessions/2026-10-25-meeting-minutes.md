# Session 6: Minutes of the 19 Oct 2026 focal-point meeting

**Date:** 25 October 2026
**Input:** `utils/meeting memory.docx`: the user's notes of the meeting, with drafting instructions in `< >`
**Output:** `notes/2026-10-19-meeting-minutes-orangebd-proposal-srs.docx`, Bangla সভার কার্যবিবরণী, 12 pages. The build script (`minutes.js`, using docx-js) is kept in the session scratchpad.

## What the meeting covered (from the user's notes)

- The user briefed the meeting on OrangeBD's financial proposal and SRS.
- **SRS:**
  - Focal points said OrangeBD did not validate requirements with them.
  - The Physical wing's corrections are not in the SRS.
  - OrangeBD says the SRS is an initial draft and will be revised during development.
- **Financial model:** three stages.
  - Restructure the existing employee and product base.
  - Develop all services by Dec 2029.
  - Maintain until Dec 2031.
- **Not accepted as proposed. The meeting asked for:**
  - a breakdown by service priority;
  - the personnel assigned to each service, since the reference team appears to stay on until 2031;
  - contracts within the DG's ৳2 crore approval limit, so a single ৳18.69 crore contract is not possible. Yearly agreements were proposed.
- **Priority list:** the meeting arranged the `serial.docx` list and all focal points approved it.

## Structure of the minutes

- **Header and meeting details:** chair, date, time, venue.
- **Paragraphs ০১–০৭:**
  - ০১: opening
  - ০২: SRS
  - ০৩: OrangeBD's model, with the year-wise table, schedule and personnel
  - ০৪: the meeting's objections (ক)–(ঘ)
  - ০৫: priority list and how it differs from the 33 services
  - ০৬: contract structure, with yearly agreements and PPR
  - ০৭: decisions
- **Decisions table:** 6 decisions, each with who implements it and by when.
- **Closing:** chair's signature, memo number and distribution list.
- **Annexes:**
  - ক: attendance (demo)
  - খ: approved priority list
  - গ: OrangeBD's quarterly schedule and both reference staff tables (rendered from proposal pp. 6–7)

## Figures used (checked against Financial Proposal V4)

- **Year-wise:**
  - 2026: 16,25,000
  - 2027: 2,05,20,000
  - 2028: 3,99,90,000
  - 2029: 4,95,30,000
  - 2030 and 2031: 3,76,20,000 each
  - Total: 18,69,05,000
- **Reference team:**
  - Rollout: 20 positions, 44 people, ৳15,77,10,000
  - Maintenance: 13 positions, 35 people, ৳7,78,20,000
  - Combined: ৳23,55,30,000. The proposal claims a 20.6% saving against this.

## Placeholders and drafting choices (highlighted yellow in the docx)

- **Placeholders:**
  - Chair, weekday, time, venue, issuing wing
  - Presenter's full name and designation
  - Attendee names and wings: 15 demo rows
  - Decision deadlines and who implements each decision
  - Memo number and date, the directors on the distribution list, and the signature blocks
  - Para ০২(গ) and the end of ০৬ are blanks for any other points raised in the meeting
- **Drafting choices:**
  - The decisions were written up from the discussion, because the notes contain no explicit decisions. The user should confirm them.
  - The WP1–WP7 revised structure (session 5) is not mentioned, because the notes don't say it was discussed in the meeting.
  - Font is Kalpurush, matching the user's edited DG note.

## Revision 1 (26 Oct 2026): user's edits plus two instructions

**What the user changed:**
- **Meeting details:** chaired by the Director (Admin); Monday, 11:30 am.
- **Presenter:** Abdullah Al Nahid, Inspector (Metrology).
- **Para ০২:**
  - Farabi Rahmatullah, AD (Textile), raised the validation gap.
  - The Programmer reported OrangeBD's "draft SRS" assurance.
  - DD Admin-1 asked for a sign-off before each service is built.
- **New fact:** at the 08-10-2026 Ministry of Industries digitalisation meeting, the Secretary directed that BSTI's customer services be digitalised by Dec 2027.
- **Tone:** the minutes now present the service model favourably. Para ০৪ asks for revisions rather than rejecting the model.
- **Decisions:** cut to four. The ≤ 2 crore and yearly-contract decision was dropped, and so were paragraph ০৬ and the chair's signature block.
- **Paragraph labels:** only ০৪ and ০৫ remain.

**Instructions carried out** (top-level XML blocks 22–29 replaced; the rest of the user's file is untouched):
1. **Comparison with other government offices.**
   - **Visit:** the Inspector and the Programmer visited the offices. The table comes from `utils/Govt office project details.xlsx`:
     - BSCIC: OSS per application, Accounts ERP 0.79 cr, Online Market 0.33 cr
     - BCIC: PMIS 5 cr, Fertilizer system 5 cr
     - Land: 5 systems, 46 cr; e-Mutation maintenance 1.37 cr
     - D-Nothi: 7 cr; maintenance 5.42 cr over 24 months
   - **Observations (ক)–(ঘ), concluding that the price is reasonable:**
     - BCIC's PMIS is 5 cr for the head office only.
     - Land spent 8–12 cr per system.
     - OrangeBD's maintenance of ৳31.35 lakh/month sits between D-Nothi (22.58) and e-Mutation (34.25).
     - BSCIC already uses a per-application (service-based) model.
2. **The bracketed staffing block was rewritten as "Version 1.0 থেকে Version 2.0":**
   - Problems caused by the v1 employee and product setup
   - The v2 redesign based on the SRS
   - A ground-up build would cost ≥ 23.553 cr, based on the reference team, and would also need an e-GP tender
   - The service model costs at most 18.69 cr, which is 4.86 cr (20.6%) less

**Placeholders (yellow):**
- The Programmer's name
- The date of the visits
- Examples of v1 setup problems

**Caveats for the user:**
- **The xlsx has no visit log.** It is assumed that the rows match the offices visited. D-Nothi and the e-Mutation maintenance figures come from e-GP awards, not visits.
- **The service model is also procurement under PPR.** Saying "e-GP tender only for ground-up" may draw questions.

The user's pre-edit version is backed up in the session scratchpad.
