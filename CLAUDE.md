# BSTI 2.0 — Digitalization Restructure

Working folder for planning the restructure of BSTI's (Bangladesh Standards and Testing Institution) digital services into one integrated platform ("BSTI 2.0"). This is an analysis/planning workspace, not a code repo (yet).

The user is a BSTI official driving this effort. Goal: BSTI owns the requirements, architecture and contract this time — not the donor, not the vendor.

## Read first

- `sessions/` — dated records of each discussion. Read the latest one before continuing; build on its findings instead of re-deriving them.

## Source documents

| File | What it is | How to read |
|---|---|---|
| `notes on BSTI_v1 history.pdf` | 19-page scanned Bangla note sheet (নোট শীট), Apr 2024 – Sep 2025, on how v1 started | No text layer. Render pages with `pymupdf` (`page.get_pixmap(dpi=90)`) and read the images |
| `BSTI 2.0 Forwarding Letter.pdf` | OrangeBD cover letter, 21 Sep 2026 | `pdftotext -layout` |
| `BSTI 2.0 - Financial Proposal V4.pdf` | OrangeBD v2 financial offer, 8 pages | `pdftotext -layout` |
| `BSTI 2.0.pptx` | 47-slide deck: offer + one slide per service (modules/feature counts) | No python-pptx; unzip and regex `<a:t>` from `ppt/slides/slideN.xml` |
| `BSTI 2.0 SRS .pdf` | 303-page SRS by OrangeBD (note the space before `.pdf`) | `pdftotext -layout` (~13k lines); architecture diagram is p.17 (render as image) |

Tools available: `pdftotext` (Git Bash mingw64), Python 3.14 with `pymupdf`. Not available: `pdftoppm`, `pypdf`, `python-pptx`, `tesseract`. Put extracted text and renders in the session scratchpad, not this folder.

## Background (short)

- **Legacy systems:** QR certificate/test-report software, BSTI billing (one-stop service only), inventory, standards sale, Alo attendance — all separate.
- **v1:** BTF (USAID-funded, run by Land O'Lakes Venture37) contracted Orange Business Development Ltd (OrangeBD), ~BDT 91 lakh, 12 Jan 2025 → 31 Jul 2026. BSTI had no direct contract. Standards e-commerce (`ec.eservice.bsti.gov.bd`), then CM rushed before the outgoing DG retired. Separate logins (`eservice.`, `admin.`, `workflow.eservice.bsti.gov.bd`). Lab test reports uploaded manually into CM; head office only. 5 services live.
- **After USAID exit (user, 6 Oct 2026):** BTF paid OrangeBD the full ~91 lakh before delivery as USAID was closing. Under a gentleman's agreement, OrangeBD finishes on its own and deals with BSTI directly; BTF has since closed. OrangeBD wrote the 303-page SRS on BSTI's order. There is no BSTI–OrangeBD contract yet. OrangeBD holds the code and servers.
- **Live now (5):** CM (new registration only), HR, Payroll, PCR, Standards sale. All 23 offices are added but run under the head office organogram. Restructuring and data migration are planned for phase 2.
- **Hosting:** BCC. **Phase 2 funding:** BSTI revenue, with the full PPR applying. Services 22/23 (Importer/Exporter) are to be replaced by the Metrology dealer licence and Standards sale. Neither replacement is described in the SRS.
- **v2 offer (Sep 2026):** 33 "services", BDT 18.69 crore + VAT (11.17 cr rollout Aug 2026–Dec 2029 + 7.52 cr maintenance 2030–31), billed per live service per month.

## Conventions

- Money in BDT; use lakh/crore as the user does (1 crore = 100 lakh = 10,000,000).
- Bangla source text: quote the original and give an English gloss.
- Verify numbers against the source files before quoting them; flag anything inferred.
- When adding a new discussion, create `sessions/YYYY-MM-DD-<topic>.md` and keep this file's background current.
