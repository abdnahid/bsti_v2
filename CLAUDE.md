# BSTI 2.0 — Digitalization Restructure

Working folder for planning the restructure of BSTI's (Bangladesh Standards and Testing Institution) digital services into one integrated platform ("BSTI 2.0"). This is an analysis/planning workspace, not a code repo (yet).

The user is a BSTI official driving this effort. Goal: BSTI owns the requirements, architecture and contract this time — not the donor, not the vendor.

## Read first

- `notes/`: official drafts (Bangla note sheets and office memos for DG approval). Government notes are written in Bangla, with Bangla numerals and numbered paragraphs (০১, ০২…), ending "সদয় অনুমোদনের জন্য…". Keep the tone neutral towards OrangeBD.
- `sessions/` — dated records of each discussion. Read the latest one before continuing; build on its findings instead of re-deriving them.

## Source documents

**The PDFs and the pptx have been replaced by the knowledge base in `kb/` (01 Nov 2026). Start with `kb/README.md`.** It has an index, the key facts per document and the SRS module/feature table. The PDFs are no longer in the working tree; they were also purged from git history on 01 Nov 2026. The originals are archived outside the repo at `/home/abdnahid/Desktop/bsti_v2_originals_backup/` (see `kb/README.md`). Never commit them back. Read the KB files, not the PDFs.

| Former PDF | KB file |
|---|---|
| `notes on BSTI_v1 history.pdf`: 19-page scanned Bangla note sheet, Apr 2024 – Jul 2025 | `kb/scanned/v1-history-notesheet.md`: transcription of paras ০১–৬৬, with gloss and timeline |
| `extras.pdf`: 61 scanned pages (BTF email, MSC/Standards observations, 2024 meetings, printed RFP, Business Automation contract 2022) | `kb/scanned/extras.md` |
| `BSTI 2.0 Forwarding Letter.pdf` (OrangeBD, 21 Sep 2026) | `kb/fulltext/orangebd-forwarding-letter.md` |
| `BSTI 2.0 - Financial Proposal V4.pdf` (8 pp) | `kb/fulltext/orangebd-financial-proposal-v4.md` |
| `BSTI 2.0 SRS .pdf` (303 pp) | `kb/fulltext/orangebd-srs-bsti-2.0.md` (page by page). Diagrams are in `kb/srs-diagrams.md` (architecture p17, Verification p292, Mobile Court p299) |
| `BSTI 2.0.pptx` (47-slide deck, 14 Sep 2026) | `kb/fulltext/orangebd-deck-bsti-2.0.md` (slide text and tables) and `kb/pptx-visuals.md` (image-only slides 2/3/4/47). Deck slide 4/31 says MSC Re-cert has 136 features, but the correct figure is 113 (total 2,145, not 2,168) |
| BTF–OrangeBD contract, Amendment 1, RFP (Revised) | `kb/fulltext/btf-orangebd-contract-25-BTF-A-C-3477.md`, `btf-orangebd-amendment-1.md`, `btf-rfp-BTF-2024-PROC-0081-revised.md` |

The Word and Excel sources are still in `utils/`. `BSTI 2.0 - Revised Financial Structure.xlsx` is in the root.

| File | What it is | How to read |
|---|---|---|
| `serial.docx` | BSTI service priority list (20 groups + suspension/cancellation + Importer/Exporter*), approved by all focal points at the 19 Oct 2026 meeting | unzip `word/document.xml`, strip tags |
| `meeting memory.docx` | User's notes of the 19 Oct 2026 meeting | unzip `word/document.xml`, strip tags |
| `Govt office project details.xlsx` | **The** reference for other government offices' software projects (see below) | `openpyxl` (`data_only=True`) |

## Other government projects: always use the xlsx

`Govt office project details.xlsx` is the single reference for comparing BSTI 2.0 with other government software projects (price, scope, maintenance, vendor). Use it whenever benchmarking comes up. Don't rebuild these figures from memory or the web without checking it first.

- **Sheets:**
  - `Projects`: office, title, scope, value (crore), maintenance (crore), remarks, vendor
  - `Maintenance benchmarks`: monthly and annual maintenance compared, including the BSTI offer
  - `Sources`: S1–S27 links
- **The user maintains this file.** Their edits override anything found online. Read it fresh each time rather than relying on a summary.
- **Writing to it:** add new findings only when asked. Add them as rows or remarks, and append the source to the `Sources` sheet. Never overwrite the user's figures; note any conflict in the remarks and tell the user.
- **Verification levels:**
  - Verified by an e-GP contract award: D-Nothi and e-Mutation maintenance.
  - Taken from OrangeBD's deck, slide 11 (now `kb/fulltext/orangebd-deck-bsti-2.0.md`), and not independently verified: myGov, RDCD, PID, Jiban Bima.
  - Everything else is user-provided or from news and EOIs.

