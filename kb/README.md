# BSTI 2.0 knowledge base (built from the PDFs and the pptx in `utils/`)

Built on 01 Nov 2026 so that the large PDFs could be taken out of the working folder. The originals were purged from git history and are archived outside the repo; see "Recovering an original" at the end. **Use the KB instead of re-reading the PDFs.**

## What is where

| Source PDF (removed) | KB file | Method | Fidelity |
|---|---|---|---|
| `BSTI 2.0 SRS .pdf` (303 pp, 14 MB) | `fulltext/orangebd-srs-bsti-2.0.md` | `pdftotext -layout`, page by page | Full text, lossless apart from the images. The image-only content is described in `srs-diagrams.md`. |
| | `srs-diagrams.md` | Pages viewed as images | Architecture (p17) and the Verification (p292) and Mobile Court (p299) workflows described in full. The per-service module diagrams repeat the text. |
| `BSTI 2.0 - Financial Proposal V4.pdf` (8 pp) | `fulltext/orangebd-financial-proposal-v4.md` | pdftotext | Full text. The only images are the logo header. |
| `BSTI 2.0 Forwarding Letter.pdf` (1 p) | `fulltext/orangebd-forwarding-letter.md` | pdftotext | Full text, without the signature or letterhead. |
| `BTF Firm Fixed Price Contract_… (2).pdf` (45 pp) | `fulltext/btf-orangebd-contract-25-BTF-A-C-3477.md` | pdftotext | Full text. p2 (signature blocks) has little text, and the signatures are images. |
| `Orange BD BSTI Automation_Amendment 1.docx.pdf` (4 pp) | `fulltext/btf-orangebd-amendment-1.md` | pdftotext | Full text. The DocuSign signatures are images, dated 6/18/2025 in the text. |
| `Request For Proposals_BSTI (Revised).pdf` (23 pp) | `fulltext/btf-rfp-BTF-2024-PROC-0081-revised.md` | pdftotext | Full text. The images are only the Venture37 header. |
| `BSTI 2.0.pptx` (47 slides, 13 MB) | `fulltext/orangebd-deck-bsti-2.0.md` | Slide XML text, in presentation order; tables kept as tables | Full text |
| | `pptx-visuals.md` | Slides rendered through LibreOffice and viewed | Image-only slides 2, 3 and 47, the service names on slide 4, and the slide 7 chart. Also flags the MSC Re-cert 136-vs-113 error. |
| `notes on BSTI_v1 history.pdf` (19 pp scan, 14 MB) | `scanned/v1-history-notesheet.md` | Read page by page as images | Full Bangla transcription, paras ০১–৬৬, with an English gloss and a timeline. Handwriting is marked `[?]` where uncertain. |
| `extras.pdf` (61 pp scan, 60 MB) | `scanned/extras.md` | Read page by page as images | Bangla and English transcription of every page. The printed RFP (pp25–47) is cross-referenced to the revised RFP text rather than re-typed. |

**Not converted (small Word/Excel files that are still in `utils/`):**
- `serial.docx`
- `meeting memory.docx`
- `Govt office project details.xlsx`

The xlsx remains **the** benchmarking reference (see CLAUDE.md).

**Page numbers.** In `fulltext/*.md`, "## Page N" is the **PDF page**. The SRS's printed page numbers are one lower, so PDF p17 is printed p16. Citations in earlier sessions use the PDF page.

---

## Key facts by document (verified against the extracted text)

### OrangeBD forwarding letter (21 Sep 2026)
- **Addressee:** "The Project Director, BSTI". Subject: "Submission of Manage Service Proposal for BSTI e-Application Management System". Signed by Hafez Ahmed, Director & COO, OrangeBD.
- **History as OrangeBD tells it:**
  - The project started under BTF on 12 Jan 2025, with an anticipated completion of 31 Jul 2026. It was amended on 13 Jun 2025.
  - Since then OrangeBD has continued enhancement, maintenance and support, and 5 services were launched.
  - Existing services and needs were reviewed "from 1 August 2026".

### OrangeBD Financial Proposal V4 (Sep 2026)
- **Totals:**
  - Total ৳18,69,05,000 + VAT, made up of rollout ৳11,16,65,000 (Aug 2026–Dec 2029) and maintenance ৳7,52,40,000 (2030–31).
  - Staff-cost "reference" ৳23,55,30,000: rollout ৳15,77,10,000 and maintenance ৳7,78,20,000. This gives the claimed saving of ৳4,86,25,000 (20.6%).
- **Per-service monthly rate:**

  | Period | Rate | Treatment |
  |---|---|---|
  | Rest of 2026 | ৳65,000 | lump sum |
  | 2027 | ৳1,80,000 | standard |
  | 2028 | ৳1,55,000 | −13.9% |
  | 2029 | ৳1,30,000 | −27.8% |
  | 2030–31 | ৳95,000 | −47.2% |

  Payment is quarterly, "based on further discussion".
