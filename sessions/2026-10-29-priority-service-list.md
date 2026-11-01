# 2026-10-29: Priority list mapped to SRS service names

Output: `BSTI 2.0 - Priority Service List (SRS names).docx` (root). It has a 4-column table: Priority serial, Category, Serial, Service name. Categories are copied verbatim from `serial.docx`, and service names are the SRS index headings ("Service-NN: …"). The generator script is in that session's scratchpad (docx-js).

Mapping decisions (flagged in the docx notes):
- "CM Non-Scope" maps to the SRS "CM Mandatory" services (05–07). This is inferred because the SRS has only the Mandatory and Scope CM families. To be confirmed with the CM wing.
- Mobile Court (8) and Surveillance (9) both map to Service-33, a single combined service.
- Verification (10) maps to Service-32, Tank Calibration (11) to Service-26 and Storage Tank (13) to Service-30. The SRS doesn't split these into the serial.docx sub-items (petrol pump, weighbridge, road-tanker, underground, etc.), so each gets one row.
- Not in the SRS: BDS sell (standards sale), MSC Scope Inclusion, API integration with BSW, and Suspension/Cancellation/Withdrawal.
- Importer/Exporter (*) maps to Services 22/23.
- The SRS heading suffix "Feature Description" was dropped for Services 07, 14 and 19.
