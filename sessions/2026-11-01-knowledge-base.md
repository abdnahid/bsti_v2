# 2026-11-01 (3): Knowledge base built from the PDFs; PDFs removed

**Request:** "generate a knowledge base thoroughly and remove them" (the large PDFs in `utils/`).

**Output:** `kb/` (about 1.1 MB). Start at `kb/README.md`.
- **`fulltext/`:** the 6 text-layer PDFs, page by page with `pdftotext -layout`:
  - SRS
  - Financial Proposal V4
  - Forwarding letter
  - BTF contract
  - Amendment 1
  - RFP (Revised)
- **`scanned/v1-history-notesheet.md`:** all 19 pages read as images; Bangla transcription with English gloss and a timeline.
- **`scanned/extras.md`:** all 61 pages read as images. The printed RFP (pp25–47) was spot-checked against the revised RFP rather than re-typed. p61 was scanned rotated and was read after rotating it.
- **`srs-diagrams.md`:** the image-only SRS content:
  - p17 architecture
  - p292 Verification workflow
  - p299 Mobile Court & Surveillance workflow
- **`README.md`:** index, key facts per document, SRS module and feature counts per service (from the TOC), and how to restore a PDF.

The PDFs were removed with `git rm` and later purged from git history (see the second addendum). CLAUDE.md now points to `kb/`.

**New findings while transcribing (not in earlier sessions):**
- **IP:** BTF contract A.23 vests the IP in all Works in **Venture37**, and the contractor assigns them to Venture37. Nothing assigns them to BSTI. SoW §6 requires only the source code, database and credentials to be *handed over* to BSTI after maintenance.
- **Amendment 1:** deliverables 6–10 were merged into ৳22,78,500 due 13 Jun 2025. The footer says contract "3447". The prime-award line says "for BTF office fitting", which looks copy-pasted.
- **2022 Business Automation contract:** it already required:
  - BSTI copyright over the source code
  - BCC hosting with no extra hosting fee
  - a BCC SQTC certificate
  - an AMC after the first year
  - a bug SLA (critical bugs fixed in 3 working days, non-critical in 2 weeks)
  - handover of the source code and admin passwords
  - integration with NID, NBR, BIDA, City Corporation and DoE

  These are useful precedent clauses for an OrangeBD agreement.
- **Tripartite meeting (26 May 2024):**
  - Business Automation had prototyped 17 services, which grew to 27.
  - ~40% of 700 observations were undefined.
  - BCC would not accept the software without SQTC.
  - There was a confidentiality bug: officers could see and approve each other's files.
  - The DG directed a phase 2 plus an SRS.
- **2025 wing comments on SRS v1:**
  - MSC: suspension, cancellation and surveillance audit missing.
  - Metrology: Verification and Import Clearance & Verification missing.
  - Standards: e-commerce shown under Admin.
  - CM: lists **CM Clearance Certificate**, which is still absent from the 33 services.
- **Date conflicts, recorded as written in the sources:**
  - Progress meeting: the minutes say 07.05.2024, but note para ০৯ says 07.06.2024.
  - MSC/Admin requirement sessions: the memo says 09-06-2024, but the note says 06-06.
  - Printed RFP deadline: 18 Nov on page 4, against 25 Nov elsewhere.
- **SRS architecture (p17):**
  - Shows LIMS, Inventory and "Import Clearance", which are not among the 33 services.
  - Has no Importer/Exporter or Mobile Court tile.
  - The only external integrations are NID, payment, SMS and email (no BSW, NBR, BIDA).

## Addendum: pptx converted and removed

- **`kb/fulltext/orangebd-deck-bsti-2.0.md`:** text from all 47 slides, extracted from the slide XML in presentation order (`scripts/pptx2md.py` in the scratchpad). Tables are kept as markdown. As a check, the text-character count is about 41.7k against 43.0k in the XML; the gap is the markdown punctuation that was stripped for the comparison.
- **`kb/pptx-visuals.md`:** the slides were rendered through LibreOffice so that the picture-only content could be read:
  - slide 2, the vision slide, with its Aug–Dec 2026 **conditions**: "no new development … only issue resolve for live services" and "Beta version under new architecture 01 Aug–31 Dec 26";
  - slide 3, the planned features;
  - the service names on slide 4;
  - slide 47.
- **New finding, the MSC Re-certification count:** the slide 4 and slide 31 headlines say **136** features, but the module catalogue on slide 31 and the SRS both add up to **113**. The deck total should be 2,145, not 2,168. The revised financial structure (Work Volume row 40) uses 136, which overweights WP5 by about 11.5 units (~৳7 lakh). The workbook has not been changed; this needs the user's decision.
- **`utils/BSTI 2.0.pptx`** was removed with `git rm`. See the second addendum for where the original is now.
- **CLAUDE.md:** the tools line was updated, since this machine is Linux with pdftoppm, soffice and tesseract (English only).

## Addendum 2: originals purged from git history

At the user's request ("remove from git history too and commit"):
- **Coverage re-checked against the originals first:**
  - SRS 303/303 pp, Financial Proposal 8/8, contract 45/45, RFP 23/23, Amendment 4/4, letter 1/1
  - deck 47/47 slides
  - note sheet 19/19 pp
  - extras 61/61 pp
- **Backup:** before the rewrite, all 9 originals and a full git bundle (`bsti_v2-full-history-before-purge.bundle`) were copied to `/home/abdnahid/Desktop/bsti_v2_originals_backup/`, outside the repo.
- **Purge:** the KB removal was committed, then `git filter-repo --invert-paths` removed every `*.pdf` and `*.pptx` from all commits. Some had first been committed at the repo root before moving to `utils/`. All commit hashes changed, so `dae7334` no longer exists in the repo; it is only in the bundle.
- **GitHub:** `origin` (github.com:abdnahid/bsti_v2) still has the old history until a force-push. See the end of the session for whether that was done.
- **Still open:** the MSC Re-cert 136-vs-113 decision on the workbook (see the addendum above).