- **Live-service count by quarter:** 5 (Aug–Dec 2026, ৳16,25,000), then 5, 8, 11, 14 in 2027, 17, 20, 23, 26 in 2028, and 29, 32, 33, 33 in 2029.
- **Maintenance:** ৳31,35,000 a month (33 × ৳95,000), so ৳3,76,20,000 a year.
- **Reference teams:**
  - Rollout: 20 positions, 44 people.
  - Maintenance: 13 positions, 35 people.

### BTF–OrangeBD contract 25-BTF-A-C-3477
- **Parties and terms:**
  - Land O'Lakes Venture37 (for USDA BTF, Cooperative Agreement FCC-388-2020/003-00) and Orange Business Development Ltd.
  - Firm fixed price ৳91,14,000, inclusive of VAT and AIT.
  - Effective 12 Jan 2025, originally to complete on 31 Jul 2026.
  - Signatories: Hafez Ahmed, Michael J Parr and Mary Jo Robinson.
- **Payment table:**

  | # | Deliverable | Due | Amount (৳) |
  |---|---|---|---|
  | 1 | SDLC work plan | 31 Jan 2025 | 13,67,100 |
  | 2 | SRA | 15 Feb 2025 | 13,67,100 |
  | 3 | Operational system | 15 Apr 2025 | 27,34,200 |
  | 4 | Manual and training | 15 May 2025 | 4,55,700 |
  | 5–6 | UAT and go-live | 15 Jun 2025 | 9,11,400 |
  | 7 | Documentation and source | 15 Jul 2025 | 9,11,400 |
  | 8 | QA/SQTC (SQTC cost not borne by the contractor) | 15 Sep 2025 | 4,55,700 |
  | 9–10 | 1-yr support and final source code | 31 Jul 2026 | 9,11,400 |
- **IP (A.23):** **Venture37** retains title to all works created under the contract, and the contractor assigns them to Venture37, not to BSTI. Pre-existing contractor IP is licensed to Venture37.
- **Handover:**
  - SoW §6: at the end of maintenance, hand over the source code, manual, database backup and **all credentials to BSTI**, supervised by a BTF IT specialist.
  - Hosting is "provided by BSTI", on a BCC server or cloud.

> **Gap for BSTI:** BSTI's title to the v1 code depends on Venture37 passing the Works on, and BTF has closed. Neither document assigns IP to BSTI directly.

### Amendment 1 (13 Jun 2025; DocuSigned 18 Jun 2025)
- Completion date moved from 31 Jul 2026 to **13 Jun 2025** because BTF closed.
- Deliverables 6–10 combined into one payment of **৳22,78,500 due 13 Jun 2025**.
- Deliverable 9 amended because SQTC could not confirm testing times.
- Deliverable 5 is ৳9,11,400, due 15 May 2025. The total is unchanged at ৳91,14,000.
- **Errors in the document:**
  - The cover says the effective date is "12 January **2024**", although the contract says 2025.
  - The page footer says "25-BTF-A-C-**3447**".
  - The amendment's prime-award text says "for BTF office fitting", which looks copy-pasted from another contract.

### RFP BTF-2024-PROC-0081 (Revised)
- **Timeline:** issued 04 Nov 2024; pre-bid meeting 11 Nov 2024; offers due 25 Nov 2024 (the printed copy in extras p28 shows 18 Nov).
- **Contract:** one fixed-price contract with no advance payment. Performance period Dec 2024 to Jun 2026, with 6 months of development and a 12-month warranty.
- **Bidders:** must be BASIS members.
- **Scoring:**
  - Technical: capability 30%, approach 40%, team 30%.
  - Price: the top 5 are shortlisted, and 20 points go in proportion to the lowest price.
- **Scope (§4.2):** admin dashboard, customer portal, and the processes for:
  - CM (Scope/Mandatory issue and renewal, CM Clearance Certificate, brand inclusion, Halal issue and renewal)
  - Chemical, Physical and Energy Meter labs
  - Metrology registration and renewal, tank lorry, I&S calibration, …
  - MSC
  - HR, budget and e-commerce
- **Security (§5.2):** application, UI, data and login security, with ≥ 2-factor login and a 30-minute idle logout.

### Deck (`BSTI 2.0.pptx`, dated 14 Sep 2026)
- **Slide 2 (image):** the Aug–Dec 2026 period carries the conditions "No new development for neither existing nor new services" and "Only issue resolve for live services", plus "Beta Version under New Architecture 01 Aug 26 – 31 Dec 26".
- **Slide 4:** 33 services, 440 modules, "2,168" features. The correct total is **2,145**, because MSC Re-cert is 113, not 136. The revised financial structure used 136; see `pptx-visuals.md`.
- **Slide 11:** the managed-service benchmark (myGov, RDCD, e-Mutation, PID, Jiban Bima). Slides 14–46: one profile per service.

### SRS (OrangeBD, BSTI 2.0, 303 pp)
- **Structure:**
  - Executive summary (p15) and challenges & business case (p16)
  - Architecture (p17)
  - Then 33 services, each with a profile page, a diagram page, a narrative, and then module and feature descriptions
