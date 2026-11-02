# 2026-11-02 (3): New framing for the minutes, DG note and letter (no "Version 2.0 / new development")

**Input:**
- `notes/meeting-minutes-eservice-background.odt` (user-edited 11:55). The priority annex now lists the 27 services from the v1 contract scope ("Developed Services") mapped to the 33 SRS services.
- The DG note as the user edited it at 09:44.

**The framing the user asked for:**
- Under the BTF agreement OrangeBD **completed the development**, and BSTI went fully live with 5 services.
- While running them, features were added to make the system user-friendly and certification smooth.
- So the other services were not taken fully live at once, for two reasons:
  1. Too many observations to resolve at the same time, plus extensive training for stakeholders and staff.
  2. Extra features after going live would hinder clients at different stages.
- Services therefore go live stage by stage, or service by service.
- Since the BTF–OrangeBD contract expired there is no contractual link with BSTI, but OrangeBD still supports the 5 live services. A maintenance agreement is therefore urgent.
- Maintenance agreements come separately: first for the 5 live services, then for each service or package as it goes live.
- OrangeBD will validate the currently developed modules with each wing and collect the features needed.
- OrangeBD will then give: the full-live timeline, maintenance years and personnel, and a revised financial proposal.
- **Do not mention v1.0/v2.0, restructuring or new development.**

**Outputs.** The generator is `revise.py` with `ed.py` (a paragraph-level editor for odt/docx) in this session's scratchpad. The originals are backed up in `scratchpad/backup/`.
- **`notes/2026-11-02-meeting-minutes-eservice-revised.odt`** (new file; the user's odt is untouched):
  - Background: OrangeBD "কাজ সম্পন্ন করে" under the BTF contract.
  - New paragraph on what was achieved, with reasons (১) and (২), and the urgency of a maintenance agreement.
  - Programmer and DD (Admin-1) remarks reworded around "before going fully live" instead of "before development".
  - Financial phases: phase 1 is now maintenance of the 5 live services, and the "restructuring" wording is gone. The table's phase column reads "পর্যায়ক্রমে লাইভ ও রক্ষণাবেক্ষণ".
  - Comparison (ক) and (খ) say "OrangeBD-এর প্রস্তাবে" instead of "BSTI 2.0".
  - The Version 1.0 paragraph is deleted.
  - All 10 decisions are rewritten:
    - ক: 5-service maintenance agreement first
    - খ: priority list; stage-wise, service- or package-wise
    - গ: SRS draft; validate developed modules and collect features; signed requirements
    - ঘ: sign-off before going fully live
    - ঙ: full-live schedule, Dec 2027 directive
    - চ: maintenance years and personnel, including the helpline
    - ছ: revised financial proposal, service- or package-wise
    - জ: PPR negotiation
    - ঝ: re-tender rationale
    - ঞ: a separate agreement per service or package after it goes live
  - Annex title: "বিএসটিআই'র সেবাসমূহের অগ্রাধিকার তালিকা".
- **`notes/2026-11-02-dg-note-orangebd-letter.docx`** (updated in place from the user's 09:44 version):
  - ০২: "সম্পন্ন করে"
  - ০৩: rewritten to the new framing
  - ০৪: "প্রাথমিক SRS", "লাইভে প্রদান"
  - ০৫: maintenance agreement, with the separate 5-service-first agreement decision
  - ০৬: the letter's five items
- **`notes/2026-11-02-letter-to-orangebd-updated-proposal.docx`** (updated in place):
  - The five requests are now:
    - ক: maintenance proposal for the 5 live services, separately and first
    - খ: full-live schedule
    - গ: maintenance years
    - ঘ: maintenance and helpline personnel
    - ঙ: revised financial proposal, with the agreement structure
  - ০২: validate developed modules and collect features
  - Sign-off before going fully live
  - ০৩: "রক্ষণাবেক্ষণ চুক্তি"
  - The "BSTI 2.0" title is dropped.
- Word (COM) opened all three and exported PDFs: minutes 11 pp, note 2 pp, letter 3 pp.

**Note:** Some Bangla text in the user's odt uses decomposed য় (য + nukta). `ed.py` NFC-normalises text before matching.