Tools (Linux machine, checked 01 Nov 2026): `pdftotext`, `pdftoppm`, `pdfimages`, ImageMagick `convert`, LibreOffice `soffice` (pptx/docx → pdf), `tesseract` (English only, no Bangla), Python 3, Node. Not available: `pymupdf`, `openpyxl`, `python-pptx` (parse xlsx/pptx XML directly, or use Node `exceljs`). Put extracted text and renders in the session scratchpad, not this folder.

## Background (short)

- **Legacy systems:** QR certificate/test-report software, BSTI billing (one-stop service only), inventory, standards sale, Alo attendance — all separate.
- **v1:** BTF (funded by **USDA** Food for Progress, not USAID as older notes say; run by Land O'Lakes Venture37) contracted Orange Business Development Ltd (OrangeBD) under contract 25-BTF-A-C-3477, BDT 91,14,000 firm fixed price, effective 12 Jan 2025, originally to end 31 Jul 2026. Amendment 1 (13 Jun 2025) cut the end date to 13 Jun 2025 because BTF was closing. Earlier steps: BSTI's own contract with Business Automation Ltd (13 Mar 2022, ৳15,11,250) stalled at ~40%. BTF emailed on 28 Apr 2024 that automation was not in the MoU and asked for a request letter; BSTI sent it on 05 May 2024. A tripartite meeting followed on 26 May 2024, and the RFP BTF-2024-PROC-0081 was issued on 04 Nov 2024. The scans, contract, amendment and RFP are now transcribed in `kb/`. Under contract clause A.23, the v1 IP vests in **Venture37**, not BSTI. BSTI had no direct contract. Standards e-commerce (`ec.eservice.bsti.gov.bd`), then CM rushed before the outgoing DG retired. Separate logins (`eservice.`, `admin.`, `workflow.eservice.bsti.gov.bd`). Lab test reports uploaded manually into CM; head office only. 5 services live.
- **After BTF closed (user, 6 Oct 2026):** BTF paid OrangeBD the full ~91 lakh before delivery as the project was closing. Under a gentleman's agreement, OrangeBD finishes on its own and deals with BSTI directly; BTF has since closed. OrangeBD wrote the 303-page SRS on BSTI's order. There is no BSTI–OrangeBD contract yet. OrangeBD holds the code and servers.
- **Live now (5):** CM (new registration only), HR, Payroll, PCR, Standards sale. All 23 offices are added but run under the head office organogram. Restructuring and data migration are planned for phase 2.
- **Hosting:** BCC. **Phase 2 funding:** BSTI revenue, with the full PPR applying. Services 22/23 (Importer/Exporter) are to be replaced by the Metrology dealer licence and Standards sale. Neither replacement is described in the SRS.
- **v2 offer (Sep 2026):** 33 "services", BDT 18.69 crore + VAT (11.17 cr rollout Aug 2026–Dec 2029 + 7.52 cr maintenance 2030–31), billed per live service per month.
- **BSTI counter-structure (19 Oct 2026):** `BSTI 2.0 - Revised Financial Structure.xlsx`. Same rollout total, split by deck feature volume in the `serial.docx` priority order into WP1–WP7. Each package is ≤ 2 crore incl. VAT and is paid on milestones. Last go-live is Dec 2029. User rules:
  - CM + PCR + labs + Accounts must be fully running by Dec 2027 (go-live 30 Nov 2027).
  - WP1 = BSTI 2.0 transformation: O&M of the 5 live services plus a total restructuring of them, and nothing else.
  - Packages run one after another, never in parallel.
  - The Summary sheet carries a sub-level price breakdown beside the package table.
- **19 Oct 2026 focal-point meeting:** the SRS has not been validated with the wings and is treated as a draft. OrangeBD's model needs some revisions: a priority-wise cost breakdown, a service-wise schedule, and personnel per service. The focal points approved the priority list (`serial.docx`). The ৳2 cr DG limit and yearly agreements were discussed, but the user removed them from the final minutes. Minutes: `notes/2026-10-19-meeting-minutes-orangebd-proposal-srs.docx` (Bangla, Kalpurush font). After the user revised them, the minutes treat the service model as cost-justified (23.55 cr ground-up vs 18.69 cr) and include the comparison visits to other government offices. The user's latest version is `meeting-minutes-eservice.odt` (root). `meeting-minutes-eservice-background.odt` is the same document plus a background section on how OrangeBD came in and why there is a service agreement (session 2026-11-01).
- **Ministry directive (08 Oct 2026):** the Secretary, Ministry of Industries, directed that BSTI customer services be digitalised by Dec 2027.
- **Tools:** Python may be missing on this machine (only the Windows Store stub). If so, use Node in the scratchpad: `exceljs` to edit xlsx files and `hyperformula` to recalculate them.
- **Number format:** show money with lakh/crore separators (11,16,65,000), not Western 111,665,000.

## Conventions

- Money in BDT; use lakh/crore as the user does (1 crore = 100 lakh = 10,000,000).
- Bangla source text: quote the original and give an English gloss.
- Verify numbers against the source files before quoting them; flag anything inferred.
- When adding a new discussion, create `sessions/YYYY-MM-DD-<topic>.md` and keep this file's background current.