- **Modules and features per service,** summed from the SRS table of contents. They match the deck slides 14–46 except Service 18: the deck headline says 136, but its own table and the SRS give 113.

| # | Service | Modules | Features |
|---|---|---|---|
| 1 | HRM & Leave Management | 11 | 49 |
| 2 | Payroll Management | 15 | 84 |
| 3 | Finance & Accounts Management | 10 | 57 |
| 4 | Case Management System | 8 | 34 |
| 5 | CM Mandatory New Certification | 12 | 46 |
| 6 | CM Mandatory Renewal | 12 | 46 |
| 7 | CM Mandatory Brand Inclusion | 12 | 46 |
| 8 | CM Scope New Certification | 16 | 83 |
| 9 | CM Scope Renewal | 16 | 83 |
| 10 | CM Scope Brand Inclusion | 16 | 83 |
| 11 | CM Halal Certification | 16 | 86 |
| 12 | CM Halal Renewal | 16 | 86 |
| 13 | CM Halal Brand Inclusion | 16 | 86 |
| 14 | Chemical Testing | 20 | 67 |
| 15 | Physical Testing | 10 | 72 |
| 16 | Physical Lab – Energy Meter | 12 | 71 |
| 17 | MSC Certification | 24 | 174 |
| 18 | MSC Re-certification | 14 | 113 |
| 19 | PCR Registration New | 13 | 48 |
| 20 | PCR Registration Renewal | 13 | 48 |
| 21 | PCR Brand Inclusion | 13 | 45 |
| 22 | Registered Importer/Exporter Certificate | 12 | 53 |
| 23 | Registered Importer/Exporter Renewal | 12 | 55 |
| 24 | Metrology License Issue | 13 | 54 |
| 25 | Metrology License Renewal | 13 | 54 |
| 26 | Tank Lorry Calibration | 12 | 49 |
| 27 | LPG Bottling/Filling/Fuel Station Registration | 12 | 53 |
| 28 | LPG Bottling/Filling/Fuel Station Renewal | 12 | 53 |
| 29 | Building (Flat)/Establishment Measurement | 12 | 53 |
| 30 | Storage Tank Calibration | 13 | 58 |
| 31 | Industrial & Scientific Metrology Calibration | 14 | 59 |
| 32 | Verification Service | 12 | 48 |
| 33 | Mobile Court & Surveillance | 8 | 49 |

### v1 history note sheet and extras (scans)

See the summary table at the end of `scanned/v1-history-notesheet.md` and the contents table at the top of `scanned/extras.md`. The facts most worth knowing:
- **Business Automation contract (13 Mar 2022):**
  - ৳15,11,250 excluding VAT, under PPR OTM.
  - Signed by Md. Taher Jamil, Director (Admin), and Jahidul Hasan, MD.
  - It already required BSTI copyright over the source code, BCC hosting, a BCC SQTC certificate, an AMC after year 1, and a bug SLA (critical bugs fixed in 3 working days, others in 2 weeks).
- **Status in May 2024:**
  - About 40% done, with ৳1,43,569 paid, and the contract extended twice (meeting of 07 May 2024).
  - CM: only licence issue worked. Metrology: 11 of 14 services ran, with faults. MSC: none developed.
- **Tripartite meeting (26 May 2024):**
  - The phase 2 and SRS decision was taken here.
  - Business Automation said the 17 prototyped services had grown to 27, and that ~40% of 700 observations were still undefined.
  - BCC refused to accept the software without SQTC.
  - There was a confidentiality bug: officers could see and approve each other's files.
- **Requirement sessions:**
  - Requirement collection Jun 2024, then validation workshops 01 Aug, 04 Sep, 15 Sep and 26 Sep 2024.
  - **OrangeBD kick-off 02 Jan 2025.** SRS v1 circulated to the wings on 03 Apr 2025.
- **Wing comments on SRS v1 (2025):**
  - **MSC:** suspension, cancellation and surveillance audit missing.
  - **Metrology:** **Verification** and **Import Clearance & Verification** missing.
  - **Physical:** not fully reflected.
  - **Standards:** E-commerce wrongly placed under Admin.
  - **CM:** listed **CM Clearance Certificate**, which is still not one of the 33 services in 2026.

---

## Recovering an original

On 01 Nov 2026 the PDFs and the pptx were purged from the whole git history with `git filter-repo` (the repo dropped from ~100 MB). They are **not** recoverable from git any more. The originals are archived outside the repo, on this machine, at:

`/home/abdnahid/Desktop/bsti_v2_originals_backup/`

That folder holds all 9 original files and `bsti_v2-full-history-before-purge.bundle`, a full git bundle of the repo before the purge (the old commit `dae7334` is in it). If an original is needed, copy it from that folder. Don't add it back to this repo.

Keep a second copy of that folder off this machine (e.g. the office share or Google Drive). The signed contract and Amendment 1 are the legal evidence; the KB transcription is not.
