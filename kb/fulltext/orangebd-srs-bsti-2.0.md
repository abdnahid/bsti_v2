# OrangeBD — BSTI 2.0 SRS (303 pages)

Full text extracted with `pdftotext -layout` from `BSTI 2.0 SRS .pdf` (303 pages). Layout preserved inside the text blocks. Images (logos, signatures, diagrams) are not in this text; see the notes in the KB index.

## Page 1

```text
e-Application Management System
             BSTI 2.0

                    Submitted To

                    Submitted By
```

## Page 2

```text
Table of Contents
Executive Summary ...................................................................................................................................... 14
Challenges & Business Case ..................................................................................................................... 15
Service-1: HRM & Leave Management .................................................................................................. 18
   Module-1: Organogram (Total Feature - 4)...................................................................................... 20
   Module-2: Employee Management (Total Feature - 6) ................................................................ 20
   Module-3: Employee Office Management (Total Feature - 5) ................................................... 21
   Module-4: ID Card Management (Total Feature - 8) ..................................................................... 22
   Module-5: PDS (Personal Data Sheet) (Total Feature - 4).......................................................... 23
   Module-6: Employee Modification with Dynamic Workflow (Total Feature - 5) ................. 24
   Module-7: Users Module for Admin (Total Feature - 4)............................................................... 25
   Module-8: Reset User Password for Admin (Total Feature - 1) ................................................ 26
   Module-9: Director General (Total Feature -1) ............................................................................... 26
   Module-10: Release and Assign (Total Feature - 4) ..................................................................... 26
   Module-11: Leave Management (Total Feature - 7) ..................................................................... 26
Service-2: Payroll Management ............................................................................................................... 29
   Module-1: Regular Salary – Earnings/Deductions (Total Feature - 6)..................................... 31
   Module-2: Payroll Pay Scale (Total Feature - 2) ............................................................................ 31
   Module-3: Salary Fixation (Total Feature - 5) ................................................................................. 31
   Features Description ................................................................................................................................ 31
   Module-4: Salary Process (Total Feature - 4).................................................................................. 32
   Module-5: Bonus Process (Total Feature - 1).................................................................................. 32
   Module-6: Bank Advice (Salary/Bonus) (Total Feature - 3) ........................................................ 32
   Module-7: Top Sheet (Salary/Bonus) (Total Feature - 2) ............................................................ 33
   Module-8: Salary Certification (Total Feature - 6) ......................................................................... 33
   Module-9: Income Tax Statement (Total Feature - 8) .................................................................. 33
   Module-10: Journal Voucher (Total Feature - 9) ............................................................................ 34
   Module-11: Payroll Accounts (Total Feature - 2)........................................................................... 35
   Module-12: Salary Month Lock (Total Feature - 1)........................................................................ 35
   Module-13: Download Payslip (Total Feature - 1) ....................................................................... 35
   Module-14: Loan Management (Total Feature - 22) ..................................................................... 35
   Module-15: GPF (General Provident Fund)(Total Feature-12) .................................................. 37
Service-3: Finance & Accounts Management ....................................................................................... 40
   Module - 1: Budget Management Module (Total Feature - 7) ................................................... 42
   Module 2: Income Management (Total Feature - 5) ...................................................................... 42
   Module-3: Expense Management (Total Feature - 6) ................................................................... 43
   Module - 4: Ledger & Accounting (Total Feature - 5) ................................................................... 44
   Module - 5: Voucher Management Module (Total Feature - 5) ................................................. 44
   Module - 6: Chart of Accounts (Total Feature - 5) ......................................................................... 45
   Module - 7: Payment Gateway (Total Feature - 6) ........................................................................ 45

                                                                            1
```

## Page 3

```text
   Module - 8: Payroll Integration (Total Feature - 8) ........................................................................ 46
   Module - 9: Reporting System (Total Feature - 4) ......................................................................... 47
   Module - 10: Role-Based Access Control & Audit (Total Feature - 6) ................................... 47
Service-4: Case Management System .................................................................................................... 49
   Module-1: Case Registration (Total Feature - 5) ............................................................................ 51
   Module-2: Case Review & Assignment (Total Feature - 4) ........................................................ 51
   Module-3: Investigation Management (Total Feature - 4) .......................................................... 51
   Module-4: Hearing & Court Management (Total Feature - 4) .................................................... 51
   Module-5: Approval Management (Total Feature - 4) ................................................................. 52
   Module-6: Fine & Penalty Management (Total Feature - 4) ....................................................... 52
   Module-7: Case Closure (Total Feature - 4)..................................................................................... 52
   Module-8: Notification & Reporting (Total Feature - 5) ............................................................... 53
Service-05: CM Mandatory New Certification...................................................................................... 55
   Module-1. Application Submission (Total Feature - 4) ................................................................ 57
   Module-2. Application Review & Shortfall Management (Total Feature - 5) ....................... 57
   Module-3. Payment Processing (Total Feature - 4)....................................................................... 57
   Module-4. Inspection Setup (Total Feature - 3) .............................................................................. 58
   Module-5. Inspection & Report (Total Feature - 5) ........................................................................ 58
   Module-6. Verification Module (AD/DD) (Total Feature - 3) ...................................................... 59
   Module-7. Director Decision (Total Feature - 3) ............................................................................. 59
   Module-8. Certification Complete (Total Feature - 3)................................................................... 59
   Module-9. Rejection Management (Total Feature - 3) ................................................................. 59
   Module-10. Notification Management (Total Feature - 3) .......................................................... 60
   Module-11. Re-Inspection Management (Total Feature - 3) ...................................................... 60
   Module-12. User & Role Management (Total Feature - 7) ......................................................... 60
Service-06: CM Mandatory Renewal Service ....................................................................................... 63
   Module-1. Application Submission (Total Feature - 4) ................................................................ 65
   Module-2. Application Review & Shortfall Management (Total Feature - 5) ....................... 65
   Module-3. Payment Processing (Total Feature - 4)....................................................................... 65
   Module-4. Inspection Setup (Total Feature - 3) .............................................................................. 66
   Module-5. Inspection & Report (Total Feature - 5) ........................................................................ 66
   Module-6. Verification Module (AD/DD) (Total Feature - 3) ...................................................... 67
   Module-7. Director Decision (Total Feature - 3) ............................................................................. 67
   Module-8. Certification Complete (Total Feature - 3)................................................................... 67
   Module-9. Rejection Management (Total Feature - 3) ................................................................. 67
   Module-10. Notification Management (Total Feature - 3) .......................................................... 68
   Module-11. Re-Inspection Management (Total Feature - 3) ...................................................... 68
   Module-12. User & Role Management (Total Feature - 7) ......................................................... 68
Service-07: CM Mandatory Brand Inclusion Feature Description .................................................. 71
   Module-1. Application Submission (Total Feature - 4) ................................................................ 73

                                                                   2
```

## Page 4

```text
   Module-2. Application Review & Shortfall Management (Total Feature - 5) ....................... 73
   Module-3. Payment Processing (Total Feature - 4)....................................................................... 73
   Module-4. Inspection Setup (Total Feature - 3) .............................................................................. 74
   Module-5. Inspection & Report (Total Feature - 5) ........................................................................ 74
   Module-6. Verification Module (AD/DD) (Total Feature - 3) ...................................................... 74
   Module-7. Director Decision (Total Feature - 3) ............................................................................. 75
   Module-8. Certification Complete (Total Feature - 3)................................................................... 75
   Module-9. Rejection Management (Total Feature - 3) ................................................................. 75
   Module-10. Notification Management (Total Feature - 3) .......................................................... 76
   Module-11. Re-Inspection Management (Total Feature - 3) ...................................................... 76
   Module-12. User & Role Management (Total Feature - 7) ......................................................... 76
Service-08: CM Scope New Certification ............................................................................................... 79
   Module-1. Application Submission (Total Feature - 5) ................................................................ 81
   Module-2. Application Review & Shortfall Management (Total Feature - 8) ....................... 81
   Module-3. Inspection Planning (Total Feature - 4) ........................................................................ 82
   Module-4. Primary Inspection (Total Feature - 5) .......................................................................... 82
   Module-5. Formal Inspection (Total Feature - 5)............................................................................ 82
   Module-6. Laboratory Testing (Total Feature - 5) ......................................................................... 82
   Module-7. Technical Evaluation (Total Feature - 4) ...................................................................... 83
   Module-8. Verification & Approval (Total Feature - 5) ................................................................. 83
   Module-9. Certification Committee (Total Feature - 5) ................................................................ 83
   Module-10. Conditional Compliance (Total Feature - 5) ............................................................. 84
   Module-11. Payment Processing (Total Feature - 5) .................................................................... 84
   Module-12. License Management (Total Feature - 5) .................................................................. 85
   Module-13. Refusal & Rejection Management (Total Feature - 4) ........................................... 85
   Module-14. Notification (Total Feature - 6) ..................................................................................... 85
   Module-15. Workflow & Task Management (Total Feature - 5)............................................... 86
   Module-16. Document Management (Total Feature - 7) ............................................................. 86
Service-09: CM Scope Renewal Certification ....................................................................................... 88
   Module-1. Application Submission (Total Feature - 5) ................................................................ 90
   Module-2. Application Review & Shortfall Management (Total Feature - 8) ....................... 90
   Module-3. Inspection Planning (Total Feature - 4) ........................................................................ 91
   Module-4. Primary Inspection (Total Feature - 5) .......................................................................... 91
   Module-5. Formal Inspection (Total Feature - 5)............................................................................ 91
   Module-6. Laboratory Testing (Total Feature - 5) ......................................................................... 91
   Module-7. Technical Evaluation (Total Feature - 4) ...................................................................... 92
   Module-8. Verification & Approval (Total Feature - 5) ................................................................. 92
   Module-9. Certification Committee (Total Feature - 5) ................................................................ 92
   Module-10. Conditional Compliance (Total Feature - 5) ............................................................. 93
   Module-11. Payment Processing (Total Feature - 5) .................................................................... 93

                                                                   3
```

## Page 5

```text
   Module-12. License Management (Total Feature - 5) .................................................................. 94
   Module-13. Refusal & Rejection Management (Total Feature - 4) ........................................... 94
   Module-14. Notification (Total Feature - 6) ..................................................................................... 94
   Module-15. Workflow & Task Management (Total Feature - 5)............................................... 95
   Module-16. Document Management (Total Feature - 7) ............................................................. 95
Service-10: CM Scope Brand Inclusion Certification.......................................................................... 97
   Module-1. Application Submission (Total Feature - 5) ................................................................ 99
   Module-2. Application Review & Shortfall Management (Total Feature - 8) ....................... 99
   Module-3. Inspection Planning (Total Feature - 4) ..................................................................... 100
   Module-4. Primary Inspection (Total Feature - 5) ....................................................................... 100
   Module-5. Formal Inspection (Total Feature - 5)......................................................................... 100
   Module-6. Laboratory Testing (Total Feature - 5) ...................................................................... 100
   Module-7. Technical Evaluation (Total Feature - 4) ................................................................... 101
   Module-8. Verification & Approval (Total Feature - 5) .............................................................. 101
   Module-9. Certification Committee (Total Feature - 5) ............................................................. 101
   Module-10. Conditional Compliance (Total Feature - 5) .......................................................... 102
   Module-11. Payment Processing (Total Feature - 5) ................................................................. 102
   Module-12. License Management (Total Feature - 5) ............................................................... 102
   Module-13. Refusal & Rejection Management (Total Feature - 4) ........................................ 103
   Module-14. Notification (Total Feature - 6) .................................................................................. 103
   Module-15. Workflow & Task Management (Total Feature - 5)............................................ 103
   Module-16. Document Management (Total Feature - 7) .......................................................... 104
Service-11: CM HALAL CERTIFICATION ........................................................................................... 106
   Module-1. Certificate Application (Total Feature - 4) ................................................................ 108
   Module-2. Application Review & Shortfall Management (Total Feature - 8) .................... 108
   Module-3. Stage-1 Audit Management (Total Feature - 6) ..................................................... 108
   Module-4. Audit Observation & Compliance (Total Feature - 4) ........................................... 109
   Module-5. Stage-2 Audit & Sample Management (Total Feature - 5)................................. 109
   Module-6. Laboratory Testing (Total Feature - 5) ...................................................................... 109
   Module-7. Technical Evaluation (Total Feature - 4) ................................................................... 110
   Module-8. Verification & Approval (Total Feature - 5) .............................................................. 110
   Module-9. Certification Committee (Total Feature - 5) ............................................................. 110
   Module-10. Conditional Compliance (Total Feature - 5) .......................................................... 111
   Module-11. Payment Processing (Total Feature - 5) ................................................................. 111
   Module-12. Certificate / License Management (Total Feature - 5) ........................................ 111
   Module-13. Refusal & Rejection Management (Total Feature - 5) ........................................ 112
   Module-14. Notification (Total Feature - 7) .................................................................................. 112
   Module-15. Workflow & Task Management (Total Feature - 6)............................................ 112
   Module-16. Document Management (Total Feature - 7) .......................................................... 113
Service-12: CM HALAL RENEWAL CERTIFICATION .................................................................... 115

                                                                  4
```

## Page 6

```text
   Module-1. Certificate Application (Total Feature - 4) ................................................................ 117
   Module-2. Application Review & Shortfall Management (Total Feature - 8) .................... 117
   Module-3. Stage-1 Audit Management (Total Feature - 6) ..................................................... 117
   Module-4. Audit Observation & Compliance (Total Feature - 4) ........................................... 118
   Module-5. Stage-2 Audit & Sample Management (Total Feature - 5)................................. 118
   Module-6. Laboratory Testing (Total Feature - 5) ...................................................................... 118
   Module-7. Technical Evaluation (Total Feature - 4) ................................................................... 119
   Module-8. Verification & Approval (Total Feature - 5) .............................................................. 119
   Module-9. Certification Committee (Total Feature - 5) ............................................................. 119
   Module-10. Conditional Compliance (Total Feature - 5) .......................................................... 120
   Module-11. Payment Processing (Total Feature - 5) ................................................................. 120
   Module-12. Certificate / License Management (Total Feature - 5) ........................................ 120
   Module-13. Refusal & Rejection Management (Total Feature - 5) ........................................ 121
   Module-14. Notification (Total Feature - 7) .................................................................................. 121
   Module-15. Workflow & Task Management (Total Feature - 6)............................................ 121
   Module-16. Document Management (Total Feature - 7) .......................................................... 122
Service-13: CM Halal Brand Inclusion ................................................................................................. 124
   Module-1. Certificate Application (Total Feature - 4) ................................................................ 126
   Module-2. Application Review & Shortfall Management (Total Feature - 8) .................... 126
   Module-3. Stage-1 Audit Management (Total Feature - 6) ..................................................... 126
   Module-4. Audit Observation & Compliance (Total Feature - 4) ........................................... 127
   Module-5. Stage-2 Audit & Sample Management (Total Feature - 5)................................. 127
   Module-6. Laboratory Testing (Total Feature - 5) ...................................................................... 127
   Module-7. Technical Evaluation (Total Feature - 4) ................................................................... 128
   Module-8. Verification & Approval (Total Feature - 5) .............................................................. 128
   Module-9. Certification Committee (Total Feature - 5) ............................................................. 128
   Module-10. Conditional Compliance (Total Feature - 5) .......................................................... 129
   Module-11. Payment Processing (Total Feature - 5) ................................................................. 129
   Module-12. Certificate / License Management (Total Feature - 5) ........................................ 129
   Module-13. Refusal & Rejection Management (Total Feature - 5) ........................................ 130
   Module-14. Notification (Total Feature - 7) .................................................................................. 130
   Module-15. Workflow & Task Management (Total Feature - 6)............................................ 130
   Module-16. Document Management (Total Feature - 7) .......................................................... 131
Service-14: Chemical Testing Feature Description ......................................................................... 133
   Module-1. Sample Tracking (Total Feature - 4) ........................................................................... 135
   Module-2. Resample Management (Total Feature - 4) ............................................................. 135
   Module-3. Sample Security (Total Feature - 3)............................................................................ 135
   Module-4. Multi-Level Verification (Total Feature - 4) .............................................................. 136
   Module-5. Correction & Return (Total Feature - 4)..................................................................... 136
   Module-6. Re-Test Management (Total Feature - 3) ................................................................. 136

                                                                    5
```

## Page 7

```text
   Module-7. Notification (Total Feature - 4) ..................................................................................... 137
   Module-8. Remarks & Comment (Total Feature - 4) .................................................................. 137
   Module-9. Report Generation (Total Feature - 3) ....................................................................... 137
   Module-10. Task Management (Total Feature - 3) ..................................................................... 138
   Module-11. Dashboard (Total Feature - 3) ................................................................................... 138
   Module-12. Audit & Activity Log (Total Feature - 4).................................................................. 138
   Module-13. Workflow Engine (Total Feature - 3) ...................................................................... 139
   Module-14. Search (Total Feature - 4) ........................................................................................... 139
   Module-15. Access Control (Total Feature - 3) ........................................................................... 139
   Module-16. Localization (Total Feature - 2).................................................................................. 140
   Module-17. Data Security (Total Feature - 3) .............................................................................. 140
   Module-18. Report Delivery (Total Feature - 3) .......................................................................... 140
   Module-19. Multiple Role Management (Total Feature - 3) .................................................... 140
   Module-20. Regional Office Workflow (Total Feature - 3) ...................................................... 141
Service-15: Physical Testing................................................................................................................... 143
   Module-1. User & Role Management (Total Feature - 9) ......................................................... 145
   Module-2. Application Management (Total Feature - 7) .......................................................... 145
   Module-3. Sample Management (Total Feature - 6).................................................................. 146
   Module-4. Workflow Management (Total Feature - 7) ............................................................. 146
   Module-5. Parameter Management (Total Feature - 6) ............................................................ 147
   Module-6. Test & Result Management (Total Feature - 7) ...................................................... 147
   Module-7. Report Management (Total Feature - 9) ................................................................... 148
   Module-8. Notification Management (Total Feature - 5) .......................................................... 149
   Module-9. Energy Meter Management (Total Feature - 10).................................................... 149
   Module-10. Product & Laboratory Management (Total Feature - 6) .................................... 150
Service-16: Physical Lab- Energy Meter ............................................................................................. 152
   Module-1. User & Role Management (Total Feature - 7) ......................................................... 154
   Module-2. Application Management (Total Feature - 7) .......................................................... 154
   Module-3. Shortfall Management (Total Feature - 5) ............................................................... 155
   Module-4. Sample Collection Management (Total Feature - 7) ............................................. 155
   Module-5. Energy Meter Testing Management (Total Feature - 6) ...................................... 156
   Module-6. Result Verification & Approval (Total Feature - 7) ................................................ 157
   Module-7. Workflow Management (Total Feature - 6) ............................................................. 157
   Module-8. Retest Management (Total Feature - 5) .................................................................... 158
   Module-9. Test Report Management (Total Feature - 6).......................................................... 158
   Module-10. Notification Management (Total Feature - 5) ....................................................... 159
   Module-11. Energy Meter Information Management (Total Feature - 5) ............................ 159
   Module-12. Tracking & Audit Management (Total Feature - 5) ............................................. 160
Service-17: MSC Certification ................................................................................................................ 162
   Module-1: MSC Application Management (Total Feature - 6) ................................................ 164

                                                                        6
```

## Page 8

```text
  Module-2: Application Payment and Document Management Module (Total Feature - 6)
  ...................................................................................................................................................................... 164
  Module-3: Application Review and Adequacy Audit Module (Total Feature - 8) ............ 165
  Module-4: Acceptance and Agreement Management Module (Total Feature - 8) .......... 166
  Module-5: Man-Day Calculation and Audit Scheduling Module (Total Feature - 7) ....... 166
  Module-6: Stage-1 Audit Management Module (Total Feature - 8) ..................................... 167
  Module-7: Corrective Action Management Module (Total Feature - 9) ............................... 168
  Module-8: Stage-2 Audit Notice and Scheduling Module (Total Feature - 8) ................... 169
  Module-9: Stage-2 Audit Management Module (Total Feature - 8) ..................................... 169
  Module-10: Stage-2 Corrective Action and Findings Closure Module (Total Feature - 8)
  ...................................................................................................................................................................... 170
  Module-11: Initial Certification Proposal Management Module (Total Feature - 6) ........ 171
  Module-12: Audit and Certification Billing Module (Total Feature - 9) ............................... 171
  Module-13: Certification Committee Meeting Management Module (Total Feature - 8)
  ...................................................................................................................................................................... 172
  Module-14: Certification Committee Minutes Management Module (Total Feature - 6)173
  Module-15: MSC Certificate Generation and Approval Module (Total Feature - 7) ........ 173
  Module-16: Rejection, Rework and Follow-Up Audit Module (Total Feature - 6) ........... 174
  Module-17: Workflow and Approval Management Module (Total Feature - 6) .............. 175
  Module-18: Notification and Communication Management Module (Total Feature - 10)
  ...................................................................................................................................................................... 175
  Module-19: Application and Workflow Tracking Module (Total Feature - 7) ................... 176
  Module-20: MSC Reports and Dashboard Module (Total Feature - 9) ................................ 177
  Module-21: Audit Trail and Activity Log Module (Total Feature - 7) ................................... 178
  Module-22: Role-Based User and Access Management Module (Total Feature - 5) ..... 178
  Module-23: External Integration Management Module (Total Feature - 7) ....................... 179
  Module-24: Certificate Verification and QR Code (Total Feature - 5) .................................. 179
Service-18: MSC Re-certification Management System ................................................................ 182
  Module-1: Re-certification Application (Total Feature - 7) ...................................................... 184
  Module - 2: Application Review & Agreement Management (Total Feature - 10) .......... 184
  Module - 3: Audit Planning & Scheduling (Total Feature - 10) .............................................. 185
  Module - 4: Re-certification Audit Management (Total Feature - 9) ..................................... 185
  Module - 5: Audit Findings & Corrective Action Management (Total Feature -10) ........ 186
  6. Improvement Notice Management Module (Total Feature - 7).......................................... 186
  7. Technical Review & Proposal Management Module (Total Feature -6) ......................... 187
  8. Certification Committee Management Module (Total Feature - 9) ................................... 187
  9. Payment Processing Module (Total Feature - 7) .................................................................... 188
  10. Certificate & Document Management Module (Total Feature -7) .................................. 188
  11. Rejection Management Module (Total Feature - 4)............................................................. 189
  12. Workflow & Task Management Module (Total Feature - 7) ............................................ 189

                                                                                   7
```

## Page 9

```text
   13. Notification Module (Total Feature - 10) ................................................................................ 190
   14. Document Management Module (Total Feature - 10) ........................................................ 190
Service-19: PCR Registration New Feature Description ............................................................... 193
   Module-1. Application Submission (Total Feature - 4) ............................................................. 195
   Module-2. Application Review & Shortfall Management (Total Feature - 5) .................... 195
   Module-3. Payment Processing (Total Feature - 4).................................................................... 195
   Module-4. Inspection Setup (Total Feature - 3) ........................................................................... 196
   Module-5. Inspection & Report (Total Feature - 5) ..................................................................... 196
   Module-6. Verification Module (AD/DD) (Total Feature - 3) ................................................... 197
   Module-7. Approval Management (Total Feature - 3) .............................................................. 197
   Module-8. Registration Complete (Total Feature - 3) ............................................................... 197
   Module-9. Rejection Management (Total Feature - 2) .............................................................. 197
   Module-10. Notification Management (Total Feature - 3) ....................................................... 198
   Module-11. Re-Inspection Management (Total Feature - 3) ................................................... 198
   Module-12. User & Role Management (Total Feature - 7) ...................................................... 198
   Module-13. Regional Office Workflow (Total Feature - 3) ...................................................... 199
Service-20: PCR Registration Renewal ............................................................................................... 201
   Module - 1: Application Submission (Total Feature - 4) ........................................................... 203
   Module - 2: Application Review & Shortfall Management (Total Feature - 5) .................. 203
   Module - 3. Payment Processing (Total Feature - 4) ................................................................. 203
   Module-4. Inspection Setup (Total Feature - 3) ........................................................................... 204
   Module-5. Inspection & Report (Total Feature - 5) ..................................................................... 204
   Module-6. Verification Module (AD/DD) (Total Feature - 3) ................................................... 205
   Module-7. Approval Management (Total Feature - 3) .............................................................. 205
   Module-8. Registration Complete (Total Feature - 3) ............................................................... 205
   Module-9. Rejection Management (Total Feature - 2) .............................................................. 205
   Module-10. Notification Management (Total Feature - 3) ....................................................... 206
   Module-11. Re-Inspection Management (Total Feature - 3) ................................................... 206
   Module-12. User & Role Management (Total Feature - 7) ...................................................... 206
   Module-13. Regional Office Workflow (Total Feature - 3) ...................................................... 207
Service-21: PCR Brand Inclusion .......................................................................................................... 209
   Module-1: Application Submission (Total Feature - 3) ............................................................. 211
   Module-2: Application Review & Shortfall Management (Total Feature - 5) .................... 211
   Module-3: Payment Processing (Total Feature - 4).................................................................... 211
   Module-4: Inspection Setup (Total Feature - 3) ........................................................................... 212
   Module-5: Inspection & Report (Total Feature - 5) ..................................................................... 212
   Module-6: Verification (AD/DD) (Total Feature - 3) ................................................................... 213
   Module-7: Approval Management (Total Feature - 3) .............................................................. 213
   Module-8: Registration Complete (Total Feature - 1) ............................................................... 213
   Module-9: Rejection Management (Total Feature - 2) .............................................................. 213

                                                                      8
```

## Page 10

```text
   Module-10: Notification Management (Total Feature - 3) ....................................................... 214
   Module-11: Re-Inspection Management (Total Feature - 3) ................................................... 214
   Module-12: User & Role Management (Total Feature - 7) ...................................................... 214
   Module-13: Regional Office Workflow (Total Feature - 3) ...................................................... 215
Service-22: Registered Importer/Exporter Certificate Service ..................................................... 217
   Module-1. Application Submission (Total Feature - 4) ............................................................. 219
   Module-2. Application Review & Shortfall Management (Total Feature - 6) .................... 219
   Module-3. Inspection Scheduling (Total Feature - 4) ................................................................ 219
   Module-4. Inspection Management (Total Feature - 4) ............................................................ 220
   Module-5. Inspection Report Verification (Total Feature - 4) .................................................. 220
   Module-6. Re-inspection Management (Total Feature - 4) ..................................................... 220
   Module-7. Payment Processing (Total Feature - 4).................................................................... 221
   Module-8. Certificate Management (Total Feature - 5)............................................................. 221
   Module-9. Rejection Management (Total Feature - 3) .............................................................. 221
   Module-10. Notification (Total Feature - 6) .................................................................................. 221
   Module-11. Workflow & Task Management (Total Feature - 5)............................................ 222
   Module-12. Document Management (Total Feature - 4) .......................................................... 222
Service-23: Registered Importer/Exporter Certificate Management Renewal ....................... 224
   Module- 1: Re-Application Submission (Total Feature - 6) ..................................................... 226
   Module- 2: Application Review & Shortfall Management (Total Feature - 6) ................... 226
   Module- 3: Inspection Scheduling (Total Feature - 4) ............................................................... 226
   Module- 4: Inspection Management (Total Feature - 4) ........................................................... 227
   Module- 5: Inspection Report Verification (Total Feature - 4)................................................. 227
   Module- 6: Re-inspection Management (Total Feature - 4) .................................................... 227
   Module- 7: Payment Processing (Total Feature - 4) .................................................................. 228
   Module- 8: Certificate Management (Total Feature - 5) ........................................................... 228
   Module- 9: Rejection Management (Total Feature - 3) ............................................................. 228
   Module- 10: Notification Management (Total Feature - 6) ...................................................... 228
   Module- 11: Workflow & Task Management (Total Feature - 5) .......................................... 229
   Module- 12. Document Management (Total Feature - 4)......................................................... 229
Service-24: Metrology License Issue ................................................................................................... 231
   Module-1. Application Submission (Total Feature - 4) ............................................................. 233
   Module-2. Application Review & Assignment (Total Feature - 4) ......................................... 233
   Module-3. Shortfall Management (Total Feature - 5) ............................................................... 233
   Module-4. Inspection Scheduling (Total Feature - 4) ................................................................ 234
   Module-5. Inspection Management (Total Feature - 3) ............................................................ 234
   Module-6. Inspection Verification & Approval (Total Feature - 4) ......................................... 234
   Module-7. Re-inspection Management (Total Feature - 4) ..................................................... 235
   Module-8. Payment Processing (Total Feature - 4).................................................................... 235
   Module-9. License Management (Total Feature - 4) .................................................................. 235

                                                                    9
```

## Page 11

```text
   Module-10. Rejection Management (Total Feature - 3) ............................................................ 236
   Module-11. Notification (Total Feature - 6) .................................................................................. 236
   Module-12. Workflow & Task Management (Total Feature - 5)............................................ 236
   Module-13. Document Management (Total Feature - 4) .......................................................... 237
Service-25: Metrology License Renewal Registration ................................................................... 239
   Module-1. Application Submission (Total Feature - 4) ............................................................. 241
   Module-2. Application Review & Assignment (Total Feature - 4) ......................................... 241
   Module-3. Shortfall Management (Total Feature - 5) ............................................................... 241
   Module-4. Inspection Scheduling (Total Feature - 4) ................................................................ 242
   Module-5. Inspection Management (Total Feature - 3) ............................................................ 242
   Module-6. Inspection Verification & Approval (Total Feature - 4) ......................................... 242
   Module-7. Re-inspection Management (Total Feature - 4) ..................................................... 243
   Module-8. Payment Processing (Total Feature - 4).................................................................... 243
   Module-9. License Management (Total Feature - 4) .................................................................. 243
   Module-10. Rejection Management (Total Feature - 3) ............................................................ 244
   Module-11. Notification (Total Feature - 6) .................................................................................. 244
   Module-12. Workflow & Task Management (Total Feature - 5)............................................ 244
   Module-13. Document Management (Total Feature - 4) .......................................................... 245
Service-26: Tank Lorry Calibration ....................................................................................................... 247
   Module-1. Application Submission (Total Feature - 4) ............................................................. 249
   Module- 2: Application Review & Assignment (Total Feature - 4)........................................ 249
   Module- 3: Shortfall Management (Total Feature - 5) .............................................................. 249
   Module- 4: Calibration Scheduling (Total Feature - 4) .............................................................. 249
   Module- 5: Calibration Management (Total Feature - 3) .......................................................... 250
   Module- 6: Calibration Report Verification (Total Feature - 4) ............................................... 250
   Module- 7: License Management (Total Feature - 4) ................................................................. 250
   Module- 8: Re-inspection / Re-calibration Management (Total Feature - 4) ..................... 250
   Module- 9: Rejection Management (Total Feature - 3) ............................................................. 251
   Module- 10: Notification (Total Feature - 5) ................................................................................. 251
   Module- 11: Workflow & Task Management (Total Feature - 5) .......................................... 251
   Module- 12: Document Management (Total Feature - 4)......................................................... 252
Service-27: LPG Bottling Plant / LPG Filling Station / Fuel Filling Station Registration Service
.......................................................................................................................................................................... 254
   Module- 1: Application Submission (Total Feature - 4) ............................................................ 256
   Module- 2: Application Review & Shortfall Management (Total Feature - 6) ................... 256
   Module- 3: Inspection Scheduling (Total Feature - 4) ............................................................... 256
   Module- 4: Inspection Management (Total Feature - 4) ........................................................... 257
   Module- 5: Inspection Report Verification & Approval (Total Feature - 4) ......................... 257
   Module- 6: Re-inspection Management (Total Feature - 4) .................................................... 257
   Module- 7: Payment Processing (Total Feature - 4) .................................................................. 257

                                                                                    10
```

## Page 12

```text
   Module- 8: Registration Certificate Management (Total Feature - 5) .................................. 258
   Module- 9: Rejection Management (Total Feature - 3) ............................................................. 258
   Module- 10: Notification (Total Feature - 6) ................................................................................. 258
   Module- 11: Workflow & Task Management (Total Feature - 5) .......................................... 259
   Module- 12: Document Management (Total Feature - 4)......................................................... 259
Service-28: LPG Bottling Plant / LPG Filling Station / Fuel Filling Station Renewal ........... 261
   Module- 1: Application Submission (Total Feature - 4) ............................................................ 263
   Module- 2: Application Review & Shortfall Management (Total Feature - 6) ................... 263
   Module- 3: Inspection Scheduling (Total Feature - 4) ............................................................... 263
   Module- 4: Inspection Management (Total Feature - 4) ........................................................... 264
   Module- 5: Inspection Report Verification & Approval (Total Feature - 4) ......................... 264
   Module- 6: Re-inspection Management (Total Feature - 4) .................................................... 264
   Module- 7: Payment Processing (Total Feature - 4) .................................................................. 264
   Module- 8: Registration Certificate Management (Total Feature - 5) .................................. 265
   Module- 9: Rejection Management (Total Feature - 3) ............................................................. 265
   Module- 10: Notification (Total Feature - 6) ................................................................................. 265
   Module- 11: Workflow & Task Management (Total Feature - 5) .......................................... 266
   Module- 12: Document Management (Total Feature - 4)......................................................... 266
Service-29: Building (Flat) / Establishment Measurement ........................................................... 268
   Module- 1: Application Submission (Total Feature - 4) ............................................................ 270
   Module- 2: Application Review & Shortfall Management (Total Feature - 6) ................... 270
   Module- 3: Inspection Scheduling (Total Feature - 4) ............................................................... 270
   Module- 4: Inspection Management (Total Feature - 4) ........................................................... 271
   Module- 5: Inspection Report Verification & Approval (Total Feature - 4) ......................... 271
   Module- 6: Re-inspection Management (Total Feature - 4) .................................................... 271
   Module- 7: Payment Processing (Total Feature - 4) .................................................................. 271
   Module- 8: Certificate Management (Total Feature - 5) ........................................................... 272
   Module- 9: Rejection Management (Total Feature - 3) ............................................................. 272
   Module- 10: Notification (Total Feature - 6) ................................................................................. 272
   Module- 11: Workflow & Task Management (Total Feature - 5) .......................................... 273
   Module- 12: Document Management (Total Feature - 4)......................................................... 273
Service-30: Storage Tank Calibration Service................................................................................... 275
   Module- 1. Application Submission (Total Feature - 5) ............................................................ 277
   Feature Description: .............................................................................................................................. 277
   Module- 2: Application Review & Shortfall Management (Total Feature - 6) ................... 277
   Feature Description: .............................................................................................................................. 277
   Module- 3: Calibration Scheduling (Total Feature - 4) .............................................................. 277
   Feature Description: .............................................................................................................................. 277
   Schedules calibration appointments based on operational requirements. ......................... 277
   Module- 4: Calibration Management (Total Feature - 4) .......................................................... 278

                                                                          11
```

## Page 13

```text
   Feature Description: .............................................................................................................................. 278
   Module- 5: Calibration Report Verification (Total Feature - 4) ............................................... 278
   Feature Description: .............................................................................................................................. 278
   Module- 6: Additional Fee Management (Total Feature - 4) ................................................... 278
   Feature Description: .............................................................................................................................. 278
   Module- 7: Payment Processing (Total Feature - 6) .................................................................. 278
   Feature Description: .............................................................................................................................. 278
   Module- 8: Calibration Certificate (Total Feature - 4) ................................................................ 279
   Module- 9: Re-calibration Management (Total Feature - 4) .................................................... 279
   Module-10: Rejection Management (Total Feature - 3) ............................................................ 279
   Feature Description: .............................................................................................................................. 279
   Module- 11: Notification Management (Total Feature - 5) ...................................................... 280
   Feature Description: .............................................................................................................................. 280
   Module-12. Workflow & Task Management (Total Feature - 5)............................................ 280
   Feature Description: .............................................................................................................................. 280
   Supports sequential processing through multiple approval authorities. ............................. 280
   Module 13: Document Management (Total Feature - 4) .......................................................... 280
   Feature Description: .............................................................................................................................. 280
   Securely stores and manages submitted application documents. ......................................... 280
Service-31: Industrial and Scientific Metrology Calibration ......................................................... 282
   Module- 1: Application Submission (Total Feature - 4) ............................................................ 284
   Module- 2: Application Review & Shortfall Management (Total Feature - 6) ................... 284
   Module- 3: Payment Processing (Total Feature - 4) .................................................................. 284
   Module- 4: Calibration Type Selection (Total Feature - 3) ....................................................... 285
   Module- 5: Instrument Receiving (OSS) (Total Feature - 4) .................................................... 285
   Module- 6: Calibration Scheduling (Total Feature - 4) .............................................................. 285
   Module- 7: Calibration & Inspection (Total Feature - 4)............................................................ 285
   Module- 8: Report Verification & Approval (Total Feature - 3) .............................................. 286
   Module- 9: Re-calibration / Re-inspection (Total Feature - 4) ................................................ 286
   Module- 10: Calibration Certificate Release (Total Feature - 4) ............................................ 286
   Module- 11: Rejection Management (Total Feature - 3) ........................................................... 286
   Module- 12: Notification Module (Total Feature - 6) ................................................................. 287
   Module- 13: Workflow & Task Management (Total Feature - 5) .......................................... 287
   Feature Description: .............................................................................................................................. 287
   Module- 14: Document Management (Total Feature - 5)......................................................... 287
   Feature Description: .............................................................................................................................. 287
Service-32: Verification Service ............................................................................................................. 290
   Module-1: Application Submission Module (Total Feature - 4).............................................. 292
   Module-2: Application Review & Assignment Module (Total Feature - 4) ......................... 292
   Module-3: Shortfall Management Module (Total Feature - 5)................................................ 292

                                                                          12
```

## Page 14

```text
   Module-4: Calibration Scheduling Module (Total Feature - 4) ............................................... 293
   Module-5: Calibration Management Module (Total Feature - 3) ........................................... 293
   Module-6: Calibration Report Verification Module (Total Feature - 4) ................................ 293
   Module-7: Calibration Certificate and Sticker Module (Total Feature - 3) .......................... 293
   Module-8: Re-inspection / Re-calibration Management Module (Total Feature - 4) ...... 294
   Module-9: Rejection Management Module (Total Feature - 3)............................................... 294
   Module-10: Notification Module (Total Feature - 5) .................................................................. 294
   Module-11: Workflow & Task Management Module (Total Feature - 5) ............................ 295
   Module-12: Document Management Module (Total Feature - 4) .......................................... 295
Service-33: Mobile Court & Surveillance e-Service ........................................................................ 297
   Module 1: Mobile Court Management (Total Feature - 18) ..................................................... 299
   Module 2: Product Management (Total Feature - 5) .................................................................. 300
   Module 3: Surveillance Management (Total Feature - 10)....................................................... 300
   Module 4: Sample Management (Total Feature - 7) .................................................................. 301
   Module 5: Test Report Management (Total Feature - 2) .......................................................... 301
   Module 6: Tracking & Monitoring (Total Feature - 3) ................................................................. 301
   Module 7: Administration (Total Feature - 2) ............................................................................... 301
   Module 8: Workflow Management (Future Phase) (Total Feature - 2) ................................ 302

                                                               13
```

## Page 15

```text
Executive Summary
This is to presents the detailed Scope of Work (SoW) for the proposed BSTI Enterprise
Resource Planning (ERP) Solution, a fully integrated digital platform designed to automate,
standardize, and streamline the end-to-end business operations of Bangladesh Standards
and Testing Institution (BSTI). The solution aims to establish a centralized, paperless, and
workflow-driven environment where all operational, administrative, financial, laboratory,
certification, inspection, and human resource activities are managed through a single unified
system.
The proposed ERP solution will serve as the core digital platform for BSTI, enabling seamless
collaboration among departments, regional offices, laboratories, and stakeholders while
ensuring data consistency, transparency, accountability, and real-time information sharing
across the organization. By integrating all business functions into a single ecosystem, the
system will eliminate fragmented processes, reduce manual intervention, improve
operational efficiency, strengthen governance, and support data-driven decision-making.
This document provides a comprehensive description of the modules, sub-modules, and
functional features included within the proposed solution. Each section outlines the purpose,
business functionality, workflow, user responsibilities, approval mechanisms, notifications,
reporting capabilities, integrations, and system controls required to support BSTI's
operational and regulatory processes.
The feature descriptions contained in this document collectively define the functional scope
of the proposed ERP solution and establish a common understanding among all stakeholders
regarding the system capabilities, implementation boundaries, and expected business
outcomes. This document will serve as the primary reference for solution design,
development, testing, implementation, user acceptance, and future system enhancements,
ensuring that the delivered solution aligns with BSTI's digital transformation objectives and
long-term organizational vision.

                                             14
```

## Page 16

```text
Challenges & Business Case
The Bangladesh Standards and Testing Institution (BSTI) manages a wide range of
regulatory, certification, laboratory, inspection, financial, and administrative functions across
multiple departments, regional offices, and laboratories. Most of these business processes
operate through independent systems or manual procedures, resulting in fragmented
information, duplicated data entry, limited process visibility, and lengthy approval cycles. The
absence of an integrated enterprise platform creates operational inefficiencies, increases
administrative workload, and makes it difficult to ensure consistent service delivery across
the organization.
As BSTI continues to expand its regulatory responsibilities and digital services, the need for
a centralized ERP solution has become increasingly critical. Existing processes involve
multiple stakeholders, extensive documentation, manual coordination, and disconnected
workflows, which often lead to delays, inconsistencies, and challenges in monitoring
organizational performance. Decision-makers also face difficulties in obtaining accurate, real-
time information due to data being distributed across different systems and manual records.
The proposed BSTI ERP Solution addresses these challenges by providing a unified
enterprise platform that integrates all major business functions into a single digital
ecosystem. The solution introduces standardized workflows, centralized master data
management, automated approvals, real-time monitoring, integrated reporting, and secure
information sharing across departments. By replacing isolated applications and paper-based
operations with a workflow-driven digital environment, the ERP system will improve
operational efficiency, strengthen governance, enhance regulatory compliance, and provide
greater transparency throughout the organization.
The business case for implementing the ERP solution is based on BSTI's long-term digital
transformation strategy, enabling the organization to modernize its internal operations while
improving service delivery to industries, businesses, government agencies, and the general
public. The integrated platform will establish a scalable foundation capable of supporting
future business growth, policy changes, new regulatory services, and emerging digital
initiatives without requiring major structural modifications.

                                               15
```

## Page 17

```text
This is the BSTI ERP Solution Architecture which shows all the ADmin,E-service and Ecommerce parts and their integration with each other.

                                                   Fig: Solution Architecture of BSTI

                                                                    16
```

## Page 18

```text
  SERVICE
                HRM & LEAVE MANAGEMENT
    01
                Human Resource Administration • Employee Lifecycle • Leave Management

Service Profile
Domain                            Service Type                   Primary Users
Human Resource Management         Internal Enterprise Service    HR • Administrators • Employees
                                                                 • Management
Core Scope                      Modules                          Features
Employee & Leave Administration
                                  11                             49

Functional Coverage
Organization                    Employee                           Identification
• Organogram                    • Employee Profile                 • Digital Id Card
• Office Management             • Employee Records                 • Unique Employee Id
• Designation Management        • PDS                              • QR Verification

Employee Administration         Workflow & Access                  Leave Management
• Office Assignment             • Employee Modification            • Leave Policy
• Designation Assignment        • Approval Workflow                • Leave Type
• Transfer & Posting            • User Roles & Permissions         • Leave Application
• Release & joining             • User Management                  • Leave Approval
                                                                   • Leave History

Module Catalogue
Sl. Module                               No. of     Sl.   Module                           No. of
No.                                     Features    No.                                   Features

 01 Organogram                             4         07   Users Module for Admin             4

 02 Employee Management                    6         08   Reset User Password for Admin      1

 03 Employee Office Management             5         09   Director General                   1

 04 ID Card Management                     8         10   Release and Assign                 4

 05 PDS (Personal Data Sheet)              4         11   Leave Management                   7

 06 Employee   Modification      with      5
    Dynamic Workflow

                                               17
```

## Page 19

```text
Service-1: HRM & Leave Management
The proposed HRM & Leave Management Solution is a fully integrated module of the BSTI
Enterprise Resource Planning (ERP) system, designed to automate and centralize all human
resource and leave management activities within a single digital platform. The solution
streamlines the complete employee lifecycle, from organizational setup and employee
onboarding to transfers, postings, leave administration, and workforce management.
The system enables efficient management of organizational structures, employee profiles,
office assignments, designations, and Personal Data Sheets (PDS) while maintaining
complete employee records and historical information. It also provides digital Employee ID
Card generation with unique employee IDs, QR code-based verification, and secure printing
capabilities to strengthen employee identification and authentication.
A configurable workflow engine supports employee information modifications, approvals,
notifications, and request tracking, ensuring transparency and accountability throughout HR
processes. Role-based access control allows administrators to manage users, assign
permissions, and maintain system security, while executive dashboards provide real-time
organizational insights for informed decision-making.
The integrated Leave Management module automates leave policy configuration, leave
applications, approval workflows, leave calendars, and leave history tracking, enabling a
transparent and efficient leave administration process. By eliminating manual operations and
paper-based records, the solution improves operational efficiency, enhances data accuracy,
strengthens governance, and supports seamless collaboration across departments. As part
of the overall BSTI ERP ecosystem, it provides a secure, scalable, and future-ready platform
that supports the organization's digital transformation objectives and long-term operational
excellence.

                                             18
```

## Page 20

```text
Figure Name: HRM & Leave Management System Diagram

                       19
```

## Page 21

```text
Module-1: Organogram (Total Feature - 4)
Features Description
1. Create Office
Allows administrators to create and maintain organizational offices, branches, and regional
units within the system.
2. Assign Office Address
Enables administrators to record and update the official address and contact information for
each office.
3. Assign Bank Advice Details
Allows configuration of office-wise bank advice information required for salary and financial
transaction processing.
4. Create Designation
Enables administrators to create and manage organizational designations and position
hierarchies.

                                     Fig: Organogram
Module-2: Employee Management (Total Feature - 6)
Features Description
1. Employee Profile Creation and Management
Allows authorized users to create, maintain, and update employee profiles containing
personal, official, and employment information.

                                             20
```

## Page 22

```text
2. Employee Search Filter
Provides search and filtering options to quickly locate employees using Employee ID, name,
designation, office, or other criteria.
3. Employee Status Tracking (Active/Inactive)
Maintains the employment status of employees, allowing users to track active, inactive,
retired, or resigned employees.
4. View Employee
Allows authorized users to view employee profile information without modification
privileges.
5. View Employee Full PDS
Provides access to the complete Personal Data Sheet (PDS) containing all employee
information and employment records.
6. Download and Print Employee PDS in BSTI Format
Enables users to download and print the approved Personal Data Sheet in the prescribed
BSTI format.

Module-3: Employee Office Management (Total Feature - 5)
Feature Description:
1. Employee Office Assign
Allows administrators to assign employees to their respective offices or organizational units.
2. Employee Designation Assign
Enables assignment of employee designations based on approved organizational structures
and positions.

                                             21
```

## Page 23

```text
3. Edit Employee Information
Allows authorized users to update employee official information while maintaining data
accuracy.
4. Transfer Employees from One Office to Another
Supports employee transfer between offices while maintaining complete transfer history.
5. Update Employee Designation
Allows authorized users to update employee designations due to promotion, transfer, or
administrative decisions.

Module-4: ID Card Management (Total Feature - 8)
Feature Description:
1. Digital Employee ID Card Generation
Automatically generates digital employee identity cards using approved employee
information.
2. Unique Employee ID Number Generation
Generates a unique identification number for each employee to ensure accurate identification.
3. Employee Photo, Designation, Department and Office Details on ID Card
Displays essential employee information, including photograph, designation, department,
and office details on the ID card.
4. QR Code Generation for Each Employee
Generates a unique QR code for every employee to support secure identity verification.

                                             22
```

## Page 24

```text
5. QR Code Scanning for Employee Verification
Allows authorized users to scan employee QR codes for quick identity verification.
6. Display Verified Employee Information After Scanning QR Code
Displays verified employee details immediately after successful QR code scanning.
7. ID Card Print and Download in PDF Format
Enables employees and administrators to print or download ID cards in PDF format.
8. ID Card Validity Date and Expiry Management
Maintains ID card validity periods and manages renewal or expiry information.

Module-5: PDS (Personal Data Sheet) (Total Feature - 4)
Feature Description
1. Online Personal Data Sheet Form Submission
Allows employees to complete and submit their Personal Data Sheet electronically through
the system.
2. Document Attachment Facility
Enables employees to upload supporting documents required for PDS verification and
approval.
3. PDS Review, Approval and Update Request Process
Supports a structured workflow for reviewing, approving, and requesting modifications to
Personal Data Sheets.

                                            23
```

## Page 25

```text
4. PDS Download and Print in Approved Format
Allows approved Personal Data Sheets to be downloaded and printed in the prescribed
organizational format.

Module-6: Employee Modification with Dynamic Workflow (Total
Feature - 5)
Features Description
1. Employee Information Modification Request Submission
Allows employees or authorized users to submit requests for updating employee information
through the system.
2. Forward, Return, Reject and Approve Options
Supports workflow actions including forwarding, returning, approving, or rejecting
modification requests.
3. Comments and Remarks During Approval Process
Allows reviewers and approvers to provide comments and remarks throughout the approval
workflow.
4. Notification to Employee and Approvers
Automatically notifies employees and approvers about request submissions, approvals,
rejections, and pending actions.
5. Pending, Approved, Rejected and Returned Request Tracking
Tracks the current status of modification requests throughout the approval process.

                                            24
```

## Page 26

```text
Module-7: Users Module for Admin (Total Feature - 4)
Features Description
1. User Role Assignment (Admin, HR, Director, Officer, Employee, etc.)
Allows administrators to assign appropriate user roles based on organizational
responsibilities.
2. Module-wise Permission Setup
Enables administrators to configure module-level access permissions for different user roles.
3. View and Edit User Accounts
Allows administrators to manage user account information, including updates and account
maintenance.

                                             25
```

## Page 27

```text
4. Search Filter
Provides search and filtering options to quickly locate user accounts using various search
criteria.
Module-8: Reset User Password for Admin (Total Feature - 1)
Features Description
1. Admin Password Reset for Any User
Allows authorized administrators to securely reset passwords for users who have forgotten
or require password recovery.
Module-9: Director General (Total Feature -1)
Feature Description
1. Director General Dashboard with Organizational Summary
Provides the Director General with a centralized dashboard displaying key organizational
statistics, employee information, and HR operational summaries.
Module-10: Release and Assign (Total Feature - 4)
Feature Description
1. Transfer, Posting, Deputation and Attachment Management
Supports the management of employee transfers, postings, deputations, and attachments
across organizational offices.
2. Release Date and Joining Date Management
Maintains employee release and joining dates to ensure accurate posting and transfer
records.
3. Assign Employee to Designation, Department, Office and Reporting Authority
Allows administrators to assign employees to appropriate designations, departments,
offices, and reporting supervisors.
4. Maintain Employee Posting and Transfer History
Maintains a complete history of employee postings, transfers, deputations, and assignments
for future reference and audit purposes.
Module-11: Leave Management (Total Feature - 7)
Feature Description
1. Employee Dashboard
Provides employees with a personalized dashboard displaying leave balances, pending
requests, approval status, upcoming holidays, and leave history.
2. Leave Calendar
Displays an organizational leave calendar showing approved leaves, public holidays,
weekends, and employee leave schedules for effective planning.
3. Create Leave
Allows administrators to create and configure different leave policies, leave rules, and leave
categories as per organizational requirements.

                                             26
```

## Page 28

```text
4. Leave Type
Enables the management of various leave types, such as Casual Leave, Sick Leave, Earned
Leave, Maternity Leave, and other organization-specific leave categories.
5. Leave Application
Allows employees to apply for leave online by selecting the leave type, duration, and
providing the necessary supporting information or documents.
6. Dynamic Approval Workflow
Supports a configurable multi-level approval workflow for leave requests based on the
organization's reporting hierarchy and approval policies.
7. Leave History Tracking
Maintains a complete record of employee leave applications, approvals, rejections,
cancellations, and leave balances for reporting and audit purposes.

                                             27
```

## Page 29

```text
  SERVICE
                PAYROLL MANAGEMENT
    02
                Salary Processing • Payroll Administration • Employee Financial Benefits

Service Profile
Domain                              Service Type                   Primary Users
Payroll & Employee Benefits         Internal Enterprise Service    HR • Payroll        •   Finance   •
                                                                   Employees
Core Scope                          Modules                        Features
Salary,  Benefits     &   Payroll
Accounting
                                    15                             84

Functional Coverage
SALARY                           BENEFITS                            TAX & ACCOUNTING
• Earnings & Deductions          • Bonus                             • Income Tax Statement
• Pay Scale                      • Bank Advice                       • Journal Voucher
• Salary Fixation                • Salary Certification              • Payroll Accounts
• Salary Processing              • Payslip

EMPLOYEE FINANCE                 CONTROL                             OUTPUT
• Loan Management                • Salary Month Lock                 • Salary Sheets
• GPF Management                 • Payroll Controls                  • Certificates
                                                                     • Statements
                                                                     • Payslips

Module Catalogue
Sl. Module                                 No. of  Sl. Module                                 No. of
No.                                       Features No.                                       Features
 01 Regular         Salary            –      6        07   Top Sheet (Salary/Bonus)             2
    Earnings/Deductions
 02 Payroll Pay Scale                        2        08   Salary Certification                 6
 03 Salary Fixation                          5        09   Income Tax Statement                 8
 04 Salary Process                           4        10   Journal Voucher                      9
 05 Bonus Process                            1        11   Payroll Accounts                     2
 06 Bank Advice (Salary/Bonus)               3        12   Salary Month Lock                    1

                                                 28
```

## Page 30

```text
Service-2: Payroll Management
The proposed Payroll Management Solution is a comprehensive module of the BSTI
Enterprise Resource Planning (ERP) system, designed to automate and streamline end-to-
end payroll operations through a centralized, secure, and workflow-driven platform. The
solution manages the complete payroll lifecycle, including salary structure configuration, pay
scale management, salary fixation, payroll processing, bonus management, and employee
financial records while ensuring compliance with organizational policies and government
regulations.
The system supports flexible configuration of earnings, deductions, allowances, payroll
heads, and calculation rules, enabling accurate salary processing for individual employees
and offices. It also automates the generation of bank advice, salary sheets, payslips, salary
certificates, income tax statements, and journal vouchers with integrated approval
workflows, digital authorization, and comprehensive reporting capabilities.
An integrated payroll accounts module securely maintains employee banking and payroll-
related information, while salary month locking prevents unauthorized modifications after
payroll completion, ensuring data integrity and financial accuracy. The solution also includes
a robust Loan Management module that supports eligibility verification, loan application
processing, multi-level approvals, disbursement, repayment scheduling, payroll-based
installment deductions, loan statements, audit trails, and analytical reporting.
By integrating payroll, taxation, accounting, banking, and loan management into a single
platform, the solution eliminates manual processing, improves payroll accuracy, strengthens
financial governance, and enhances operational efficiency. As part of the BSTI ERP
ecosystem, it provides a scalable, transparent, and future-ready payroll management
platform that supports digital transformation, regulatory compliance, and efficient financial
administration across the organization.

                                              29
```

## Page 31

```text
Figure Name: Payroll Management

              30
```

## Page 32

```text
Module-1: Regular Salary – Earnings/Deductions (Total Feature - 6)
Features Description
1. Create & Manage Salary Heads
Allows administrators to create, update, and manage salary components such as earnings
and deductions used in payroll processing.
2. Earnings & Deductions Setup
Enables configuration of various earning and deduction components according to
organizational payroll policies.
3. Payroll Head Configuration
Allows administrators to configure payroll heads and define their calculation methods and
applicable rules.
4. Fixed & Percentage Calculation
Supports salary components calculated as fixed amounts or percentages based on
predefined payroll rules.
5. Allowance Configuration Setup
Enables the creation and management of different allowance types applicable to employees
based on organizational policies.
6. Deduction Configuration Setup
Allows administrators to configure statutory and organizational deductions such as tax,
provident fund, and loan deductions.
Module-2: Payroll Pay Scale (Total Feature - 2)
Features Description
1. Pay Scale Management
Enables administrators to create, maintain, and update government-approved pay scales,
grades, and salary structures.
2. Pay Scale Selection from Dropdown
Allows users to select the appropriate pay scale from a predefined dropdown list during
employee salary configuration.
Module-3: Salary Fixation (Total Feature - 5)
Features Description
1. Employee Salary Fixation
Enables administrators to assign and fix an employee's salary based on the approved pay
scale, grade, and applicable allowances.
2. Salary Fixation Update
Allows authorized users to revise employee salary fixation due to promotion, increment, or
policy changes while maintaining history.

                                             31
```

## Page 33

```text
3. Common Head Implementation for All Employees
Provides the facility to apply common salary heads and payroll components across all
employees to ensure uniform payroll processing.
4. Office-wise Search Filter
Allows users to search and filter salary fixation records based on office or organizational unit
for efficient management.
5. Employee Search Option
Provides a search facility to quickly locate employee salary fixation records using employee
ID, name, or other search criteria.
Module-4: Salary Process (Total Feature - 4)
Features Description
1. Office-wise Salary Processing
Enables authorized users to process monthly salaries for all employees within a selected
office in a single operation based on approved payroll data.
2. Individual Salary Processing
Allows salary processing for individual employees to accommodate corrections,
adjustments, or special payroll requirements.
3. Employee Search Filter
Provides a search facility to locate employees using Employee ID, name, designation, or other
predefined search criteria during salary processing.
4. Status-wise Search Filter
Allows users to filter salary records based on processing status, such as Pending, Processed,
Approved, or Locked, for efficient payroll management.
Module-5: Bonus Process (Total Feature - 1)
Feature Description
1. Office-wise Bonus Processing
Enables authorized users to calculate and process bonus payments for all eligible employees
within a selected office based on predefined bonus policies.
Module-6: Bank Advice (Salary/Bonus) (Total Feature - 3)
Features Description
1. Employee Bank Information Import
Allows the system to import employee bank account details required for salary and bonus
disbursement through electronic bank transfer.
2. Regional Office Bank Advice Format
Generates bank advice in the prescribed format required by regional offices to facilitate salary
and bonus payment processing.

                                              32
```

## Page 34

```text
3. Office-wise Bank Advice Generation
Enables the generation of office-specific bank advice containing employee payment details
for submission to the designated bank.
Module-7: Top Sheet (Salary/Bonus) (Total Feature - 2)
Features Description
1. Office-wise Salary Sheet for Employees
Generates office-wise salary and bonus top sheets containing employee-wise payment
details for review, approval, and financial processing.
2. Office-wise Format Implementation
Supports predefined office-specific top sheet formats to ensure compliance with
organizational and government reporting requirements.
Module-8: Salary Certification (Total Feature - 6)
Features Description
1. Salary Certificate Application
Allows employees to submit requests for salary certificates through the system for official
purposes.
2. Salary Certificate Approval Workflow
Supports a multi-level approval process to review and authorize salary certificate requests
before issuance.
3. Salary Certificate Generation
Automatically generates salary certificates using approved employee payroll information
and predefined templates.
4. Digital Signature & Authorized Approval
Enables authorized officials to digitally sign and approve salary certificates for official use.
5. Download & Print Salary Certificate
Allows employees to securely download and print approved salary certificates from the
employee portal.
6. Salary Certificate History & Reports
Maintains a history of issued salary certificates and generates reports for monitoring and
audit purposes.
Module-9: Income Tax Statement (Total Feature - 8)
Features Description
1. Annual Income Tax Statement Generation
Automatically generates annual income tax statements based on employee earnings and
deductions for the selected financial year.
2. Income & Tax Deduction Summary
Provides a consolidated summary of employee income, taxable earnings, and tax deductions
for reporting purposes.

                                               33
```

## Page 35

```text
3. Tax Calculation Based on Government Tax Rules
Calculates income tax according to the applicable government tax regulations and approved
tax slabs.
4. Financial Year-wise Tax Statement
Generates income tax statements separately for each financial year to support tax filing and
record management.
5. Employee Tax Statement Download
Allows employees to securely view and download their income tax statements from the
employee portal.
6. Tax Statement Approval
Supports the review and approval of generated tax statements by authorized officials before
issuance.
7. Income Tax Reports
Generates comprehensive income tax reports for employees, departments, and
organizational reporting requirements.
8. Tax Statement History
Maintains historical records of employee income tax statements for future reference,
compliance, and audit purposes.
Module-10: Journal Voucher (Total Feature - 9)
Features Description
1. Journal Voucher Generation
Automatically generates journal vouchers from payroll transactions for financial accounting
and record-keeping.
2. Automatic Payroll Journal Voucher
Creates payroll-related journal vouchers automatically after successful salary processing,
reducing manual accounting effort.
3. Chart of Accounts Mapping
Maps payroll transactions to the appropriate Chart of Accounts (COA) to ensure accurate
financial posting.
4. Voucher Approval Workflow
Supports a configurable approval workflow for reviewing and authorizing journal vouchers
before posting.
5. Voucher Posting to Accounts
Allows approved journal vouchers to be posted to the accounting system for financial
reconciliation and reporting.
6. Voucher Search & View
Provides search and filtering options to quickly locate and review journal vouchers using
various criteria.

                                            34
```

## Page 36

```text
7. Journal Voucher Printing/PDF
Enables users to generate and print journal vouchers or export them in PDF format for official
documentation.
8. Journal Voucher Reports
Generates reports on journal vouchers, including posting status, transaction summaries, and
financial records.
9. Journal Voucher Audit Trail
Maintains a complete history of journal voucher creation, approval, modification, and posting
activities to support audit and compliance requirements.
Module-11: Payroll Accounts (Total Feature - 2)
Features Description
1. Bank Account Details Entry for Employee
Allows authorized users to record and maintain employee bank account information required
for salary, bonus, and other payroll-related payments.
2. Employee Payroll Account Information Management
Enables administrators to maintain employee payroll-related information, including Bank
Account Number, TIN, GPF details, and other financial records required for payroll
processing.
Module-12: Salary Month Lock (Total Feature - 1)
Features Description
1. Lock Processed Salary Month
Allows authorized users to lock a processed payroll month to prevent further modifications,
ensuring payroll accuracy and maintaining financial integrity.
Module-13: Download Payslip (Total Feature - 1)
Features Description
13.1 Office-wise Salary Sheet Download
Enables authorized users to download office-wise salary sheets and payslips in the
prescribed format for record-keeping and distribution.
Module-14: Loan Management (Total Feature - 22)
Features Description
1. Employee Loan Eligibility Verification
Automatically verifies employee loan eligibility based on organizational policies, savings
balance, salary criteria, age, and other predefined conditions.
2. Loan Application Submission
Allows eligible employees to apply for loans electronically by submitting the required
information through the employee portal.

                                              35
```

## Page 37

```text
3. Loan Application Validation
Validates loan application details against predefined eligibility rules before forwarding the
application for approval.
4. Loan Application Status Tracking
Provides employees with real-time visibility into the current status of their loan applications
throughout the approval process.
5. Multi-Level Loan Approval Workflow
Supports a configurable multi-level approval process to review, approve, reject, or return
loan applications.
6. Loan Approval and Rejection Management
Allows authorized officials to approve or reject loan applications with remarks based on
organizational loan policies.
7. Loan Voucher Generation
Automatically generates a loan voucher after successful approval of the loan application for
financial processing.
8. Voucher Forwarding to Accounts
Forwards the approved loan voucher to the Accounts section for verification and loan
disbursement processing.
9. Accounts Verification
Enables the Accounts section to verify approved loan vouchers before releasing the loan
amount.
10. Loan Disbursement Management
Processes approved loans and facilitates the disbursement of loan amounts to the
employee's registered bank account.
11. Loan Repayment Schedule Management
Automatically generates the loan repayment schedule, including installment amount,
repayment period, and due dates.
12. Loan Installment Deduction Management
Supports automatic deduction of loan installments from the employee's monthly salary
based on the approved repayment schedule.
13. Payroll Integration for Loan Deduction
Integrates loan deductions with the payroll system to ensure accurate salary calculation and
payment processing.
14. Separate Loan Payslip Generation
Generates a dedicated loan payslip showing loan disbursement and repayment details
separately from the regular salary payslip.
15. Employee Loan Dashboard
Provides employees with a centralized dashboard displaying loan details, outstanding
balance, repayment schedule, and current loan status.

                                              36
```

## Page 38

```text
16. Loan Statement Management
Allows employees to view and download detailed loan statements, including repayment
history and outstanding balances.
17. Loan Transaction History
Maintains a complete record of all loan-related transactions, including disbursements,
repayments, and adjustments.
18. Loan Rules and Policy Configuration
Allows administrators to configure loan eligibility rules, loan limits, repayment policies, and
other organizational loan settings.
19. Education Loan Validation
Validates education loan applications by ensuring eligibility criteria, including the
beneficiary's age, comply with organizational policies.
20. Savings-Based Loan Eligibility and Calculation
Automatically calculates the maximum eligible loan amount based on the employee's
savings balance and applicable loan policies.
21. Loan Reports and Analytics
Generates comprehensive reports on loan applications, approvals, disbursements,
repayments, outstanding balances, and loan utilization.
22. Loan Audit Trail and Activity Log
Maintains a complete audit trail of all loan-related activities, including applications,
approvals, disbursements, repayments, and user actions for compliance and accountability.

Module-15: GPF (General Provident Fund)(Total Feature-12)
Features Description
1. GPF Account Setup
Creates and maintains employee-wise GPF accounts with essential account information.
2. Opening Balance Entry
Records the opening GPF balance for employees during account initialization or migration.
3. Monthly GPF Deduction Setup
Configures employee-wise monthly GPF subscription amounts for payroll processing.
4. Automatic GPF Deduction from Payroll
Automatically deducts the configured GPF contribution from employee salaries during
payroll processing.
5. GPF Advance Application
Allows employees to submit applications for GPF advances through the system.
6. GPF Advance Approval
Supports the review, approval, or rejection of GPF advance applications through the
defined workflow.

                                              37
```

## Page 39

```text
7. Advance Recovery Management
Manages the recovery of approved GPF advances through scheduled payroll deductions.
8. GPF Withdrawal Management
Facilitates the application, approval, and processing of eligible partial or final GPF
withdrawals.
9. Annual Interest Calculation
Automatically calculates and applies annual interest on employee GPF balances based on
the configured rate.
10. Employee GPF Ledger
Maintains a detailed ledger of all GPF transactions, including contributions, advances,
recoveries, withdrawals, and interest.
11. GPF Statement Generation
Generates employee-wise GPF statements showing contributions, interest, withdrawals,
recoveries, and current balance.
12. Final GPF Settlement
Processes the final settlement of GPF accounts upon retirement, resignation, or other
eligible separation cases.

                                              38
```

## Page 40

```text
  SERVICE
                FINANCE & ACCOUNTS MANAGEMENT
    03
                Budgeting • Revenue & Expenditure • Accounting • Financial Control

Service Profile
Domain                             Service Type                  Primary Users
Finance & Accounts                 Internal Enterprise Service   Finance • Accounts • Authorized
                                                                 Management
Core Scope                      Modules                          Features
End-to-End Financial Management
                                   10                            57

Functional Coverage
BUDGET                           REVENUE & EXPENSE                ACCOUNTING
• Budget Creation & Allocation   • Income Management              • Ledger & Accounting
• Budget Distribution            • Expense Management             • Voucher Management
• Budget Control                 • Collection Tracking            • Chart of Accounts

PAYMENT & PAYROLL                REPORTING                        CONTROL & AUDIT
• Payment Gateway                • Income Reports                 • Role-Based Access
• Payroll Integration            • Expense Reports                • Approval
                                 • Budget Utilization             • Audit Trail
                                 • Ledger & Trial Balance         • Activity History

Module Catalogue
Sl. Module                               No. of  Sl. Module                                No. of
No.                                     Features No.                                      Features
 01 Budget Management Module               7        06   Chart of Accounts                   5
 02 Income Management                      5        07   Payment Gateway                     6
 03 Expense Management                     6        08   Payroll Integration                 8
 04 Ledger & Accounting                    5        09   Reporting System                    4
 05 Voucher Management Module              5        10   Role-Based Access Control &         6
                                                         Audit

                                               39
```

## Page 41

```text
Service-3: Finance & Accounts Management
This document outlines the proposed Finance & Accounts Management System for the
Bangladesh Technical Framework (BTF). It defines the functional scope and key business
capabilities required to establish a centralized, transparent, and efficient financial
management platform.
The proposed solution covers the end-to-end financial management process, including
budgeting, income and expense management, accounting, payment processing, payroll
integration, reporting, and access control. The following sections describe the functional
scope and implementation requirements of each module in detail.

                                           40
```

## Page 42

```text
Figure Name: Workflow of Finance & Account Management Service

                             41
```

## Page 43

```text
Module - 1: Budget Management Module (Total Feature - 7)
The Budget Management Module is designed to facilitate annual budget planning, allocation,
approval, utilization monitoring, and budget control. It ensures efficient financial planning,
prevents overspending, and supports transparent budget management across the
organization.
This module enables finance personnel to prepare annual budgets, allocate funds to different
offices, monitor budget utilization, control expenditures within approved limits, and maintain
budget revision history. The module supports structured financial planning and strengthens
budget governance.
Features Description
1. Budget Creation & Allocation
Allows authorized users to create annual budgets and allocate funds to different offices,
departments, or activities based on approved financial plans.
2. Office-wise Budget Distribution
Enables budget allocation and distribution to individual offices according to approved budget
limits.
3. Budget Approval Workflow
Supports a multi-level approval process for budget creation, allocation, and revision before
implementation.
4. Remaining Budget Tracking
Provides real-time tracking of available and utilized budgets to monitor remaining funds
throughout the fiscal year.
5. Over Budget Control
Prevents transactions that exceed the approved budget limit unless authorized by
designated officials.
6. Fiscal Year Budget Setup
Allows administrators to configure budgets for each fiscal year based on organizational
financial policies.
7. Budget Adjustment & History Logs
Maintains records of budget revisions, reallocations, and adjustment history for transparency
and audit purposes.

Module 2: Income Management (Total Feature - 5)
The Income Management Module is designed to manage organizational revenue collection,
accurately record income transactions, generate official receipts, and ensure proper
accounting of all income sources. This module centralizes all revenue collection activities,
including licence fees, testing fees, certification fees, and other income sources. It ensures
accurate recording, approval, receipt generation, and financial reporting of revenue
transactions.

                                             42
```

## Page 44

```text
Features Description
1. License, Testing & Certification Fee Collection
Records revenue collected from licensing, testing, certification, and other BSTI services.
2. Revenue Entry & Approval
Allows authorized users to record revenue transactions and process them through
an approval workflow.
3. Money Receipt & Income Voucher Generation
Automatically generates money receipts and income vouchers for completed revenue
transactions.
4. Daily Collection Report
Generates daily reports summarizing income collected from all offices and service categories.
5. Office-wise Revenue Tracking
Tracks revenue collection separately for each office to support financial monitoring and
reporting.
Module-3: Expense Management (Total Feature - 6)
The Expense Management Module is designed to manage organizational expenses through
a structured approval process while ensuring that expenditures remain within the approved
budget limits. This module enables finance personnel to record expenses, upload supporting
documents, validate available budgets, generate expense vouchers, and automatically
update the remaining budget after approved transactions.
Features Description
1. Expense Entry & Approval
Allows authorized users to record expenses and submit them through the approval
workflow.
2. Budget Validation
Verifies expense requests against the available approved budget before processing.
3. Over Expense Blocking
Restricts expense transactions that exceed the approved budget allocation.
4. Bill/Document Upload
Enables users to upload bills, invoices, and supporting documents for expense
verification.
5. Expense Voucher Generation
Automatically generates expense vouchers after successful approval of expense
transactions.
6. Remaining Budget Auto Update
Automatically updates the remaining budget after approved expenses are
processed.

                                              43
```

## Page 45

```text
Module - 4: Ledger & Accounting (Total Feature - 5)
The Ledger & Accounting Module is designed to maintain accurate accounting records and
ensure proper financial transaction management.         This module records all financial
transactions, maintains general ledger accounts, manages cash and bank books, processes
journal entries, and generates trial balance reports.
Features Description
1. General Ledger
Maintains all financial transactions in the General Ledger for accurate accounting
and financial reporting.
2. Cash Book & Bank Book
Records cash and bank transactions separately to support daily financial operations
and reconciliation.
3. Journal Entry & Transaction Posting
Allows authorized users to create journal entries and post financial transactions to
the ledger.
4. Opening & Closing Balance Setup
Maintains opening and closing balances for each financial period to ensure accurate
accounting records.
5. Trial Balance Generation
Generates trial balance reports to verify the accuracy of financial transactions and
ledger balances.
Module - 5: Voucher Management Module (Total Feature - 5)
The Voucher Management Module is designed to manage financial vouchers through
standardized workflows and approval processes.
This module manages payment, receipt, journal, and contra vouchers with automatic
numbering, approval workflow, document attachment, and printing facilities.
Features Description
1. Payment / Receive / Journal / Contra Voucher
Supports the creation and management of payment, receipt, journal, and contra
vouchers for financial transactions.
2. Auto Voucher Number Generation
Automatically generates unique voucher numbers for every financial transaction.
3. Voucher Approval Workflow
Supports a configurable approval process for reviewing and approving vouchers
before posting.
4. Attachment Support

                                              44
```

## Page 46

```text
Allows users to attach bills, invoices, and supporting documents to vouchers for
verification.
5. Print & Download Option
Enables users to print or download approved vouchers in PDF format for official
records.
Module - 6: Chart of Accounts (Total Feature - 5)
The Chart of Accounts Module is designed to maintain a standardized financial account
structure for accurate accounting and reporting.
This module allows administrators to define account heads, organize hierarchical account
structures, and map accounts to the general ledger.
Features Description
1. Account Head Management
Allows administrators to create, update, and manage financial account heads used
in accounting transactions.
2. Parent & Child Account Structure
Supports hierarchical account structures by maintaining parent and child account
relationships.
3. Income / Expense / Asset / Liability Setup
Allows configuration of account categories based on standard accounting
classifications.
4. Auto Account Code Generation
Automatically generates unique account codes for newly created account heads.
5. General Ledger Mapping
Maps account heads to the General Ledger for accurate financial transaction
posting.

Module - 7: Payment Gateway (Total Feature - 6)
The Payment Gateway Module is designed to integrate online banking services for secure
and efficient payment processing. This module supports bank integration, online payment
processing, payment verification, reconciliation, and collection tracking.
Features Description
1. Manage Bank Payment (Sonali Bank)
Supports integration with Sonali Bank for secure processing of financial transactions.
2. Transactions
Records and manages all online payment transactions processed through the
payment gateway.
3. Online Payment Gateway

                                              45
```

## Page 47

```text
Enables secure online payment collection through integrated payment gateway
services.
4. Payment Verification
Verifies successful payment transactions before updating financial records.
5. Reconciliation
Performs reconciliation between payment gateway transactions and accounting
records.
6. Collection Tracking
Tracks payment collections and transaction status for financial monitoring and
reporting.
Module - 8: Payroll Integration (Total Feature - 8)
The Payroll Integration Module is designed to integrate payroll operations with the financial
accounting system. This module synchronizes salary, bonuses, deductions, pension, and GPF
information with financial records to ensure accurate payroll accounting.
Features Description
1. Salary Integration
Integrates payroll salary transactions with the financial accounting system.
2. Bonus Management Integration
Synchronizes employee bonus transactions with the accounting module.
3. Deduction Management Integration
Transfers payroll deductions to the accounting system for accurate financial
recording.
4. GPF Management Integration
Integrates General Provident Fund (GPF) transactions with the finance module.
5. Pension Management Integration
Supports integration of pension-related financial transactions with accounting
records.
6. Payroll Financial Posting
Automatically posts payroll transactions to the appropriate accounting ledgers.
7. Payroll Accounting Verification
Allows verification of payroll accounting entries before final posting to financial
records.
8. Payroll Reconciliation & Reporting
Generates payroll reconciliation reports to verify payroll transactions and financial
balances.

                                             46
```

## Page 48

```text
Module - 9: Reporting System (Total Feature - 4)
Feature Description
1. Income Report
Generates detailed reports on revenue collected from various organizational
services.
2. Expense Report
Provides reports summarizing approved expenses across offices and departments.
3. Budget Utilization Report
Displays allocated, utilized, and remaining budget information for effective financial
monitoring.
4. Ledger & Trial Balance Report
Generates General Ledger and Trial Balance reports to support financial analysis
and auditing.
Module - 10: Role-Based Access Control & Audit (Total Feature - 6)
Feature Description
1. Role-Based Access Control
Provides system access based on user roles and assigned responsibilities.
2. User Permission Management
Allows administrators to configure module-wise permissions for different user roles.
3. Multi-Level Approval System
Supports configurable multi-level approval workflows for financial transactions and
documents.
4. Audit Trail & Activity Logs
Maintains a complete history of user activities, approvals, and financial transactions
for audit purposes.
5. Login History & IP Tracking
Records user login history, login timestamps, and IP addresses to enhance system
security.
6. Data Change History
Tracks all data modifications, including previous and updated values, to ensure
accountability and compliance.

                                          47
```

## Page 49

```text
  SERVICE
                CASE MANAGEMENT SYSTEM
    04
                Case Registration • Investigation • Hearing • Decision & Closure

Service Profile
Domain                             Service Type                   Primary Users
Regulatory /          Legal   Case Internal Enterprise Service    Case Officers • Authorized
Management                                                        Officials • Management
Core Scope                          Modules                       Features
End-to-End Case Lifecycle
                                    8                             34

Functional Coverage
CASE INTAKE                      INVESTIGATION                      HEARING & DECISION
• Case Registration              • Investigation Management         • Hearing & Court
• Case Review                    • Evidence & Findings              • Approval Management
• Assignment

PENALTY                          CLOSURE                            REPORTING
• Fine Calculation               • Case Disposal                    • Notifications
• Penalty Recording              • Disposal Report                  • Case Reports
• Payment Verification           • Archive                          • Dashboard

Module Catalogue
Sl. Module                               No. of  Sl. Module                              No. of
No.                                     Features No.                                    Features
 01 Case Registration                        5        05   Approval Management              4
 02 Case Review & Assignment                 4        06   Fine & Penalty Management        4
 03 Investigation Management                 4        07   Case Closure                     4
 04 Hearing & Court Management               4        08   Notification & Reporting         5

                                                 48
```

## Page 50

```text
Service-4: Case Management System
The Case Management System is a comprehensive digital solution designed to manage the
complete lifecycle of regulatory and legal cases initiated by BSTI, from case registration to
final disposal. The system enables authorized officials to register cases by capturing
complainant details, accused information, offence details, applicable laws, evidence, and
supporting documents. Each case is assigned a unique Case ID to ensure traceability and
efficient monitoring throughout its lifecycle. Authorized officers can assign cases to
investigators or responsible officials, schedule hearings, maintain investigation records,
upload evidence, and record legal proceedings. The system supports hearing management,
court order recording, penalty and fine management, imprisonment records, and case status
tracking. Workflow-based approvals ensure that case-related activities are reviewed and
approved by designated authorities before progressing to the next stage. Automated
notifications keep concerned stakeholders informed regarding hearing schedules, document
submissions, approvals, and final decisions. Comprehensive reporting and dashboard
facilities provide real-time insights into pending, ongoing, and disposed cases for effective
monitoring and decision-making. Role-based access control ensures secure access for
investigators, legal officers, magistrates, directors, and administrators while maintaining
complete audit trails of all activities. The system improves transparency, accountability,
operational efficiency, and compliance by replacing manual case handling with a centralized,
secure, and fully digital case management platform.

                                             49
```

## Page 51

```text
Figure Name: Workflow of Case Management Service

                      50
```

## Page 52

```text
Module-1: Case Registration (Total Feature - 5)
Feature Description
1. Online Case Registration
Allows authorized users to register new cases by entering all required case information
through the system.
2. Case Information Entry
Captures case details including case type, offence, location, and case description.
3. Complainant & Accused Information
Allows recording of complainant and accused details along with contact information.
4. Supporting Document Upload
Allows users to upload supporting documents, images, and evidence related to the case.
5. Auto Case ID Generation
Automatically generates a unique Case ID for tracking and future reference.
Module-2: Case Review & Assignment (Total Feature - 4)
Feature Description
1. Case Review
Allows designated officers to review newly registered cases.
2. Case Assignment
Enables supervisors to assign cases to responsible officers or investigators.
3. Workflow Remarks
Allows officers to provide remarks while forwarding cases.
4. Return for Correction
Allows reviewers to return incomplete cases for correction.
Module-3: Investigation Management (Total Feature - 4)
Feature Description
1. Investigation Scheduling
Allows investigators to schedule investigation activities.
2. Investigation Findings
Records investigation observations and findings.
3. Evidence Upload
Allows investigators to upload additional evidence and supporting documents.
4. Investigation Report
Enables preparation and submission of investigation reports.
Module-4: Hearing & Court Management (Total Feature - 4)
Feature Description
1. Hearing Schedule
Allows hearing dates to be scheduled for registered cases.

                                              51
```

## Page 53

```text
2. Hearing Proceedings
Records hearing discussions and proceedings.
3. Court Order Entry
Allows recording of court orders and legal decisions.
4. Hearing Remarks
Provides an option to record additional hearing observations.
Module-5: Approval Management (Total Feature - 4)
Feature Description
1. Case Verification
Allows authorized officers to verify investigation reports and supporting documents.
2. Approval
Enables designated authorities to approve case decisions.
3. Rejection
Allows authorized officers to reject cases with appropriate reasons.
4. Re-Investigation Request
Allows returning cases for additional investigation when required.
Module-6: Fine & Penalty Management (Total Feature - 4)
Feature Description
1. Fine Calculation
Allows recording of imposed fines and penalties.
2. Fine Payment Tracking
Tracks payment status of imposed fines.
3. Penalty Recording
Maintains records of penalties and imprisonment, if applicable.
4. Payment Verification
Verifies successful payment before case closure.
Module-7: Case Closure (Total Feature - 4)
Feature Description
1. Case Disposal
Allows authorized officers to close completed cases.
2. Disposal Report
Generates the final case disposal report.
3. Case Status Tracking
Tracks the current status of every case throughout its lifecycle.
4. Archive Case
Moves completed cases into the archive for future reference.

                                              52
```

## Page 54

```text
Module-8: Notification & Reporting (Total Feature - 5)
Feature Description
1. Email Notification
Sends email notifications regarding case progress and decisions.
2. SMS Notification
Provides SMS alerts for important workflow activities.
3. Status Update Notification
Automatically informs users whenever the case status changes.
4. Case Reports
Generates case-wise, officer-wise, and status-wise reports.
5. Dashboard
Displays real-time case statistics, pending cases, disposed cases, and performance
summaries.

                                            53
```

## Page 55

```text
  SERVICE
                   CM MANDATORY NEW CERTIFICATION
    05
                   Certification Application • Inspection • Verification • CM Certification

Service Profile
Domain                                Service Type               Primary Users
Certification of Marks (CM)           Regulatory / Certification Applicants    •   Reviewers     •
                                      Service                    Inspectors • AD • DD • Director •
                                                                 System Admin
Core Scope                            Modules                       Features
Mandatory CM Certification
                                      12                            46

Functional Coverage
APPLICATION                         REVIEW                            INSPECTION
• Online Application                • Application Review              • Inspector Assignment
• Document Upload                   • Shortfall Identification        • Inspection Scheduling
• Application Fee                   • Correction & Resubmission       • Inspection & Report
• Application ID

VERIFICATION                        CERTIFICATION                     CONTROL
• AD/DD Verification                • Registration Completion         • Re-inspection
• Director Decision                 • CM Certificate Generation       • Notifications
• Approval / Rejection              • Download                        • User & Role Management

Module Catalogue
Sl. Module                                  No. of  Sl. Module                                 No. of
No.                                        Features No.                                       Features
 01 Application Submission                     4        07   Director Decision                   3
 02 Application Review & Shortfall             5        08   Certification Complete              3
    Management
 03 Payment Processing                         4        09   Rejection Management                3
 04 Inspection Setup                           3        10   Notification Management             3
 05 Inspection & Report                        5        11   Re-Inspection Management            3
 06 Verification Module (AD/DD)                3        12   User & Role Management              7

                                                   54
```

## Page 56

```text
Service-05: CM Mandatory New Certification
The CM Mandatory New Certification Management System consists of 12 functional
modules with a total of 46 key features, designed to automate the complete certification
lifecycle from application submission to certificate issuance.
The solution enables applicants to submit applications online, upload required documents,
pay application fees, and receive automatically generated application IDs. Applications are
reviewed through a structured shortfall management process, allowing reviewers to identify
deficiencies, request additional documents, and manage correction and resubmission cycles
while keeping applicants informed through automated notifications.
The system supports secure payment processing with fee collection, verification, and
automatic status updates. Inspection activities are managed through inspector assignment,
scheduling, physical inspections, report preparation, photo uploads, and remark recording.
Inspection reports are then verified by the Assistant Director (AD) and Deputy Director (DD)
before being forwarded to the Director for the final approval, rejection, or re-inspection
decision.
Upon approval, the system completes the registration process, generates the CM Certificate,
and provides applicants with a downloadable certificate. In case of rejection, automated
rejection letters are issued along with notifications and product quality improvement
guidance. The solution also includes integrated notification management through email and
SMS, re-inspection workflow management, and comprehensive role-based access control
for Applicants, Reviewers, Inspectors, ADs, DDs, Directors, and System Administrators.

                                              55
```

## Page 57

```text
Figure Name: Workflow of CM Mandatory New Certification Service

                              56
```

## Page 58

```text
Module-1. Application Submission (Total Feature - 4)
Features Description
1. Online Application Submission
Allows applicants to submit Certification Mark (CM) applications electronically through the
online portal. The system validates mandatory information before accepting the application
for processing.
2. Document Upload
Enables applicants to upload all required supporting documents in approved formats. Each
document is securely stored and linked to the corresponding application.
3. Application Fee Payment
Allows applicants to pay the prescribed application fee through the integrated payment
gateway. Payment information is automatically recorded and associated with the application.
4. Auto Application ID Generation
Automatically generates a unique Application ID upon successful submission. The ID is used
for application tracking and future correspondence.
Module-2. Application Review & Shortfall Management (Total Feature
- 5)
Features Description
1. Application Review
Allows authorized officers to review submitted applications and verify the completeness of
the provided information and supporting documents.
2. Shortfall Identification
Enables reviewers to identify missing documents, incorrect information, or compliance gaps
during the application assessment process.
3. Required Document Request
Allows reviewers to request additional documents or information from applicants whenever
necessary. All requests are recorded within the application history.
4. Shortfall Correction & Resubmission Loop
Enables applicants to correct identified shortfalls and resubmit the application. The workflow
supports multiple review and correction cycles until all requirements are fulfilled.
5. Applicant Notification
Automatically notifies applicants regarding application review results, shortfall requests, and
resubmission status through the notification system.
Module-3. Payment Processing (Total Feature - 4)
Features Description
1. Fee Display
Displays applicable fees dynamically based on the selected service and predefined fee
configuration.

                                              57
```

## Page 59

```text
2. Payment Collection
Collects application fees securely through the integrated online payment gateway while
maintaining complete transaction records.
3. Payment Verification
Verifies payment transactions automatically or through authorized verification before
allowing the application to proceed.
4. Automatic Status Update
Automatically updates the application status once the payment is successfully verified,
ensuring smooth workflow progression.
Module-4. Inspection Setup (Total Feature - 3)
Features Description
1. Inspector Assignment
Allows authorized officials to assign qualified inspectors based on workload, expertise, or
geographical jurisdiction.
2. Inspection Scheduling
Enables inspection schedules to be created based on inspector availability and organizational
requirements.
3. Inspection Date/Time/Location Setup
Allows authorized users to define and approve the inspection date, time, and inspection
location before the inspection is conducted.
Module-5. Inspection & Report (Total Feature - 5)
Features Description
1. Physical Inspection
Allows inspectors to conduct on-site inspections according to approved standards,
guidelines, and regulatory requirements.
2. Inspection Findings
Records inspection observations, compliance status, and identified non-conformities during
the inspection process.
3. Report Preparation
Enables inspectors to prepare structured inspection reports based on field observations and
collected evidence.
4. Photo Upload
Allows inspectors to upload photographs as supporting evidence for inspection findings and
compliance verification.
5. Remarks Entry
Provides inspectors with the option to record additional comments, recommendations, or
observations related to the inspection.

                                               58
```

## Page 60

```text
Module-6. Verification Module (AD/DD) (Total Feature - 3)
Features Description
1. Inspection Report Review
Allows the Assistant Director (AD) and Deputy Director (DD) to review submitted inspection
reports for completeness and compliance.
2. Verification
Enables authorized officers to verify inspection findings before forwarding the application for
the Director's decision.
3. Comments & Feedback
Allows reviewers to provide comments, recommendations, or clarification requests during
the verification process.
Module-7. Director Decision (Total Feature - 3)
Features Description
1. Approval
Allows the Director to approve applications that fully satisfy all regulatory and inspection
requirements.
2. Rejection
Allows the Director to reject applications with documented reasons whenever required
compliance criteria are not met.
3. Re-Inspection Decision
Enables the Director to request a re-inspection if additional verification is required before
making the final decision.
Module-8. Certification Complete (Total Feature - 3)
Features Description
1. Registration Completion
Finalizes the Certification Mark (CM) registration process after successful verification and
approval.
2. CM Certificate Generation
Automatically generates the official Certification Mark (CM) Certificate using the approved
application information.
3. Download Link
Provides applicants with secure access to download the issued CM Certificate directly from
the system.
Module-9. Rejection Management (Total Feature - 3)
Features Description
1. Rejection Letter Generation
Automatically generates a formal rejection letter including the reasons for rejection and
applicable recommendations.

                                              59
```

## Page 61

```text
2. Applicant Notification
Notifies applicants immediately after the rejection decision through email, SMS, or in-system
notifications.
3. Product Quality Improvement Process
Allows applicants to review identified quality issues, implement corrective actions, and
improve product compliance before submitting a new application.
Module-10. Notification Management (Total Feature - 3)
Features Description
1. Email Notification
Automatically sends email notifications for application events, approvals, inspections, and
workflow updates.
2. SMS Notification
Delivers SMS alerts regarding payment confirmation, application status, inspection
schedules, and final decisions.
3. Status Update Notification
Provides real-time notifications whenever the application progresses to a new workflow
stage.
Module-11. Re-Inspection Management (Total Feature - 3)
Features Description
1. Re-Inspection Request
Allows authorized officials to initiate a re-inspection whenever additional verification or
compliance confirmation is required.
2. Return to Inspection Setup
Automatically routes the application back to the inspection scheduling stage for planning the
re-inspection.
3. Repeat Inspection Cycle
Supports multiple inspection cycles until all compliance requirements are successfully
fulfilled.
Module-12. User & Role Management (Total Feature - 7)
Features Description
1. Applicant
Allows applicants to submit applications, upload documents, make payments, track
application progress, and download issued certificates.
2. Reviewer
Enables reviewers to examine applications, identify shortfalls, request additional
information, and verify submitted documents.

                                             60
```

## Page 62

```text
3. Inspector
Allows inspectors to perform field inspections, record findings, upload supporting evidence,
and prepare inspection reports.
4. AD
Provides the Assistant Director (AD) with authority to review inspection reports, verify
findings, and recommend applications for higher approval.
5. DD
Allows the Deputy Director (DD) to perform final verification and forward eligible
applications to the Director for decision.
6. Director
Provides the Director with authority to approve, reject, or request re-inspection based on the
overall evaluation and compliance status.
7. System Admin Role Management
Allows system administrators to manage users, assign roles and permissions, and control
secure access across the entire application.

                                               61
```

## Page 63

```text
  SERVICE
                   CM MANDATORY RENEWAL SERVICE
    06
                   Renewal Application • Inspection • Verification • CM Certification

Service Profile
Domain                                Service Type               Primary Users
Certification of Marks (CM)           Regulatory / Certification Applicants    •   Reviewers     •
                                      Service                    Inspectors • AD • DD • Director •
                                                                 System Admin
Core Scope                            Modules                      Features
Mandatory CM Renewal
                                      12                           46

Functional Coverage
APPLICATION                        REVIEW                            INSPECTION
• Online Application               • Application Review              • Inspector Assignment
• Document Upload                  • Shortfall Identification        • Inspection Scheduling
• Application Fee                  • Correction & Resubmission       • Inspection & Report
• Application ID

VERIFICATION                       CERTIFICATION                     CONTROL
• AD/DD Verification               • Registration Completion         • Re-inspection
• Director Decision                • CM Certificate Generation       • Notifications
• Approval / Rejection             • Download                        • User & Role Management

Module Catalogue
Sl. Module                                  No. of  Sl. Module                                No. of
No.                                        Features No.                                      Features
 01 Application Submission                    4        07   Director Decision                   3
 02 Application Review & Shortfall            5        08   Certification Complete              3
    Management
 03 Payment Processing                        4        09   Rejection Management                3
 04 Inspection Setup                          3        10   Notification Management             3
 05 Inspection & Report                       5        11   Re-Inspection Management            3
 06 Verification Module (AD/DD)               3        12   User & Role Management              7

                                                  62
```

## Page 64

```text
Service-06: CM Mandatory Renewal Service
The proposed Application & Certification Management System consists of 12 functional
modules with a total of 46 key features, designed to automate the complete certification
lifecycle from application submission to certificate issuance.
The solution enables applicants to submit applications online, upload required documents,
pay application fees, and receive automatically generated application IDs. Applications are
reviewed through a structured shortfall management process, allowing reviewers to identify
deficiencies, request additional documents, and manage correction and resubmission cycles
while keeping applicants informed through automated notifications.
The system supports secure payment processing with fee collection, verification, and
automatic status updates. Inspection activities are managed through inspector assignment,
scheduling, physical inspections, report preparation, photo uploads, and remark recording.
Inspection reports are then verified by the Assistant Director (AD) and Deputy Director (DD)
before being forwarded to the Director for the final approval, rejection, or re-inspection
decision.
Upon approval, the system completes the registration process, generates the CM Certificate,
and provides applicants with a downloadable certificate. In case of rejection, automated
rejection letters are issued along with notifications and product quality improvement
guidance. The solution also includes integrated notification management through email and
SMS, re-inspection workflow management, and comprehensive role-based access control
for Applicants, Reviewers, Inspectors, ADs, DDs, Directors, and System Administrators.

                                              63
```

## Page 65

```text
Fig: CM Mandatory Renew Service Workflow

                  64
```

## Page 66

```text
Module-1. Application Submission (Total Feature - 4)
Features Description
1. Online Application Submission
Allows applicants to submit Certification Mark (CM) applications electronically through the
online portal. The system validates mandatory information before accepting the application
for processing.
2. Document Upload
Enables applicants to upload all required supporting documents in approved formats. Each
document is securely stored and linked to the corresponding application.
3. Application Fee Payment
Allows applicants to pay the prescribed application fee through the integrated payment
gateway. Payment information is automatically recorded and associated with the application.
4. Auto Application ID Generation
Automatically generates a unique Application ID upon successful submission. The ID is used
for application tracking and future correspondence.
Module-2. Application Review & Shortfall Management (Total Feature
- 5)
Features Description
1. Application Review
Allows authorized officers to review submitted applications and verify the completeness of
the provided information and supporting documents.
2. Shortfall Identification
Enables reviewers to identify missing documents, incorrect information, or compliance gaps
during the application assessment process.
3. Required Document Request
Allows reviewers to request additional documents or information from applicants whenever
necessary. All requests are recorded within the application history.
4. Shortfall Correction & Resubmission Loop
Enables applicants to correct identified shortfalls and resubmit the application. The workflow
supports multiple review and correction cycles until all requirements are fulfilled.
5. Applicant Notification
Automatically notifies applicants regarding application review results, shortfall requests, and
resubmission status through the notification system.
Module-3. Payment Processing (Total Feature - 4)
Features Description
1. Fee Display
Displays applicable fees dynamically based on the selected service and predefined fee
configuration.

                                              65
```

## Page 67

```text
2. Payment Collection
Collects application fees securely through the integrated online payment gateway while
maintaining complete transaction records.
3. Payment Verification
Verifies payment transactions automatically or through authorized verification before
allowing the application to proceed.
4. Automatic Status Update
Automatically updates the application status once the payment is successfully verified,
ensuring smooth workflow progression.
Module-4. Inspection Setup (Total Feature - 3)
Features Description
1. Inspector Assignment
Allows authorized officials to assign qualified inspectors based on workload, expertise, or
geographical jurisdiction.
2. Inspection Scheduling
Enables inspection schedules to be created based on inspector availability and organizational
requirements.
3. Inspection Date/Time/Location Setup
Allows authorized users to define and approve the inspection date, time, and inspection
location before the inspection is conducted.
Module-5. Inspection & Report (Total Feature - 5)
Features Description
1. Physical Inspection
Allows inspectors to conduct on-site inspections according to approved standards,
guidelines, and regulatory requirements.
2. Inspection Findings
Records inspection observations, compliance status, and identified non-conformities during
the inspection process.
3. Report Preparation
Enables inspectors to prepare structured inspection reports based on field observations and
collected evidence.
4. Photo Upload
Allows inspectors to upload photographs as supporting evidence for inspection findings and
compliance verification.
5. Remarks Entry
Provides inspectors with the option to record additional comments, recommendations, or
observations related to the inspection.

                                               66
```

## Page 68

```text
Module-6. Verification Module (AD/DD) (Total Feature - 3)
Features Description
1. Inspection Report Review
Allows the Assistant Director (AD) and Deputy Director (DD) to review submitted inspection
reports for completeness and compliance.
2. Verification
Enables authorized officers to verify inspection findings before forwarding the application for
the Director's decision.
3. Comments & Feedback
Allows reviewers to provide comments, recommendations, or clarification requests during
the verification process.
Module-7. Director Decision (Total Feature - 3)
Features Description
1. Approval
Allows the Director to approve applications that fully satisfy all regulatory and inspection
requirements.
2. Rejection
Allows the Director to reject applications with documented reasons whenever required
compliance criteria are not met.
3. Re-Inspection Decision
Enables the Director to request a re-inspection if additional verification is required before
making the final decision.
Module-8. Certification Complete (Total Feature - 3)
Features Description
1. Registration Completion
Finalizes the Certification Mark (CM) registration process after successful verification and
approval.
2. CM Certificate Generation
Automatically generates the official Certification Mark (CM) Certificate using the approved
application information.
3. Download Link
Provides applicants with secure access to download the issued CM Certificate directly from
the system.
Module-9. Rejection Management (Total Feature - 3)
Features Description
1. Rejection Letter Generation
Automatically generates a formal rejection letter including the reasons for rejection and
applicable recommendations.

                                              67
```

## Page 69

```text
2. Applicant Notification
Notifies applicants immediately after the rejection decision through email, SMS, or in-system
notifications.
3. Product Quality Improvement Process
Allows applicants to review identified quality issues, implement corrective actions, and
improve product compliance before submitting a new application.
Module-10. Notification Management (Total Feature - 3)
Features Description
1. Email Notification
Automatically sends email notifications for application events, approvals, inspections, and
workflow updates.
2. SMS Notification
Delivers SMS alerts regarding payment confirmation, application status, inspection
schedules, and final decisions.
3. Status Update Notification
Provides real-time notifications whenever the application progresses to a new workflow
stage.
Module-11. Re-Inspection Management (Total Feature - 3)
Features Description
1. Re-Inspection Request
Allows authorized officials to initiate a re-inspection whenever additional verification or
compliance confirmation is required.
2. Return to Inspection Setup
Automatically routes the application back to the inspection scheduling stage for planning the
re-inspection.
3. Repeat Inspection Cycle
Supports multiple inspection cycles until all compliance requirements are successfully
fulfilled.
Module-12. User & Role Management (Total Feature - 7)
Features Description
1. Applicant
Allows applicants to submit applications, upload documents, make payments, track
application progress, and download issued certificates.
2. Reviewer
Enables reviewers to examine applications, identify shortfalls, request additional
information, and verify submitted documents.

                                             68
```

## Page 70

```text
3. Inspector
Allows inspectors to perform field inspections, record findings, upload supporting evidence,
and prepare inspection reports.
4. AD
Provides the Assistant Director (AD) with authority to review inspection reports, verify
findings, and recommend applications for higher approval.
5. DD
Allows the Deputy Director (DD) to perform final verification and forward eligible
applications to the Director for decision.
6. Director
Provides the Director with authority to approve, reject, or request re-inspection based on the
overall evaluation and compliance status.
7. System Admin Role Management
Allows system administrators to manage users, assign roles and permissions, and control
secure access across the entire application.

                                               69
```

## Page 71

```text
  SERVICE
                   CM MANDATORY BRAND INCLUSION
    07
                   Brand Inclusion • Application Review • Inspection • Certification

Service Profile
Domain                                Service Type               Primary Users
Certification of Marks (CM)           Regulatory / Certification Applicants    •   Reviewers     •
                                      Service                    Inspectors • AD • DD • Director •
                                                                 System Admin
Core Scope                            Modules                      Features
Mandatory Brand Inclusion
                                      12                           46

Functional Coverage
APPLICATION                        REVIEW                            INSPECTION
• Online Application               • Application Review              • Inspector Assignment
• Document Upload                  • Shortfall Identification        • Inspection Scheduling
• Application Fee                  • Correction & Resubmission       • Inspection & Report
• Application ID

VERIFICATION                       CERTIFICATION                     CONTROL
• AD/DD Verification               • Registration Completion         • Re-inspection
• Director Decision                • CM Certificate Generation       • Notifications
• Approval / Rejection             • Download                        • User & Role Management

Module Catalogue
Sl. Module                                  No. of  Sl. Module                                No. of
No.                                        Features No.                                      Features
 01 Application Submission                    4        07   Director Decision                   3
 02 Application Review & Shortfall            5        08   Certification Complete              3
    Management
 03 Payment Processing                        4        09   Rejection Management                3
 04 Inspection Setup                          3        10   Notification Management             3
 05 Inspection & Report                       5        11   Re-Inspection Management            3
 06 Verification Module (AD/DD)               3        12   User & Role Management              7

                                                  70
```

## Page 72

```text
Service-07: CM Mandatory Brand Inclusion Feature
Description
The proposed Application & Certification Management System consists of 12 functional
modules with a total of 46 key features, designed to automate the complete certification
lifecycle from application submission to certificate issuance.
The solution enables applicants to submit applications online, upload required documents,
pay application fees, and receive automatically generated application IDs. Applications are
reviewed through a structured shortfall management process, allowing reviewers to identify
deficiencies, request additional documents, and manage correction and resubmission cycles
while keeping applicants informed through automated notifications.
The system supports secure payment processing with fee collection, verification, and
automatic status updates. Inspection activities are managed through inspector assignment,
scheduling, physical inspections, report preparation, photo uploads, and remark recording.
Inspection reports are then verified by the Assistant Director (AD) and Deputy Director (DD)
before being forwarded to the Director for the final approval, rejection, or re-inspection
decision.
Upon approval, the system completes the registration process, generates the CM Certificate,
and provides applicants with a downloadable certificate. In case of rejection, automated
rejection letters are issued along with notifications and product quality improvement
guidance. The solution also includes integrated notification management through email and
SMS, re-inspection workflow management, and comprehensive role-based access control
for Applicants, Reviewers, Inspectors, ADs, DDs, Directors, and System Administrators.

                                              71
```

## Page 73

```text
Fig: CM Mandatory Brand Inclusion Service Workflow

                       72
```

## Page 74

```text
Module-1. Application Submission (Total Feature - 4)
Features Description
1. Online Application Submission
Allows applicants to submit Certification Mark (CM) applications electronically through the
online portal. The system validates mandatory information before accepting the application
for processing.
2. Document Upload
Enables applicants to upload all required supporting documents in approved formats. Each
document is securely stored and linked to the corresponding application.
3. Application Fee Payment
Allows applicants to pay the prescribed application fee through the integrated payment
gateway. Payment information is automatically recorded and associated with the application.
4. Auto Application ID Generation
Automatically generates a unique Application ID upon successful submission. The ID is used
for application tracking and future correspondence.
Module-2. Application Review & Shortfall Management (Total Feature
- 5)
Features Description
1. Application Review
Allows authorized officers to review submitted applications and verify the completeness of
the provided information and supporting documents.
2. Shortfall Identification
Enables reviewers to identify missing documents, incorrect information, or compliance gaps
during the application assessment process.
3. Required Document Request
Allows reviewers to request additional documents or information from applicants whenever
necessary. All requests are recorded within the application history.
4. Shortfall Correction & Resubmission Loop
Enables applicants to correct identified shortfalls and resubmit the application. The workflow
supports multiple review and correction cycles until all requirements are fulfilled.
5. Applicant Notification
Automatically notifies applicants regarding application review results, shortfall requests, and
resubmission status through the notification system.
Module-3. Payment Processing (Total Feature - 4)
Features Description
1. Fee Display
Displays applicable fees dynamically based on the selected service and predefined fee
configuration.

                                              73
```

## Page 75

```text
2. Payment Collection
Collects application fees securely through the integrated online payment gateway while
maintaining complete transaction records.
3. Payment Verification
Verifies payment transactions automatically or through authorized verification before
allowing the application to proceed.
4. Automatic Status Update
Automatically updates the application status once the payment is successfully verified,
ensuring smooth workflow progression.
Module-4. Inspection Setup (Total Feature - 3)
Features Description
1. Inspector Assignment
Allows authorized officials to assign qualified inspectors based on workload, expertise, or
geographical jurisdiction.
2. Inspection Scheduling
Enables inspection schedules to be created based on inspector availability and organizational
requirements.
3. Inspection Date/Time/Location Setup
Allows authorized users to define and approve the inspection date, time, and inspection
location before the inspection is conducted.
Module-5. Inspection & Report (Total Feature - 5)
Features Description
1. Physical Inspection
Allows inspectors to conduct on-site inspections according to approved standards,
guidelines, and regulatory requirements.
2. Inspection Findings
Records inspection observations, compliance status, and identified non-conformities during
the inspection process.
3. Report Preparation
Enables inspectors to prepare structured inspection reports based on field observations and
collected evidence.
4. Photo Upload
Allows inspectors to upload photographs as supporting evidence for inspection findings and
compliance verification.
5. Remarks Entry
Provides inspectors with the option to record additional comments, recommendations, or
observations related to the inspection.
Module-6. Verification Module (AD/DD) (Total Feature - 3)

                                               74
```

## Page 76

```text
Features Description
1. Inspection Report Review
Allows the Assistant Director (AD) and Deputy Director (DD) to review submitted inspection
reports for completeness and compliance.
2. Verification
Enables authorized officers to verify inspection findings before forwarding the application for
the Director's decision.
3. Comments & Feedback
Allows reviewers to provide comments, recommendations, or clarification requests during
the verification process.
Module-7. Director Decision (Total Feature - 3)
Features Description
1. Approval
Allows the Director to approve applications that fully satisfy all regulatory and inspection
requirements.
2. Rejection
Allows the Director to reject applications with documented reasons whenever required
compliance criteria are not met.
3. Re-Inspection Decision
Enables the Director to request a re-inspection if additional verification is required before
making the final decision.
Module-8. Certification Complete (Total Feature - 3)
Features Description
1. Registration Completion
Finalizes the Certification Mark (CM) registration process after successful verification and
approval.
2. CM Certificate Generation
Automatically generates the official Certification Mark (CM) Certificate using the approved
application information.
3. Download Link
Provides applicants with secure access to download the issued CM Certificate directly from
the system.
Module-9. Rejection Management (Total Feature - 3)
Features Description
1. Rejection Letter Generation
Automatically generates a formal rejection letter including the reasons for rejection and
applicable recommendations.

                                              75
```

## Page 77

```text
2. Applicant Notification
Notifies applicants immediately after the rejection decision through email, SMS, or in-system
notifications.
3. Product Quality Improvement Process
Allows applicants to review identified quality issues, implement corrective actions, and
improve product compliance before submitting a new application.
Module-10. Notification Management (Total Feature - 3)
Features Description
1. Email Notification
Automatically sends email notifications for application events, approvals, inspections, and
workflow updates.
2. SMS Notification
Delivers SMS alerts regarding payment confirmation, application status, inspection
schedules, and final decisions.
3. Status Update Notification
Provides real-time notifications whenever the application progresses to a new workflow
stage.
Module-11. Re-Inspection Management (Total Feature - 3)
Features Description
1. Re-Inspection Request
Allows authorized officials to initiate a re-inspection whenever additional verification or
compliance confirmation is required.
2. Return to Inspection Setup
Automatically routes the application back to the inspection scheduling stage for planning the
re-inspection.
3. Repeat Inspection Cycle
Supports multiple inspection cycles until all compliance requirements are successfully
fulfilled.
Module-12. User & Role Management (Total Feature - 7)
Features Description
1. Applicant
Allows applicants to submit applications, upload documents, make payments, track
application progress, and download issued certificates.
2. Reviewer
Enables reviewers to examine applications, identify shortfalls, request additional
information, and verify submitted documents.

                                             76
```

## Page 78

```text
3. Inspector
Allows inspectors to perform field inspections, record findings, upload supporting evidence,
and prepare inspection reports.
4. AD
Provides the Assistant Director (AD) with authority to review inspection reports, verify
findings, and recommend applications for higher approval.
5. DD
Allows the Deputy Director (DD) to perform final verification and forward eligible
applications to the Director for decision.
6. Director
Provides the Director with authority to approve, reject, or request re-inspection based on the
overall evaluation and compliance status.
7. System Admin Role Management
Allows system administrators to manage users, assign roles and permissions, and control
secure access across the entire application.

                                               77
```

## Page 79

```text
  SERVICE
                 CM SCOPE NEW CERTIFICATION
    08
                 Scope Product Certification • Inspection • Laboratory Testing • Licensing

Service Profile
Domain                              Service Type               Primary Users
Certification of Marks (CM)         Regulatory / Certification Applicants     •  Reviewers     •
                                    Service                    Inspectors • AD • DD • Director •
                                                               Certification Committee
Core Scope                          Modules                      Features
Scope Product Certification
                                    16                           83

Functional Coverage
APPLICATION                      REVIEW                            INSPECTION & TESTING
• License Application            • Multi-Level Review              • Inspection Planning
• Initial Questionnaire          • Shortfall Management            • Primary Inspection
• Fee Payment                    • Customer Resubmission           • Formal Inspection
• Application Tracking                                             • Laboratory Testing

EVALUATION                       COMPLIANCE                        LICENSING & CONTROL
• Technical Evaluation           • Conditional Compliance          • Payment
• Verification & Approval        • Re-inspection                   • License Management
• Certification Committee        • Corrective Evidence             • Notifications
                                                                   • Workflow
                                                                   • Documents

Module Catalogue
Sl. Module                                No. of  Sl. Module                                No. of
No.                                      Features No.                                      Features
 01 Application Submission                  5        07   Technical Evaluation                4
 02 Application Review & Shortfall          8        08   Verification & Approval             5
    Management
 03 Inspection Planning                     4        09   Certification Committee             5
 04 Primary Inspection                      5        10   Conditional Compliance              5
 05 Formal Inspection                       5        11   Payment Processing                  5
 06 Laboratory Testing                      5        12   License Management                  5

                                                78
```

## Page 80

```text
Service-08: CM Scope New Certification
The CM Mandatory New Certification System is a comprehensive workflow-driven
platform designed to automate and manage the complete mandatory certification
and licensing lifecycle from application submission to license issuance. The solution
enables applicants to submit online applications, complete initial questionnaires, pay
application fees, and track application progress through a centralized digital portal.
Applications undergo a structured multi-level review process where designated
officials evaluate submissions, identify shortfalls, request corrections, and coordinate
inspection activities. The system supports inspection planning, site inspections,
laboratory testing, technical evaluations, and verification workflows to ensure
compliance with regulatory standards. Based on inspection and testing outcomes,
applications proceed through approval, conditional approval, re-inspection, or
rejection processes managed by the certification committee. The platform also
facilitates conditional compliance management by enabling applicants to submit
corrective evidence and allowing officials to verify compliance before final decisions.
Integrated payment processing automates license fee collection and verification prior
to license issuance. The system further provides automated document management,
notification services, workflow tracking, and audit trails to ensure transparency,
accountability, and efficient collaboration among all stakeholders. By digitizing every
stage of the certification process, the solution minimizes manual intervention,
improves operational efficiency, enhances regulatory compliance, ensures complete
process traceability, and delivers faster, more transparent licensing services for both
applicants and regulatory authorities.

                                          79
```

## Page 81

```text
Fig: Workflow diagram of CM Mandatory New Certification

                          80
```

## Page 82

```text
Module-1. Application Submission (Total Feature - 5)
Features Description
1. Online License Application:
Enables applicants to submit mandatory license applications through a secure online
portal.
2. Initial Questionnaire:
Collects preliminary business, product, and compliance information required for
application assessment.
3. Application Fee Payment:
Allows applicants to pay the prescribed application fee through integrated payment
channels.
4. Application Submission:
Finalizes and submits the completed application for official processing.
5. Application Tracking:
Allows applicants to monitor the real-time status of their submitted applications.
Module-2. Application Review & Shortfall Management (Total Feature
- 8)
Features Description
1. Director Review:
Enables the Director to review applications and provide approval comments or
decisions.
2. DD Review:
Supports Deputy Director review and recommendation during application
processing.
3. AD Review:
Allows the Assistant Director to perform detailed application verification.
4. Inspector Assignment:
Assigns the appropriate inspector for application assessment.
5. Application Review:
Reviews submitted documents for completeness and regulatory compliance.
6. Shortfall Identification:
Identifies missing documents or compliance deficiencies.
7. Shortfall Notification:
Notifies applicants about identified deficiencies requiring correction.
8. Customer Resubmission:
Allows applicants to resubmit corrected documents and information.

                                          81
```

## Page 83

```text
Module-3. Inspection Planning (Total Feature - 4)
Features Description
1. Inspector Assignment:
Assigns inspectors based on workload, expertise, and jurisdiction.
2. Man-Day Calculation (System Generated):
Automatically calculates the required inspection effort based on predefined rules.
3. Inspection Schedule:
Creates inspection schedules for assigned inspectors.
4. Inspection Date Management:
Manages inspection dates, rescheduling, and calendar updates.
Module-4. Primary Inspection (Total Feature - 5)
Features Description
1. Primary Site Visit:
Records the initial site inspection conducted by inspectors.
2. Primary Inspection Report:
Generates a report containing preliminary inspection findings.
3. Observation Recording:
Captures observations and non-conformities identified during inspection.
4. Customer Feedback Request:
Requests clarification or feedback from applicants regarding inspection observations.
5. Evidence Submission:
Allows applicants to upload supporting evidence for inspection findings.
Module-5. Formal Inspection (Total Feature - 5)
Features Description
1. Formal Inspection Scheduling:
Schedules official compliance inspections.
2. Formal Site Inspection:
Records detailed inspection activities conducted at the applicant's premises.
3. Formal Inspection Report:
Generates the official inspection report following completion.
4. Sample Collection:
Records samples collected for laboratory testing.
5. Sample Handover to AD:
Tracks the secure handover of collected samples to the Assistant Director.
Module-6. Laboratory Testing (Total Feature - 5)

                                            82
```

## Page 84

```text
Features Description
1. Sample Forwarding to Lab:
Forwards collected samples to the designated laboratory.
2. Sample Registration:
Registers laboratory samples with unique identification numbers.
3. Resampling Request:
Initiates additional sample collection when required.
4. Test Execution:
Performs laboratory testing according to approved standards.
5. Test Report Generation:
Generates official laboratory test reports.
Module-7. Technical Evaluation (Total Feature - 4)
Features Description
1. Test Report Review:
Reviews laboratory test results for technical accuracy.
2. Inspection Report Compilation:
Consolidates inspection findings for evaluation.
3. Evaluation Report Generation:
Produces comprehensive technical evaluation reports.
4. Technical Recommendation:
Provides recommendations for approval, rejection, or further action.
Module-8. Verification & Approval (Total Feature - 5)
Features Description
1. DD Verification:
Enables the Deputy Director to verify evaluation results.
2. Evaluation Checklist:
Validates compliance using standardized evaluation checklists.
3. Director Approval:
Allows the Director to provide final administrative approval.
4. Workflow Remarks:
Records comments and observations throughout the approval process.
5. Approval History:
Maintains a complete history of approval decisions.
Module-9. Certification Committee (Total Feature - 5)

                                          83
```

## Page 85

```text
Features Description
1. Committee Review:
Facilitates committee evaluation of completed applications.
2. Final Approval:
Grants final certification approval.
3. Conditional Approval:
Approves applications subject to specified compliance conditions.
4. Re-inspection Decision:
Determines whether additional inspections are required.
5. Application Rejection:
Rejects applications that fail to meet regulatory requirements.
Module-10. Conditional Compliance (Total Feature - 5)
Features Description
1. Condition Notification:
Notifies applicants of conditions that must be fulfilled.
2. Customer Compliance Submission:
Allows applicants to submit compliance evidence.
3. Evidence Upload:
Supports uploading documents required for compliance verification.
4. Compliance Verification:
Reviews submitted evidence to verify compliance.
5. Re-verification Request:
Initiates additional verification when necessary.
Module-11. Payment Processing (Total Feature - 5)
Features Description
1. License Fee Request:
Generates the payable license fee request.
2. Payment Notification:
Notifies applicants regarding pending payments.
3. License Fee Collection:
Records license fee payments from applicants.
4. Payment Verification:
Verifies payment through the integrated payment gateway.
5. Payment Confirmation:
Confirms successful payment before license issuance.

                                           84
```

## Page 86

```text
Module-12. License Management (Total Feature - 5)
Features Description
1. License Generation:
Generates the approved digital license.
2. License Number Generation:
Automatically assigns a unique license number.
3. License Issuance:
Issues the approved license to the applicant.
4. License Download:
Allows applicants to download issued licenses.
5. License Record Management:
Maintains a centralized repository of all issued licenses.
Module-13. Refusal & Rejection Management (Total Feature - 4)
Features Description
1. Refusal Letter Preparation:
Prepares official refusal letters for unsuccessful applications.
2. Rejection Letter Generation:
Generates rejection letters with documented reasons.
3. Approval Workflow for Refusal:
Routes refusal documents through the approval process.
4. Customer Notification:
Notifies applicants of refusal or rejection decisions.
Module-14. Notification (Total Feature - 6)
Features Description
1. Shortfall Notification:
Sends alerts regarding missing documents or deficiencies.
2. Inspection Schedule Notification:
Notifies applicants about inspection schedules.
3. Payment Request Notification:
Informs applicants when payments are due.
4. Conditional Approval Notification:
Communicates conditional approval decisions.
5. License Issued Notification:
Notifies applicants after license issuance.
6. Rejection/Refusal Notification:
Informs applicants of rejection or refusal outcomes.

                                           85
```

## Page 87

```text
Module-15. Workflow & Task Management (Total Feature - 5)
Features Description
1. Role-based Task Assignment:
Assigns workflow tasks according to user roles and responsibilities.
2. Application Forwarding:
Routes applications to the next stage of the workflow.
3. Status Tracking:
Tracks application progress throughout the certification lifecycle.
4. Workflow Remarks:
Records comments and decisions during workflow execution.
5. Audit Trail:
Maintains a complete history of all workflow activities for transparency and
accountability.
Module-16. Document Management (Total Feature - 7)
Features Description
1. Questionnaire Management:
Stores and manages completed application questionnaires.
2. Inspection Report Management:
Maintains inspection reports in a centralized repository.
3. Test Report Management:
Stores laboratory test reports for future reference.
4. Evaluation Report Management:
Manages technical evaluation reports.
5. Evidence Upload:
Supports secure uploading and storage of supporting documents.
6. Refusal Letter Management:
Maintains official refusal and rejection documents.
7. License Document Storage:
Stores issued licenses and related documents in a centralized digital repository.

                                          86
```

## Page 88

```text
  SERVICE
                 CM SCOPE RENEWAL CERTIFICATION
    09
                 Scope Renewal • Inspection • Laboratory Testing • Licensing

Service Profile
Domain                                Service Type               Primary Users
Certification of Marks (CM)           Regulatory / Certification Applicants     •  Reviewers     •
                                      Service                    Inspectors • AD • DD • Director •
                                                                 Certification Committee
Core Scope                            Modules                     Features
Scope
Certification
             Product        Renewal
                                      16                          83

Functional Coverage
APPLICATION                       REVIEW                            INSPECTION & TESTING
• License Application             • Multi-Level Review              • Inspection Planning
• Initial Questionnaire           • Shortfall Management            • Primary Inspection
• Fee Payment                     • Customer Resubmission           • Formal Inspection
• Application Tracking                                              • Laboratory Testing

EVALUATION                        COMPLIANCE                        LICENSING & CONTROL
• Technical Evaluation            • Conditional Compliance          • Payment
• Verification & Approval         • Re-inspection                   • License Management
• Certification Committee         • Corrective Evidence             • Notifications
                                                                    • Workflow
                                                                    • Documents

Module Catalogue
Sl. Module                                  No. of  Sl. Module                               No. of
No.                                        Features No.                                     Features
 01 Application Submission                   5        07   Technical Evaluation                4
 02 Application Review & Shortfall           8        08   Verification & Approval             5
    Management
 03 Inspection Planning                      4        09   Certification Committee             5
 04 Primary Inspection                       5        10   Conditional Compliance              5
 05 Formal Inspection                        5        11   Payment Processing                  5
 06 Laboratory Testing                       5        12   License Management                  5

                                                 87
```

## Page 89

```text
Service-09: CM Scope Renewal Certification
The CM Scope Renewal Certification System is a comprehensive workflow-driven
platform designed to automate and manage the complete mandatory certification
and licensing lifecycle from application submission to license issuance. The solution
enables applicants to submit online applications, complete initial questionnaires, pay
application fees, and track application progress through a centralized digital portal.
Applications undergo a structured multi-level review process where designated
officials evaluate submissions, identify shortfalls, request corrections, and coordinate
inspection activities. The system supports inspection planning, site inspections,
laboratory testing, technical evaluations, and verification workflows to ensure
compliance with regulatory standards. Based on inspection and testing outcomes,
applications proceed through approval, conditional approval, re-inspection, or
rejection processes managed by the certification committee. The platform also
facilitates conditional compliance management by enabling applicants to submit
corrective evidence and allowing officials to verify compliance before final decisions.
Integrated payment processing automates license fee collection and verification prior
to license issuance. The system further provides automated document management,
notification services, workflow tracking, and audit trails to ensure transparency,
accountability, and efficient collaboration among all stakeholders. By digitizing every
stage of the certification process, the solution minimizes manual intervention,
improves operational efficiency, enhances regulatory compliance, ensures complete
process traceability, and delivers faster, more transparent licensing services for both
applicants and regulatory authorities.

                                          88
```

## Page 90

```text
Fig: Workflow diagram of CM Scope Renewal Certification

                          89
```

## Page 91

```text
Module-1. Application Submission (Total Feature - 5)
Features Description
1. Online License Application:
Enables applicants to submit mandatory license applications through a secure online
portal.
2. Initial Questionnaire:
Collects preliminary business, product, and compliance information required for
application assessment.
3. Application Fee Payment:
Allows applicants to pay the prescribed application fee through integrated payment
channels.
4. Application Submission:
Finalizes and submits the completed application for official processing.
5. Application Tracking:
Allows applicants to monitor the real-time status of their submitted applications.
Module-2. Application Review & Shortfall Management (Total Feature
- 8)
Features Description
1. Director Review:
Enables the Director to review applications and provide approval comments or
decisions.
2. DD Review:
Supports Deputy Director review and recommendation during application
processing.
3. AD Review:
Allows the Assistant Director to perform detailed application verification.
4. Inspector Assignment:
Assigns the appropriate inspector for application assessment.
5. Application Review:
Reviews submitted documents for completeness and regulatory compliance.
6. Shortfall Identification:
Identifies missing documents or compliance deficiencies.
7. Shortfall Notification:
Notifies applicants about identified deficiencies requiring correction.
8. Customer Resubmission:
Allows applicants to resubmit corrected documents and information.

                                          90
```

## Page 92

```text
Module-3. Inspection Planning (Total Feature - 4)
Features Description
1. Inspector Assignment:
Assigns inspectors based on workload, expertise, and jurisdiction.
2. Man-Day Calculation (System Generated):
Automatically calculates the required inspection effort based on predefined rules.
3. Inspection Schedule:
Creates inspection schedules for assigned inspectors.
4. Inspection Date Management:
Manages inspection dates, rescheduling, and calendar updates.
Module-4. Primary Inspection (Total Feature - 5)
Features Description
1. Primary Site Visit:
Records the initial site inspection conducted by inspectors.
2. Primary Inspection Report:
Generates a report containing preliminary inspection findings.
3. Observation Recording:
Captures observations and non-conformities identified during inspection.
4. Customer Feedback Request:
Requests clarification or feedback from applicants regarding inspection observations.
5. Evidence Submission:
Allows applicants to upload supporting evidence for inspection findings.
Module-5. Formal Inspection (Total Feature - 5)
Features Description
1. Formal Inspection Scheduling:
Schedules official compliance inspections.
2. Formal Site Inspection:
Records detailed inspection activities conducted at the applicant's premises.
3. Formal Inspection Report:
Generates the official inspection report following completion.
4. Sample Collection:
Records samples collected for laboratory testing.
5. Sample Handover to AD:
Tracks the secure handover of collected samples to the Assistant Director.
Module-6. Laboratory Testing (Total Feature - 5)

                                            91
```

## Page 93

```text
Features Description
1. Sample Forwarding to Lab:
Forwards collected samples to the designated laboratory.
2. Sample Registration:
Registers laboratory samples with unique identification numbers.
3. Resampling Request:
Initiates additional sample collection when required.
4. Test Execution:
Performs laboratory testing according to approved standards.
5. Test Report Generation:
Generates official laboratory test reports.
Module-7. Technical Evaluation (Total Feature - 4)
Features Description
1. Test Report Review:
Reviews laboratory test results for technical accuracy.
2. Inspection Report Compilation:
Consolidates inspection findings for evaluation.
3. Evaluation Report Generation:
Produces comprehensive technical evaluation reports.
4. Technical Recommendation:
Provides recommendations for approval, rejection, or further action.
Module-8. Verification & Approval (Total Feature - 5)
Features Description
1. DD Verification:
Enables the Deputy Director to verify evaluation results.
2. Evaluation Checklist:
Validates compliance using standardized evaluation checklists.
3. Director Approval:
Allows the Director to provide final administrative approval.
4. Workflow Remarks:
Records comments and observations throughout the approval process.
5. Approval History:
Maintains a complete history of approval decisions.
Module-9. Certification Committee (Total Feature - 5)

                                          92
```

## Page 94

```text
Features Description
1. Committee Review:
Facilitates committee evaluation of completed applications.
2. Final Approval:
Grants final certification approval.
3. Conditional Approval:
Approves applications subject to specified compliance conditions.
4. Re-inspection Decision:
Determines whether additional inspections are required.
5. Application Rejection:
Rejects applications that fail to meet regulatory requirements.
Module-10. Conditional Compliance (Total Feature - 5)
Features Description
1. Condition Notification:
Notifies applicants of conditions that must be fulfilled.
2. Customer Compliance Submission:
Allows applicants to submit compliance evidence.
3. Evidence Upload:
Supports uploading documents required for compliance verification.
4. Compliance Verification:
Reviews submitted evidence to verify compliance.
5. Re-verification Request:
Initiates additional verification when necessary.
Module-11. Payment Processing (Total Feature - 5)
Features Description
1. License Fee Request:
Generates the payable license fee request.
2. Payment Notification:
Notifies applicants regarding pending payments.
3. License Fee Collection:
Records license fee payments from applicants.
4. Payment Verification:
Verifies payment through the integrated payment gateway.
5. Payment Confirmation:
Confirms successful payment before license issuance.

                                           93
```

## Page 95

```text
Module-12. License Management (Total Feature - 5)
Features Description
1. License Generation:
Generates the approved digital license.
2. License Number Generation:
Automatically assigns a unique license number.
3. License Issuance:
Issues the approved license to the applicant.
4. License Download:
Allows applicants to download issued licenses.
5. License Record Management:
Maintains a centralized repository of all issued licenses.
Module-13. Refusal & Rejection Management (Total Feature - 4)
Features Description
1. Refusal Letter Preparation:
Prepares official refusal letters for unsuccessful applications.
2. Rejection Letter Generation:
Generates rejection letters with documented reasons.
3. Approval Workflow for Refusal:
Routes refusal documents through the approval process.
4. Customer Notification:
Notifies applicants of refusal or rejection decisions.
Module-14. Notification (Total Feature - 6)
Features Description
1. Shortfall Notification:
Sends alerts regarding missing documents or deficiencies.
2. Inspection Schedule Notification:
Notifies applicants about inspection schedules.
3. Payment Request Notification:
Informs applicants when payments are due.
4. Conditional Approval Notification:
Communicates conditional approval decisions.
5. License Issued Notification:
Notifies applicants after license issuance.
6. Rejection/Refusal Notification:
Informs applicants of rejection or refusal outcomes.

                                           94
```

## Page 96

```text
Module-15. Workflow & Task Management (Total Feature - 5)
Features Description
1. Role-based Task Assignment:
Assigns workflow tasks according to user roles and responsibilities.
2. Application Forwarding:
Routes applications to the next stage of the workflow.
3. Status Tracking:
Tracks application progress throughout the certification lifecycle.
4. Workflow Remarks:
Records comments and decisions during workflow execution.
5. Audit Trail:
Maintains a complete history of all workflow activities for transparency and
accountability.
Module-16. Document Management (Total Feature - 7)
Features Description
1. Questionnaire Management:
Stores and manages completed application questionnaires.
2. Inspection Report Management:
Maintains inspection reports in a centralized repository.
3. Test Report Management:
Stores laboratory test reports for future reference.
4. Evaluation Report Management:
Manages technical evaluation reports.
5. Evidence Upload:
Supports secure uploading and storage of supporting documents.
6. Refusal Letter Management:
Maintains official refusal and rejection documents.
7. License Document Storage:
Stores issued licenses and related documents in a centralized digital repository.

                                          95
```

## Page 97

```text
  SERVICE        CM SCOPE BRAND INCLUSION CERTIFICATION
    10           Brand Inclusion • Inspection • Laboratory Testing • Certification

Service Profile
Domain                              Service Type               Primary Users
Certification of Marks (CM)         Regulatory / Certification Applicants     •  Reviewers     •
                                    Service                    Inspectors • AD • DD • Director •
                                                               Certification Committee
Core Scope                          Modules                      Features
Scope Brand Inclusion Certification
                                    16                           83

Functional Coverage
APPLICATION                      REVIEW                            INSPECTION & TESTING
• License Application            • Multi-Level Review              • Inspection Planning
• Initial Questionnaire          • Shortfall Management            • Primary Inspection
• Fee Payment                    • Customer Resubmission           • Formal Inspection
• Application Tracking                                             • Laboratory Testing

EVALUATION                       COMPLIANCE                        LICENSING & CONTROL
• Technical Evaluation           • Conditional Compliance          • Payment
• Verification & Approval        • Re-inspection                   • License Management
• Certification Committee        • Corrective Evidence             • Notifications
                                                                   • Workflow
                                                                   • Documents

Module Catalogue
Sl. Module                                No. of  Sl. Module                                No. of
No.                                      Features No.                                      Features
 01 Application Submission                  5        07   Technical Evaluation                4
 02 Application Review & Shortfall          8        08   Verification & Approval             5
    Management
 03 Inspection Planning                     4        09   Certification Committee             5
 04 Primary Inspection                      5        10   Conditional Compliance              5
 05 Formal Inspection                       5        11   Payment Processing                  5
 06 Laboratory Testing                      5        12   License Management                  5

                                                96
```

## Page 98

```text
Service-10: CM Scope Brand Inclusion Certification
The CM Scope Brand Inclusion Certification System is a comprehensive workflow-
driven platform designed to automate and manage the complete brand inclusion
certification and licensing lifecycle from application submission to license issuance.
The solution enables applicants to submit online applications, complete initial
questionnaires, pay application fees, and track application progress through a
centralized digital portal. Applications undergo a structured multi-level review
process where designated officials evaluate submissions, identify shortfalls, request
corrections, and coordinate inspection activities. The system supports inspection
planning, site inspections, laboratory testing, technical evaluations, and verification
workflows to ensure compliance with regulatory standards. Based on inspection and
testing outcomes, applications proceed through approval, conditional approval, re-
inspection, or rejection processes managed by the certification committee. The
platform also facilitates conditional compliance management by enabling applicants
to submit corrective evidence and allowing officials to verify compliance before final
decisions. Integrated payment processing automates license fee collection and
verification prior to license issuance. The system further provides automated
document management, notification services, workflow tracking, and audit trails to
ensure transparency, accountability, and efficient collaboration among all
stakeholders. By digitizing every stage of the certification process, the solution
minimizes manual intervention, improves operational efficiency, enhances regulatory
compliance, ensures complete process traceability, and delivers faster, more
transparent licensing services for both applicants and regulatory authorities.

                                          97
```

## Page 99

```text
Fig: Workflow diagram of CM Scope Brand Inclusion Service

                           98
```

## Page 100

```text
Module-1. Application Submission (Total Feature - 5)
Feature Description
1. Online License Application:
Enables applicants to submit mandatory license applications through a secure online
portal.
2. Initial Questionnaire:
Collects preliminary business, product, and compliance information required for
application assessment.
3. Application Fee Payment:
Allows applicants to pay the prescribed application fee through integrated payment
channels.
4. Application Submission:
Finalizes and submits the completed application for official processing.
5. Application Tracking:
Allows applicants to monitor the real-time status of their submitted applications.
Module-2. Application Review & Shortfall Management (Total Feature
- 8)
Feature Description
1. Director Review:
Enables the Director to review applications and provide approval comments or
decisions.
2. DD Review:
Supports Deputy Director review and recommendation during application
processing.
3. AD Review:
Allows the Assistant Director to perform detailed application verification.
4. Inspector Assignment:
Assigns the appropriate inspector for application assessment.
5. Application Review:
Reviews submitted documents for completeness and regulatory compliance.
6. Shortfall Identification:
Identifies missing documents or compliance deficiencies.
7. Shortfall Notification:
Notifies applicants about identified deficiencies requiring correction.
8. Customer Resubmission:
Allows applicants to resubmit corrected documents and information.

                                          99
```

## Page 101

```text
Module-3. Inspection Planning (Total Feature - 4)
Feature Description
1. Inspector Assignment:
Assigns inspectors based on workload, expertise, and jurisdiction.
2. Man-Day Calculation (System Generated):
Automatically calculates the required inspection effort based on predefined rules.
3. Inspection Schedule:
Creates inspection schedules for assigned inspectors.
4. Inspection Date Management:
Manages inspection dates, rescheduling, and calendar updates.
Module-4. Primary Inspection (Total Feature - 5)
Feature Description
1. Primary Site Visit:
Records the initial site inspection conducted by inspectors.
2. Primary Inspection Report:
Generates a report containing preliminary inspection findings.
3. Observation Recording:
Captures observations and non-conformities identified during inspection.
4. Customer Feedback Request:
Requests clarification or feedback from applicants regarding inspection observations.
5. Evidence Submission:
Allows applicants to upload supporting evidence for inspection findings.
Module-5. Formal Inspection (Total Feature - 5)
Feature Description
1. Formal Inspection Scheduling:
Schedules official compliance inspections.
2. Formal Site Inspection:
Records detailed inspection activities conducted at the applicant's premises.
3. Formal Inspection Report:
Generates the official inspection report following completion.
4. Sample Collection:
Records samples collected for laboratory testing.
5. Sample Handover to AD:
Tracks the secure handover of collected samples to the Assistant Director.
Module-6. Laboratory Testing (Total Feature - 5)
Feature Description

                                            100
```

## Page 102

```text
1. Sample Forwarding to Lab:
Forwards collected samples to the designated laboratory.
2. Sample Registration:
Registers laboratory samples with unique identification numbers.
3. Resampling Request:
Initiates additional sample collection when required.
4. Test Execution:
Performs laboratory testing according to approved standards.
5. Test Report Generation:
Generates official laboratory test reports.
Module-7. Technical Evaluation (Total Feature - 4)
Feature Description
1. Test Report Review:
Reviews laboratory test results for technical accuracy.
2. Inspection Report Compilation:
Consolidates inspection findings for evaluation.
3. Evaluation Report Generation:
Produces comprehensive technical evaluation reports.
4. Technical Recommendation:
Provides recommendations for approval, rejection, or further action.
Module-8. Verification & Approval (Total Feature - 5)
Feature Description
1. DD Verification:
Enables the Deputy Director to verify evaluation results.
2. Evaluation Checklist:
Validates compliance using standardized evaluation checklists.
3. Director Approval:
Allows the Director to provide final administrative approval.
4. Workflow Remarks:
Records comments and observations throughout the approval process.
5. Approval History:
Maintains a complete history of approval decisions.
Module-9. Certification Committee (Total Feature - 5)
Feature Description
1. Committee Review:
Facilitates committee evaluation of completed applications.

                                          101
```

## Page 103

```text
2. Final Approval:
Grants final certification approval.
3. Conditional Approval:
Approves applications subject to specified compliance conditions.
4. Re-inspection Decision:
Determines whether additional inspections are required.
5. Application Rejection:
Rejects applications that fail to meet regulatory requirements.
Module-10. Conditional Compliance (Total Feature - 5)
Feature Description
1. Condition Notification:
Notifies applicants of conditions that must be fulfilled.
2. Customer Compliance Submission:
Allows applicants to submit compliance evidence.
3. Evidence Upload:
Supports uploading documents required for compliance verification.
4. Compliance Verification:
Reviews submitted evidence to verify compliance.
5. Re-verification Request:
Initiates additional verification when necessary.
Module-11. Payment Processing (Total Feature - 5)
Feature Description
1. License Fee Request:
Generates the payable license fee request.
2. Payment Notification:
Notifies applicants regarding pending payments.
3. License Fee Collection:
Records license fee payments from applicants.
4. Payment Verification:
Verifies payment through the integrated payment gateway.
5. Payment Confirmation:
Confirms successful payment before license issuance.
Module-12. License Management (Total Feature - 5)
Feature Description
1. License Generation:
Generates the approved digital license.

                                          102
```

## Page 104

```text
2. License Number Generation:
Automatically assigns a unique license number.
3. License Issuance:
Issues the approved license to the applicant.
4. License Download:
Allows applicants to download issued licenses.
5. License Record Management:
Maintains a centralized repository of all issued licenses.
Module-13. Refusal & Rejection Management (Total Feature - 4)
Feature Description
1. Refusal Letter Preparation:
Prepares official refusal letters for unsuccessful applications.
2. Rejection Letter Generation:
Generates rejection letters with documented reasons.
3. Approval Workflow for Refusal:
Routes refusal documents through the approval process.
4. Customer Notification:
Notifies applicants of refusal or rejection decisions.
Module-14. Notification (Total Feature - 6)
Feature Description
1. Shortfall Notification:
Sends alerts regarding missing documents or deficiencies.
2. Inspection Schedule Notification:
Notifies applicants about inspection schedules.
3. Payment Request Notification:
Informs applicants when payments are due.
4. Conditional Approval Notification:
Communicates conditional approval decisions.
5. License Issued Notification:
Notifies applicants after license issuance.
6. Rejection/Refusal Notification:
Informs applicants of rejection or refusal outcomes.
Module-15. Workflow & Task Management (Total Feature - 5)
Feature Description
1. Role-based Task Assignment:
Assigns workflow tasks according to user roles and responsibilities.

                                          103
```

## Page 105

```text
2. Application Forwarding:
Routes applications to the next stage of the workflow.
3. Status Tracking:
Tracks application progress throughout the certification lifecycle.
4. Workflow Remarks:
Records comments and decisions during workflow execution.
5. Audit Trail:
Maintains a complete history of all workflow activities for transparency and
accountability.
Module-16. Document Management (Total Feature - 7)
Feature Description
1. Questionnaire Management:
Stores and manages completed application questionnaires.
2. Inspection Report Management:
Maintains inspection reports in a centralized repository.
3. Test Report Management:
Stores laboratory test reports for future reference.
4. Evaluation Report Management:
Manages technical evaluation reports.
5. Evidence Upload:
Supports secure uploading and storage of supporting documents.
6. Refusal Letter Management:
Maintains official refusal and rejection documents.
7. License Document Storage:
Stores issued licenses and related documents in a centralized digital repository.

                                         104
```

## Page 106

```text
  SERVICE
                 CM HALAL CERTIFICATION
    11
                 Halal Certification • Audit • Laboratory Testing • Certificate Management

Service Profile
Domain                               Service Type               Primary Users
Certification of Marks (CM)          Regulatory / Certification Applicants • AD • DD • Director •
                                     Service                    Audit Team • Certification
                                                                Committee
Core Scope                           Modules                         Features
Halal Certification Lifecycle
                                     16                              86

Functional Coverage
APPLICATION & REVIEW             AUDIT                                 LABORATORY
• Certificate Application        • Stage-1 Audit                       • Sample Management
• Shortfall Management           •     Audit       Observation      & • Laboratory Testing
• Customer Resubmission          Compliance                            • Test Reports
                                 • Stage-2 Audit & Sample
                                 Management

EVALUATION & APPROVAL            COMPLIANCE & CERTIFICATE CONTROL & RECORDS
• Technical Evaluation           • Conditional Compliance              • Refusal & Rejection
• Verification & Approval        • Payment                             • Notification
• Certification Committee        • Certificate / License               • Workflow
                                                                       • Document Management

Module Catalogue
Sl. Module                                 No. of  Sl. Module                                      No. of
No.                                       Features No.                                            Features
 01 Certificate Application                    4         07   Technical Evaluation                   4
 02 Application Review & Shortfall             8         08   Verification & Approval                5
    Management
 03 Stage-1 Audit Management                   6         09   Certification Committee                5
 04 Audit Observation & Compliance             4         10   Conditional Compliance                 5
 05 Stage-2  Audit          &   Sample         5         11   Payment Processing                     5
    Management
 06 Laboratory Testing                         5         12   Certificate       /       License      5
                                                              Management

                                                   105
```

## Page 107

```text
Service-11: CM HALAL CERTIFICATION
The proposed CM Hala Certificate Management System is a comprehensive digital platform
designed to automate and manage the complete certification lifecycle, from online
application submission to certificate issuance. The solution enables applicants to submit
certificate applications, complete initial questionnaires, and monitor application progress
through a centralized online portal. Applications undergo a structured multi-level review
process involving Assistant Director (AD), Deputy Director (DD), and Director verification,
with integrated shortfall management to ensure complete and accurate submissions. The
system supports Stage-1 and Stage-2 audit management, including auditor assignment,
audit scheduling, observation recording, compliance monitoring, and sample collection.
Laboratory testing is seamlessly integrated to manage sample registration, testing,
resampling, and report generation. Technical evaluations consolidate audit findings and
laboratory results to produce recommendations for management approval. The certification
committee reviews evaluation outcomes and determines final approval, conditional approval,
re-inspection, or rejection. Conditional compliance workflows enable applicants to submit
corrective actions and supporting evidence before final certification. The solution also
automates payment processing, digital certificate generation, certificate issuance, and record
management. Supporting modules such as workflow management, document management,
and automated notifications ensure transparency, traceability, and efficient communication
throughout the certification process. By digitizing every stage of the certification lifecycle, the
system improves operational efficiency, reduces manual processing, enhances regulatory
compliance, and delivers faster, more transparent certification services.

                                               106
```

## Page 108

```text
Fig: CM Halal New Certification Workflow

                  107
```

## Page 109

```text
Module-1. Certificate Application (Total Feature - 4)
Feature Description
1. Online Certificate Application:
Enables applicants to submit certificate applications electronically.
2. Initial Questionnaire:
Collects preliminary organizational and product information required for assessment.
3. Application Submission:
Finalizes and submits the completed application for review.
4. Application Tracking:
Allows applicants to monitor the progress of their submitted applications.
Module-2. Application Review & Shortfall Management (Total Feature
- 8)
Feature Description
1. Director Review:
Enables Director-level review and approval recommendations.
2. DD Review:
Supports Deputy Director verification of submitted applications.
3. AD Review:
Allows Assistant Director to perform detailed document verification.
4. Inspector Assignment:
Assigns inspectors or auditors for audit activities.
5. Application Review:
Reviews submitted documents for completeness and compliance.
6. Shortfall Identification:
Identifies missing documents or compliance issues.
7. Shortfall Notification:
Notifies applicants about deficiencies requiring correction.
8. Customer Resubmission:
Allows applicants to submit corrected information and documents.
Module-3. Stage-1 Audit Management (Total Feature - 6)
Feature Description
1. Stage-1 Audit Scheduling:
Plans and schedules the initial audit.
2. Auditor/Inspector Assignment:
Assigns qualified auditors or inspectors.

                                            108
```

## Page 110

```text
3. Stage-1 Audit Execution:
Records audit activities conducted during Stage-1.
4. Stage-1 Audit Report Generation:
Generates the official Stage-1 audit report.
5. Observation Recording:
Captures audit observations and findings.
6. Audit Findings:
Records non-conformities and audit conclusions.
Module-4. Audit Observation & Compliance (Total Feature - 4)
Feature Description
1. Observation Notification:
Notifies applicants regarding audit observations.
2. Evidence Submission:
Allows applicants to upload corrective evidence.
3. Evidence Verification by AD:
Enables Assistant Director to verify submitted evidence.
4. Compliance Tracking:
Tracks corrective action progress until closure.
Module-5. Stage-2 Audit & Sample Management (Total Feature - 5)
Feature Description
1. Stage-2 Audit Scheduling:
Schedules the final certification audit.
2. Stage-2 Audit Execution:
Conducts the Stage-2 audit.
3. Stage-2 Audit Report Generation:
Generates the Stage-2 audit report.
4. Sample Collection:
Records sample collection during the audit.
5. Sample Handover to AD:
Tracks sample handover for laboratory processing.
Module-6. Laboratory Testing (Total Feature - 5)
Feature Description
1. Sample Forwarding to Laboratory:
Sends collected samples to the laboratory.
2. Sample Registration:
Registers samples with unique tracking identifiers.

                                           109
```

## Page 111

```text
3. Resampling Request:
Requests additional samples when necessary.
4. Test Execution:
Performs laboratory testing according to approved standards.
5. Test Report Generation:
Produces official laboratory test reports.
Module-7. Technical Evaluation (Total Feature - 4)
Feature Description
1. Test Report Review:
Reviews laboratory testing results.
2. Audit Report Compilation:
Consolidates audit findings into a technical assessment.
3. Technical Report Generation:
Generates the official technical evaluation report.
4. Technical Recommendation:
Provides recommendations for approval or rejection.
Module-8. Verification & Approval (Total Feature - 5)
Feature Description
1. DD Verification:
Verifies technical evaluation results.
2. Technical Checklist Preparation:
Prepares standardized evaluation checklists.
3. Director Approval:
Enables final approval by the Director.
4. Workflow Remarks:
Records review comments and observations.
5. Approval History:
Maintains a complete history of approvals.
Module-9. Certification Committee (Total Feature - 5)
Feature Description
1. Committee Review:
Facilitates committee review of evaluated applications.
2. Final Approval:
Grants final certification approval.
3. Conditional Approval:
Approves applications with specified conditions.

                                             110
```

## Page 112

```text
4. Re-inspection Decision:
Determines whether another audit is required.
5. Application Rejection:
Rejects applications that fail to meet certification requirements.
Module-10. Conditional Compliance (Total Feature - 5)
Feature Description
1. Conditional Issue Notification:
Notifies applicants of approval conditions.
2. Corrective Action Submission:
Allows applicants to submit corrective actions.
3. Evidence Upload:
Supports uploading compliance evidence.
4. Compliance Verification:
Verifies submitted corrective actions.
5. Re-verification Request:
Initiates additional verification when required.
Module-11. Payment Processing (Total Feature - 5)
Feature Description
1. Certificate/License Fee Request:
Generates payment requests.
2. Payment Notification:
Notifies applicants regarding pending payments.
3. Payment Collection:
Records payment received.
4. Payment Verification:
Verifies payment through integrated payment services.
5. Payment Confirmation:
Confirms successful payment.
Module-12. Certificate / License Management (Total Feature - 5)
Feature Description
1. Certificate/License Generation:
Generates approved certificates or licenses.
2. Certificate Number Generation:
Automatically assigns unique certificate numbers.
3. Digital Certificate Issuance:
Issues digitally signed certificates.

                                          111
```

## Page 113

```text
4. Certificate Download:
Allows applicants to download certificates.
5. Certificate Record Management:
Maintains centralized certificate records.
Module-13. Refusal & Rejection Management (Total Feature - 5)
Feature Description
1. Refusal Letter Preparation:
Prepares official refusal letters.
2. Rejection Letter Generation:
Generates rejection letters.
3. Refusal Verification:
Verifies refusal decisions before issuance.
4. Director Approval:
Obtains Director approval for refusals.
5. Customer Notification:
Notifies applicants of refusal or rejection.
Module-14. Notification (Total Feature - 7)
Feature Description
1. Shortfall Notification:
Sends notifications regarding missing documents.
2. Audit Schedule Notification:
Informs applicants about audit schedules.
3. Observation Notification:
Notifies applicants of audit findings.
4. Payment Request Notification:
Sends payment reminders.
5. Conditional Approval Notification:
Notifies applicants of conditional approvals.
6. Certificate Issued Notification:
Confirms certificate issuance.
7. Rejection/Refusal Notification:
Notifies applicants of rejection decisions.
Module-15. Workflow & Task Management (Total Feature - 6)
Feature Description
1. Role-based Task Assignment:
Assigns tasks according to user roles.

                                             112
```

## Page 114

```text
2. Multi-Level Workflow:
Supports hierarchical approval workflows.
3. Application Forwarding:
Routes applications between workflow stages.
4. Status Tracking:
Tracks the progress of every application.
5. Workflow Remarks:
Records workflow comments.
6. Audit Trail:
Maintains a complete audit history.
Module-16. Document Management (Total Feature - 7)
Feature Description
1. Questionnaire Management:
Stores application questionnaires.
2. Audit Report Management:
Maintains audit reports.
3. Test Report Management:
Stores laboratory reports.
4. Technical Report Management:
Maintains technical evaluation reports.
5. Evidence Upload:
Stores compliance evidence.
6. Refusal Letter Management:
Maintains refusal and rejection letters.
7. Certificate Repository:
Stores issued certificates in a centralized repository.

                                           113
```

## Page 115

```text
  SERVICE
                 CM HALAL RENEWAL CERTIFICATION
    12
                 Halal Certification • Audit • Laboratory Testing • Certificate Management

Service Profile
Domain                               Service Type               Primary Users
Certification of Marks (CM)          Regulatory / Certification Applicants • AD • DD • Director •
                                     Service                    Audit Team • Certification
                                                                Committee
Core Scope                           Modules                         Features
Halal Certification Lifecycle
                                     16                              86

Functional Coverage
APPLICATION & REVIEW             AUDIT                                 LABORATORY
• Certificate Application        • Stage-1 Audit                       • Sample Management
• Shortfall Management           •     Audit       Observation      & • Laboratory Testing
• Customer Resubmission          Compliance                            • Test Reports
                                 • Stage-2 Audit & Sample
                                 Management

EVALUATION & APPROVAL            COMPLIANCE & CERTIFICATE CONTROL & RECORDS
• Technical Evaluation           • Conditional Compliance              • Refusal & Rejection
• Verification & Approval        • Payment                             • Notification
• Certification Committee        • Certificate / License               • Workflow
                                                                       • Document Management

Module Catalogue
Sl. Module                                 No. of  Sl. Module                                      No. of
No.                                       Features No.                                            Features
 01 Certificate Application                    4         07   Technical Evaluation                   4
 02 Application Review & Shortfall             8         08   Verification & Approval                5
    Management
 03 Stage-1 Audit Management                   6         09   Certification Committee                5
 04 Audit Observation & Compliance             4         10   Conditional Compliance                 5
 05 Stage-2  Audit          &   Sample         5         11   Payment Processing                     5
    Management
 06 Laboratory Testing                         5         12   Certificate       /       License      5
                                                              Management

                                                   114
```

## Page 116

```text
Service-12: CM HALAL RENEWAL CERTIFICATION
The proposed CM Halal Renewal Certificate Management System is a comprehensive
digital platform designed to automate and manage the complete certification lifecycle, from
online application submission to certificate issuance. The solution enables applicants to
submit certificate applications, complete initial questionnaires, and monitor application
progress through a centralized online portal. Applications undergo a structured multi-level
review process involving Assistant Director (AD), Deputy Director (DD), and Director
verification, with integrated shortfall management to ensure complete and accurate
submissions. The system supports Stage-1 and Stage-2 audit management, including
auditor assignment, audit scheduling, observation recording, compliance monitoring, and
sample collection. Laboratory testing is seamlessly integrated to manage sample
registration, testing, resampling, and report generation. Technical evaluations consolidate
audit findings and laboratory results to produce recommendations for management
approval. The certification committee reviews evaluation outcomes and determines final
approval, conditional approval, re-inspection, or rejection. Conditional compliance workflows
enable applicants to submit corrective actions and supporting evidence before final
certification. The solution also automates payment processing, digital certificate generation,
certificate issuance, and record management. Supporting modules such as workflow
management, document management, and automated notifications ensure transparency,
traceability, and efficient communication throughout the certification process. By digitizing
every stage of the certification lifecycle, the system improves operational efficiency, reduces
manual processing, enhances regulatory compliance, and delivers faster, more transparent
certification services.

                                             115
```

## Page 117

```text
Fig: CM Halal Renewal Workflow

             116
```

## Page 118

```text
Module-1. Certificate Application (Total Feature - 4)
Feature Description
1. Online Certificate Application:
Enables applicants to submit certificate applications electronically.
2. Initial Questionnaire:
Collects preliminary organizational and product information required for assessment.
3. Application Submission:
Finalizes and submits the completed application for review.
4. Application Tracking:
Allows applicants to monitor the progress of their submitted applications.
Module-2. Application Review & Shortfall Management (Total Feature
- 8)
Feature Description
1. Director Review:
Enables Director-level review and approval recommendations.
2. DD Review:
Supports Deputy Director verification of submitted applications.
3. AD Review:
Allows Assistant Director to perform detailed document verification.
4. Inspector Assignment:
Assigns inspectors or auditors for audit activities.
5. Application Review:
Reviews submitted documents for completeness and compliance.
6. Shortfall Identification:
Identifies missing documents or compliance issues.
7. Shortfall Notification:
Notifies applicants about deficiencies requiring correction.
8. Customer Resubmission:
Allows applicants to submit corrected information and documents.
Module-3. Stage-1 Audit Management (Total Feature - 6)
Feature Description
1. Stage-1 Audit Scheduling:
Plans and schedules the initial audit.
2. Auditor/Inspector Assignment:
Assigns qualified auditors or inspectors.

                                            117
```

## Page 119

```text
3. Stage-1 Audit Execution:
Records audit activities conducted during Stage-1.
4. Stage-1 Audit Report Generation:
Generates the official Stage-1 audit report.
5. Observation Recording:
Captures audit observations and findings.
6. Audit Findings:
Records non-conformities and audit conclusions.
Module-4. Audit Observation & Compliance (Total Feature - 4)
Feature Description
1. Observation Notification:
Notifies applicants regarding audit observations.
2. Evidence Submission:
Allows applicants to upload corrective evidence.
3. Evidence Verification by AD:
Enables Assistant Director to verify submitted evidence.
4. Compliance Tracking:
Tracks corrective action progress until closure.
Module-5. Stage-2 Audit & Sample Management (Total Feature - 5)
Feature Description
1. Stage-2 Audit Scheduling:
Schedules the final certification audit.
2. Stage-2 Audit Execution:
Conducts the Stage-2 audit.
3. Stage-2 Audit Report Generation:
Generates the Stage-2 audit report.
4. Sample Collection:
Records sample collection during the audit.
5. Sample Handover to AD:
Tracks sample handover for laboratory processing.
Module-6. Laboratory Testing (Total Feature - 5)
Feature Description
1. Sample Forwarding to Laboratory:
Sends collected samples to the laboratory.
2. Sample Registration:
Registers samples with unique tracking identifiers.

                                           118
```

## Page 120

```text
3. Resampling Request:
Requests additional samples when necessary.
4. Test Execution:
Performs laboratory testing according to approved standards.
5. Test Report Generation:
Produces official laboratory test reports.
Module-7. Technical Evaluation (Total Feature - 4)
Feature Description
1. Test Report Review:
Reviews laboratory testing results.
2. Audit Report Compilation:
Consolidates audit findings into a technical assessment.
3. Technical Report Generation:
Generates the official technical evaluation report.
4. Technical Recommendation:
Provides recommendations for approval or rejection.
Module-8. Verification & Approval (Total Feature - 5)
Feature Description
1. DD Verification:
Verifies technical evaluation results.
2. Technical Checklist Preparation:
Prepares standardized evaluation checklists.
3. Director Approval:
Enables final approval by the Director.
4. Workflow Remarks:
Records review comments and observations.
5. Approval History:
Maintains a complete history of approvals.
Module-9. Certification Committee (Total Feature - 5)
Feature Description
1. Committee Review:
Facilitates committee review of evaluated applications.
2. Final Approval:
Grants final certification approval.
3. Conditional Approval:
Approves applications with specified conditions.

                                             119
```

## Page 121

```text
4. Re-inspection Decision:
Determines whether another audit is required.
5. Application Rejection:
Rejects applications that fail to meet certification requirements.
Module-10. Conditional Compliance (Total Feature - 5)
Feature Description
1. Conditional Issue Notification:
Notifies applicants of approval conditions.
2. Corrective Action Submission:
Allows applicants to submit corrective actions.
3. Evidence Upload:
Supports uploading compliance evidence.
4. Compliance Verification:
Verifies submitted corrective actions.
5. Re-verification Request:
Initiates additional verification when required.
Module-11. Payment Processing (Total Feature - 5)
Feature Description
1. Certificate/License Fee Request:
Generates payment requests.
2. Payment Notification:
Notifies applicants regarding pending payments.
3. Payment Collection:
Records payment received.
4. Payment Verification:
Verifies payment through integrated payment services.
5. Payment Confirmation:
Confirms successful payment.
Module-12. Certificate / License Management (Total Feature - 5)
Feature Description
1. Certificate/License Generation:
Generates approved certificates or licenses.
2. Certificate Number Generation:
Automatically assigns unique certificate numbers.
3. Digital Certificate Issuance:
Issues digitally signed certificates.

                                          120
```

## Page 122

```text
4. Certificate Download:
Allows applicants to download certificates.
5. Certificate Record Management:
Maintains centralized certificate records.
Module-13. Refusal & Rejection Management (Total Feature - 5)
Feature Description
1. Refusal Letter Preparation:
Prepares official refusal letters.
2. Rejection Letter Generation:
Generates rejection letters.
3. Refusal Verification:
Verifies refusal decisions before issuance.
4. Director Approval:
Obtains Director approval for refusals.
5. Customer Notification:
Notifies applicants of refusal or rejection.
Module-14. Notification (Total Feature - 7)
Feature Description
1. Shortfall Notification:
Sends notifications regarding missing documents.
2. Audit Schedule Notification:
Informs applicants about audit schedules.
3. Observation Notification:
Notifies applicants of audit findings.
4. Payment Request Notification:
Sends payment reminders.
5. Conditional Approval Notification:
Notifies applicants of conditional approvals.
6. Certificate Issued Notification:
Confirms certificate issuance.
7. Rejection/Refusal Notification:
Notifies applicants of rejection decisions.
Module-15. Workflow & Task Management (Total Feature - 6)
Feature Description
1. Role-based Task Assignment:
Assigns tasks according to user roles.

                                             121
```

## Page 123

```text
2. Multi-Level Workflow:
Supports hierarchical approval workflows.
3. Application Forwarding:
Routes applications between workflow stages.
4. Status Tracking:
Tracks the progress of every application.
5. Workflow Remarks:
Records workflow comments.
6. Audit Trail:
Maintains a complete audit history.
Module-16. Document Management (Total Feature - 7)
Feature Description
1. Questionnaire Management:
Stores application questionnaires.
2. Audit Report Management:
Maintains audit reports.
3. Test Report Management:
Stores laboratory reports.
4. Technical Report Management:
Maintains technical evaluation reports.
5. Evidence Upload:
Stores compliance evidence.
6. Refusal Letter Management:
Maintains refusal and rejection letters.
7. Certificate Repository:
Stores issued certificates in a centralized repository.

                                           122
```

## Page 124

```text
  SERVICE
                 CM HALAL BRAND INCLUSION
    13
                 Halal Certification • Audit • Laboratory Testing • Certificate Management

Service Profile
Domain                               Service Type               Primary Users
Certification of Marks (CM)          Regulatory / Certification Applicants • AD • DD • Director •
                                     Service                    Audit Team • Certification
                                                                Committee
Core Scope                           Modules                         Features
Halal Certification Lifecycle
                                     16                              86

Functional Coverage
APPLICATION & REVIEW             AUDIT                                 LABORATORY
• Certificate Application        • Stage-1 Audit                       • Sample Management
• Shortfall Management           •     Audit       Observation      & • Laboratory Testing
• Customer Resubmission          Compliance                            • Test Reports
                                 • Stage-2 Audit & Sample
                                 Management

EVALUATION & APPROVAL            COMPLIANCE & CERTIFICATE CONTROL & RECORDS
• Technical Evaluation           • Conditional Compliance              • Refusal & Rejection
• Verification & Approval        • Payment                             • Notification
• Certification Committee        • Certificate / License               • Workflow
                                                                       • Document Management

Module Catalogue
Sl. Module                                 No. of  Sl. Module                                      No. of
No.                                       Features No.                                            Features
 01 Certificate Application                    4         07   Technical Evaluation                   4
 02 Application Review & Shortfall             8         08   Verification & Approval                5
    Management
 03 Stage-1 Audit Management                   6         09   Certification Committee                5
 04 Audit Observation & Compliance             4         10   Conditional Compliance                 5
 05 Stage-2  Audit          &   Sample         5         11   Payment Processing                     5
    Management
 06 Laboratory Testing                         5         12   Certificate       /       License      5
                                                              Management

                                                   123
```

## Page 125

```text
Service-13: CM Halal Brand Inclusion
The proposed CM Hala Certificate Management System is a comprehensive digital platform
designed to automate and manage the complete certification lifecycle, from online
application submission to certificate issuance. The solution enables applicants to submit
certificate applications, complete initial questionnaires, and monitor application progress
through a centralized online portal. Applications undergo a structured multi-level review
process involving Assistant Director (AD), Deputy Director (DD), and Director verification,
with integrated shortfall management to ensure complete and accurate submissions. The
system supports Stage-1 and Stage-2 audit management, including auditor assignment,
audit scheduling, observation recording, compliance monitoring, and sample collection.
Laboratory testing is seamlessly integrated to manage sample registration, testing,
resampling, and report generation. Technical evaluations consolidate audit findings and
laboratory results to produce recommendations for management approval. The certification
committee reviews evaluation outcomes and determines final approval, conditional approval,
re-inspection, or rejection. Conditional compliance workflows enable applicants to submit
corrective actions and supporting evidence before final certification. The solution also
automates payment processing, digital certificate generation, certificate issuance, and record
management. Supporting modules such as workflow management, document management,
and automated notifications ensure transparency, traceability, and efficient communication
throughout the certification process. By digitizing every stage of the certification lifecycle, the
system improves operational efficiency, reduces manual processing, enhances regulatory
compliance, and delivers faster, more transparent certification services.

                                               124
```

## Page 126

```text
Fig: CM Halal Brand Inclusion Service Workflow

                     125
```

## Page 127

```text
Module-1. Certificate Application (Total Feature - 4)
Feature Description
1. Online Certificate Application:
Enables applicants to submit certificate applications electronically.
2. Initial Questionnaire:
Collects preliminary organizational and product information required for assessment.
3. Application Submission:
Finalizes and submits the completed application for review.
4. Application Tracking:
Allows applicants to monitor the progress of their submitted applications.
Module-2. Application Review & Shortfall Management (Total Feature
- 8)
Feature Description
1. Director Review:
Enables Director-level review and approval recommendations.
2. DD Review:
Supports Deputy Director verification of submitted applications.
3. AD Review:
Allows Assistant Director to perform detailed document verification.
4. Inspector Assignment:
Assigns inspectors or auditors for audit activities.
5. Application Review:
Reviews submitted documents for completeness and compliance.
6. Shortfall Identification:
Identifies missing documents or compliance issues.
7. Shortfall Notification:
Notifies applicants about deficiencies requiring correction.
8. Customer Resubmission:
Allows applicants to submit corrected information and documents.
Module-3. Stage-1 Audit Management (Total Feature - 6)
Feature Description
1. Stage-1 Audit Scheduling:
Plans and schedules the initial audit.
2. Auditor/Inspector Assignment:
Assigns qualified auditors or inspectors.

                                            126
```

## Page 128

```text
3. Stage-1 Audit Execution:
Records audit activities conducted during Stage-1.
4. Stage-1 Audit Report Generation:
Generates the official Stage-1 audit report.
5. Observation Recording:
Captures audit observations and findings.
6. Audit Findings:
Records non-conformities and audit conclusions.
Module-4. Audit Observation & Compliance (Total Feature - 4)
Feature Description
1. Observation Notification:
Notifies applicants regarding audit observations.
2. Evidence Submission:
Allows applicants to upload corrective evidence.
3. Evidence Verification by AD:
Enables Assistant Director to verify submitted evidence.
4. Compliance Tracking:
Tracks corrective action progress until closure.
Module-5. Stage-2 Audit & Sample Management (Total Feature - 5)
Feature Description
1. Stage-2 Audit Scheduling:
Schedules the final certification audit.
2. Stage-2 Audit Execution:
Conducts the Stage-2 audit.
3. Stage-2 Audit Report Generation:
Generates the Stage-2 audit report.
4. Sample Collection:
Records sample collection during the audit.
5. Sample Handover to AD:
Tracks sample handover for laboratory processing.
Module-6. Laboratory Testing (Total Feature - 5)
Feature Description
1. Sample Forwarding to Laboratory:
Sends collected samples to the laboratory.
2. Sample Registration:
Registers samples with unique tracking identifiers.

                                           127
```

## Page 129

```text
3. Resampling Request:
Requests additional samples when necessary.
4. Test Execution:
Performs laboratory testing according to approved standards.
5. Test Report Generation:
Produces official laboratory test reports.
Module-7. Technical Evaluation (Total Feature - 4)
Feature Description
1. Test Report Review:
Reviews laboratory testing results.
2. Audit Report Compilation:
Consolidates audit findings into a technical assessment.
3. Technical Report Generation:
Generates the official technical evaluation report.
4. Technical Recommendation:
Provides recommendations for approval or rejection.
Module-8. Verification & Approval (Total Feature - 5)
Feature Description
1. DD Verification:
Verifies technical evaluation results.
2. Technical Checklist Preparation:
Prepares standardized evaluation checklists.
3. Director Approval:
Enables final approval by the Director.
4. Workflow Remarks:
Records review comments and observations.
5. Approval History:
Maintains a complete history of approvals.
Module-9. Certification Committee (Total Feature - 5)
Feature Description
1. Committee Review:
Facilitates committee review of evaluated applications.
2. Final Approval:
Grants final certification approval.
3. Conditional Approval:
Approves applications with specified conditions.

                                             128
```

## Page 130

```text
4. Re-inspection Decision:
Determines whether another audit is required.
5. Application Rejection:
Rejects applications that fail to meet certification requirements.
Module-10. Conditional Compliance (Total Feature - 5)
Feature Description
1. Conditional Issue Notification:
Notifies applicants of approval conditions.
2. Corrective Action Submission:
Allows applicants to submit corrective actions.
3. Evidence Upload:
Supports uploading compliance evidence.
4. Compliance Verification:
Verifies submitted corrective actions.
5. Re-verification Request:
Initiates additional verification when required.
Module-11. Payment Processing (Total Feature - 5)
Feature Description
1. Certificate/License Fee Request:
Generates payment requests.
2. Payment Notification:
Notifies applicants regarding pending payments.
3. Payment Collection:
Records payment received.
4. Payment Verification:
Verifies payment through integrated payment services.
5. Payment Confirmation:
Confirms successful payment.
Module-12. Certificate / License Management (Total Feature - 5)
Feature Description
1. Certificate/License Generation:
Generates approved certificates or licenses.
2. Certificate Number Generation:
Automatically assigns unique certificate numbers.
3. Digital Certificate Issuance:
Issues digitally signed certificates.

                                          129
```

## Page 131

```text
4. Certificate Download:
Allows applicants to download certificates.
5. Certificate Record Management:
Maintains centralized certificate records.
Module-13. Refusal & Rejection Management (Total Feature - 5)
Feature Description
1. Refusal Letter Preparation:
Prepares official refusal letters.
2. Rejection Letter Generation:
Generates rejection letters.
3. Refusal Verification:
Verifies refusal decisions before issuance.
4. Director Approval:
Obtains Director approval for refusals.
5. Customer Notification:
Notifies applicants of refusal or rejection.
Module-14. Notification (Total Feature - 7)
Feature Description
1. Shortfall Notification:
Sends notifications regarding missing documents.
2. Audit Schedule Notification:
Informs applicants about audit schedules.
3. Observation Notification:
Notifies applicants of audit findings.
4. Payment Request Notification:
Sends payment reminders.
5. Conditional Approval Notification:
Notifies applicants of conditional approvals.
6. Certificate Issued Notification:
Confirms certificate issuance.
7. Rejection/Refusal Notification:
Notifies applicants of rejection decisions.
Module-15. Workflow & Task Management (Total Feature - 6)
Feature Description
1. Role-based Task Assignment:
Assigns tasks according to user roles.

                                             130
```

## Page 132

```text
2. Multi-Level Workflow:
Supports hierarchical approval workflows.
3. Application Forwarding:
Routes applications between workflow stages.
4. Status Tracking:
Tracks the progress of every application.
5. Workflow Remarks:
Records workflow comments.
6. Audit Trail:
Maintains a complete audit history.
Module-16. Document Management (Total Feature - 7)
Feature Description
1. Questionnaire Management:
Stores application questionnaires.
2. Audit Report Management:
Maintains audit reports.
3. Test Report Management:
Stores laboratory reports.
4. Technical Report Management:
Maintains technical evaluation reports.
5. Evidence Upload:
Stores compliance evidence.
6. Refusal Letter Management:
Maintains refusal and rejection letters.
7. Certificate Repository:
Stores issued certificates in a centralized repository.

                                           131
```

## Page 133

```text
  SERVICE
                CHEMICAL TESTING
    14
                Sample Testing • Verification • Re-Test • Report Delivery

Service Profile
Domain                            Service Type                    Primary Users
Chemical Wing Testing             Laboratory Testing Service      Applicant • OSS • Director
                                                                  (Chemical) • DD • AD • Examiner
                                                                  / Senior Examiner
Core Scope                        Modules                         Features
Laboratory Testing Lifecycle
                                  20                              67

Functional Coverage
SAMPLE MANAGEMENT               VERIFICATION                        REPORTING
• Sample Tracking               • Multi-Level Verification          • Report Generation
• Resample Management           • Correction & Return               • Report Delivery
• Sample Security               • Re-Test Management                • Remarks & Comment

WORKFLOW                        SECURITY & ACCESS                   MONITORING
• Workflow Engine               • Access Control                    • Dashboard
• Task Management               • Data Security                     • Audit & Activity Log
• Regional Office Workflow      • Multiple Role Management          • Search
                                                                    • Localization

Module Catalogue
Sl. Module                              No. of  Sl. Module                                    No. of
No.                                    Features No.                                          Features
 01 Sample Tracking                        4         07   Notification                          4
 02 Resample Management                    4         08   Remarks & Comment                     4
 03 Sample Security                        3         09   Report Generation                     3
 04 Multi-Level Verification               4         10   Task Management                       3
 05 Correction & Return                    4         11   Dashboard                             3
 06 Re-Test Management                     3         12   Audit & Activity Log                  4

                                               132
```

## Page 134

```text
Service-14: Chemical Testing Feature Description
The proposed Chemical Wing Testing Service Management System is a comprehensive
digital platform designed to automate and manage the complete laboratory testing lifecycle,
from sample registration to final report delivery. The system generates unique sample
tracking IDs, automatic serial numbers, and fiscal year-based sequences while ensuring
complete sample traceability throughout the testing process.
The solution supports resample and re-test management through structured workflow
loops, enabling sample resubmission, reassignment, and updated test results. A multi-level
verification process allows Examiners, Deputy Directors, and Directors to review, verify,
approve, or return reports for correction through an efficient desk-to-desk workflow. Secure
sample handling, data encryption, confidential information protection, and role-based access
control ensure compliance with security and regulatory requirements.
The system provides real-time email, SMS, and in-app notifications, enabling applicants and
officials to monitor testing progress. Users can record remarks, verification comments, review
notes, and change instructions at every stage of the workflow. Additional capabilities include
automated PDF report generation with digital signature support, controlled report delivery
based on applicant type, advanced search and filtering, role-based task management,
operational   dashboards,    comprehensive    audit   trails,   and   configurable   workflow
management. With bilingual Bangla and English support, multiple role assignments, and
dedicated workflows for both Head Office and Regional Offices, the system enhances
operational efficiency, transparency, accuracy, and accountability in the Chemical Wing
Testing Service.

                                             133
```

## Page 135

```text
Figure Name: Workflow of Chemical Testing Service

                      134
```

## Page 136

```text
Module-1. Sample Tracking (Total Feature - 4)
Features Description
1. Unique Sample Tracking ID Generation
Automatically generates a unique tracking ID for every registered sample to ensure accurate
identification and tracking throughout the testing lifecycle.
2. Auto Serial Number Generation
Generates sequential serial numbers automatically based on predefined business rules,
eliminating manual numbering errors.
3. Sample Traceability
Maintains complete traceability of each sample by recording every movement, processing
stage, and responsible user within the system.
4. Fiscal Year-wise Sequence Management
Manages sample numbering sequences separately for each fiscal year to ensure organized
record-keeping and regulatory compliance.
Module-2. Resample Management (Total Feature - 4)
Features Description
1. Resample Decision
Allows authorized officials to initiate a resample process when the original sample is found
unsuitable or requires further verification.
2. New Tracking ID Generation
Automatically generates a new tracking ID for each resubmitted sample while maintaining
linkage with the original application.
3. Resample Workflow Loop
Supports a complete resample workflow by routing the application through the required
processing stages until completion.
4. Sample Re-submission Management
Enables applicants or authorized personnel to submit replacement samples while preserving
previous submission history.
Module-3. Sample Security (Total Feature - 3)
Features Description
1. Sample Encryption
Secures sensitive sample information using encryption techniques to prevent unauthorized
access during processing and storage.
2. Secure Data Handling
Ensures that all sample-related data is processed, transferred, and stored following
established security standards.

                                               135
```

## Page 137

```text
3. Confidential Information Protection
Protects confidential laboratory and applicant information through controlled access and
secure data management practices.
Module-4. Multi-Level Verification (Total Feature - 4)
Features Description
1. Result Verification
Allows designated officers to verify laboratory test results before proceeding to the next
approval stage.
2. DD Verification
Enables the Deputy Director (DD) to review and validate verified test reports for regulatory
compliance.
3. File Note Preparation
Allows authorized officers to prepare official file notes containing observations,
recommendations, and verification outcomes.
4. Director Approval Workflow
Routes verified reports and file notes to the Director for final review and approval through a
structured workflow.
Module-5. Correction & Return (Total Feature - 4)
Features Description
1. Send Back Option
Allows reviewers to return applications or reports to previous users for correction or
additional information.
2. Desk-to-Desk Routing
Supports seamless routing of applications between different user desks according to the
defined workflow.
3. Change Request Management
Enables reviewers to raise correction requests and monitor their completion throughout the
workflow.
4. Previous Step Return Support
Allows applications to be returned to any previous workflow stage while maintaining
complete processing history.
Module-6. Re-Test Management (Total Feature - 3)
Features Description
1. Re-Test Request by Director
Allows the Director to request a re-test whenever additional verification or confirmation of
results is required.

                                            136
```

## Page 138

```text
2. Re-Test Workflow
Supports a complete re-testing workflow from assignment to final result verification and
approval.
3. Test Reassignment and Result Update
Allows laboratory tests to be reassigned to authorized personnel and updates the final test
results accordingly.
Module-7. Notification (Total Feature - 4)
Features Description
1. Email Notification
Automatically sends email notifications for workflow events, approvals, and application
status updates.
2. SMS Notification
Delivers SMS alerts to users regarding important workflow activities and processing
milestones.
3. In-App Notification
Displays real-time notifications within the system dashboard to keep users informed of
pending actions.
4. Real-Time Status Update
Provides instant status updates whenever application or sample processing progresses to
the next stage.
Module-8. Remarks & Comment (Total Feature - 4)
Features Description
1. Remarks Entry
Allows users to record observations, comments, and recommendations at different workflow
stages.
2. Verification Comments
Enables reviewers to document verification findings and additional clarification for future
reference.
3. Review Notes
Allows reviewing officers to maintain structured notes throughout the evaluation and
approval process.
4. Change Instructions
Provides clear correction instructions to responsible users whenever modifications are
required.
Module-9. Report Generation (Total Feature - 3)

                                           137
```

## Page 139

```text
Features Description
1. Automated PDF Report Generation
Automatically generates standardized PDF reports using approved templates and validated
laboratory data.
2. Report Download Facility
Allows authorized users and applicants to securely download generated reports from the
system.
3. Digital Signature Support
Supports digitally signed reports to ensure document authenticity, integrity, and legal
validity.
Module-10. Task Management (Total Feature - 3)
Features Description
1. Role-based Inbox
Provides each user with a personalized inbox displaying tasks based on assigned roles and
responsibilities.
2. Pending Task Management
Allows users to monitor, prioritize, and complete pending workflow tasks efficiently.
3. User-wise Work Queue
Maintains separate work queues for each user to facilitate effective task distribution and
workload management.
Module-11. Dashboard (Total Feature - 3)
Features Description
1. Role-wise Dashboard
Displays customized dashboards with relevant information according to each user's assigned
role.
2. Work Monitoring
Provides real-time monitoring of ongoing activities, pending tasks, and workflow
performance.
3. Status Summary and Reporting
Presents summarized statistics and graphical reports to support operational monitoring and
decision-making.
Module-12. Audit & Activity Log (Total Feature - 4)
Features Description
1. Full Audit Trail
Maintains a complete audit trail of all system activities for transparency and regulatory
compliance.
2. Activity History
Records chronological histories of user activities and workflow events for future reference.

                                            138
```

## Page 140

```text
3. User Action Tracking
Tracks every user action performed within the system to ensure accountability and
traceability.
4. Data Change Log
Captures all modifications made to application and laboratory data, including timestamps
and responsible users.
Module-13. Workflow Engine (Total Feature - 3)
Features Description
1. Dynamic Workflow Configuration
Allows administrators to configure and modify workflow processes without requiring system
redevelopment.
2. Loop Support
Supports workflow loops such as correction, resubmission, re-inspection, and re-testing
whenever required.
3. Future Workflow Flexibility
Provides a scalable workflow architecture capable of accommodating future business
process changes.
Module-14. Search (Total Feature - 4)
Features Description
1. Advanced Search
Allows users to perform comprehensive searches using multiple search criteria
simultaneously.
2. Filter Option
Provides advanced filtering capabilities to quickly locate applications, reports, or samples.
3. Sample Tracking Search
Enables users to search samples instantly using tracking IDs or other identifying information.
4. Report Search Facility
Allows users to retrieve laboratory reports efficiently using various search parameters.
Module-15. Access Control (Total Feature - 3)
Features Description
1. Role-Based Access Control (RBAC)
Restricts system access based on predefined user roles and assigned responsibilities.
2. User Permission Management
Allows administrators to manage user permissions and control access to specific system
functions.
3. Security Control
Implements security measures to prevent unauthorized access and protect sensitive system
resources.

                                             139
```

## Page 141

```text
Module-16. Localization (Total Feature - 2)
Features Description
1. Bangla and English Support
Supports both Bangla and English languages to improve accessibility for different user
groups.
2. Bilingual Interface
Provides a bilingual user interface with seamless language switching throughout the system.
Module-17. Data Security (Total Feature - 3)
Features Description
1. Data Encryption
Encrypts sensitive data during storage and transmission to maintain information security.
2. Secure Storage
Stores system data securely using industry-standard security mechanisms and backup
strategies.
3. Confidential Data Protection
Ensures confidential information is accessible only to authorized users through strict access
controls.
Module-18. Report Delivery (Total Feature - 3)
Features Description
1. CM vs Govt/Private Delivery Logic
Supports configurable report delivery processes based on applicant type, including CM,
Government, and Private organizations.
2. Applicant Notification
Automatically informs applicants when laboratory reports are generated and ready for
access.
3. Report Access Control
Restricts report access to authorized users while ensuring secure distribution of sensitive
information.
Module-19. Multiple Role Management (Total Feature - 3)
Features Description
1. Multiple Role Assignment
Allows a single user to hold multiple system roles based on organizational responsibilities.
2. AD Acting as Examiner
Enables Assistant Directors to perform Examiner responsibilities whenever operationally
required.
3. Flexible User Responsibility
Supports dynamic assignment of responsibilities to ensure uninterrupted workflow and
efficient resource utilization.

                                            140
```

## Page 142

```text
Module-20. Regional Office Workflow (Total Feature - 3)
Features Description
1. Head Office Workflow
Supports centralized workflow management for applications and laboratory activities
processed by the Head Office.
2. Regional Office Workflow
Enables Regional Offices to independently process assigned applications while following
the centralized workflow.
3. Wing Head-Centric Processing
Allows Wing Heads to monitor, verify, and approve workflow activities within their
respective wings while maintaining organizational governance.

                                          141
```

## Page 143

```text
  SERVICE
               PHYSICAL TESTING
    15
               Laboratory Testing • Sample Management • Test Results • Report Delivery

Service Profile
Domain                           Service Type                  Primary Users
Physical Wing Testing            Laboratory Testing Service    Applicant • OSS • Director • DD •
                                                               AD • Examiner / Senior Examiner
Core Scope                    Modules                          Features
Physical Testing & Laboratory
Management
                              10                               72

Functional Coverage
APPLICATION                   SAMPLES                           TESTING
• Application Management      • Sample Management               • Parameter Management
• User & Role Management      • Energy Meter Management         • Test & Result Management
                                                                •    Product      &   Laboratory
                                                                Management

REPORTING                     WORKFLOW                          CONTROL
• Report Management           • Workflow Management             • User & Role Management
• Notification Management     • Role-Based Processing           • Testing Records
                                                                • Activity Tracking

Module Catalogue
Sl. Module                            No. of  Sl. Module                                  No. of
No.                                  Features No.                                        Features
 01 User & Role Management               9         06   Test & Result Management            7
 02 Application Management               7         07   Report Management                   9

 03 Sample Management                    6         08   Notification Management             5

 04 Workflow Management                  7         09   Energy Meter Management             10

 05 Parameter Management                 6         10   Product    &        Laboratory      6
                                                        Management

                                             142
```

## Page 144

```text
Service-15: Physical Testing
The proposed Physical Wing Testing Management System is a comprehensive digital
platform designed to automate and streamline the complete laboratory testing process, from
application submission and sample registration to test report generation and delivery. The
system enables applicants to submit testing requests online, upload required documents,
complete application payments, and track application status through a centralized portal.
Each application is assigned a unique registration ID, while samples are securely received,
encrypted, and managed throughout the testing lifecycle, including resample requests and
sample collection scheduling for Energy Meter testing.
The solution supports a structured workflow where applications and test results progress
through Director, DD, AD, and Examiner approval stages with forward, send-back, correction,
retest, and backward workflow capabilities. Examiners perform laboratory testing, record
test results, attach raw data, and submit findings for multi-level verification before
generating standardized test reports. The system also manages product information,
laboratory assignments, BDS standards, testing parameters, and standard limit validation to
ensure accurate and compliant testing procedures.
Specialized Energy Meter testing features include shortfall management, sample collection
workflows, retest management, meter-based certification, quantity-based pass/fail logic,
and multiple certificate generation options. The platform further provides automated
notifications, dynamic report generation, role-based access control, dashboards, and
comprehensive tracking of applications, samples, and testing activities. Overall, the system
delivers a secure, paperless, workflow-driven environment that enhances operational
efficiency, traceability, transparency, and service quality for Physical Wing Testing services.

                                             143
```

## Page 145

```text
Figure Name: Physical Testing Workflow diagram

                     144
```

## Page 146

```text
Module-1. User & Role Management (Total Feature - 9)
Features Description
1. Applicant Role
Provides applicants with access to submit applications, upload documents, make payments,
track application status, and download approved test reports.
2. OSS Dashboard
Provides the One Stop Service (OSS) dashboard displaying pending applications, sample
receiving tasks, report delivery status, and workflow activities.
3. OSS Role
Allows OSS users to receive applications and samples, verify submitted documents, manage
report delivery, and communicate with applicants.
4. Director (Chemical/Physical) Role
Enables the Director to assign testing parameters, monitor laboratory activities, review
reports, and approve testing workflows.
5. DD Role
Allows the Deputy Director to verify test results, review reports, approve workflow stages,
and monitor laboratory operations.
6. AD Role
Enables the Assistant Director to review examiner submissions, verify laboratory results, and
forward reports for higher-level approval.
7. Examiner/Senior Examiner Role
Allows examiners to perform laboratory tests, enter test results, upload raw data, and submit
findings for verification.
8. System Admin Role
Provides administrators with full control over user management, role assignment, system
configuration, master data, and application settings.
9. User Dashboard
Displays personalized dashboards showing assigned tasks, pending approvals, notifications,
and application progress based on user roles.

Module-2. Application Management (Total Feature - 7)
Features Description
1. Application Submission
Allows applicants to submit laboratory testing applications online with the required
information and supporting documents.
2. Payment Management
Supports online payment processing, payment verification, and payment status tracking for
submitted applications.

                                             145
```

## Page 147

```text
3. Document Upload
Enables applicants to upload required documents and supporting files securely during the
application process.
4. Application Registration
Registers submitted applications after successful verification and assigns them for further
processing.
5. Unique Application ID Generation
Automatically generates a unique application identification number for tracking and
reference purposes.
6. Application Status Tracking
Allows applicants and officials to monitor the real-time status of applications throughout the
testing workflow.
7. Application Source Management (CM Wing/Govt./Private)
Records and categorizes applications based on their source, such as CM Wing, Government
Organizations, or Private Organizations.
Module-3. Sample Management (Total Feature - 6)
Features Description
1. Sample Receiving by OSS
Allows OSS officials to receive, verify, and register submitted samples for laboratory testing.
2. Sample Encryption
Assigns encrypted sample identification to maintain confidentiality and ensure unbiased
laboratory testing.
3. Resample Request
Allows authorized officials to request additional or replacement samples when required.
4. Resample Submission & Receiving
Enables applicants to submit replacement samples and allows OSS to receive and register
them.
5. Sample Collection Scheduling (Energy Meter)
Supports scheduling of field sample collection for Energy Meter testing and related
inspection activities.
6. Sample Collection Approval
Allows authorized officials to review and approve sample collection schedules before
execution.
Module-4. Workflow Management (Total Feature - 7)
Features Description
1. Director → DD → AD → Examiner Workflow
Supports a configurable workflow routing applications through Director, DD, AD, and
Examiner based on organizational processes.

                                             146
```

## Page 148

```text
2. Forward Option
Allows users to forward applications, reports, and tasks to the next responsible officer.
3. Send Back Option
Enables reviewers to return applications or reports for correction before approval.
4. Pull Back Option
Allows authorized users to retrieve previously forwarded applications before further
processing.
5. Retest Workflow
Supports the complete workflow for retest requests, approvals, testing, and result
generation.
6. Correction Workflow
Manages report correction requests and routes them through the appropriate approval
process.
7. Backward Workflow Support
Allows applications to move back to previous workflow stages when additional review or
correction is required.
Module-5. Parameter Management (Total Feature - 6)
Features Description
1. Parameter Assignment by Director
Allows the Director to assign laboratory testing parameters based on the submitted
application.
2. Parameter Selection by Examiner
Enables examiners to select applicable testing parameters before conducting laboratory
tests.
3. Standard Limit Management
Maintains standard testing limits according to approved BSTI standards and specifications.
4. Client Declared Value Management
Records and manages client-declared parameter values for comparison during testing.
5. Parameter Validation
Validates assigned parameters to ensure compliance with applicable testing standards.
6. Add/Edit Parameter
Allows authorized users to create, modify, and maintain laboratory testing parameters.
Module-6. Test & Result Management (Total Feature - 7)
Features Description
1. Test Execution
Allows examiners to conduct laboratory testing according to approved testing procedures
and standards.

                                            147
```

## Page 149

```text
2. Test Result Entry
Enables authorized users to record laboratory test results in the system.
3. Raw Data Attachment
Allows examiners to upload raw laboratory data and supporting test documents.
4. AD Verification
Enables the Assistant Director to review and verify submitted laboratory test results.
5. DD Verification
Allows the Deputy Director to review and approve verified laboratory test results.
6. File Note Creation
Supports preparation and management of official file notes related to laboratory testing.
7. Result Correction Request
Allows authorized officials to request corrections to submitted laboratory results when
necessary.
Module-7. Report Management (Total Feature - 9)
Features Description
1. Test Report Generation
Automatically generates laboratory test reports based on approved test results.
2. Report Approval
Supports multi-level approval of laboratory test reports before final release.
3. Report Delivery by OSS
Allows OSS officials to deliver approved reports to applicants through the designated service
channel.
4. Applicant Report Access
Enables applicants to securely view and download approved laboratory reports.
5. Report Edit & Update
Allows authorized users to revise reports before final approval where permitted.
6. Dynamic Report Format
Supports multiple report templates based on product type, laboratory, and testing
requirements.
7. Feedback & Observation Entry
Allows laboratory officials to record observations, comments, and recommendations within
the report.
8. Dynamic Remarks Generation
Automatically generates remarks based on testing outcomes and predefined business rules.
9. Multiple Report Format Generation
Supports generation of reports in different approved formats to meet organizational and
regulatory requirements.

                                            148
```

## Page 150

```text
Module-8. Notification Management (Total Feature - 5)
Features Description
1. Approval Notification
Automatically notifies applicants and officials when applications or reports are approved.
2. Rejection Notification
Sends notifications containing rejection reasons and required corrective actions.
3. Sample Collection Notification
Notifies applicants regarding scheduled sample collection dates and related instructions.
4. Stage-wise Status Notification
Provides automated notifications whenever an application progresses to the next workflow
stage.
5. Pending/Processing/Completed Status Tracking
Allows users to monitor the current processing status of applications and laboratory
activities.
Module-9. Energy Meter Management (Total Feature - 10)
Features Description
1. Shortfall Management
Records and manages application or document shortfalls requiring applicant action.
2. Resubmission After Shortfall
Allows applicants to resubmit corrected documents or information after resolving identified
shortfalls.
3. Sample Collection Workflow
Manages the complete workflow for Energy Meter sample collection, approval, and tracking.
4. Energy Meter Test Execution
Supports laboratory testing of energy meters according to approved BSTI testing procedures.
5. Retest Management
Allows authorized officials to initiate and manage retesting of Energy Meter samples when
required.
6. Meter Number Integration
Records and manages unique meter numbers for identification and traceability during testing.
7. General Certificate Generation
Automatically generates certificates for approved Energy Meter testing results.
8. Product-wise Certificate Generation
Supports certificate generation based on specific product categories and testing outcomes.
9. Meter Range Based Certificate Generation
Generates certificates according to approved meter range classifications and testing
standards.

                                            149
```

## Page 151

```text
10. Quantity Based Pass/Fail Logic
Automatically determines pass or fail status based on predefined quantity-based acceptance
criteria.
Module-10. Product & Laboratory Management (Total Feature - 6)
Features Description
1. Product Management
Allows administrators to create, update, and manage products available for laboratory
testing.
2. Product Variation Management
Supports management of different product variants and testing configurations.
3. Sub Product Management
Allows creation and maintenance of sub-products associated with parent product categories.
4. Office-wise Laboratory Assignment
Assigns laboratory facilities to specific offices based on operational requirements.
5. Parameter-wise Laboratory Mapping
Maps testing parameters to designated laboratories for efficient test allocation.
6. BDS Standard Management
Maintains Bangladesh Standards (BDS) specifications and associates them with applicable
products and testing parameters.

                                             150
```

## Page 152

```text
  SERVICE
               PHYSICAL LAB- ENERGY METER
    16
               Energy Meter Testing • Sample Collection • Result Verification • Test Report

Service Profile
Domain                             Service Type                      Primary Users
Physical Laboratory / Energy Meter Laboratory Testing Service        Applicant • OSS • Director • DD •
                                                                     AD / Senior Examiner • Examiner
Core Scope                            Modules                        Features
Energy Meter Testing Lifecycle
                                      12                             71

Functional Coverage
APPLICATION & SHORTFALL           SAMPLE COLLECTION                   TESTING
• Application Management          •        Sample           Collection • Energy Meter Testing
• Shortfall Management            Management                          • Test Result Entry
• User & Role Management          • Energy Meter Information          • Retest Management

VERIFICATION                      REPORTING                           TRACKING & AUDIT
• Result Verification & Approval • Test Report Management             • Application Tracking
• Workflow Management             • Notification Management           • Sample Tracking
                                                                      • Test Result Tracking
                                                                      • User Activity

Module Catalogue
Sl. Module                                  No. of  Sl. Module                                   No. of
No.                                        Features No.                                         Features
 01 User & Role Management                   7         07    Workflow Management                   6
 02 Application Management                   7         08    Retest Management                     5
 03 Shortfall Management                     5         09    Test Report Management                6
 04 Sample Collection Management             7         10    Notification Management               5
 05 Energy     Meter             Testing     6         11    Energy  Meter       Information       5
    Management                                               Management
 06 Result Verification & Approval           7         12    Tracking & Audit Management           5

                                                 151
```

## Page 153

```text
Service-16: Physical Lab- Energy Meter
The proposed Physical Lab- Energy Meter Testing Management System is a comprehensive
digital platform designed to automate and streamline the complete Energy Meter testing
process, from online application submission and payment to sample collection, laboratory
testing, result verification, approval, retest, and final report delivery. The system enables
applicants to submit testing applications with required documents and payments through a
centralized portal, while providing role-based access to OSS, Director (Physical), DD,
AD/Senior Examiner, and Examiner users. Each application is routed through a structured
workflow where the Director can forward or assign applications to the appropriate testing
personnel for further processing.
The solution supports shortfall management, customer resubmission, sample collection
scheduling and approval, laboratory test execution, result entry, raw data attachment, multi-
level verification, file note creation, and final approval. Examiners can identify application
shortfalls, communicate required corrections to customers, schedule or reschedule sample
collection, collect samples, perform testing, and submit results for verification. AD verifies
the test results, DD verifies the results and prepares the file note, and the Director provides
final approval. The system also supports send-back and pull-back options up to the Director
level, along with retest processing when required.
After final approval, OSS users can access the approved test report and deliver it to the
customer through the designated service channel. If the test result is not approved, the
system automatically notifies the customer regarding the outcome. Overall, the system
provides a secure, paperless, workflow-driven environment that improves transparency,
traceability, testing efficiency, and service delivery for Energy Meter testing.

                                              152
```

## Page 154

```text
Figure: Physical Lab- Energy Meter Workflow diagram

                       153
```

## Page 155

```text
Module-1. User & Role Management (Total Feature - 7)
Features Description
   1. Applicant Role
      Provides applicants with access to submit Energy Meter testing applications, upload
      required documents, make payments, respond to shortfalls, track application status,
      and receive approved test reports.
   2. OSS Role
      Allows OSS users to access processed applications, monitor approved test reports,
      manage report delivery, and deliver final test reports to customers.
   3. Director (Physical) Role
      Enables the Director to review applications, forward or assign applications to
      DD/AD/Examiner, approve sample collection schedules, review test results and file
      notes, and provide final approval.
   4. DD Role
      Allows the Deputy Director to verify test results, prepare and manage file notes,
      approve sample collection schedules, and forward verified results for Director
      approval.
   5. AD/Senior Examiner Role
      Enables AD/Senior Examiner users to review applications, approve sample
      collection schedules, verify examiner test results, and forward results to DD for
      further processing.
   6. Examiner Role
      Allows examiners to review assigned applications, identify shortfalls, schedule
      sample collection, collect samples, perform Energy Meter tests, enter test results,
      and upload raw data.
   7. Role-based Dashboard
      Provides personalized dashboards displaying assigned applications, pending
      actions, approval tasks, sample collection schedules, testing activities, notifications,
      and workflow status according to user roles.
Module-2. Application Management (Total Feature - 7)
Features Description
   1. Application Submission
      Allows applicants to submit Energy Meter testing applications online with the
      required application information and supporting documents.
   2. Payment Management
      Supports online payment submission, payment verification, and tracking of
      application payment status.

                                            154
```

## Page 156

```text
   3. Document Upload
      Enables applicants to securely upload required documents and supporting files
      during the application process.
   4. Application Registration
      Registers submitted applications and makes them available for further review and
      workflow processing after successful submission and payment.
   5. Application Forwarding & Assignment
      Allows the Director (Physical) to forward or assign applications to DD, AD/Senior
      Examiner, or Examiner based on testing requirements.
   6. Application Review
      Allows assigned examiners and authorized officials to review application
      information and submitted documents before proceeding with testing activities.
   7. Application Status Tracking
      Allows applicants and authorized officials to monitor the current status and
      processing stage of applications throughout the Energy Meter testing lifecycle.
Module-3. Shortfall Management (Total Feature - 5)
Features Description
   1. Shortfall Identification
      Allows the Examiner to identify missing, incorrect, or insufficient information and
      documents during application review.
   2. Shortfall Notification
      Automatically communicates identified shortfalls to the customer along with the
      required corrective actions.
   3. Customer Shortfall Rectification
      Allows customers to correct identified deficiencies and provide the required
      information or documents.
   4. Shortfall Resubmission
      Enables customers to resubmit corrected documents or information after resolving
      the identified shortfall.
   5. Shortfall Verification
      Allows the Examiner to review and verify the customer's resubmitted information
      before continuing the application workflow.
Module-4. Sample Collection Management (Total Feature - 7)
Features Description
   1. Sample Collection Scheduling
      Allows the Examiner to set a suitable sample collection date based on testing
      requirements and operational availability.

                                           155
```

## Page 157

```text
   2. Sample Collection Rescheduling
      Enables the Examiner to modify or reschedule the sample collection date when
      required.
   3. Sample Collection Approval
      Allows AD/Senior Examiner, DD, and Director to review and approve the proposed
      sample collection date.
   4. Customer Collection Notification
      Automatically notifies the customer about the approved sample collection date and
      related instructions.
   5. Sample Collection Tracking
      Maintains the schedule and status of Energy Meter sample collection activities
      throughout the testing process.
   6. Sample Receiving & Registration
      Allows authorized users to record received Energy Meter samples and associate
      them with the relevant application.
   7. Sample Identification & Traceability
      Maintains unique sample identification and links samples with applications, testing
      activities, results, and reports for complete traceability.
Module-5. Energy Meter Testing Management (Total Feature - 6)
Features Description
   1. Test Assignment
      Provides assigned examiners with access to Energy Meter applications and samples
      for conducting the required laboratory tests.
   2. Test Execution
      Allows examiners to perform Energy Meter testing according to applicable testing
      procedures and approved requirements.
   3. Test Result Entry
      Enables examiners to record Energy Meter test results and relevant testing
      observations in the system.
   4. Raw Data Attachment
      Allows examiners to upload raw laboratory data, test records, and supporting
      documents associated with the performed tests.
   5. Test Result Submission
      Enables examiners to submit completed test results and supporting raw data for AD
      verification.
   6. Test Activity Tracking
      Maintains records of testing activities, assigned examiners, test dates, results, and
      workflow progression for audit and traceability purposes.

                                             156
```

## Page 158

```text
Module-6. Result Verification & Approval (Total Feature - 7)
Features Description
   1. AD Result Verification
      Allows the AD/Senior Examiner to review and verify test results and attached raw
      data submitted by the Examiner.
   2. DD Result Verification
      Enables the Deputy Director to review and verify the results after completion of AD-
      level verification.
   3. File Note Creation
      Allows the DD to create and manage official file notes associated with the Energy
      Meter test results and approval process.
   4. Director Result Approval
      Enables the Director (Physical) to review and provide final approval for the test
      result and associated file note.
   5. Result Rejection
      Allows authorized officials to reject test results when they do not meet the required
      criteria or approval conditions.
   6. Customer Result Notification
      Automatically notifies the customer when the test result is not approved, including
      the applicable outcome or next action.
   7. Result Approval Tracking
      Maintains complete records of verification, approval, rejection, dates, remarks, and
      responsible officials throughout the result approval process.
Module-7. Workflow Management (Total Feature - 6)
Features Description
   1. Role base Workflow
      Supports structured routing of Energy Meter applications and test results through
      Director, DD, AD/Senior Examiner, and Examiner based on the defined
      organizational workflow.
   2. Forward Option
      Allows authorized users to forward applications, sample collection requests, test
      results, and file notes to the next responsible user or approval stage.
   3. Send Back Option
      Enables authorized users to send applications, sample collection requests, results,
      or file notes back to the previous stage for correction or additional review.
   4. Pull Back Option
      Allows authorized users to retrieve previously forwarded applications or workflow
      items before further processing, where permitted.

                                            157
```

## Page 159

```text
   5. Approval Workflow
      Manages the complete approval sequence from application assignment and sample
      collection approval through test result verification and final Director approval.
   6. Workflow History
      Maintains a complete chronological history of forwarding, sending back, pulling
      back, verification, approval, rejection, and other workflow actions.
Module-8. Retest Management (Total Feature - 5)
Features Description
   1. Retest Request
      Allows authorized officials to initiate a retest when the Energy Meter test result
      requires additional testing or verification.
   2. Retest Approval
      Supports review and approval of retest requests by authorized officials according to
      the defined workflow.
   3. Retest Sample Management
      Allows the system to associate the required sample and testing information with
      the retest process.
   4. Retest Execution & Result Entry
      Enables examiners to perform the required retest and record the new test results
      and supporting raw data.
   5. Retest Result Verification
      Routes retest results through the defined AD, DD, and Director verification and
      approval workflow before final report generation.
Module-9. Test Report Management (Total Feature - 6)
Features Description
   1. Test Report Generation
      Generates the Energy Meter test report based on the approved laboratory test
      results.
   2. Report Approval
      Ensures that test reports are generated and released only after completion of the
      required result approval process.
   3. OSS Report Access
      Provides OSS users with access to approved test reports for customer delivery.
   4. Report Delivery to Customer
      Allows OSS officials to deliver approved test reports to the respective customer
      through the designated service channel.

                                             158
```

## Page 160

```text
     5. Applicant Report Access
        Enables customers to receive and access their approved Energy Meter test reports
        through the applicable service channel.
     6. Report Status Tracking
        Maintains the status of test reports from generation and approval through OSS
        access and final delivery to the customer.
Module-10. Notification Management (Total Feature - 5)
Features Description
     1. Application Status Notification
        Provides applicants with notifications regarding important changes in their
        application processing status.
     2. Shortfall Notification
        Notifies customers when additional information, documents, or corrections are
        required to proceed with the application.
     3. Sample Collection Notification
        Automatically notifies customers regarding approved or rescheduled sample
        collection dates.
     4. Result Approval/Rejection Notification
        Notifies customers when the test result has been approved or not approved by the
        competent authority.
     5. Report Delivery Notification
        Notifies customers when the approved Energy Meter test report is available for
        delivery or access through the designated service channel.
Module-11. Energy Meter Information Management (Total Feature -
5)
Features Description
     1. Energy Meter Information
        Records and maintains essential Energy Meter information associated with each
        testing application and sample.
     2. Meter Identification Management
        Maintains unique meter identification information to ensure proper association
        between the meter, sample, application, test, and report.
     3. Product/Model Information
        Records Energy Meter product and model information required for testing and
        reporting purposes.
     4. Test Parameter Management
        Maintains applicable testing parameters and requirements for Energy Meter
        laboratory testing.

                                             159
```

## Page 161

```text
   5. Testing Record Management
        Maintains complete historical records of Energy Meter applications, samples, testing
        results, approvals, retests, and reports.
Module-12. Tracking & Audit Management (Total Feature - 5)
Features Description
   1. Application Tracking
        Provides end-to-end tracking of applications from submission, payment, review,
        testing, approval, and report delivery.
   2. Sample Tracking
   3.
        Tracks sample scheduling, collection, receiving, testing, retesting, and final status.
   4. Test Result Tracking
        Maintains the complete lifecycle of test results from examiner entry through AD,
        DD, and Director verification and approval.
   5. User Activity Tracking
        Records important activities performed by applicants, OSS, Director, DD, AD/Senior
        Examiner, and Examiner users.
   6. Workflow Audit Trail
        Maintains a detailed audit trail of workflow actions, including forwarding, sending
        back, pulling back, approvals, rejections, corrections, and retest activities.

                                               160
```

## Page 162

```text
  SERVICE
                MSC CERTIFICATION
    17
                Management System Certification • Audit • Corrective Action • Certification

Service Profile
Domain                          Service Type                  Primary Users
Management System Certification Certification / Audit Service Applicant • DD (DC) • DCO • IAO
(MSC)                                                         • DD (IA) • Head of MSC • Audit
                                                              Team • DG • Certification
                                                              Committee
Core Scope                            Modules                      Features
Complete   MSC        Certification
Lifecycle
                                      24                           174

Functional Coverage
APPLICATION                      AGREEMENT & PLANNING             AUDIT & CORRECTIVE ACTION
• MSC Application                • Acceptance & Agreement         • Stage-1 Audit
• Payment & Documents            • Man-Day Calculation            • Corrective Action
• Adequacy Audit                 • Audit Scheduling               • Stage-2 Audit
                                                                  • Findings Closure
CERTIFICATION                    CERTIFICATE & FOLLOW- DIGITAL CONTROL
• Technical Proposal             UP                       • Workflow
• Billing                        • Certificate Generation • Notifications
• Certification Committee        • Rejection / Rework     • Tracking
• Minutes                        • Follow-Up Audit        • Dashboard
                                                          • Audit Trail
                                                          • QR Verification

Module Catalogue
Sl. Module                                  No. of  Sl. Module                                 No. of
No.                                        Features No.                                       Features
 01 MSC Application Management               6         07   Corrective Action Management         9
                                                            Module
 02 Application  Payment    and              6         08   Stage-2 Audit Notice       and       8
    Document Management Module                              Scheduling Module
 03 Application Review and Adequacy          8         09   Stage-2   Audit   Management         8
    Audit Module                                            Module
 04 Acceptance  and   Agreement              8         10   Stage-2 Corrective Action and        8
    Management Module                                       Findings Closure Module
 05 Man-Day Calculation and Audit            7         11   Initial Certification Proposal       6
    Scheduling Module                                       Management Module
 06 Stage-1     Audit       Management       8         12   Audit and Certification Billing      9
    Module                                                  Module

                                                 161
```

## Page 163

```text
Service-17: MSC Certification
The proposed MSC Certification Management System is a comprehensive digital platform
designed to automate and manage the complete MSC certification lifecycle, from online
application submission to certificate issuance and verification. The system enables applicants
to register, submit certification applications, upload required documents, and complete online
payments while providing real-time application tracking and automated workflow routing.
Applications undergo a structured review and adequacy audit process, allowing BSTI
officials to verify submissions, identify deficiencies, request corrections, and manage
resubmission cycles with automated notifications.
Following successful application review, the system manages agreement preparation, man-
day calculation, audit scheduling, and Stage-1 and Stage-2 audit processes. Audit teams
prepare audit plans, conduct on-site assessments, record findings, and generate audit
reports, while applicants submit corrective actions and supporting evidence through an
integrated corrective action management workflow. Multi-level verification and approval
processes ensure compliance before certification proposals are reviewed by the Certification
Committee. The system also supports committee meeting management, meeting minutes,
billing, online payment verification, and certificate generation with digital approval.
Generated certificates include QR-code-based public verification to ensure authenticity and
transparency.
The solution incorporates role-based access control, workflow automation, audit trails,
dashboards, reporting, and integration with payment gateways, digital signatures, SMS,
email, and existing BSTI eService modules. Overall, the system provides a centralized,
paperless, secure, and workflow-driven environment that enhances operational efficiency,
transparency, compliance, and service delivery for MSC Certification services.

                                            162
```

## Page 164

```text
Figure Name: MSC Certification Management

                  163
```

## Page 165

```text
Module-1: MSC Application Management (Total Feature - 6)
Features Description
1 Applicant Registration and Login
Enables applicants to securely register and log in to the MSC Certification Portal using
authenticated credentials. The system ensures secure user access and personalized
application management.
2 Online MSC Certification Application Form Submission
Allows applicants to complete and submit the MSC certification application electronically
through a structured online form. The system validates mandatory information before
submission.
3 Application Tracking Number Generation
Automatically generates a unique application tracking number upon successful submission.
This reference number enables applicants and BSTI officials to track the application
throughout the certification process.
4 Draft, Submit and Resubmit Application Facility
Allows applicants to save applications as drafts before final submission. Applicants can also
update and resubmit applications when additional information or corrections are requested
during the review process.
5 Application Status Tracking
Provides real-time visibility into the current status of the application, including submitted,
under review, pending correction, approved, or rejected. This helps applicants monitor
progress without manual follow-up.
6 Automatic Routing of Submitted Application to DD (DC)
Automatically forwards submitted applications to the designated Deputy Director (DD-DC)
based on the predefined workflow. This ensures timely review and eliminates manual
assignment delays.
Module-2: Application Payment and Document Management Module
(Total Feature - 6)
Features Description
1. Upload Required Application Documents
Allows applicants to upload all mandatory supporting documents required for MSC
certification. The system ensures documents are securely stored and linked to the
corresponding application.
2. Document Validation and Verification Support
Provides tools for BSTI officials to verify the completeness, authenticity, and compliance of
submitted documents. This helps ensure that only valid applications proceed to the next
stage.

                                            164
```

## Page 166

```text
3. Online Application Fee Payment
Enables applicants to pay the required application fees through integrated online payment
gateways. The system securely processes transactions and records payment information.
4. Payment Confirmation and Payment History
Automatically confirms successful payments and maintains a complete history of all
payment transactions. Applicants and authorized officials can review payment records
whenever required.
5. Missing-Document Upload and Resubmission Facility
Allows applicants to upload missing or revised documents after receiving review comments.
The system supports resubmission without requiring a new application.
6. Secure Document Upload/Download Management
Provides secure document storage with controlled upload and download access based on
user roles. All document activities are protected to maintain confidentiality and data integrity.
Module-3: Application Review and Adequacy Audit Module (Total
Feature - 8)
Features Description
1. DD (DC) Receives and Reviews Submitted Applications
Enables the DD (DC) to receive newly submitted applications and perform an initial review
for completeness and compliance with certification requirements.
2. Forward Application to DCO
Allows the DD (DC) to forward reviewed applications to the Designated Certification Officer
(DCO) for adequacy assessment through the system workflow.
3. DCO Performs Adequacy Audit/Review
Enables the DCO to conduct a detailed adequacy review of the submitted application and
supporting documents to ensure compliance with MSC certification requirements.
4. Prepare Adequacy Audit Report
Allows the DCO to prepare a structured adequacy audit report documenting the review
findings, observations, and recommendations.
5. Add Review Remarks and Shortage Observations
Provides the ability to record review comments, document deficiencies, and any identified
non-compliance requiring applicant action.
6. Notify Applicant Regarding Document Shortfall
Automatically notifies the applicant of missing documents, deficiencies, or required
corrections identified during the adequacy review process.
7. Applicant Rectifies and Resubmits Documents
Allows applicants to address review observations by uploading corrected or additional
documents and resubmitting the application for further review.

                                              165
```

## Page 167

```text
8. Approve or Reject Adequacy Audit Result
Enables authorized officials to approve applications that meet adequacy requirements or
reject applications that fail to satisfy the necessary criteria.
Module-4: Acceptance and Agreement Management Module (Total
Feature - 8)
Features Description
1. Prepare Acceptance Letter
Allows the system to generate an acceptance letter for applications that successfully pass
the adequacy review process, confirming their progression to the next stage.
2. Prepare Agreement Paper
Enables the preparation of the official agreement document outlining the terms, conditions,
and responsibilities related to the MSC certification process.
3. DCO Drafts Acceptance Letter and Agreement Paper
Allows the DCO to prepare and manage draft versions of the acceptance letter and
agreement paper before initiating the approval workflow.
4. DD (DC) Verifies and Approves Acceptance Letter
Enables the DD (DC) to review the acceptance letter for accuracy and compliance before
providing formal approval.
5. DD (DC) Verifies Agreement Paper
Allows the DD (DC) to examine the agreement paper to ensure all information, terms, and
conditions are complete and accurate prior to higher-level approval.
6. Director/Head of MSC Approves Agreement Paper
Enables the Director/Head of MSC to provide final approval of the agreement paper,
authorizing the applicant to proceed with the certification process.
7. Notify Applicant After Approval
Automatically sends notifications to applicants once the acceptance letter and agreement
paper have been approved, informing them of the next steps.
8. Applicant Can Access Approved Agreement Paper
Allows applicants to securely view and download the approved agreement paper from the
system for reference and record-keeping.
Module-5: Man-Day Calculation and Audit Scheduling Module (Total
Feature - 7)
Features Description
1. IAO Performs Man-Day Calculation
Enables the Inspection and Audit Officer (IAO) to calculate the required audit man-days
based on the organization's scope, size, complexity, and applicable certification standards.

                                                166
```

## Page 168

```text
2. Set, Reschedule or Revise Audit Dates
Allows authorized officials to schedule, modify, or reschedule audit dates based on
operational requirements, applicant requests, or unforeseen circumstances.
3. Prepare Stage-1 Audit Notice
Enables the IAO to prepare and issue the official Stage-1 audit notice containing the audit
schedule, scope, and relevant instructions for the applicant.
4. DD (IA) Verifies Man-Day Calculation and Audit Notice
Allows the Deputy Director (IA) to review and verify the calculated audit man-days and the
Stage-1 audit notice before approval.
5. Director/Head of MSC Approves Stage-1 Audit Schedule
Enables the Director/Head of MSC to review and provide final approval for the proposed
Stage-1 audit schedule.
6. Notify Applicant About Approved Stage-1 Audit Date
Automatically notifies the applicant once the Stage-1 audit schedule is approved, providing
the confirmed audit date and related information.
7. Maintain Audit Schedule Calendar and History
Maintains a centralized audit calendar along with a complete history of scheduled, revised,
and completed audit activities for future reference and reporting.
Module-6: Stage-1 Audit Management Module (Total Feature - 8)
Features Description
1. Audit Team Prepares Stage-1 Audit Plan
Allows the Audit Team to prepare a comprehensive Stage-1 audit plan outlining the audit
scope, objectives, schedule, and assigned auditors.
2. Share Audit Plan with Applicant
Enables the approved Stage-1 audit plan to be shared electronically with the applicant
before the scheduled audit.
3. Applicant Receives Stage-1 Audit Plan Notification
Automatically notifies the applicant when the Stage-1 audit plan is published, ensuring
timely communication of audit details.
4. Audit Team Conducts Stage-1 Audit
Allows the Audit Team to perform the Stage-1 audit according to the approved audit plan
and applicable MSC certification requirements.
5. Prepare Stage-1 Audit Report
Enables the Audit Team to prepare a detailed audit report summarizing the audit activities,
observations, and overall assessment.
6. Prepare Stage-1 Audit Findings Report
Allows auditors to document all audit findings, including observations, non-conformities, and
areas requiring corrective action.

                                             167
```

## Page 169

```text
7. Applicant Submits Audit Feedback Form
Enables applicants to provide feedback regarding the audit process, auditor performance,
and overall audit experience through the system.
8. DD (IA) Reviews, Edits and Approves Audit Report
Allows the Deputy Director (IA) to review, revise where necessary, and approve the finalized
Stage-1 audit report before proceeding to the corrective action stage.
Module-7: Corrective Action Management Module (Total Feature - 9)
Features Description
1. Identify Findings/Non-Conformities from Stage-1 Audit
Enables the system to record and categorize audit findings and non-conformities identified
during the Stage-1 audit for corrective action.
2. Send Findings to Applicant with Corrective-Action Reply Date
Automatically communicates audit findings to the applicant along with the deadline for
submitting corrective actions and supporting evidence.
3. Applicant Submits Corrective Action Form
Allows applicants to submit corrective action plans describing how each identified non-
conformity will be resolved.
4. Applicant Uploads Corrective-Action Evidence/Supporting Documents
Enables applicants to upload supporting documents and evidence demonstrating the
implementation of proposed corrective actions.
5. Applicant Requests Extension of Reply Date
Allows applicants to request an extension of the corrective action submission deadline by
providing appropriate justification.
6. BSTI Officials Approve or Reject Extension Request
Enables authorized BSTI officials to review extension requests and approve or reject them
based on the provided justification.
7. DD (IA)/IAO Reviews Corrective Action
Allows the DD (IA) or IAO to evaluate submitted corrective actions and supporting evidence
to determine whether the identified non-conformities have been adequately addressed.
8. Send Rejection Note if Corrective Action is Not Acceptable
Enables the system to issue a rejection notice with review comments when the submitted
corrective action does not satisfy the required standards.
9. Maintain Corrective-Action Status and History
Maintains a complete record of corrective action submissions, reviews, approvals, rejections,
and status updates to ensure full traceability throughout the certification process.

                                             168
```

## Page 170

```text
Module-8: Stage-2 Audit Notice and Scheduling Module (Total
Feature - 8)
Features Description
1. IAO Prepares Stage-2 Audit Notice
Enables the Inspection and Audit Officer (IAO) to prepare the official Stage-2 audit notice
containing the audit schedule, scope, and relevant instructions for the applicant.
2. Set or Reschedule Stage-2 Audit Date
Allows authorized officials to schedule or revise the Stage-2 audit date based on operational
requirements, applicant requests, or other valid circumstances.
3. DD (IA) Verifies and Approves Stage-2 Audit Notice
Enables the Deputy Director (IA) to review the Stage-2 audit notice for accuracy and approve
it before forwarding it for final authorization.
4. Director/Head of MSC Reviews and Approves Stage-2 Audit Date
Allows the Director/Head of MSC to review and provide final approval of the proposed
Stage-2 audit schedule before notifying the applicant.
5. Notify Applicant About Stage-2 Audit Schedule
Automatically sends notifications to the applicant with the approved Stage-2 audit date,
schedule, and related audit information.
6. Maintain Stage-2 Schedule and Rescheduling History
Maintains a complete history of Stage-2 audit schedules, revisions, and rescheduling
activities to ensure transparency and audit traceability.
Module-9: Stage-2 Audit Management Module (Total Feature - 8)
Features Description
1. Audit Team Prepares Stage-2 Audit Plan
Enables the Audit Team to prepare a detailed Stage-2 audit plan outlining the audit scope,
objectives, schedule, and assigned audit members.
2. Share Stage-2 Audit Plan with Applicant
Allows the approved Stage-2 audit plan to be shared electronically with the applicant prior
to the scheduled audit.
3. Audit Team Performs Stage-2 Audit
Enables the Audit Team to conduct the Stage-2 audit in accordance with the approved audit
plan and MSC certification requirements.
4. Prepare Stage-2 Audit Report
Allows auditors to prepare a comprehensive report summarizing the audit activities,
observations, conclusions, and overall assessment.
5. Prepare NC Report and Audit Findings Report
Enables the Audit Team to document identified non-conformities (NCs), audit findings, and
recommendations in structured reports.

                                               169
```

## Page 171

```text
6. Applicant Submits Stage-2 Audit Feedback
Allows applicants to provide feedback on the Stage-2 audit process, audit team performance,
and overall experience through the system.
7. DD (IA) Reviews, Edits and Approves Stage-2 Audit Report, NC Report and
Findings
Enables the Deputy Director (IA) to review, revise where necessary, and approve the finalized
Stage-2 audit report, NC report, and audit findings before proceeding to finding closure.
Module-10: Stage-2 Corrective Action and Findings Closure Module
(Total Feature - 8)
Features Description
1. Send Stage-2 Findings to Applicant with Reply Deadline
Automatically communicates Stage-2 audit findings to the applicant along with the deadline
for submitting corrective actions and supporting evidence.
2. Applicant Submits Corrective Action Against Stage-2 Findings
Allows applicants to submit corrective action plans addressing each Stage-2 audit finding
and identified non-conformity.
3. Applicant Uploads Supporting Evidence
Enables applicants to upload documents and other supporting evidence demonstrating the
implementation of corrective actions.
4. Applicant Requests Deadline Extension if Required
Allows applicants to request an extension of the corrective action submission deadline by
providing valid reasons for the request.
5. DD (IA) Reviews Corrective Action and Evidence
Enables the Deputy Director (IA) to evaluate submitted corrective actions and supporting
evidence to determine whether the audit findings have been adequately addressed.
6. Approve Findings Closure if Acceptable
Allows authorized officials to approve the closure of audit findings after verifying that all
corrective actions have been satisfactorily implemented.
7. Issue Rejection Note if Corrective Action is Unacceptable
Enables the system to generate a rejection note with review comments when the submitted
corrective action or evidence does not meet certification requirements.
8. Approve Final Stage-2 Audit Report When All Findings Are Closed
Allows the final Stage-2 audit report to be approved after all non-conformities have been
resolved and the corresponding findings have been formally closed.

                                             170
```

## Page 172

```text
Module-11: Initial Certification Proposal Management Module (Total
Feature - 6)
Features Description
1. DCO Prepares Initial Certification Proposal
Enables the Designated Certification Officer (DCO) to prepare the initial certification proposal
based on the completed audit results, findings, and compliance status.
2. DCO Prepares MSC Intimation
Allows the DCO to prepare the official MSC intimation document containing relevant
certification information and recommendations.
3. DD (DC) Verifies, Edits and Approves Proposal
Enables the Deputy Director (DD-DC) to review, modify if necessary, and approve the
certification proposal before forwarding it for higher-level review.
4. Director/Head of MSC Reviews Proposal
Allows the Director/Head of MSC to review the certification proposal and ensure it complies
with applicable certification policies and requirements.
5. Determine Whether Proposal is Ready for Certification Committee
Enables authorized officials to assess the proposal's completeness and determine whether
it is ready to be presented to the Certification Committee for final evaluation.
6. Maintain Proposal Approval/Rejection History
Maintains a complete record of proposal reviews, approvals, rejections, and related
comments to ensure transparency and audit traceability.
Module-12: Audit and Certification Billing Module (Total Feature - 9)
Features Description
1. Generate Audit Bill/Invoice
Enables the system to generate audit invoices based on the approved audit activities and
applicable fee structure.
2. Generate Certification Bill/Invoice
Allows the system to generate certification invoices after successful completion of the
certification process and applicable approvals.
3. DCO Prepares Audit and Certification Bills
Enables the DCO to prepare audit and certification bills for review before they are issued to
the applicant.
4. DD (DC) Verifies and Approves Bills
Allows the Deputy Director (DD-DC) to review the generated invoices for accuracy and
approve them before issuance.
5. Send Payment Request to Applicant
Automatically sends payment requests to applicants along with invoice details, payment
instructions, and applicable deadlines.

                                             171
```

## Page 173

```text
6. Applicant Receives Audit Bill and Certification Bill
Allows applicants to securely access, view, and download audit and certification invoices
through the system.
7. Online Payment Facility
Enables applicants to make audit and certification payments electronically through
integrated and secure online payment gateways.
8. Payment Confirmation Before Certificate Generation
Verifies successful payment before allowing the certificate generation process to proceed,
ensuring all financial obligations have been fulfilled.
9. Payment Report and Payment History
Maintains comprehensive payment records, transaction history, and financial reports for
monitoring, reconciliation, and auditing purposes.
Module-13: Certification Committee Meeting Management Module
(Total Feature - 8)
Features Description
1. DD (DC) Prepares Certification Committee Meeting Notice
Enables the Deputy Director (DD-DC) to prepare the official meeting notice for the
Certification Committee with the meeting schedule and agenda.
2. Director/Head of MSC Verifies Meeting Notice
Allows the Director/Head of MSC to review and verify the meeting notice before forwarding
it for final approval.
3. DG Approves Meeting Notice
Enables the Director General (DG) to provide final approval for the Certification Committee
meeting notice before distribution.
4. Send Meeting Notice to Certification Committee
Automatically distributes the approved meeting notice to all Certification Committee
members through the system.
5. Generate Certification Committee Meeting Notice PDF
Allows the system to generate the approved meeting notice in PDF format for official
communication and record-keeping.
6. Certification Committee Reviews Certification Proposal
Enables the Certification Committee to evaluate the submitted certification proposal,
supporting documents, and audit outcomes before making a decision.
7. Record Approval, Rejection or Follow-Up Audit Decision
Allows the committee to record its final decision, including approval, rejection, or the
requirement for a follow-up audit, within the system.

                                              172
```

## Page 174

```text
8. DD (DC) Uploads Committee Decision
Enables the DD (DC) to upload and publish the official Certification Committee decision,
making it available for subsequent workflow activities and applicant notification.
Module-14: Certification Committee Minutes Management Module
(Total Feature - 6)
Features Description
1. Certification Committee Prepares Meeting Minutes
Enables the Certification Committee to prepare detailed meeting minutes documenting
discussions, decisions, recommendations, and action items related to certification proposals.
2. DG Prepares and Approves Meeting Minutes
Allows the Director General (DG) to review, finalize, and approve the official meeting minutes
for formal record and organizational compliance.
3. Director/Head of MSC Approves Meeting Minutes
Enables the Director/Head of MSC to review and approve the meeting minutes before they
are officially published and archived.
4. Store Meeting Decisions and Minutes Digitally
Provides secure digital storage of approved meeting minutes and committee decisions for
future reference, audit, and document management.
5. Generate Meeting-Minutes Report
Allows the system to generate comprehensive meeting-minutes reports in a standardized
format for official use and reporting purposes.
6. Link Committee Decision with the Relevant Application and Certification
Proposal
Associates each committee decision with its corresponding application and certification
proposal to ensure complete traceability throughout the certification process.
Module-15: MSC Certificate Generation and Approval Module (Total
Feature - 7)
Features Description
1. Generate Certificate After Payment Confirmation and Committee Approval
Enables the system to generate the MSC certificate only after successful payment verification
and Certification Committee approval, ensuring compliance with the certification workflow.
2. Head of MSC Generates Certificate
Allows the Head of MSC to generate the official certificate based on the approved
certification decision and applicant information.
3. Head of MSC Approves Generated Certificate
Enables the Head of MSC to review and approve the generated certificate before it is finalized
for issuance.

                                             173
```

## Page 175

```text
4. DD (DC) Finalizes Certificate Approval
Allows the Deputy Director (DD-DC) to complete the final approval process, authorizing the
certificate for official release.
5. Generate Downloadable Certificate PDF
Automatically generates the approved certificate in PDF format for secure distribution,
printing, and digital record-keeping.
6. Applicant Accesses Approved Certificate
Enables applicants to securely view and download their approved MSC certificate through
the online portal.
7. Maintain Certificate Issuance Record and Status
Maintains a complete record of certificate generation, approval, issuance status, and validity
for monitoring, reporting, and audit purposes.
Module-16: Rejection, Rework and Follow-Up Audit Module (Total
Feature - 6)
Features Description
1. Generate Rejection Note for Rejected Application, Corrective Action or
Committee Decision
Allows the system to generate official rejection notes with appropriate reasons for rejected
applications, corrective actions, or Certification Committee decisions.
2. Notify Applicant About Rejection Reason
Automatically notifies applicants of rejection decisions along with detailed reasons and
guidance for the next required actions.
3. Allow Resubmission Where Applicable
Enables applicants to revise and resubmit applications or required documents when
resubmission is permitted under the certification process.
4. Record Certification Committee Follow-Up Audit Decision
Allows the system to record the Certification Committee's decision requiring a follow-up
audit and maintain it as part of the certification history.
5. Initiate Follow-Up Audit Using the Same Audit Workflow
Enables authorized officials to initiate a follow-up audit using the existing audit workflow,
ensuring consistency with the standard certification process.
6. Track Follow-Up Audit Status and Outcome
Maintains the progress, status, and final outcome of follow-up audits, providing complete
visibility and traceability until the certification process is concluded.

                                               174
```

## Page 176

```text
Module-17: Workflow and Approval Management Module (Total
Feature - 6)
Features Description
1. Configure Workflow Routing Among Applicants, DD (DC), DCO, IAO, etc.
Enables administrators to configure and manage workflow routing among applicants and
BSTI officials based on predefined business rules, ensuring a standardized certification
process.
2. Role-Based Task Assignment
Automatically assigns tasks to the appropriate users based on their roles and responsibilities,
ensuring accountability and efficient workflow execution.
3. Multi-Level Approval and Verification Flow
Supports configurable multi-level review, verification, and approval processes to ensure
every application passes through the required authorization hierarchy.
4. Approve, Reject, Return and Forward Actions
Allows authorized officials to approve, reject, return for correction, or forward applications
and documents to the next stage of the workflow.
5. Workflow Status Monitoring
Provides real-time monitoring of application workflows, enabling users to track the progress
and current stage of each certification request.
6. Pending-Task Dashboard
Displays all pending reviews, approvals, and assigned tasks for each user, helping officials
manage their workload efficiently.
Module-18: Notification and Communication Management Module
(Total Feature - 10)
Features Description
1. SMS Notification
Automatically sends SMS alerts to applicants and officials regarding important events,
deadlines, and workflow updates.
2. Email Notification
Sends email notifications for application updates, approvals, audit schedules, payment
requests, and other system-generated communications.
3. In-System Notification
Provides real-time notifications within the application to keep users informed about pending
tasks, approvals, and workflow activities.
4 Application Submission Notification
Automatically notifies designated BSTI officials when a new application is successfully
submitted for review.

                                             175
```

## Page 177

```text
5. Approval/Rejection Notification
Notifies applicants and relevant officials whenever an application, document, or request is
approved or rejected.
6. Document-Shortage Notification
Alerts applicants when mandatory documents are missing or additional information is
required during the review process.
7. Audit Notice Notification
Automatically sends notifications regarding audit schedules, audit plans, and other audit-
related updates to the concerned users.
8. Corrective-Action Deadline Notification
Sends reminder notifications before corrective-action deadlines to ensure timely submission
and compliance.
18.9 Payment Request Notification
Notifies applicants when audit or certification fees are due, including invoice details
and payment instructions.
10. Certificate Approval Notification
Automatically informs applicants once their MSC certificate has been approved and is
available for download.
Module-19: Application and Workflow Tracking Module (Total
Feature - 7)
Features Description
1. Track Draft, Submitted, Under Review, Pending Correction, Approved and
Rejected Status
Provides real-time tracking of application status from draft creation through submission,
review, correction, approval, or rejection.
2. Track Audit Scheduled and Audit Completed Status
Allows applicants and officials to monitor the scheduling, progress, and completion status
of Stage-1 and Stage-2 audits.
3. Track Pending Corrective Action Status
Displays the status of pending corrective actions, including submission deadlines, review
progress, and closure status.
4. Track Pending Payment Status
Enables users to monitor outstanding invoices, payment confirmations, and pending financial
transactions throughout the certification process.
5. Track Certificate Generated and Certificate Approved Status
Provides visibility into certificate generation, approval, and issuance until the certification
process is successfully completed.

                                              176
```

## Page 178

```text
6. Applicant Dashboard for Application Progress
Provides applicants with a personalized dashboard displaying application status,
notifications, pending actions, payment status, and certification progress.
7. Officer Dashboard for Pending Approvals
Provides BSTI officials with a centralized dashboard showing pending reviews, approvals,
assigned tasks, and workflow activities based on their roles.
Module-20: MSC Reports and Dashboard Module (Total Feature - 9)
Features Description
1. Application Status Report
Generates reports showing the status and progress of all MSC certification applications to
support operational monitoring and decision-making.
2. Audit Schedule Report
Provides detailed reports of scheduled, completed, postponed, and upcoming audits along
with assigned audit teams and timelines.
3. Pending Approval Report
Generates reports identifying applications, documents, and requests awaiting review or
approval by authorized officials.
4. Corrective Action Report
Provides reports on identified non-conformities, submitted corrective actions, review
outcomes, and findings closure status.
5. Payment Report
Generates comprehensive reports of invoices, payment transactions, outstanding dues, and
payment confirmations for financial monitoring.
6. Certificate Issuance Report
Provides reports on generated and issued certificates, including issuance dates, approval
status, and certificate validity information.
7. Audit Findings Report
Generates reports summarizing audit findings, non-conformities, corrective actions, and
overall audit outcomes.
8. Meeting Minutes Report
Provides   reports    containing    Certification   Committee   meeting   minutes,   decisions,
recommendations, and related certification records.
9. Dashboard-Based Workflow Monitoring
Provides an interactive dashboard with real-time KPIs, workflow status, pending tasks, audit
progress, application statistics, and operational insights for effective management.

                                                177
```

## Page 179

```text
Module-21: Audit Trail and Activity Log Module (Total Feature - 7)
Features Description
1. Login/Logout History
Maintains a complete record of user login and logout activities, including timestamps, to
support system security and user accountability.
2. Data Modification History
Records all data creation, modification, and deletion activities, enabling administrators to
track changes and maintain data integrity.
3. Approval and Rejection Action History
Maintains a detailed history of all approval, rejection, return, and forwarding actions
performed throughout the certification workflow.
4. Document Upload/Download History
Tracks all document upload and download activities, providing a complete audit trail of
document access and management.
5. Payment Activity History
Records all payment-related transactions, including invoices, payment confirmations,
refunds (if applicable), and transaction timestamps for financial auditing.
6. Certificate Generation History
Maintains a history of certificate generation, approvals, issuance, reissuance, and related
activities for complete certification traceability.
7. User-Wise Activity Tracking for Accountability
Tracks system activities performed by each user, ensuring accountability, transparency, and
compliance with organizational audit requirements.
Module-22: Role-Based User and Access Management Module (Total
Feature - 5)
Features Description
1. Separate Access for Applicant, DD (DC), DCO, IAO, DD (IA), Head of MSC, Audit
Team, DG and Certification Committee
Provides dedicated system access for each stakeholder with permissions tailored to their
assigned roles and responsibilities within the certification process.
2. Role-Based Menu and Feature Permissions
Controls system menus, modules, and features based on user roles, ensuring that users can
access only the functions relevant to their responsibilities.
3. Authentication/Login Control
Implements secure user authentication and login mechanisms to prevent unauthorized
access and protect system resources.

                                                178
```

## Page 180

```text
4. Restrict Certificate Approval to Authorized Officials
Ensures that certificate approval functions are accessible only to designated authorized
officials in accordance with the defined approval hierarchy.
5. Secure User-Session Management
Manages user sessions securely by handling session timeouts, automatic logout, and access
controls to protect against unauthorized system usage.
Module-23: External Integration Management Module (Total Feature
- 7)
Features Description
1. National Payment Gateway Integration
Integrates with the National Payment Gateway to facilitate secure online payment
processing and automatic payment confirmation.
2. SMS Gateway Integration
Integrates with SMS gateway services to deliver automated notifications, alerts, reminders,
and workflow updates to users.
3. Email Service Integration
Integrates with email services to send automated notifications, approvals, audit notices,
payment requests, and other official communications.
4. PDF Generation Service Integration
Integrates with PDF generation services to produce official documents, reports, invoices,
certificates, and meeting notices in standardized PDF format.
5. Digital Signature Module Integration
Supports integration with digital signature services to enable secure electronic approval and
authentication of official documents.
6. Integration with Existing BSTI eService Modules
Enables seamless data exchange and interoperability with existing BSTI eService modules
to ensure a unified digital service ecosystem.
7. Integration with Document-Management and User-Management Modules
Facilitates integration with centralized document management and user management
systems for secure document handling and unified user administration.
Module-24: Certificate Verification and QR Code (Total Feature - 5)
Features Description
1 QR-Based Certificate Verification Facility
Generates a unique QR code for each issued certificate, allowing users to verify certificate
authenticity through quick and secure scanning.
2 Public Certificate Authenticity Verification
Provides a public verification portal where anyone can confirm the authenticity of an issued
MSC certificate without requiring system login.

                                             179
```

## Page 181

```text
3 Certificate Number Search Facility
Allows users to search and verify certificates using the unique certificate number issued by
the system.
4 Certificate Validity-Status Display
Displays the current status of a certificate, including whether it is valid, expired, suspended,
revoked, or otherwise inactive.
5 Verification History and Scan Tracking
Maintains a history of certificate verification requests and QR code scans, supporting
monitoring, reporting, and security auditing.

                                                180
```

## Page 182

```text
  SERVICE
                MSC RE-CERTIFICATION MANAGEMENT
    18
                SYSTEM
                Re-certification • Audit • Corrective Action • Certification

Service Profile
Domain                          Service Type                  Primary Users
Management System Certification Certification / Audit Service Applicant • DD (DC) • DCO • DD
(MSC)                                                         (IA) • Head of MSC • Audit Team
                                                              • Certification Committee
Core Scope                              Modules                         Features
Complete MSC         Re-certification
Lifecycle
                                        14                              136

Functional Coverage
APPLICATION                        AUDIT PLANNING                        AUDIT & FINDINGS
• Re-certification Application     • Man-Day Calculation                 • Re-certification Audit
• Application Review               • Auditor Assignment                  • Audit Findings
• Agreement Management             • Audit Scheduling                    • Corrective Action
                                                                         • Improvement Notice

TECHNICAL REVIEW                   CERTIFICATION                         CONTROL
• Technical Review                 • Payment Processing                  • Workflow
• Certification Proposal           •     Certificate   &       Document • Notifications
• Committee Management             Management                            • Tracking
                                   • Rejection                           • Audit Trail

Module Catalogue
Sl. Module                                    No. of  Sl. Module                                     No. of
No.                                          Features No.                                           Features
 01 Re-certification Application                7         07    Technical Review & Proposal            6
                                                                Management
 02 Application Review & Agreement             10         08    Certification         Committee        9
    Management                                                  Management
 03 Audit Planning & Scheduling                10         09    Payment Processing                     7
 04 Re-certification                Audit       9         10    Certificate &         Document         7
    Management                                                  Management
 05 Audit Findings & Corrective Action         10         11    Rejection Management                   4
    Management
 06 Improvement Notice Management               7

                                                    181
```

## Page 183

```text
Service-18: MSC Re-certification Management System
The proposed MSC Re-certification Management System is a comprehensive digital
platform designed to automate and manage the complete re-certification lifecycle,
from application submission to certificate issuance. The system enables applicants to
submit re-certification applications online, upload required documents, complete fee
payments, and track application status through a centralized portal. Submitted
applications undergo a structured multi-level review process involving the Deputy
Director (DD), Documentation & Certification Officer (DCO), Director/Head of MSC,
and other authorized officials to ensure completeness and regulatory compliance.
The solution supports automated shortfall management, agreement preparation,
audit planning, man-day calculation, auditor assignment, and audit scheduling. It
further manages Stage-wise re-certification audits, audit findings, corrective actions,
improvement notices, and compliance verification with integrated evidence
management.      Technical   recommendations,       re-certification   proposals,   MSC
intimations, and certification bills are processed through configurable approval
workflows before being presented to the Certification Committee for final decision.
The system also automates payment processing, certificate generation, digital
certificate issuance, and document management while maintaining complete
workflow traceability through audit trails. Integrated notification services keep
applicants informed throughout every stage of the process. By digitizing the end-to-
end re-certification workflow, the solution improves operational efficiency, reduces
manual intervention, enhances transparency, strengthens regulatory compliance, and
ensures timely delivery of re-certification services.

                                          182
```

## Page 184

```text
Fig: Workflow of MSC Re-Certification System

                    183
```

## Page 185

```text
Module-1: Re-certification Application (Total Feature - 7)
Features Description
1. Online Re-certification Application:
Enables applicants to submit re-certification applications electronically.
2. Application Form Management:
Captures all required applicant, product, and certification information.
3. Supporting Document Upload:
Allows applicants to upload mandatory supporting documents.
4. Re-certification Fee Payment:
Supports online payment of applicable re-certification fees.
5. Application Submission:
Finalizes and submits completed applications for review.
6. Application Tracking:
Allows applicants to monitor application status throughout the process.
7. Application History:
Maintains historical records of previous re-certification applications.
Module - 2: Application Review & Agreement Management (Total
Feature - 10)
Features Description
1. DD (DC) Application Review:
Enables the Deputy Director to review submitted applications.
2. DCO Application Review:
Supports detailed document verification by the Documentation & Certification Officer.
3. Shortfall Identification:
Identifies missing documents or non-compliance issues.
4. Shortfall Notification:
Notifies applicants regarding identified deficiencies.
5. Customer Resubmission:
Allows applicants to submit corrected information and documents.
6. Acceptance Letter Preparation:
Generates official acceptance letters for eligible applications.
7. Agreement Paper Generation:
Prepares re-certification agreement documents.
8. DD (DC) Approval:
Approves acceptance letters and agreement documents.

                                          184
```

## Page 186

```text
9. Director/Head of MSC Approval:
Provides final approval of agreement documents.
10. Agreement Notification to Applicant:
Sends approved agreements to applicants.
Module - 3: Audit Planning & Scheduling (Total Feature - 10)
Features Description
1. Man-Day Calculation:
Automatically calculates audit effort based on predefined criteria.
2. Auditor Assignment:
Assigns qualified auditors for re-certification audits.
3. Audit Team Assignment:
Allocates audit team members according to expertise.
4. Re-certification Audit Scheduling:
Schedules audit activities.
5. Audit Date Rescheduling:
Supports audit date modifications when required.
6. Audit Notice Generation:
Generates official audit notices.
7. Audit Calendar Management:
Maintains centralized audit schedules.
8. DD (IA) Verification:
Verifies audit planning activities.
9. Director Approval:
Approves audit schedules and plans.
10. Audit Schedule Notification:
Notifies applicants of scheduled audits.
Module - 4: Re-certification Audit Management (Total Feature - 9)
Features Description
1. Audit Plan Preparation:
Prepares audit plans before audit execution.
2. Audit Plan Approval:
Approves audit plans before implementation.
3. Audit Notification:
Notifies applicants regarding audit plans.
4. Audit Execution:
Records audit activities conducted by auditors.

                                           185
```

## Page 187

```text
5. Audit Checklist:
Supports standardized audit checklists.
6. Audit Observation Recording:
Records audit observations.
7. Audit Findings Management:
Maintains identified audit findings.
8. Audit Report Preparation:
Generates official audit reports.
9. Audit Report Approval:
Approves completed audit reports.
Module - 5: Audit Findings & Corrective Action Management (Total
Feature -10)
Features Description
1. Findings Review:
Reviews audit findings for corrective action.
2. Finding Notification:
Notifies applicants of identified findings.
3. Reply Date Assignment:
Assigns deadlines for corrective action submission.
4. Extension Request:
Allows applicants to request deadline extensions.
5. Extension Approval:
Approves or rejects extension requests.
6. Corrective Action Submission:
Allows applicants to submit corrective actions.
7. Evidence Upload:
Supports uploading evidence of corrective actions.
8. Evidence Verification:
Verifies submitted evidence.
9. Corrective Action Acceptance:
Approves satisfactory corrective actions.
10. Corrective Action Rejection:
Rejects insufficient corrective actions.
6. Improvement Notice Management Module (Total Feature - 7)

                                              186
```

## Page 188

```text
Features Description
1. Improvement Notice Generation:
Generates formal improvement notices.
2. DD (DC) Approval:
Approves improvement notices.
3. Director/Head of MSC Approval:
Provides final approval before issuance.
4. Notice Notification:
Sends improvement notices to applicants.
5. Customer Response Submission:
Allows applicants to respond to notices.
6. Follow-up Verification:
Verifies corrective responses.
7. Final Acceptance:
Confirms successful completion of improvement requirements.
7. Technical Review & Proposal Management Module (Total Feature -
6)
Features Description
1. Re-certification Proposal Preparation:
Prepares technical proposals for re-certification.
2. MSC Intimation Preparation:
Generates official MSC intimation documents.
3. Certification Bill Generation:
Produces certification fee bills.
4. Technical Recommendation:
Provides recommendations based on audit outcomes.
5. Proposal Review:
Reviews technical proposals.
6. Proposal Approval:
Approves proposals before committee review.
8. Certification Committee Management Module (Total Feature - 9)
Features Description
1. Certification Committee Meeting Notice:
Generates committee meeting notices.
2. Meeting Schedule:
Schedules certification committee meetings.

                                           187
```

## Page 189

```text
3. Director Verification:
Verifies committee documents.
4. DG Approval:
Obtains approval from the Director General.
5. Committee Review:
Supports committee review of applications.
6. Committee Decision Recording:
Records committee decisions.
7. Decision Upload:
Publishes approved committee decisions.
8. Approval History:
Maintains historical committee decisions.
9. Rejection Decision Management:
Records rejected applications.
9. Payment Processing Module (Total Feature - 7)
Features Description
1. Certification Bill Generation:
Generates payable certification bills.
2. Payment Request:
Sends payment requests to applicants.
3. Payment Notification:
Notifies applicants regarding pending payments.
4. Payment Collection:
Records received payments.
5. Payment Verification:
Verifies payment transactions.
6. Payment Confirmation:
Confirms successful payment.
7. Payment Status Tracking:
Tracks payment progress.
10. Certificate & Document Management Module (Total Feature -7)
Features Description
1. Certificate Generation:
Generates approved re-certification certificates.
2. Certificate Number Generation:
Assigns unique certificate numbers.

                                         188
```

## Page 190

```text
3. Digital Certificate Issuance:
Issues digitally generated certificates.
4. MSC Intimation Generation:
Produces official MSC intimation documents.
5. Agreement Paper Management:
Stores approved agreement documents.
6. Certificate Download:
Allows applicants to download issued certificates.
7. Certificate Repository:
Maintains centralized certificate records.
11. Rejection Management Module (Total Feature - 4)
Features Description
1. Rejection Note Generation:
Generates official rejection notes.
2. Rejection Approval:
Routes rejection notes through the approval workflow.
3. Customer Notification:
Notifies applicants of rejection decisions.
4. Rejection History:
Maintains records of rejected applications.
12. Workflow & Task Management Module (Total Feature - 7)
Features Description
1. Role-based Task Assignment:
Assigns tasks according to user responsibilities.
2. Multi-Level Approval Workflow:
Supports hierarchical approval processes.
3. Application Forwarding:
Routes applications between workflow stages.
4. Status Tracking:
Tracks application progress in real time.
5. Pending Task Dashboard:
Displays pending tasks for authorized users.
6. Workflow Remarks:
Records workflow comments and decisions.
7. Audit Trail:
Maintains a complete history of workflow activities.

                                             189
```

## Page 191

```text
13. Notification Module (Total Feature - 10)
Features Description
1. Shortfall Notification:
Alerts applicants regarding application deficiencies.
2. Agreement Notification:
Sends approved agreement documents.
3. Audit Schedule Notification:
Notifies applicants of audit schedules.
4. Audit Plan Notification:
Share audit plans with applicants.
5. Finding Notification:
Informs applicants of audit findings.
6. Improvement Notice Notification:
Send improvement notices.
7. Payment Request Notification:
Notifies applicants regarding pending payments.
8. Committee Meeting Notification:
Sends committee-related notifications.
9. Certificate Issued Notification:
Confirms certificate issuance.
10. Rejection Notification:
Notifies applicants of rejected applications.
14. Document Management Module (Total Feature - 10)
Features Description
1. Application Document Repository:
Stores submitted application documents.
2. Agreement Paper Management:
Maintains agreement documents.
3. Audit Plan Management:
Stores audit plans.
4. Audit Report Repository:
Maintains audit reports.
5. Corrective Action Repository:
Stores corrective action records.
6. Evidence Management:
Maintains uploaded evidence files.

                                          190
```

## Page 192

```text
7. Proposal Repository:
Stores technical proposals.
8. MSC Intimation Repository:
Maintains official MSC intimation documents.
9. Certificate Repository:
Stores issued certificates.
10. Rejection Note Repository:
Maintains rejection-related documents.

                                         191
```

## Page 193

```text
  SERVICE
                PCR REGISTRATION NEW
    19
                PCR Registration • Inspection • Approval • Certificate

Service Profile
Domain                             Service Type                 Primary Users
PCR Registration                   Registration / Certification Applicants    •   Reviewers     •
                                   Service                      Inspectors • AD • DD • Director •
                                                                System Admin
Core Scope                         Modules                        Features
New PCR Registration
                                   13                             48

Functional Coverage
APPLICATION                     REVIEW                              INSPECTION
• Application Submission        • Application Review                • Inspection Setup
• Document Upload               • Shortfall Management              • Inspection & Report
• Application Fee               • Resubmission                      • Re-inspection

APPROVAL                        REGISTRATION                        CONTROL
• AD/DD Verification            • Registration Complete             • Notifications
• Approval Management           • Certificate Generation            • User & Role Management
• Director Decision             • Download                          • Regional Office Workflow

Module Catalogue
Sl. Module                               No. of  Sl. Module                                  No. of
No.                                     Features No.                                        Features
 01 Application Submission                 4         07    Approval Management                 3

 02 Application Review & Shortfall         5         08    Registration Complete               3
    Management
 03 Payment Processing                     4         09    Rejection Management                2

 04 Inspection Setup                       3         10    Notification Management             3

 05 Inspection & Report                    5         11    Re-Inspection Management            3

 06 Verification Module (AD/DD)            3         12    User & Role Management              7

                                               192
```

## Page 194

```text
Service-19: PCR Registration New Feature Description
The PCR Registration System is a comprehensive digital platform designed to automate the
complete registration process, from application submission to certificate issuance. Applicants
can submit online applications, upload required documents, and pay registration fees through
an integrated payment gateway. The system automatically generates a unique Application
ID for tracking purposes. Submitted applications undergo a structured review process where
authorized officers verify the provided information and supporting documents. If any
discrepancies or missing information are identified, applicants are notified to submit
corrections through an integrated shortfall management process. Once the application is
complete, inspectors are assigned, inspection schedules are prepared, and physical
inspections are conducted. Inspection findings, photographs, remarks, and reports are
recorded within the system and subsequently reviewed by the Assistant Director (AD) and
Deputy Director (DD) for verification. After successful verification, the Director makes the
final decision by approving, rejecting, or requesting re-inspection when additional verification
is required. Upon approval, the system automatically generates the registration certificate,
which applicants can securely download online. Throughout the entire process, applicants
receive real-time email and SMS notifications regarding application status, payments,
inspections, approvals, and other workflow updates. The system also supports multiple
inspection cycles, centralized Head Office and Regional Office workflows, role-based access
control, and comprehensive user management to ensure transparency, accountability,
operational efficiency, and regulatory compliance across the PCR registration process.

                                             193
```

## Page 195

```text
Fig: PCR Registration Service Workflow

                 194
```

## Page 196

```text
Module-1. Application Submission (Total Feature - 4)
Features Description
1. Online Application Submission
Allows applicants to submit registration applications through an online portal by providing
all required information. The system validates mandatory fields before accepting the
application.
2. Document Upload
Enables applicants to upload all required supporting documents in approved file formats.
Uploaded documents are securely stored and linked with the application for further review.
3. Application Fee Payment
Allows applicants to pay the prescribed application fee through the integrated online
payment gateway. Payment status is automatically recorded against the submitted
application.
4. Auto Application ID Generation
Automatically generates a unique Application ID upon successful submission. The generated
ID is used for application tracking and future correspondence.
Module-2. Application Review & Shortfall Management (Total Feature
- 5)
Features Description
1. Application Review
Allows authorized officers to review submitted applications and verify the completeness of
information and supporting documents before further processing.
2. Shortfall Identification
Enables reviewers to identify missing information, incorrect data, or incomplete
documentation during the verification process.
3. Required Document Request
Allows reviewers to request additional documents or corrections from the applicant
whenever required. The request is recorded within the application history.
4. Shortfall Correction & Resubmission Loop
Applicants can update the requested information and resubmit the application for further
review. The review cycle continues until all requirements are fulfilled.
5. Applicant Notification
Automatically informs applicants regarding review status, identified shortfalls, and
resubmission requirements through the notification system.
Module-3. Payment Processing (Total Feature - 4)

                                             195
```

## Page 197

```text
Features Description
1. Fee Display
Displays the applicable fees dynamically based on the selected service and predefined fee
structure.
2. Payment Collection
Collects payments securely through integrated payment gateways while maintaining
transaction records for auditing purposes.
3. Payment Verification
Verifies successful payment transactions automatically or through authorized verification
before processing the application further.
4. Automatic Status Update
Automatically updates the application status once payment is successfully completed and
verified.
Module-4. Inspection Setup (Total Feature - 3)
Features Description
1. Inspector Assignment
Allows authorized officials to assign inspectors based on workload, expertise, or jurisdiction.
2. Inspection Scheduling
Enables scheduling of inspection dates according to availability and organizational workflow
requirements.
3. Inspection Date/Team Setup & Approval
Allows designated authorities to finalize inspection teams and approve the inspection
schedule before execution.
Module-5. Inspection & Report (Total Feature - 5)
Features Description
1. Physical Inspection
Allows inspectors to conduct on-site inspections according to defined regulatory guidelines
and inspection criteria.
2. Inspection Findings
Records observations, compliance status, and identified issues during the inspection process.
3. Report Preparation
Enables inspectors to prepare structured inspection reports based on collected findings and
observations.
4. Photo Upload
Allows inspectors to upload inspection photographs as supporting evidence for the
inspection report.

                                             196
```

## Page 198

```text
5. Remarks Entry
Provides inspectors with the option to include additional comments, recommendations, or
observations in the inspection report.
Module-6. Verification Module (AD/DD) (Total Feature - 3)
Features Description
1. Inspection Report Review
Allows Assistant Director (AD) and Deputy Director (DD) to review submitted inspection
reports for completeness and accuracy.
2. Verification
Enables authorized officers to verify inspection findings before forwarding them for final
approval.
3. Comments & Feedback
Allows reviewers to provide comments, recommendations, or clarification requests during
the verification process.
Module-7. Approval Management (Total Feature - 3)
Features Description
1. Director Approval
Allows the Director to review verified applications and provide final approval for registration
based on compliance requirements.
2. Rejection
Allows the Director to reject applications with appropriate reasons whenever regulatory
requirements are not fulfilled.
3. Re-Inspection Decision
Enables the Director to request a re-inspection if additional verification is required before
making a final decision.
Module-8. Registration Complete (Total Feature - 3)
Features Description
1. Registration Completion
Finalizes the registration process after receiving all required approvals and successful
verification.
2. Registration Certificate Generation
Automatically generates the official registration certificate upon successful completion of the
registration process.
3. Download Link
Provides applicants with a secure link to download the issued registration certificate from
the system.
Module-9. Rejection Management (Total Feature - 2)

                                             197
```

## Page 199

```text
Features Description
1. Rejection Button Generation
Provides authorized users with the option to reject an application directly from the workflow
with proper justification.
2. Applicant Notification
Automatically notifies applicants regarding application rejection along with the stated
reasons and further instructions.
Module-10. Notification Management (Total Feature - 3)
Features Description
1. Email Notification
Automatically sends email notifications for important application events and workflow
updates.
2. SMS Notification
Sends SMS alerts to applicants regarding application progress, payment confirmation, and
approval status.
3. Status Update Notification
Provides real-time notifications whenever the application status changes throughout the
workflow.
Module-11. Re-Inspection Management (Total Feature - 3)
Features Description
1. Re-Inspection Request
Allows authorized officials to initiate a re-inspection request whenever additional verification
is necessary.
2. Return to Inspection Setup
Automatically routes the application back to the inspection scheduling stage for re-
inspection planning.
3. Repeat Inspection Cycle
Supports multiple inspection cycles until all compliance requirements are successfully
fulfilled.
Module-12. User & Role Management (Total Feature - 7)
Features Description
1. Applicant
Allows applicants to submit applications, upload documents, make payments, and track
application progress.
2. Reviewer
Enables reviewers to examine applications, identify shortfalls, and request additional
information from applicants.

                                             198
```

## Page 200

```text
3. Inspector
Allows inspectors to conduct inspections, record findings, upload evidence, and prepare
inspection reports.
4. AD
Provides Assistant Directors with authority to verify inspection reports and forward eligible
applications for higher approval.
5. DD
Allows Deputy Directors to review verified applications and recommend them for final
approval.
6. Director
Provides the Director with authority to approve, reject, or request re-inspection before final
registration.
7. System Admin Role Management
Allows administrators to create, manage, and assign user roles, permissions, and access
controls across the system.
Module-13. Regional Office Workflow (Total Feature - 3)
Features Description
1. Head Office Workflow
Supports centralized application processing and approval activities managed by the Head
Office.
2. Regional Office Workflow
Enables regional offices to process applications, perform inspections, and complete assigned
workflow activities independently.
3. Wing Head-Centric Processing
Allows Wing Heads to supervise, monitor, and approve workflow activities within their
respective organizational units.

                                            199
```

## Page 201

```text
  SERVICE
                PCR REGISTRATION RENEWAL
    20
                PCR Renewal • Inspection • Approval • Certificate Renewal

Service Profile
Domain                            Service Type                 Primary Users
PCR Registration                  Registration / Certification Applicants    •   Reviewers     •
                                  Service                      Inspectors • AD • DD • Director •
                                                               System Admin
Core Scope                        Modules                        Features
PCR Registration Renewal
                                  13                             48

Functional Coverage
APPLICATION                    REVIEW                              INSPECTION
• Application Submission       • Application Review                • Inspection Setup
• Document Upload              • Shortfall Management              • Inspection & Report
• Application Fee              • Resubmission                      • Re-inspection

APPROVAL                       REGISTRATION                        CONTROL
• AD/DD Verification           • Registration Complete             • Notifications
• Approval Management          • Certificate Generation            • User & Role Management
• Director Decision            • Download                          • Regional Office Workflow

Module Catalogue
Sl. Module                              No. of  Sl. Module                                  No. of
No.                                    Features No.                                        Features
 01 Application Submission                4         07    Approval Management                 3
 02 Application Review & Shortfall        5         08    Registration Complete               3
    Management
 03 Payment Processing                    4         09    Rejection Management                2
 04 Inspection Setup                      3         10    Notification Management             3
 05 Inspection & Report                   5         11    Re-Inspection Management            3
 06 Verification Module (AD/DD)           3         12    User & Role Management              7

                                              200
```

## Page 202

```text
Service-20: PCR Registration Renewal
The proposed PCR Registration Management System is a comprehensive digital platform
designed to automate and streamline the complete PCR registration process from online
application submission to registration certificate issuance. The system enables applicants to
submit applications online, upload required documents, pay registration fees through an
integrated payment gateway, and receive automatically generated application IDs with real-
time status tracking. Applications are processed through a structured review workflow
where reviewers assess submissions, identify shortfalls, request additional information, and
manage correction and resubmission cycles while keeping applicants informed through
automated email and SMS notifications.
Following successful document review, the system manages inspection planning by
assigning inspectors, scheduling inspections, and approving inspection teams. Inspectors
conduct physical inspections, capture findings, upload photographs, prepare inspection
reports, and record remarks for further evaluation. Inspection reports are reviewed and
verified by authorized officers (AD/DD) before being forwarded for Director approval. Based
on the evaluation, the Director may approve the registration, reject the application, or initiate
a re-inspection process. If re-inspection is required, the application automatically returns to
the inspection workflow until all compliance requirements are fulfilled. Upon final approval,
the system generates a digital registration certificate with download facilities for applicants.
The solution also supports role-based access control, Head Office and Regional Office
workflows, automated notifications, workflow tracking, and centralized processing, providing
a secure, transparent, paperless, and efficient environment for delivering PCR Registration
services.

                                              201
```

## Page 203

```text
Figure Name: PCR Renewal Service Workflow

                  202
```

## Page 204

```text
Module - 1: Application Submission (Total Feature - 4)
Features Description
1. Online Application Submission
Allows applicants to submit registration applications through an online portal by providing
all required information. The system validates mandatory fields before accepting the
application.
2. Document Upload
Enables applicants to upload all required supporting documents in approved file formats.
Uploaded documents are securely stored and linked with the application for further review.
3. Application Fee Payment
Allows applicants to pay the prescribed application fee through the integrated online
payment gateway. Payment status is automatically recorded against the submitted
application.
4. Auto Application ID Generation
Automatically generates a unique Application ID upon successful submission. The generated
ID is used for application tracking and future correspondence.

Module - 2: Application Review & Shortfall Management (Total
Feature - 5)
Features Description
1. Application Review
Allows authorized officers to review submitted applications and verify the completeness of
information and supporting documents before further processing.
2. Shortfall Identification
Enables reviewers to identify missing information, incorrect data, or incomplete
documentation during the verification process.
3. Required Document Request
Allows reviewers to request additional documents or corrections from the applicant
whenever required. The request is recorded within the application history.
4. Shortfall Correction & Resubmission Loop
Applicants can update the requested information and resubmit the application for further
review. The review cycle continues until all requirements are fulfilled.
5. Applicant Notification
Automatically informs applicants regarding review status, identified shortfalls, and
resubmission requirements through the notification system.
Module - 3. Payment Processing (Total Feature - 4)

                                             203
```

## Page 205

```text
Features Description
1. Fee Display
Displays the applicable fees dynamically based on the selected service and predefined fee
structure.
2. Payment Collection
Collects payments securely through integrated payment gateways while maintaining
transaction records for auditing purposes.
3. Payment Verification
Verifies successful payment transactions automatically or through authorized verification
before processing the application further.
4. Automatic Status Update
Automatically updates the application status once payment is successfully completed and
verified.
Module-4. Inspection Setup (Total Feature - 3)
Features Description
1. Inspector Assignment
Allows authorized officials to assign inspectors based on workload, expertise, or jurisdiction.
2. Inspection Scheduling
Enables scheduling of inspection dates according to availability and organizational workflow
requirements.
3. Inspection Date/Team Setup & Approval
Allows designated authorities to finalize inspection teams and approve the inspection
schedule before execution.
Module-5. Inspection & Report (Total Feature - 5)
Features Description
1. Physical Inspection
Allows inspectors to conduct on-site inspections according to defined regulatory guidelines
and inspection criteria.
2. Inspection Findings
Records observations, compliance status, and identified issues during the inspection process.
3. Report Preparation
Enables inspectors to prepare structured inspection reports based on collected findings and
observations.
4. Photo Upload
Allows inspectors to upload inspection photographs as supporting evidence for the
inspection report.
5. Remarks Entry

                                             204
```

## Page 206

```text
Provides inspectors with the option to include additional comments, recommendations, or
observations in the inspection report.
Module-6. Verification Module (AD/DD) (Total Feature - 3)
Features Description
1. Inspection Report Review
Allows Assistant Director (AD) and Deputy Director (DD) to review submitted inspection
reports for completeness and accuracy.
2. Verification
Enables authorized officers to verify inspection findings before forwarding them for final
approval.
3. Comments & Feedback
Allows reviewers to provide comments, recommendations, or clarification requests during
the verification process.
Module-7. Approval Management (Total Feature - 3)
Features Description
1. Director Approval
Allows the Director to review verified applications and provide final approval for registration
based on compliance requirements.
2. Rejection
Allows the Director to reject applications with appropriate reasons whenever regulatory
requirements are not fulfilled.
3. Re-Inspection Decision
Enables the Director to request a re-inspection if additional verification is required before
making a final decision.
Module-8. Registration Complete (Total Feature - 3)
Features Description
1. Registration Completion
Finalizes the registration process after receiving all required approvals and successful
verification.
2. Registration Certificate Generation
Automatically generates the official registration certificate upon successful completion of the
registration process.
3. Download Link
Provides applicants with a secure link to download the issued registration certificate from
the system.
Module-9. Rejection Management (Total Feature - 2)

                                             205
```

## Page 207

```text
Features Description
1. Rejection Button Generation
Provides authorized users with the option to reject an application directly from the workflow
with proper justification.
2. Applicant Notification
Automatically notifies applicants regarding application rejection along with the stated
reasons and further instructions.
Module-10. Notification Management (Total Feature - 3)
Features Description
1. Email Notification
Automatically sends email notifications for important application events and workflow
updates.
2. SMS Notification
Sends SMS alerts to applicants regarding application progress, payment confirmation, and
approval status.
3. Status Update Notification
Provides real-time notifications whenever the application status changes throughout the
workflow.
Module-11. Re-Inspection Management (Total Feature - 3)
Features Description
1. Re-Inspection Request
Allows authorized officials to initiate a re-inspection request whenever additional verification
is necessary.
2. Return to Inspection Setup
Automatically routes the application back to the inspection scheduling stage for re-
inspection planning.
3. Repeat Inspection Cycle
Supports multiple inspection cycles until all compliance requirements are successfully
fulfilled.
Module-12. User & Role Management (Total Feature - 7)
Features Description
1. Applicant
Allows applicants to submit applications, upload documents, make payments, and track
application progress.
2. Reviewer
Enables reviewers to examine applications, identify shortfalls, and request additional
information from applicants.

                                             206
```

## Page 208

```text
3. Inspector
Allows inspectors to conduct inspections, record findings, upload evidence, and prepare
inspection reports.
4. AD
Provides Assistant Directors with authority to verify inspection reports and forward eligible
applications for higher approval.
5. DD
Allows Deputy Directors to review verified applications and recommend them for final
approval.
6. Director
Provides the Director with authority to approve, reject, or request re-inspection before final
registration.
7. System Admin Role Management
Allows administrators to create, manage, and assign user roles, permissions, and access
controls across the system.

Module-13. Regional Office Workflow (Total Feature - 3)
Features Description
1. Head Office Workflow
Supports centralized application processing and approval activities managed by the Head
Office.
2. Regional Office Workflow
Enables regional offices to process applications, perform inspections, and complete assigned
workflow activities independently.
3. Wing Head-Centric Processing
Allows Wing Heads to supervise, monitor, and approve workflow activities within their
respective organizational units.

                                            207
```

## Page 209

```text
    SERVICE 21
                           PCR BRAND INCLUSION
                           Brand Inclusion • Inspection • Approval • PCR Certificate

Service Profile
Domain                             Service Type                 Primary Users
PCR Registration                   Registration / Certification Applicants    •   Reviewers     •
                                   Service                      Inspectors • AD • DD • Director •
                                                                System Admin
Core Scope                         Modules                       Features
PCR Brand Inclusion
                                   13                            45

Functional Coverage
APPLICATION                      REVIEW                            INSPECTION
• Application Submission         • Application Review              • Inspection Setup
• Document Upload                • Shortfall Management            • Inspection & Report
• Application Fee                • Resubmission                    • Re-inspection

APPROVAL                         REGISTRATION                      CONTROL
• AD/DD Verification             • Registration Complete           • Notifications
• Approval Management            • Certificate Generation          • User & Role Management
• Director Decision              • Download                        • Regional Office Workflow

Module Catalogue
    Sl. No.     Module                            No. of Sl. Module                         No. of
                                                 Features No.                              Features
      01        Application Submission                 3    07 Approval Management            3
      02        Application    Review        &         5    08 Registration Complete          1
                Shortfall Management
      03        Payment Processing                     4    09 Rejection Management           2
      04        Inspection Setup                       3    10 Notification Management        3
      05        Inspection & Report                    5    11 Re-Inspection                  3
                                                               Management
      06        Verification (AD/DD)                   3    12 User & Role Management         7

                                                 208
```

## Page 210

```text
Service-21: PCR Brand Inclusion
The proposed PCR Brand Inclusion Service Management System is a comprehensive digital
platform designed to automate and manage the complete PCR Brand Inclusion process from
application submission to final approval. The system enables applicants to submit brand
inclusion applications online, upload required documents, and complete application fee
payments through an integrated payment processing module with automatic verification and
status updates. Submitted applications undergo a structured review process where
reviewers assess the application, identify shortfalls, request additional information, and
manage correction and resubmission cycles while keeping applicants informed through
automated notifications. Once the application is complete, inspection activities are scheduled,
inspectors are assigned, and inspection reports are prepared with findings, photographs, and
remarks. Laboratory testing is conducted where required, and the inspection and laboratory
reports are verified by AD/DD officials before being forwarded to the Director for the final
decision. Based on the Director's decision, the application may be approved, rejected, or sent
for re-inspection. Approved applications proceed to brand registration and PCR Brand
Inclusion certificate generation, while rejected applications trigger rejection notifications and
record management. Re-inspection requests return the application to the inspection stage
for further evaluation. The system also provides email, SMS, and status update notifications,
comprehensive role-based access control, and supports both Head Office and Regional
Office workflows, ensuring a transparent, standardized, and efficient PCR Brand Inclusion
service across the organization.

                                              209
```

## Page 211

```text
Figure Name: PCR Brand Inclusion Service Workflow

                      210
```

## Page 212

```text
Module-1: Application Submission (Total Feature - 3)
Feature Description
1. Online Application Submission
Allows applicants to submit applications electronically through the system by the
certification or licence number. System will automatically fill up the general information and
Factory Address information. Applicant will edit the product information like Add product,
variant or Brand.
2. Document Upload
Enables applicants to upload all required supporting documents, such as licenses,
certificates, identity documents, and other regulatory documents, in approved digital formats.
The system verifies file type, size, and completeness before accepting uploads.
3. Application Fee Payment
Allows applicants to pay the required application fee through integrated online payment
methods. The application is forwarded for review only after successful payment confirmation.
Module-2: Application Review & Shortfall Management (Total Feature
- 5)
Feature Description
1. Application Review
Enables designated reviewers to examine submitted applications and supporting documents
to verify completeness, accuracy, and compliance with applicable registration requirements.
2. Shortfall Identification
Allows reviewers to identify missing documents, incorrect information, incomplete
submissions, or regulatory non-compliance during the review process.
3. Required Document Request
Provides functionality to request additional documents, corrections, or clarifications from the
applicant whenever deficiencies are identified.
4. Shortfall Correction & Resubmission Loop
Allows applicants to update application information, upload revised documents, and
resubmit the application repeatedly until all identified shortfalls have been successfully
addressed.
5. Applicant Notification
Automatically sends notifications to applicants regarding review outcomes, identified
shortfalls, required corrective actions, and submission deadlines.
Module-3: Payment Processing (Total Feature - 4)
Feature Description
1. Fee Display
Automatically calculates and displays the applicable registration fee based on the selected
application category, product type, or registration service.

                                             211
```

## Page 213

```text
2. Payment Collection
Facilitates secure collection of registration fees through integrated online payment gateways
while recording complete transaction details.
3. Payment Verification
Verifies successful payment transactions by communicating with the integrated payment
gateway or banking system before allowing further application processing.
4. Automatic Status Update
Automatically updates the application status after successful payment verification,
eliminating the need for manual intervention.
Module-4: Inspection Setup (Total Feature - 3)
Feature Description
1. Inspector Assignment
Allows authorized officials to assign qualified inspectors based on predefined criteria such
as expertise, workload, geographical location, or department.
2. Inspection Scheduling
Enables scheduling of inspection dates and times while considering inspector availability,
applicant convenience, and organizational priorities.
3. Inspection Date/Team Setup & Approval
Allows management to finalize inspection schedules, assign inspection teams, and approve
inspection plans before the inspection process begins.
Module-5: Inspection & Report (Total Feature - 5)
Feature Description
1. Physical Inspection
Supports inspectors in conducting on-site inspections according to regulatory standards and
approved inspection procedures.
2. Inspection Findings
Enables inspectors to record inspection observations, compliance status, identified
deficiencies, and overall inspection results.
3. Report Preparation
Allows inspectors to prepare comprehensive digital inspection reports based on collected
findings, observations, and compliance assessments.
4. Photo Upload
Enables inspectors to upload photographs and supporting visual evidence to strengthen
inspection reports and document inspection findings.
5. Remarks Entry
Provides inspectors with the ability to record additional comments, recommendations,
observations, or special notes relevant to the inspection.

                                                212
```

## Page 214

```text
Module-6: Verification (AD/DD) (Total Feature - 3)
Feature Description
1. Inspection Report Review
Allows Assistant Directors (AD) and Deputy Directors (DD) to review submitted inspection
reports for completeness, consistency, and regulatory compliance.
2. Verification
Enables authorized officers to verify inspection findings and confirm that all regulatory
requirements have been fulfilled before forwarding the application for final approval.
3. Comments & Feedback
Allows reviewing officers to provide comments, recommendations, observations, or request
clarification whenever additional information is required.
Module-7: Approval Management (Total Feature - 3)
Feature Description
1. Director Approval
Allows the Director to review verified applications and grant final approval for registration
after ensuring all regulatory requirements have been satisfied.
2. Rejection
Enables the Director to reject applications that fail to comply with regulatory requirements
while recording the reasons for rejection.
3. Re-Inspection Decision
Allows the Director to request a re-inspection whenever additional verification or further
inspection is considered necessary before making the final decision.
Module-8: Registration Complete (Total Feature - 1)
Feature Description
1. Registration Completion
Finalizes the registration process by updating the application status to "Approved,"
completing all registration formalities, and preparing the application for certificate issuance.
Module-9: Rejection Management (Total Feature - 2)
Feature Description
1. Rejection Button Generation
Provides authorized users with the functionality to formally reject an application through the
system workflow while maintaining proper approval records.
2. Applicant Notification
Automatically informs applicants about the rejection decision along with the reasons for
rejection and any applicable guidance for future applications.

                                              213
```

## Page 215

```text
Module-10: Notification Management (Total Feature - 3)
Feature Description
1. Email Notification
Automatically sends email notifications to applicants and relevant officials regarding
application progress, payment confirmation, inspections, approvals, rejections, and other
workflow events.
2. SMS Notification
Sends SMS alerts for important application updates, reminders, inspection schedules,
payment confirmations, and final decisions to ensure timely communication.
3. Status Update Notification
Automatically notifies applicants whenever the application status changes throughout the
registration lifecycle, enabling real-time application tracking.
Module-11: Re-Inspection Management (Total Feature - 3)
Feature Description
1. Re-Inspection Request
Allows authorized officials to initiate a re-inspection request when additional verification or
corrective inspection is required.
2. Return to Inspection Setup
Automatically routes the application back to the Inspection Setup Module for scheduling and
assigning a new inspection.
3. Repeat Inspection Cycle
Supports multiple inspection cycles until all identified deficiencies have been resolved and
regulatory compliance has been achieved.
Module-12: User & Role Management (Total Feature - 7)
Features Description
1. Applicant
Allows applicants to create accounts, submit applications, upload documents, make
payments, monitor application status, and respond to shortfall requests.
2. Reviewer
Enables reviewing officers to examine submitted applications, identify deficiencies, request
additional information, and forward applications for inspection.
3. Inspector
Allows inspectors to conduct field inspections, record inspection findings, upload supporting
evidence, and submit inspection reports through the system.
4. Assistant Director (AD)
Provides Assistant Directors with authority to review inspection reports, verify compliance,
provide recommendations, and forward applications for higher-level verification.

                                              214
```

## Page 216

```text
5. Deputy Director (DD)
Enables Deputy Directors to perform final verification, validate inspection outcomes, provide
comments, and recommend approval, rejection, or re-inspection.
6. Director
Allows the Director to make the final decision by approving, rejecting, or requesting re-
inspection of registration applications.
7. System Admin Role Management
Enables system administrators to create and manage user accounts, assign roles, configure
permissions, manage access rights, reset passwords, and maintain overall system security.
Module-13: Regional Office Workflow (Total Feature - 3)
Features Description
1. Head Office Workflow
Supports centralized application processing and approval activities performed by the Head
Office while maintaining standardized operational procedures.
2. Regional Office Workflow
Enables Regional Offices to receive, review, inspect, and process applications independently
while following the organization's standardized workflow.
3. Wing Head-Centric Processing
Routes applications to the appropriate Wing Head based on jurisdiction or application
category, allowing the Wing Head to supervise, review, and approve applications before final
processing.

                                            215
```

## Page 217

```text
           REGISTERED                                          IMPORTER/EXPORTER
SERVICE 22 CERTIFICATE SERVICE
                  Importer/Exporter Registration • Inspection • Certification

Service Profile
Domain                               Service Type                 Primary Users
Importer / Exporter Registration     Registration / Certification Applicants • Director • DD • AD •
                                     Service                      Inspectors • System Admin
Core Scope                     Modules                              Features
Registered Importer / Exporter
Certification
                               12                                   53

Functional Coverage
APPLICATION                        REVIEW & SHORTFALL                 INSPECTION
• Application Submission           • Director Review                  • Scheduling
• Document Upload                  • AD Review                        • Inspection
• Registration Fee                 • Shortfall                        • Report Verification
                                   • Resubmission                     • Re-inspection

CERTIFICATION                      COMMUNICATION                     RECORDS
• Payment Processing               • Notifications                   • Document Management
• Certificate Management           •     Workflow  &            Task • Certificate Repository
• Rejection                        Management                        • Audit Records

Module Catalogue
Sl. Module                                No. of       Sl.   Module                            No. of
No.                                      Features      No.                                    Features

 01 Application Submission                   4         07    Payment Processing                  4
 02 Application Review & Shortfall           6         08    Certificate Management              5
    Management
 03 Inspection Scheduling                    4         09    Rejection Management                3
 04 Inspection Management                    4         10    Notification                        6
 05 Inspection Report Verification           4         11    Workflow & Task Management          5
 06 Re-inspection Management                 4         12    Document Management                 4

                                                 216
```

## Page 218

```text
Service-22: Registered Importer/Exporter Certificate Service
The Registered Importer/Exporter Certificate Service is a comprehensive digital solution
designed to automate and manage the complete registration and certification process for
importers and exporters. The system enables applicants to submit registration applications
online, upload mandatory documents, complete registration fee payments, and monitor
application progress through a centralized portal. Submitted applications undergo a
structured multi-level review process involving the Director, Deputy Director (DD), Assistant
Director (AD), and Inspectors to ensure regulatory compliance. If incomplete or incorrect
information is identified, the system automatically manages shortfall notifications, applicant
corrections, and application resubmissions without restarting the process.
The solution supports end-to-end inspection management, including inspection scheduling,
inspector assignment, inspection execution, report preparation, verification, approval, and re-
inspection when required. A role-based approval workflow ensures transparency and
accountability throughout the certification process. Following successful inspection approval,
the system generates payment requests, verifies payments, and automatically issues the
Registered Importer/Exporter Certificate with a unique certificate number.
The platform also provides centralized document management, automated notifications,
workflow tracking, audit trails, rejection management, and certificate repository services.
Every action is securely recorded to ensure complete traceability and regulatory compliance.
By replacing manual operations with a fully integrated digital workflow, the system improves
processing efficiency, reduces paperwork, enhances service transparency, and delivers faster
and more reliable certificate issuance.

                                             217
```

## Page 219

```text
Figure Name: Registered Importer/Exporter Certificate Service Diagram

                                218
```

## Page 220

```text
Module-1. Application Submission (Total Feature - 4)
Feature Description
1. Online Application Submission
Allows applicants to submit importer/exporter registration applications electronically
through the online portal.
2. Required Document Upload
Enables applicants to upload all mandatory supporting documents required for registration
verification.
3. Registration Fee Payment
Allows applicants to pay the prescribed registration fee through the integrated payment
system during application submission.
4. Application Tracking
Provides real-time tracking of application status from submission through certificate
issuance.
Module-2. Application Review & Shortfall Management (Total
Feature - 6)
Feature Description
1. Director Application Review
Allows the Director to review submitted applications and determine whether they are ready
for further processing.
2. Application Forwarding (DD/AD)
Enables the Director to forward applications to the Deputy Director or Assistant Director for
detailed review.
3. AD Application Review
Allows the Assistant Director to examine application details, supporting documents, and
compliance requirements.
4. Shortfall Identification
Identifies incomplete information, missing documents, or non-compliance that must be
corrected.
5. Shortfall Notification
Automatically informs applicants about identified deficiencies and required corrections.
6. Customer Resubmission
Allows applicants to correct deficiencies and resubmit the application for continued
processing.
Module-3. Inspection Scheduling (Total Feature - 4)
Feature Description
1. Inspection Date Scheduling
Allows authorized officers to schedule inspection dates based on operational requirements.

                                            219
```

## Page 221

```text
2. Inspection Date Rescheduling
Enables modification of scheduled inspection dates when necessary.
3. Multi-Level Inspection Date Approval (AD, DD, Director)
Supports hierarchical approval of inspection schedules before confirmation.
4. Inspection Schedule Notification
Automatically notifies applicants and inspectors about confirmed inspection schedules.
Module-4. Inspection Management (Total Feature - 4)
Feature Description
1. Inspector Assignment
Assigns qualified inspectors based on availability, workload, and expertise.
2. Inspection Execution
Allows inspectors to perform on-site inspections according to regulatory guidelines.
3. Inspection Report Preparation
Enables inspectors to prepare structured inspection reports after completing inspections.
4. Inspection Findings Recording
Records observations, compliance status, violations, and recommendations identified during
inspections.
Module-5. Inspection Report Verification (Total Feature - 4)
Feature Description
1. AD Inspection Report Preparation
Allows the Assistant Director to prepare or consolidate inspection reports based on
submitted findings.
2. AD Inspection Report Verification
Enables the Assistant Director to verify report completeness, accuracy, and compliance.
3. DD Inspection Report Approval
Allows the Deputy Director to review verified inspection reports and provide managerial
approval.
4. Director Final Approval
Enables the Director to provide final approval before certificate processing.
Module-6. Re-inspection Management (Total Feature - 4)
Feature Description
1. Re-inspection Request
Allows authorized officers to request another inspection when compliance issues remain
unresolved.
2. Re-inspection Scheduling
Schedules follow-up inspections after deficiencies have been addressed.
3. Re-inspection Workflow
Manages the approval, execution, and monitoring of repeat inspections.

                                             220
```

## Page 222

```text
4. Updated Inspection Report
Generates revised inspection reports reflecting the latest inspection results.
Module-7. Payment Processing (Total Feature - 4)
Feature Description
1. Registration Fee Request
Automatically generates payment requests after successful completion of the approval
process.
2. Payment Collection
Collects registration fees through integrated payment channels.
3. Payment Verification
Verifies successful payment transactions before certificate issuance.
4. Payment Confirmation
Confirms payment completion and authorizes certificate generation.
Module-8. Certificate Management (Total Feature - 5)
Feature Description
1. Certificate Generation
Automatically generates the Registered Importer/Exporter Certificate after successful
approval.
2. Certificate Number Generation
Assigns a unique certificate number for identification and traceability.
3. Certificate Issuance
Issues the approved certificate to the applicant.
4. Certificate Download
Allows applicants to securely download the issued certificate.
5. Certificate Record Management
Maintains a centralized repository of all issued certificates for future reference, renewal, and
verification.
Module-9. Rejection Management (Total Feature - 3)
Feature Description
1. Rejection Decision
Allows authorized officers to reject applications that fail to satisfy regulatory requirements.
2. Reject Note Generation
Automatically generates a formal rejection note explaining the reasons for rejection.
3. Customer Notification
Notifies applicants regarding application rejection through the notification system.
Module-10. Notification (Total Feature - 6)
Feature Description

                                             221
```

## Page 223

```text
1. Shortfall Notification
Sends notifications whenever deficiencies are identified in the application.
2. Inspection Schedule Notification
Notifies applicants and inspectors about inspection schedules.
3. Inspection Approval Notification
Informs stakeholders after inspection reports receive final approval.
4. Payment Request Notification
Notifies applicants when payment is required before certificate issuance.
5. Certificate Issued Notification
Informs applicants immediately after certificate issuance.
6. Rejection Notification
Send rejection notifications together with the rejection reason.
Module-11. Workflow & Task Management (Total Feature - 5)
Feature Description
1. Multi-Level Workflow
Controls the end-to-end application workflow across multiple approval levels.
2. Role-based Task Assignment
Assigns processing tasks according to predefined organizational roles.
3. Application Status Tracking
Tracks application progress throughout every stage of processing.
4. Workflow Remarks
Stores comments, observations, and recommendations recorded during application
processing.
5. Audit Trail
Maintains a complete history of user activities, approvals, and workflow actions for
accountability.
Module-12. Document Management (Total Feature - 4)
Feature Description
1. Application Document Management
Stores and manages all application-related documents in a secure repository.
2. Inspection Report Management
Maintains inspection reports with version control and secure storage.
3. Certificate Repository
Provides centralized storage for all issued importer/exporter certificates.
4. Reject Note Management
Stores rejection notes and related documents for audit and future reference.

                                             222
```

## Page 224

```text
                REGISTERED      IMPORTER/EXPORTER
  SERVICE
    23          CERTIFICATE MANAGEMENT RENEWAL
                Renewal / Re-Certification • Inspection • Certificate

Service Profile
Domain                               Service Type                 Primary Users
Importer / Exporter Registration     Renewal /      Certification Applicants • Director • DD • AD •
                                     Service                      Inspectors • System Admin
Core Scope                     Modules                             Features
Registered Importer / Exporter
Renewal
                               12                                  55

Functional Coverage
APPLICATION                        REVIEW & SHORTFALL                 INSPECTION
• Application Submission           • Director Review                  • Scheduling
• Document Upload                  • AD Review                        • Inspection
• Registration Fee                 • Shortfall                        • Report Verification
                                   • Resubmission                     • Re-inspection

CERTIFICATION                      COMMUNICATION                    RECORDS
• Payment Processing               • Notifications                  • Document Management
• Certificate Management           •     Workflow  &           Task • Certificate Repository
• Rejection                        Management                       • Audit Records

Module Catalogue
Sl. Module                                No. of       Sl.   Module                            No. of
No.                                      Features      No.                                    Features

 01 Re-Application Submission                6         07    Payment Processing                  4
 02 Application Review & Shortfall           6         08    Certificate Management              5
    Management
 03 Inspection Scheduling                    4         09    Rejection Management                3
 04 Inspection Management                    4         10    Notification Management             6
 05 Inspection Report Verification           4         11    Workflow & Task Management          5
 06 Re-inspection Management                 4         12    Document Management                 4

                                                 223
```

## Page 225

```text
Service-23: Registered Importer/Exporter Certificate
Management Renewal
The Registered Importer/Exporter Re-Certification Service is a comprehensive digital
solution designed to automate and manage the complete registration and certification
process for importers and exporters. The system enables applicants to submit registration
applications online, upload mandatory documents, complete registration fee payments, and
monitor application progress through a centralized portal. Submitted applications undergo a
structured multi-level review process involving the Director, Deputy Director (DD), Assistant
Director (AD), and Inspectors to ensure regulatory compliance. If incomplete or incorrect
information is identified, the system automatically manages shortfall notifications, applicant
corrections, and application resubmissions without restarting the process.
The solution supports end-to-end inspection management, including inspection scheduling,
inspector assignment, inspection execution, report preparation, verification, approval, and re-
inspection when required. A role-based approval workflow ensures transparency and
accountability throughout the certification process. Following successful inspection approval,
the system generates payment requests, verifies payments, and automatically issues the
Registered Importer/Exporter Certificate with a unique certificate number.
The platform also provides centralized document management, automated notifications,
workflow tracking, audit trails, rejection management, and certificate repository services.
Every action is securely recorded to ensure complete traceability and regulatory compliance.
By replacing manual operations with a fully integrated digital workflow, the system improves
processing efficiency, reduces paperwork, enhances service transparency, and delivers faster
and more reliable certificate issuance.

                                             224
```

## Page 226

```text
Fig: Workflow diagram of Registered Importer/Exporter Re-Certification Service

                                     225
```

## Page 227

```text
Module- 1: Re-Application Submission (Total Feature - 6)
Feature Description:
1. Online Application Submission
Allows applicants to submit importer/exporter registration applications electronically
through the online portal.
2. Required Document Upload
Enables applicants to upload all mandatory supporting documents required for registration
verification.
3. Registration Fee Payment
Allows applicants to pay the prescribed registration fee through the integrated payment
system during application submission.
4. Application Tracking
Provides real-time tracking of application status from submission through certificate
issuance.
Module- 2: Application Review & Shortfall Management (Total
Feature - 6)
Feature Description:
1. Director Application Review
Allows the Director to review submitted applications and determine whether they are ready
for further processing.
2. Application Forwarding (DD/AD)
Enables the Director to forward applications to the Deputy Director or Assistant Director for
detailed review.
3. AD Application Review
Allows the Assistant Director to examine application details, supporting documents, and
compliance requirements.
4. Shortfall Identification
Identifies incomplete information, missing documents, or non-compliance that must be
corrected.
5. Shortfall Notification
Automatically informs applicants about identified deficiencies and required corrections.
6. Customer Resubmission
Allows applicants to correct deficiencies and resubmit the application for continued
processing.
Module- 3: Inspection Scheduling (Total Feature - 4)
Feature Description:
1. Inspection Date Scheduling
Allows authorized officers to schedule inspection dates based on operational requirements.

                                            226
```

## Page 228

```text
2. Inspection Date Rescheduling
Enables modification of scheduled inspection dates when necessary.
3. Multi-Level Inspection Date Approval (AD, DD, Director)
Supports hierarchical approval of inspection schedules before confirmation.
4. Inspection Schedule Notification
Automatically notifies applicants and inspectors about confirmed inspection schedules.
Module- 4: Inspection Management (Total Feature - 4)
Feature Description:
1. Inspector Assignment
Assigns qualified inspectors based on availability, workload, and expertise.
2. Inspection Execution
Allows inspectors to perform on-site inspections according to regulatory guidelines.
3. Inspection Report Preparation
Enables inspectors to prepare structured inspection reports after completing inspections.
4. Inspection Findings Recording
Records observations, compliance status, violations, and recommendations identified during
inspections.
Module- 5: Inspection Report Verification (Total Feature - 4)
Feature Description:
1. AD Inspection Report Preparation
Allows the Assistant Director to prepare or consolidate inspection reports based on
submitted findings.
2. AD Inspection Report Verification
Enables the Assistant Director to verify report completeness, accuracy, and compliance.
3. DD Inspection Report Approval
Allows the Deputy Director to review verified inspection reports and provide managerial
approval.
4. Director Final Approval
Enables the Director to provide final approval before certificate processing.
Module- 6: Re-inspection Management (Total Feature - 4)
Feature Description:
1. Re-inspection Request
Allows authorized officers to request another inspection when compliance issues remain
unresolved.
2. Re-inspection Scheduling
Schedules follow-up inspections after deficiencies have been addressed.
3. Re-inspection Workflow
Manages the approval, execution, and monitoring of repeat inspections.

                                             227
```

## Page 229

```text
4. Updated Inspection Report
Generates revised inspection reports reflecting the latest inspection results.
Module- 7: Payment Processing (Total Feature - 4)
Feature Description:
1. Registration Fee Request
Automatically generates payment requests after successful completion of the approval
process.
2. Payment Collection
Collects registration fees through integrated payment channels.
3. Payment Verification
Verifies successful payment transactions before certificate issuance.
4. Payment Confirmation
Confirms payment completion and authorizes certificate generation.
Module- 8: Certificate Management (Total Feature - 5)
Feature Description:
1. Certificate Generation
Automatically generates the Registered Importer/Exporter Certificate after successful
approval.
2. Certificate Number Generation
Assigns a unique certificate number for identification and traceability.
3. Certificate Issuance
Issues the approved certificate to the applicant.
4. Certificate Download
Allows applicants to securely download the issued certificate.
5. Certificate Record Management
Maintains a centralized repository of all issued certificates for future reference, renewal, and
verification.
Module- 9: Rejection Management (Total Feature - 3)
Feature Description:
1. Rejection Decision
Allows authorized officers to reject applications that fail to satisfy regulatory requirements.
2. Reject Note Generation
Automatically generates a formal rejection note explaining the reasons for rejection.
3. Customer Notification
Notifies applicants regarding application rejection through the notification system.
Module- 10: Notification Management (Total Feature - 6)
Feature Description:

                                             228
```

## Page 230

```text
1. Shortfall Notification
Sends notifications whenever deficiencies are identified in the application.
2. Inspection Schedule Notification
Notifies applicants and inspectors about inspection schedules.
3. Inspection Approval Notification
Informs stakeholders after inspection reports receive final approval.
4. Payment Request Notification
Notifies applicants when payment is required before certificate issuance.
5. Certificate Issued Notification
Informs applicants immediately after certificate issuance.
6. Rejection Notification
Send rejection notifications together with the rejection reason.
Module- 11: Workflow & Task Management (Total Feature - 5)
Feature Description:
1. Multi-Level Workflow
Controls the end-to-end application workflow across multiple approval levels.
2. Role-based Task Assignment
Assigns processing tasks according to predefined organizational roles.
3. Application Status Tracking
Tracks application progress throughout every stage of processing.
4. Workflow Remarks
Stores comments, observations, and recommendations recorded during application
processing.
5. Audit Trail
Maintains a complete history of user activities, approvals, and workflow actions for
accountability.
Module- 12. Document Management (Total Feature - 4)
Feature Description:
1. Application Document Management
Stores and manages all application-related documents in a secure repository.
2. Inspection Report Management
Maintains inspection reports with version control and secure storage.
3. Certificate Repository
Provides centralized storage for all issued importer/exporter certificates.
4. Reject Note Management
Stores rejection notes and related documents for audit and future reference.

                                             229
```

## Page 231

```text
  SERVICE      METROLOGY LICENSE ISSUE
    24         License Application • Inspection • Verification • Licensing

Service Profile
Domain                            Service Type                    Primary Users
Metrology Licensing               Licensing /         Calibration Applicants • Director • DD • AD •
                                  Service                         Inspectors • System Admin
Core Scope                        Modules                          Features
Metrology License Lifecycle
                                  13                               54

Functional Coverage
APPLICATION                     INSPECTION                           VERIFICATION
• Application Submission        • Inspection Scheduling              • AD Verification
• Category-wise Application     • Inspection Management              • DD Approval
• Shortfall Management          • Re-inspection                      • Director Approval

LICENSING                       COMMUNICATION                        RECORDS
• Payment Processing            • Notification                       • Document Management
• License Generation            • Status Tracking                    • License Repository
• License Download              • Workflow                           • Rejection Records

Module Catalogue
Sl. Module                                No. of      Sl.   Module                          No. of
No.                                      Features     No.                                  Features

 01 Application Submission                  4         07    Re-inspection Management          4
 02 Application Review & Assignment         4         08    Payment Processing                4
 03 Shortfall Management                    5         09    License Management                4
 04 Inspection Scheduling                   4         10    Rejection Management              3
 05 Inspection Management                   3         11    Notification                      6
 06 Inspection Verification & Approval      4         12    Workflow & Task Management        5

                                                230
```

## Page 232

```text
Service-24: Metrology License Issue
The Metrology License Registration New System is a centralized, workflow-driven digital
solution that automates the complete licensing process from application submission to
license issuance. The system enables applicants to submit category-wise applications online,
upload required documents, and monitor application progress in real time. Every application
passes through a structured multi-level review process involving Directors, Deputy Directors
(DD), Assistant Directors (AD), and Inspectors. During the review stage, incomplete
applications are managed through an automated shortfall process that allows applicants to
correct deficiencies and resubmit documents without restarting the workflow.
The solution includes comprehensive inspection management, where inspections are
scheduled, approved, executed, verified, and, if necessary, repeated through a re-inspection
workflow. Role-based approvals ensure transparency and accountability at every stage.
Once inspection activities are successfully completed, the system generates payment
requests based on the application category and verifies payment before proceeding to license
issuance.
The platform also supports automated notifications, centralized document management,
workflow tracking, audit trails, and rejection management for unsuccessful applications.
Every activity is recorded to ensure complete traceability and regulatory compliance. By
digitizing manual processes, reducing paperwork, and providing end-to-end workflow
automation, the system improves operational efficiency, enhances transparency, minimizes
processing time, and delivers a secure and paperless licensing management environment.

                                            231
```

## Page 233

```text
Fig: Metrology License New Service Workflow

                   232
```

## Page 234

```text
Module-1. Application Submission (Total Feature - 4)
Feature Description
1. Online Application Submission
Allows applicants to submit license applications electronically through a web portal,
eliminating manual paperwork while ensuring standardized application submission.
2. Required Document Upload
Enables applicants to upload all mandatory supporting documents such as certificates,
identification documents, reports, and declarations required for application processing.
3. Category Wise Application Submission
Allows applicants to select the appropriate license category or service type so that the
application follows the correct workflow, requirements, and fee structure.
4. Application Tracking
Provides real-time tracking of application progress, allowing applicants to monitor the
current processing stage, assigned officer, pending actions, and final status.
Module-2. Application Review & Assignment (Total Feature - 4)
Feature Description
1. Director Application Review
Allows the Director to review newly submitted applications, verify completeness, and decide
whether they are ready for further processing.
2. Application Forwarding (DD/AD/Inspector)
Enables the Director to forward reviewed applications to the appropriate Deputy Director,
Assistant Director, or Inspector for subsequent processing.
3. Role-based Assignment
Automatically or manually assigns applications to officers according to predefined roles,
responsibilities, workload, or organizational hierarchy.
4. Workflow Remarks
Allows reviewing officers to record comments, recommendations, observations, or
processing notes throughout the application lifecycle.
Module-3. Shortfall Management (Total Feature - 5)
Feature Description
1. Application Review
Allows assigned officers to review submitted information and verify compliance with
licensing requirements.
2. Shortfall Identification
Identifies missing documents, incorrect information, or compliance gaps that must be
corrected before further processing.

                                             233
```

## Page 235

```text
3. Shortfall Notification
Automatically notifies applicants about identified deficiencies with detailed correction
instructions.
4. Customer Correction
Allows applicants to update application information and upload corrected documents based
on the received shortfall notice.
5. Application Resubmission
Enables applicants to resubmit corrected applications, returning them to the review
workflow without creating a new application.
Module-4. Inspection Scheduling (Total Feature - 4)
Feature Description
1. Inspection Date Scheduling
Allows authorized officers to schedule inspection dates according to inspector availability
and application requirements.
2. Inspection Date Rescheduling
Enables modification of scheduled inspection dates due to operational requirements or
applicant requests.
3. Multi-Level Inspection Date Approval (AD, DD, Director)
Supports hierarchical approval of inspection schedules before confirmation.
4. Inspection Notification
Automatically informs applicants and inspectors about confirmed inspection schedules
through system notifications.
Module-5. Inspection Management (Total Feature - 3)
Feature Description
1. Inspection Execution
Allows inspectors to conduct field inspections according to approved schedules and
regulatory guidelines.
2. Inspection Report Preparation
Enables inspectors to prepare structured inspection reports based on inspection findings.
3. Inspection Findings Recording
Records inspection observations, compliance status, violations, recommendations, and
supporting evidence.
Module-6. Inspection Verification & Approval (Total Feature - 4)
Feature Description
1. AD Report Verification
Allows the Assistant Director to verify the completeness and accuracy of inspection reports.

                                            234
```

## Page 236

```text
2. DD Report Approval
Enables the Deputy Director to review verified inspection reports and provide managerial
approval.
3. Director Final Approval
Allows the Director to perform the final review and authorize inspection completion.
4. Workflow Tracking
Maintains complete tracking of report movement, approvals, pending actions, and processing
history.
Module-7. Re-inspection Management (Total Feature - 4)
Feature Description
1. Re-inspection Request
Allows authorized officers to request another inspection when deficiencies remain
unresolved.
2. Re-scheduling Inspection
Schedules a new inspection date for follow-up verification.
3. Re-inspection Workflow
Manages the complete approval and execution process for repeat inspections.
4. Updated Inspection Report
Generates revised inspection reports reflecting the latest inspection findings.
Module-8. Payment Processing (Total Feature - 4)
Feature Description
1. License Payment Request
Automatically generates payment requests after successful completion of all approval
stages.
2. Application Category Wise Payment Collection
Calculates and collects fees based on the selected license category or service type.
3. Payment Verification
Verifies payment transactions received from the integrated payment gateway or banking
system.
4. Payment Confirmation
Confirms successful payment and activates the next stage of license generation.
Module-9. License Management (Total Feature - 4)
Feature Description
1. License Generation
Automatically generates the official license after successful approval and payment
verification.
2. License Issuance
Issues the approved license to the applicant through the system.

                                             235
```

## Page 237

```text
3. License Download
Allows applicants to securely download the issued digital license.
4. License Record Management
Maintains a centralized repository of all issued licenses for future verification, renewal, and
reporting.
Module-10. Rejection Management (Total Feature - 3)
Feature Description
1. Rejection Decision
Allows authorized officials to reject applications that fail to satisfy regulatory requirements.
2. Rejection Letter Generation
Automatically generates formal rejection letters with reasons for rejection.
3. Customer Notification
Notifies applicants about application rejection through the notification system.
Module-11. Notification (Total Feature - 6)
Feature Description
1. Shortfall Notification
Notifies applicants whenever application deficiencies are identified.
2. Inspection Schedule Notification
Sends inspection schedule information to applicants and inspectors.
3. Inspection Approval Notification
Notifies stakeholders when inspection approvals are completed.
4. Payment Request Notification
Informs applicants that payment is required before license issuance.
5. License Issued Notification
Notifies applicants immediately after successful license issuance.
6. Rejection Notification
Send rejection notifications along with the rejection reason.
Module-12. Workflow & Task Management (Total Feature - 5)
Feature Description
1. Multi-Level Workflow
Controls the complete application workflow across multiple approval levels.
2. Role-based Task Assignment
Assigns processing tasks automatically based on organizational roles and responsibilities.
3. Application Status Tracking
Tracks application progress from submission through final completion.
4. Workflow Remarks
Stores comments and observations recorded during each workflow stage.

                                              236
```

## Page 238

```text
5. Audit Trail
Maintains complete logs of every action, approval, modification, and workflow activity for
accountability.
Module-13. Document Management (Total Feature - 4)
Feature Description
1. Application Document Management
Stores, organizes, and manages all documents submitted with license applications.
2. Inspection Report Management
Maintains inspection reports with version control and secure storage.
3. License Document Repository
Provides a centralized repository for all issued license documents.
4. Rejection Letter Storage
Stores generated rejection letters for future reference and audit purposes.

                                            237
```

## Page 239

```text
               METROLOGY                            LICENSE                      RENEWAL
  SERVICE
    25         REGISTRATION
               License Renewal • Inspection • Verification • Licensing

Service Profile
Domain                            Service Type                    Primary Users
Metrology Licensing               Licensing /         Calibration Applicants • Director • DD • AD •
                                  Service                         Inspectors • System Admin
Core Scope                        Modules                          Features
Metrology License Lifecycle
                                  13                               54

Functional Coverage
APPLICATION                     INSPECTION                           VERIFICATION
• Application Submission        • Inspection Scheduling              • AD Verification
• Category-wise Application     • Inspection Management              • DD Approval
• Shortfall Management          • Re-inspection                      • Director Approval

LICENSING                       COMMUNICATION                        RECORDS
• Payment Processing            • Notification                       • Document Management
• License Generation            • Status Tracking                    • License Repository
• License Download              • Workflow                           • Rejection Records

Module Catalogue
Sl. Module                                No. of      Sl.   Module                          No. of
No.                                      Features     No.                                  Features

 01 Application Submission                  4         07    Re-inspection Management          4
 02 Application Review & Assignment         4         08    Payment Processing                4
 03 Shortfall Management                    5         09    License Management                4
 04 Inspection Scheduling                   4         10    Rejection Management              3
 05 Inspection Management                   3         11    Notification                      6
 06 Inspection Verification & Approval      4         12    Workflow & Task Management        5

                                                238
```

## Page 240

```text
Service-25: Metrology License Renewal Registration
The Metrology License Registration New System is a centralized, workflow-driven digital
solution that automates the complete licensing process from application submission to
license issuance. The system enables applicants to submit category-wise applications online,
upload required documents, and monitor application progress in real time. Every application
passes through a structured multi-level review process involving Directors, Deputy Directors
(DD), Assistant Directors (AD), and Inspectors. During the review stage, incomplete
applications are managed through an automated shortfall process that allows applicants to
correct deficiencies and resubmit documents without restarting the workflow.
The solution includes comprehensive inspection management, where inspections are
scheduled, approved, executed, verified, and, if necessary, repeated through a re-inspection
workflow. Role-based approvals ensure transparency and accountability at every stage.
Once inspection activities are successfully completed, the system generates payment
requests based on the application category and verifies payment before proceeding to license
issuance.
The platform also supports automated notifications, centralized document management,
workflow tracking, audit trails, and rejection management for unsuccessful applications.
Every activity is recorded to ensure complete traceability and regulatory compliance. By
digitizing manual processes, reducing paperwork, and providing end-to-end workflow
automation, the system improves operational efficiency, enhances transparency, minimizes
processing time, and delivers a secure and paperless licensing management environment.

                                            239
```

## Page 241

```text
Fig: Workflow diagram of Metrology Re-New Registration

                         240
```

## Page 242

```text
Module-1. Application Submission (Total Feature - 4)
Feature Description
1. Online Re-Application Submission
Allows applicants to submit license re-applications electronically through a web portal,
eliminating manual paperwork while ensuring standardized application submission.
2. Required Document Upload
Enables applicants to upload all mandatory supporting documents such as certificates,
identification documents, reports, and declarations required for application processing.
3. Category Wise Application Submission
Allows applicants to select the appropriate license category or service type so that the
application follows the correct workflow, requirements, and fee structure.
4. Application Tracking
Provides real-time tracking of application progress, allowing applicants to monitor the
current processing stage, assigned officer, pending actions, and final status.
Module-2. Application Review & Assignment (Total Feature - 4)
Feature Description
1. Director Application Review
Allows the Director to review newly submitted applications, verify completeness, and decide
whether they are ready for further processing.
2. Application Forwarding (DD/AD/Inspector)
Enables the Director to forward reviewed applications to the appropriate Deputy Director,
Assistant Director, or Inspector for subsequent processing.
3. Role-based Assignment
Automatically or manually assigns applications to officers according to predefined roles,
responsibilities, workload, or organizational hierarchy.
4. Workflow Remarks
Allows reviewing officers to record comments, recommendations, observations, or
processing notes throughout the application lifecycle.
Module-3. Shortfall Management (Total Feature - 5)
Feature Description
1. Application Review
Allows assigned officers to review submitted information and verify compliance with
licensing requirements.
2. Shortfall Identification
Identifies missing documents, incorrect information, or compliance gaps that must be
corrected before further processing.

                                             241
```

## Page 243

```text
3. Shortfall Notification
Automatically notifies applicants about identified deficiencies with detailed correction
instructions.
4. Customer Correction
Allows applicants to update application information and upload corrected documents based
on the received shortfall notice.
5. Application Resubmission
Enables applicants to resubmit corrected applications, returning them to the review
workflow without creating a new application.
Module-4. Inspection Scheduling (Total Feature - 4)
Feature Description
1. Inspection Date Scheduling
Allows authorized officers to schedule inspection dates according to inspector availability
and application requirements.
2. Inspection Date Rescheduling
Enables modification of scheduled inspection dates due to operational requirements or
applicant requests.
3. Multi-Level Inspection Date Approval (AD, DD, Director)
Supports hierarchical approval of inspection schedules before confirmation.
4. Inspection Notification
Automatically informs applicants and inspectors about confirmed inspection schedules
through system notifications.
Module-5. Inspection Management (Total Feature - 3)
Feature Description
1. Inspection Execution
Allows inspectors to conduct field inspections according to approved schedules and
regulatory guidelines.
2. Inspection Report Preparation
Enables inspectors to prepare structured inspection reports based on inspection findings.
3. Inspection Findings Recording
Records inspection observations, compliance status, violations, recommendations, and
supporting evidence.
Module-6. Inspection Verification & Approval (Total Feature - 4)
Feature Description
1. AD Report Verification
Allows the Assistant Director to verify the completeness and accuracy of inspection reports.

                                            242
```

## Page 244

```text
2. DD Report Approval
Enables the Deputy Director to review verified inspection reports and provide managerial
approval.
3. Director Final Approval
Allows the Director to perform the final review and authorize inspection completion.
4. Workflow Tracking
Maintains complete tracking of report movement, approvals, pending actions, and processing
history.
Module-7. Re-inspection Management (Total Feature - 4)
Feature Description
1. Re-inspection Request
Allows authorized officers to request another inspection when deficiencies remain
unresolved.
2. Re-scheduling Inspection
Schedules a new inspection date for follow-up verification.
3. Re-inspection Workflow
Manages the complete approval and execution process for repeat inspections.
4. Updated Inspection Report
Generates revised inspection reports reflecting the latest inspection findings.
Module-8. Payment Processing (Total Feature - 4)
Feature Description
1. License Payment Request
Automatically generates payment requests after successful completion of all approval
stages.
2. Application Category Wise Payment Collection
Calculates and collects fees based on the selected license category or service type.
3. Payment Verification
Verifies payment transactions received from the integrated payment gateway or banking
system.
4. Payment Confirmation
Confirms successful payment and activates the next stage of license generation.
Module-9. License Management (Total Feature - 4)
Feature Description
1. License Generation
Automatically generates the official license after successful approval and payment
verification.
2. License Issuance
Issues the approved license to the applicant through the system.

                                             243
```

## Page 245

```text
3. License Download
Allows applicants to securely download the issued digital license.
4. License Record Management
Maintains a centralized repository of all issued licenses for future verification, renewal, and
reporting.
Module-10. Rejection Management (Total Feature - 3)
Feature Description
1. Rejection Decision
Allows authorized officials to reject applications that fail to satisfy regulatory requirements.
2. Rejection Letter Generation
Automatically generates formal rejection letters with reasons for rejection.
3. Customer Notification
Notifies applicants about application rejection through the notification system.
Module-11. Notification (Total Feature - 6)
Feature Description
1. Shortfall Notification
Notifies applicants whenever application deficiencies are identified.
2. Inspection Schedule Notification
Sends inspection schedule information to applicants and inspectors.
3. Inspection Approval Notification
Notifies stakeholders when inspection approvals are completed.
4. Payment Request Notification
Informs applicants that payment is required before license issuance.
5. License Issued Notification
Notifies applicants immediately after successful license issuance.
6. Rejection Notification
Send rejection notifications along with the rejection reason.
Module-12. Workflow & Task Management (Total Feature - 5)
Feature Description
1. Multi-Level Workflow
Controls the complete application workflow across multiple approval levels.
2. Role-based Task Assignment
Assigns processing tasks automatically based on organizational roles and responsibilities.
3. Application Status Tracking
Tracks application progress from submission through final completion.
4. Workflow Remarks
Stores comments and observations recorded during each workflow stage.

                                              244
```

## Page 246

```text
5. Audit Trail
Maintains complete logs of every action, approval, modification, and workflow activity for
accountability.
Module-13. Document Management (Total Feature - 4)
Feature Description
1. Application Document Management
Stores, organizes, and manages all documents submitted with license applications.
2. Inspection Report Management
Maintains inspection reports with version control and secure storage.
3. License Document Repository
Provides a centralized repository for all issued license documents.
4. Rejection Letter Storage
Stores generated rejection letters for future reference and audit purposes.

                                            245
```

## Page 247

```text
  SERVICE       TANK LORRY CALIBRATION
    26          Calibration • Report Verification • Re-calibration • License

Service Profile
Domain                                Service Type                   Primary Users
Metrology Calibration                 Calibration Service            Applicants • Director • DD • AD •
                                                                     Inspectors • System Admin
Core Scope                            Modules                        Features
Tank Lorry Calibration Lifecycle
                                      12                             49

Functional Coverage
APPLICATION                        CALIBRATION                         VERIFICATION
• Application Submission           • Calibration Scheduling            • AD/DD Verification
• Document Upload                  • Calibration Management            • Director Approval
• Application Fee                  • Report Preparation                • Approval History
• Shortfall

LICENSING                          RE-CALIBRATION                      CONTROL
• License Management               • Re-inspection                     • Rejection
• Volume-based Fee                 • Re-calibration                    • Notifications
• License Download                 • Updated Report                    • Workflow
                                                                       • Documents

Module Catalogue
Sl. Module                                  No. of      Sl.   Module                            No. of
No.                                        Features     No.                                    Features

 01 Application Submission                    4         07    License Management                  4
 02 Application Review & Assignment           4         08    Re-inspection / Re-calibration      4
                                                              Management
 03 Shortfall Management                      5         09    Rejection Management                3
 04 Calibration Scheduling                    4         10    Notification                        5
 05 Calibration Management                    3         11    Workflow & Task Management          5
 06 Calibration Report Verification           4         12    Document Management                 4

                                                  246
```

## Page 248

```text
Service-26: Tank Lorry Calibration
The Tank Lorry Calibration Service is a comprehensive digital solution designed to
automate the calibration, verification, approval, and license issuance process for tank
lorries. The system allows applicants to submit calibration applications online,
upload required documents, pay applicable fees, and monitor application status
throughout the process. Applications are reviewed through a role-based workflow
where authorized officials verify submissions, assign responsibilities, and identify
deficiencies requiring correction. The platform supports calibration scheduling,
rescheduling, multi-level schedule approval, calibration execution, and digital
calibration report preparation. Calibration reports undergo verification and final
approval before licenses are issued. If calibration results do not meet regulatory
requirements, the system manages re-inspection or re-calibration requests,
scheduling, and updated calibration reports. License fees are determined based on
changes in product volume, and approved applicants can download their licenses
online. The solution also provides automated notifications, workflow tracking, audit
trails, and centralized document management to ensure transparency, operational
efficiency, regulatory compliance, and accurate calibration record management.

                                         247
```

## Page 249

```text
Fig: Workflow diagram of Tank Lorry Calibration Service

                         248
```

## Page 250

```text
Module-1. Application Submission (Total Feature - 4)
Feature Description:
1. Online Application Submission
Enables applicants to submit tank lorry calibration applications through the online portal.
2. Required Document Upload
Allows applicants to upload all mandatory documents required for calibration.
3. Application Fee Payment
Facilitates payment of the prescribed calibration application fee.
4. Application Tracking
Enables applicants to monitor the progress and current status of their submitted applications.
Module- 2: Application Review & Assignment (Total Feature - 4)
Feature Description:
1. Director Application Review
Allows the Director to conduct the initial review of submitted applications.
2. Application Forwarding/Assignment (DD/AD/Inspector)
Forwards applications to the appropriate officials for detailed processing.
3. Role-based Assignment
Assigns tasks according to user roles and responsibilities.
4. Workflow Remarks
Allows officials to record comments and observations throughout the review process.
Module- 3: Shortfall Management (Total Feature - 5)
Feature Description:
1. Application Review
Reviews submitted applications for completeness and compliance.
2. Shortfall Identification
Identifies missing documents, incorrect information, or application deficiencies.
3. Shortfall Notification
Automatically informs applicants about identified shortfalls.
4. Customer Correction
Allows applicants to correct deficiencies and provide additional information.
5. Application Resubmission
Enables applicants to resubmit corrected applications for further review.
Module- 4: Calibration Scheduling (Total Feature - 4)
Feature Description:
1. Calibration Date Scheduling
Schedules calibration appointments based on operational requirements.

                                             249
```

## Page 251

```text
2. Calibration Date Rescheduling
Allows authorized officials to modify calibration schedules when necessary.
3. Multi-Level Calibration Date Approval (AD, DD, Director)
Supports hierarchical approval before confirming calibration dates.
4. Calibration Schedule Notification
Sends automated notifications regarding scheduled calibration dates.
Module- 5: Calibration Management (Total Feature - 3)
Feature Description:
1. Calibration Execution
Enables inspectors to perform calibration activities according to regulatory standards.
2. Calibration Report Preparation
Allows inspectors to prepare detailed digital calibration reports.
3. Calibration Findings Recording
Records calibration measurements, observations, and compliance results.
Module- 6: Calibration Report Verification (Total Feature - 4)
Feature Description:
1. AD Report Verification
Enables the Assistant Director to verify submitted calibration reports.
2. DD Report Verification
Allows the Deputy Director to review and verify calibration reports.
3. Director Final Approval
Supports the Director in providing final approval for calibration results.
4. Approval History
Maintains a complete history of all verification and approval activities.
Module- 7: License Management (Total Feature - 4)
Feature Description:
1. Certificate Fee Based on Product Volume
Calculates license fees based on increases or decreases in product volume.
2. License Issuance
Issues the calibration license after successful approval.
3. License Download
Allows applicants to download the approved license online.
4. License Record Management
Maintains a centralized repository of issued calibration licenses.
Module- 8: Re-inspection / Re-calibration Management (Total Feature
- 4)
Feature Description:

                                              250
```

## Page 252

```text
1. Re-inspection / Re-calibration Request
Initiates repeat calibration when corrective action is required.
2. Re-scheduling
Schedules follow-up calibration appointments.
3. Repeat Calibration Workflow
Manages the complete workflow for repeat calibration activities.
4. Updated Calibration Report
Generates revised calibration reports after re-calibration.
Module- 9: Rejection Management (Total Feature - 3)
Feature Description:
1. Rejection Decision
Records the final decision to reject an application.
2. Rejection Letter Generation
Generates an official rejection letter stating the reasons for rejection.
3. Customer Notification
Notifies applicants regarding the rejection decision.
Module- 10: Notification (Total Feature - 5)
Feature Description:
1. Shortfall Notification
Alerts applicants regarding missing information or required corrections.
2. Calibration Schedule Notification
Sends notifications about scheduled calibration dates.
3. Approval Notification
Notifies applicants after calibration approval decisions.
4. License Issued Notification
Informs applicants when their calibration license has been issued.
5. Rejection Notification
Sends notifications regarding application rejection.
Module- 11: Workflow & Task Management (Total Feature - 5)
Feature Description:
1. Multi-Level Workflow
Supports sequential processing through multiple approval authorities.
2. Role-based Task Assignment
Assigns workflow tasks based on user roles and responsibilities.
3. Application Status Tracking
Tracks application progress throughout the calibration lifecycle.
4. Workflow Remarks
Allows officials to record comments and workflow decisions.

                                              251
```

## Page 253

```text
5. Audit Trail
Maintains a complete history of all workflow activities for transparency and accountability.
Module- 12: Document Management (Total Feature - 4)
Feature Description:
1. Application Document Management
Securely stores and manages all submitted application documents.
2. Calibration Report Management
Maintains digital calibration reports and related records.
3. License Repository
Provides centralized storage for all issued calibration licenses.
4. Rejection Letter Management
Stores rejection letters and related documents for future reference.

                                             252
```

## Page 254

```text
               LPG BOTTLING PLANT / LPG FILLING STATION /
  SERVICE
    27         FUEL FILLING STATION REGISTRATION SERVICE
               Registration • Inspection • Approval • Registration Certificate

Service Profile
Domain                           Service Type                 Primary Users
Fuel    /    LPG   Establishment Registration / Certification Applicants • Director • DD • AD •
Registration                     Service                      Inspectors • System Admin
Core Scope                           Modules                        Features
Registration   &     Certification
Lifecycle
                                     12                             53

Functional Coverage
APPLICATION                     REVIEW                                INSPECTION
• Application Submission        • Application Review                  • Inspection Scheduling
• Document Upload               • Shortfall Management                • Inspection Management
• Registration Fee              • Resubmission                        • Report Verification

RE-INSPECTION                   REGISTRATION                          CONTROL
• Re-inspection Request         • Payment Processing                  • Rejection
• Scheduling                    • Registration Certificate            • Notifications
• Updated Report                • Registration Number                 • Workflow
                                                                      • Documents

Module Catalogue
Sl. Module                                 No. of      Sl.   Module                               No. of
No.                                       Features     No.                                       Features

 01 Application Submission                   4         07    Payment Processing                     4
 02 Application Review & Shortfall           6         08    Registration          Certificate      5
    Management                                               Management
 03 Inspection Scheduling                    4         09    Rejection Management                   3
 04 Inspection Management                    4         10    Notification                           6
 05 Inspection Report Verification &         4         11    Workflow & Task Management             5
    Approval
 06 Re-inspection Management                 4         12    Document Management                    4

                                                 253
```

## Page 255

```text
Service-27: LPG Bottling Plant / LPG Filling Station / Fuel
Filling Station Registration Service
The LPG Bottling Plant, LPG Filling Station, and Fuel Filling Station Registration Service
is a complete digital solution that automates the registration, inspection, approval, and
certification process for fuel-related establishments. The system enables applicants to
submit registration applications online, upload required documents, make registration fee
payments, and track application status throughout the process. Applications are reviewed by
designated officers through a role-based workflow where deficiencies can be identified,
communicated to applicants, and corrected through resubmission.
The solution supports comprehensive inspection management, including inspection
scheduling, rescheduling, inspector assignment, field inspection, report preparation, and
multi-level approval of inspection reports. Where corrective actions are required, the system
facilitates re-inspection requests, scheduling, and updated inspection reporting. Category-
wise registration fees are processed through an integrated payment management system
with payment verification and confirmation. After successful approval, the system
automatically generates registration numbers and registration certificates, allowing
applicants to download their approved registration papers online. Applications that fail to
meet regulatory requirements are processed through a structured rejection workflow with
documented reasons and automated notifications. The solution also provides document
management, workflow monitoring, audit trails, role-based task assignment, and automated
notifications to ensure transparency, efficiency, accountability, and compliance with
regulatory standards.

                                            254
```

## Page 256

```text
Figure Name: LPG Bottling Plant, LPG Filling Station, and Fuel Filling Station Registration Service Workflow

                                                    255
```

## Page 257

```text
Module- 1: Application Submission (Total Feature - 4)
Feature Description:
1. Online Application Submission
Enables applicants to submit registration applications electronically through the online
portal.
2. Required Document Upload
Allows applicants to upload all mandatory documents required for registration verification.
3. Application Fee Payment
Facilitates payment of the prescribed registration fee through integrated payment methods.
4. Application Tracking
Allows applicants to monitor the progress and current status of their submitted applications.
Module- 2: Application Review & Shortfall Management (Total
Feature - 6)
Feature Description:
1. Director Application Review
Allows the Director to perform an initial review of submitted applications.
2. Application Assignment (DD/AD/Inspector)
Assigns applications to the appropriate officers for detailed evaluation.
3. Inspector Application Review
Enables inspectors to review applications before conducting inspections.
4. Shortfall Identification
Records incomplete information, missing documents, or compliance deficiencies.
5. Shortfall Notification
Automatically notifies applicants regarding identified shortfalls.
6. Customer Resubmission
Allows applicants to submit corrected information and required documents for further
review.
Module- 3: Inspection Scheduling (Total Feature - 4)
Feature Description:
1. Inspection Date Scheduling
Schedules inspection dates based on application readiness and inspector availability.
2. Inspection Date Rescheduling
Allows authorized officials to modify inspection schedules when necessary.
3. Multi-Level Inspection Date Approval (AD, DD, Director)
Supports hierarchical approval before confirming inspection dates.
4. Inspection Schedule Notification
Automatically notifies applicants and inspectors of scheduled inspection dates.

                                             256
```

## Page 258

```text
Module- 4: Inspection Management (Total Feature - 4)
Feature Description:
1. Inspector Assignment
Assigns qualified inspectors to conduct field inspections.
2. Inspection Execution
Enables inspectors to perform inspections according to regulatory requirements.
3. Inspection Report Preparation
Allows inspectors to prepare digital inspection reports after field inspections.
4. Inspection Findings Recording
Records inspection observations, compliance status, and identified issues.
Module- 5: Inspection Report Verification & Approval (Total Feature -
4)
Feature Description:
1. AD Report Verification
Enables the Assistant Director to verify submitted inspection reports.
2. DD Report Approval
Allows the Deputy Director to review and approve verified reports.
3. Director Final Decision
Supports the Director in providing the final approval or rejection decision.
4. Approval Workflow Tracking
Tracks the progress of inspection reports throughout the approval workflow.
Module- 6: Re-inspection Management (Total Feature - 4)
Feature Description:
1. Re-inspection Request
Initiates re-inspection after corrective actions are requested.
2. Re-inspection Scheduling
Schedules follow-up inspections for previously identified deficiencies.
3. Re-inspection Workflow
Manages the approval and execution process of re-inspections.
4. Updated Inspection Report
Generates revised inspection reports after the re-inspection is completed.
Module- 7: Payment Processing (Total Feature - 4)
Feature Description:
1. LPG/Fuel Category-wise Registration Fee Request
Calculates and requests registration fees according to the facility category.
2. Payment Collection
Receives registration payments through approved payment channels.

                                              257
```

## Page 259

```text
3. Payment Verification
Verifies successful payment before continuing the registration process.
4. Payment Confirmation
Confirms payment completion and updates the application status.
Module- 8: Registration Certificate Management (Total Feature - 5)
Feature Description:
1. Registration Paper Generation
Automatically generates the official registration certificate.
2. Registration Number Generation
Creates a unique registration number for each approved registration.
3. Registration Paper Issuance
Issues the approved registration certificate to the applicant.
4. Registration Paper Download
Allows applicants to download the registration certificate online.
5. Registration Record Management
Maintains a centralized repository of all registration records.
Module- 9: Rejection Management (Total Feature - 3)
Feature Description:
1. Rejection Decision
Records the final decision to reject an application.
2. Rejection Note Generation
Generates documented reasons supporting the rejection decision.
3. Customer Notification
Notifies applicants regarding the rejection and its reasons.
Module- 10: Notification (Total Feature - 6)
Feature Description:
1. Shortfall Notification
Sends notifications when application deficiencies are identified.
2. Inspection Schedule Notification
Notifies applicants and inspectors about inspection schedules.
3. Inspection Approval Notification
Sends updates after inspection approval decisions are made.
4. Payment Request Notification
Informs applicants when registration fee payment is required.
5. Registration Paper Issued Notification
Notifies applicants after successful certificate issuance.
6. Rejection Notification
Sends rejection notifications along with the decision status.

                                              258
```

## Page 260

```text
Module- 11: Workflow & Task Management (Total Feature - 5)
Feature Description:
1. Role-based Task Assignment
Assigns workflow tasks according to user roles and responsibilities.
2. Multi-Level Workflow
Supports sequential processing through multiple approval authorities.
3. Application Status Tracking
Tracks application progress throughout the registration lifecycle.
4. Workflow Remarks
Allows officials to record comments and review observations during processing.
5. Audit Trail
Maintains a complete history of workflow activities for transparency and accountability.
Module- 12: Document Management (Total Feature - 4)
Feature Description:
1. Application Document Management
Securely stores and manages all submitted application documents.
2. Inspection Report Management
Maintains digital inspection reports and related inspection records.
3. Registration Paper Repository
Provides centralized storage for issued registration certificates.
4. Rejection Note Management
Preserves rejection notes and decision documents for future reference.

                                              259
```

## Page 261

```text
               LPG BOTTLING PLANT / LPG FILLING STATION /
  SERVICE
    28         FUEL FILLING STATION RENEWAL
               Registration • Inspection • Approval • Registration Certificate

Service Profile
Domain                           Service Type                 Primary Users
Fuel    /    LPG   Establishment Registration / Certification Applicants • Director • DD • AD •
Registration                     Service                      Inspectors • System Admin
Core Scope                           Modules                        Features
Registration   &     Certification
Lifecycle
                                     12                             53

Functional Coverage
APPLICATION                     REVIEW                                INSPECTION
• Application Submission        • Application Review                  • Inspection Scheduling
• Document Upload               • Shortfall Management                • Inspection Management
• Registration Fee              • Resubmission                        • Report Verification

RE-INSPECTION                   REGISTRATION                          CONTROL
• Re-inspection Request         • Payment Processing                  • Rejection
• Scheduling                    • Registration Certificate            • Notifications
• Updated Report                • Registration Number                 • Workflow
                                                                      • Documents

Module Catalogue
Sl. Module                                 No. of      Sl.   Module                               No. of
No.                                       Features     No.                                       Features

 01 Application Submission                   4         07    Payment Processing                     4
 02 Application Review & Shortfall           6         08    Registration          Certificate      5
    Management                                               Management
 03 Inspection Scheduling                    4         09    Rejection Management                   3
 04 Inspection Management                    4         10    Notification                           6
 05 Inspection Report Verification &         4         11    Workflow & Task Management             5
    Approval
 06 Re-inspection Management                 4         12    Document Management                    4

                                                 260
```

## Page 262

```text
Service-28: LPG Bottling Plant / LPG Filling Station / Fuel
Filling Station Renewal
The LPG Bottling Plant, LPG Filling Station, and Fuel Filling Station Renewal
Service is a complete digital solution that automates the renewal Process, inspection,
approval, and certification process for fuel-related establishments. The system
enables applicants to submit registration applications online, upload required
documents, make registration fee payments, and track application status throughout
the process. Applications are reviewed by designated officers through a role-based
workflow where deficiencies can be identified, communicated to applicants, and
corrected through resubmission.
The solution supports comprehensive inspection management, including inspection
scheduling, rescheduling, inspector assignment, field inspection, report preparation,
and multi-level approval of inspection reports. Where corrective actions are required,
the system facilitates re-inspection requests, scheduling, and updated inspection
reporting. Category-wise registration fees are processed through an integrated
payment management system with payment verification and confirmation. After
successful approval, the system automatically generates registration numbers and
registration certificates, allowing applicants to download their approved registration
papers online. Applications that fail to meet regulatory requirements are processed
through a structured rejection workflow with documented reasons and automated
notifications. The solution also provides document management, workflow
monitoring, audit trails, role-based task assignment, and automated notifications to
ensure transparency, efficiency, accountability, and compliance with regulatory
standards.

                                         261
```

## Page 263

```text
Figure name: Workflow of LPG Bottling Plant, LPG Filling Station, and Fuel Filling Station Renewal Service

                                                   262
```

## Page 264

```text
Module- 1: Application Submission (Total Feature - 4)
Feature Description:
1. Online Application Submission
Enables applicants to submit registration applications electronically through the online
portal.
2. Required Document Upload
Allows applicants to upload all mandatory documents required for registration verification.
3. Application Fee Payment
Facilitates payment of the prescribed registration fee through integrated payment methods.
4. Application Tracking
Allows applicants to monitor the progress and current status of their submitted applications.
Module- 2: Application Review & Shortfall Management (Total
Feature - 6)
Feature Description:
1. Director Application Review
Allows the Director to perform an initial review of submitted applications.
2. Application Assignment (DD/AD/Inspector)
Assigns applications to the appropriate officers for detailed evaluation.
3. Inspector Application Review
Enables inspectors to review applications before conducting inspections.
4. Shortfall Identification
Records incomplete information, missing documents, or compliance deficiencies.
5. Shortfall Notification
Automatically notifies applicants regarding identified shortfalls.
6. Customer Resubmission
Allows applicants to submit corrected information and required documents for further
review.
Module- 3: Inspection Scheduling (Total Feature - 4)
Feature Description:
1. Inspection Date Scheduling
Schedules inspection dates based on application readiness and inspector availability.
2. Inspection Date Rescheduling
Allows authorized officials to modify inspection schedules when necessary.
3. Multi-Level Inspection Date Approval (AD, DD, Director)
Supports hierarchical approval before confirming inspection dates.
4. Inspection Schedule Notification
Automatically notifies applicants and inspectors of scheduled inspection dates.

                                             263
```

## Page 265

```text
Module- 4: Inspection Management (Total Feature - 4)
Feature Description:
1. Inspector Assignment
Assigns qualified inspectors to conduct field inspections.
2. Inspection Execution
Enables inspectors to perform inspections according to regulatory requirements.
3. Inspection Report Preparation
Allows inspectors to prepare digital inspection reports after field inspections.
4. Inspection Findings Recording
Records inspection observations, compliance status, and identified issues.
Module- 5: Inspection Report Verification & Approval (Total Feature -
4)
Feature Description:
1. AD Report Verification
Enables the Assistant Director to verify submitted inspection reports.
2. DD Report Approval
Allows the Deputy Director to review and approve verified reports.
3. Director Final Decision
Supports the Director in providing the final approval or rejection decision.
4. Approval Workflow Tracking
Tracks the progress of inspection reports throughout the approval workflow.
Module- 6: Re-inspection Management (Total Feature - 4)
Feature Description:
1. Re-inspection Request
Initiates re-inspection after corrective actions are requested.
2. Re-inspection Scheduling
Schedules follow-up inspections for previously identified deficiencies.
3. Re-inspection Workflow
Manages the approval and execution process of re-inspections.
4. Updated Inspection Report
Generates revised inspection reports after the re-inspection is completed.
Module- 7: Payment Processing (Total Feature - 4)
Feature Description:
1. LPG/Fuel Category-wise Registration Fee Request
Calculates and requests registration fees according to the facility category.
2. Payment Collection
Receives registration payments through approved payment channels.

                                              264
```

## Page 266

```text
3. Payment Verification
Verifies successful payment before continuing the registration process.
4. Payment Confirmation
Confirms payment completion and updates the application status.
Module- 8: Registration Certificate Management (Total Feature - 5)
Feature Description:
1. Registration Paper Generation
Automatically generates the official registration certificate.
2. Registration Number Generation
Creates a unique registration number for each approved registration.
3. Registration Paper Issuance
Issues the approved registration certificate to the applicant.
4. Registration Paper Download
Allows applicants to download the registration certificate online.
5. Registration Record Management
Maintains a centralized repository of all registration records.
Module- 9: Rejection Management (Total Feature - 3)
Feature Description:
1. Rejection Decision
Records the final decision to reject an application.
2. Rejection Note Generation
Generates documented reasons supporting the rejection decision.
3. Customer Notification
Notifies applicants regarding the rejection and its reasons.
Module- 10: Notification (Total Feature - 6)
Feature Description:
1. Shortfall Notification
Sends notifications when application deficiencies are identified.
2. Inspection Schedule Notification
Notifies applicants and inspectors about inspection schedules.
3. Inspection Approval Notification
Sends updates after inspection approval decisions are made.
4. Payment Request Notification
Informs applicants when registration fee payment is required.
5. Registration Paper Issued Notification
Notifies applicants after successful certificate issuance.
6. Rejection Notification
Sends rejection notifications along with the decision status.

                                              265
```

## Page 267

```text
Module- 11: Workflow & Task Management (Total Feature - 5)
Feature Description:
1. Role-based Task Assignment
Assigns workflow tasks according to user roles and responsibilities.
2. Multi-Level Workflow
Supports sequential processing through multiple approval authorities.
3. Application Status Tracking
Tracks application progress throughout the registration lifecycle.
4. Workflow Remarks
Allows officials to record comments and review observations during processing.
5. Audit Trail
Maintains a complete history of workflow activities for transparency and accountability.
Module- 12: Document Management (Total Feature - 4)
Feature Description:
1. Application Document Management
Securely stores and manages all submitted application documents.
2. Inspection Report Management
Maintains digital inspection reports and related inspection records.
3. Registration Paper Repository
Provides centralized storage for issued registration certificates.
4. Rejection Note Management
Preserves rejection notes and decision documents for future reference.

                                              266
```

## Page 268

```text
  SERVICE       BUILDING  (FLAT)                            /        ESTABLISHMENT
    29
                MEASUREMENT
                Building Measurement • Inspection • Verification • Measurement Certificate

Service Profile
Domain                            Service Type                   Primary Users
Measurement & Certification       Measurement Service            Applicants • Director • DD • AD •
                                                                 Inspectors • System Admin
Core Scope                      Modules                          Features
Building   /      Establishment
Measurement Lifecycle
                                12                               53

Functional Coverage
APPLICATION                     REVIEW                             MEASUREMENT
• Application Submission        • Application Review               • Inspection Scheduling
• Document Upload               • Shortfall Management             • On-site Measurement
• Measurement Fee               • Resubmission                     • Inspection Report

VERIFICATION                    CERTIFICATE                        CONTROL
• AD Verification               • Payment Processing               • Notifications
• DD Approval                   • Registration Number              • Workflow
• Director Decision             • Registration Paper               • Document Management
• Re-inspection                                                    • Rejection

Module Catalogue
Sl. Module                              No. of      Sl.   Module                              No. of
No.                                    Features     No.                                      Features

 01 Application Submission                4         07    Payment Processing                    4
 02 Application Review & Shortfall        6         08    Certificate Management                5
    Management
 03 Inspection Scheduling                 4         09    Rejection Management                  3
 04 Inspection Management                 4         10    Notification                          6
 05 Inspection Report Verification &      4         11    Workflow & Task Management            5
    Approval
 06 Re-inspection Management              4         12    Document Management                   4

                                              267
```

## Page 269

```text
Service-29: Building (Flat) / Establishment Measurement
The Building (Flat) / Establishment Measurement Service is a digital solution
designed to streamline the complete measurement application and certification
process for buildings, flats, and commercial establishments. The system enables
applicants to submit applications online, upload required documents, pay
measurement fees based on building square footage, and track application progress
in real time. Applications are reviewed through a role-based workflow where
designated officials verify submitted information, identify deficiencies, and request
corrections when necessary. The platform supports inspection scheduling, inspector
assignment, on-site measurement, inspection report preparation, and multi-level
verification and approval of inspection findings. If discrepancies are identified, the
system facilitates re-inspection requests and updated inspection reports. Following
successful approval and payment verification, the system automatically generates
measurement certificates and registration numbers while maintaining secure digital
records. Automated notifications, workflow tracking, document management, audit
trails, and role-based task assignment ensure transparency, operational efficiency,
regulatory compliance, and accurate measurement certification.

                                         268
```

## Page 270

```text
Figure name: Workflow of Building (Flat) / Establishment Measurement Service

                                    269
```

## Page 271

```text
Module- 1: Application Submission (Total Feature - 4)
Feature Description:
1. Online Application Submission
Enables applicants to submit building or establishment measurement applications through
the online portal.
2. Required Document Upload
Allows applicants to upload all required supporting documents for verification.
3. Application Fee Payment
Facilitates online payment of the prescribed measurement fee.
4. Application Tracking
Enables applicants to monitor the progress and current status of their applications.
Module- 2: Application Review & Shortfall Management (Total
Feature - 6)
Feature Description:
1. Director Application Review
Allows the Director to conduct an initial review of submitted applications.
2. Application Assignment (DD/AD/Inspector)
Assigns applications to the appropriate officers for detailed processing.
3. Inspector Application Review
Enables inspectors to review application details before conducting measurements.
4. Shortfall Identification
Identifies missing information, incomplete documents, or application deficiencies.
5. Shortfall Notification
Automatically informs applicants about identified shortfalls.
6. Customer Resubmission
Allows applicants to submit corrected information and additional documents.
Module- 3: Inspection Scheduling (Total Feature - 4)
Feature Description:
1. Inspection Date Scheduling
Schedules measurement inspections based on application readiness.
2. Inspection Date Rescheduling
Allows authorized officials to modify inspection dates when necessary.
3. Multi-Level Inspection Date Approval (AD, DD, Director)
Supports approval of inspection schedules through multiple authority levels.
4. Inspection Schedule Notification
Sends inspection schedule notifications to applicants and inspectors.

                                             270
```

## Page 272

```text
Module- 4: Inspection Management (Total Feature - 4)
Feature Description:
1. Inspector Assignment
Assigns inspectors to perform on-site building or establishment measurements.
2. Inspection Execution
Enables inspectors to conduct field measurements according to regulatory standards.
3. Inspection Report Preparation
Allows inspectors to prepare digital measurement reports.
4. Inspection Findings Recording
Records measurement results, observations, and compliance findings.
Module- 5: Inspection Report Verification & Approval (Total Feature -
4)
Feature Description:
1. AD Report Verification
Enables the Assistant Director to verify inspection reports.
2. DD Report Approval
Allows the Deputy Director to review and approve verified reports.
3. Director Final Decision
Supports the Director in making the final approval or rejection decision.
4. Approval Workflow Tracking
Tracks inspection reports throughout the approval process.
Module- 6: Re-inspection Management (Total Feature - 4)
Feature Description:
1. Re-inspection Request
Initiates a follow-up measurement inspection when corrective actions are required.
2. Re-inspection Scheduling
Schedules re-inspections after necessary corrections are completed.
3. Re-inspection Workflow
Manages the complete approval and execution process for re-inspections.
4. Updated Inspection Report
Generates revised inspection reports based on re-inspection findings.
Module- 7: Payment Processing (Total Feature - 4)
Feature Description:
1. Building Square Feet-wise Testing Fee Request
Calculates and requests measurement fees based on the building's total square footage.
2. Payment Collection
Collects payments through approved payment channels.

                                             271
```

## Page 273

```text
3. Payment Verification
Verifies successful payment before certificate issuance.
4. Payment Confirmation
Confirms payment completion and updates the application status.
Module- 8: Certificate Management (Total Feature - 5)
Feature Description:
1. Registration Paper Generation
Automatically generates the official measurement certificate.
2. Registration Number Generation
Creates a unique registration number for each approved application.
3. Registration Paper Issuance
Issues the approved measurement certificate to the applicant.
4. Registration Paper Download
Allows applicants to download the certificate online.
5. Registration Record Management
Maintains a centralized repository of issued measurement certificates.
Module- 9: Rejection Management (Total Feature - 3)
Feature Description:
1. Rejection Decision
Records the final rejection decision for unsuccessful applications.
2. Rejection Note Generation
Generates documented reasons for application rejection.
3. Customer Notification
Notifies applicants regarding the rejection decision and supporting reasons.
Module- 10: Notification (Total Feature - 6)
Feature Description:
1. Shortfall Notification
Alerts applicants about missing documents or required corrections.
2. Inspection Schedule Notification
Sends notifications regarding scheduled inspection dates.
3. Inspection Approval Notification
Notifies applicants after inspection approval decisions.
4. Payment Request Notification
Informs applicants when measurement fee payment is required.
5. Registration Paper Issued Notification
Notifies applicants after certificate issuance.
6. Rejection Notification
Sends notifications regarding application rejection.

                                              272
```

## Page 274

```text
Module- 11: Workflow & Task Management (Total Feature - 5)
Feature Description:
1. Role-based Task Assignment
Assigns responsibilities based on user roles and organizational hierarchy.
2. Multi-Level Workflow
Supports sequential application processing through multiple approval levels.
3. Application Status Tracking
Tracks application progress throughout the entire measurement process.
4. Workflow Remarks
Allows officials to record comments and review observations.
5. Audit Trail
Maintains a complete history of all workflow activities for accountability and transparency.
Module- 12: Document Management (Total Feature - 4)
Feature Description:
1. Application Document Management
Securely stores and manages all application documents.
2. Inspection Report Management
Maintains digital inspection and measurement reports.
3. Registration Paper Repository
Provides centralized storage for issued measurement certificates.
4. Rejection Note Management
Stores rejection notes and related decision documents for future reference.

                                            273
```

## Page 275

```text
  SERVICE
                STORAGE TANK CALIBRATION SERVICE
    30
                Tank Calibration • Additional Fee • Calibration Certificate • Re-calibration

Service Profile
Domain                                Service Type                   Primary Users
Metrology Calibration                 Calibration Service            Applicants • Director • DD • AD •
                                                                     Inspectors • System Admin
Core Scope                         Modules                           Features
Storage Tank Calibration Lifecycle
                                      13                             58

Functional Coverage
APPLICATION                      REVIEW & SCHEDULING                   CALIBRATION
• Category-wise Application      • Application Review                  • Inspector Assignment
• Document Upload                • Shortfall Management                • Calibration Execution
• Application Fee                • Calibration Scheduling              • Findings
• Tracking

VERIFICATION & FEE               CERTIFICATION                         CONTROL
• Report Verification            • Calibration Certificate             • Notifications
• Additional Fee Assessment      • Re-calibration                      •     Workflow   &    Task
• Payment Processing             • Rejection                           Management
                                                                       • Document Management

Module Catalogue
Sl. Module                                  No. of      Sl.   Module                              No. of
No.                                        Features     No.                                      Features

 01 Application Submission                    5         07    Payment Processing                    6
 02 Application Review & Shortfall            6         08    Calibration Certificate               4
    Management
 03 Calibration Scheduling                    4         09    Re-calibration Management             4
 04 Calibration Management                    4         10    Rejection Management                  3
 05 Calibration Report Verification           4         11    Notification Management               5
 06 Additional Fee Management                 4         12    Workflow & Task Management            5

                                                  274
```

## Page 276

```text
Service-30: Storage Tank Calibration Service
The Storage Tank Calibration Service is a comprehensive digital solution designed
to automate the entire storage tank calibration process, from application submission
to calibration certificate issuance. The system enables applicants to submit category-
wise calibration applications online, upload required documents, pay application fees,
generate calibration charts at the client end, and monitor application status
throughout the process. Applications are reviewed through a role-based workflow
where authorized officials verify submissions, identify deficiencies, and request
corrections when necessary. The platform supports calibration scheduling,
rescheduling, inspector assignment, field calibration, report preparation, and multi-
level verification and approval of calibration reports. During report verification,
additional calibration fees can be assessed based on inspection findings and
applicable government gazette rates. The system manages additional fee approval,
payment collection, and payment verification before certificate issuance. If calibration
results do not meet regulatory standards, re-calibration requests, scheduling, and
updated calibration reports are managed through a structured workflow. Upon
successful completion, the system generates and issues calibration licenses while
maintaining centralized digital records. Automated notifications, workflow tracking,
audit trails, and secure document management ensure transparency, operational
efficiency, regulatory compliance, traceability, and accurate calibration record
management.

                                          275
```

## Page 277

```text
Figure Name: Storage Tank Calibration Service

                    276
```

## Page 278

```text
Module- 1. Application Submission (Total Feature - 5)
Feature Description:
1. Online Category-wise Application Submission
Enables applicants to submit storage tank calibration applications based on the appropriate
tank category through the online portal.
2. Required Document Upload
Allows applicants to upload all mandatory documents required for calibration.
3. Application Fee Payment
Facilitates online payment of the prescribed application fee.
4. Application Tracking
Enables applicants to monitor the progress and current status of their submitted applications.
5. Chart Generate on Client End
Allows applicants to generate and submit calibration charts from the client side where
applicable.
Module- 2: Application Review & Shortfall Management (Total
Feature - 6)
Feature Description:
1. Director Application Review
Allows the Director to perform the initial review of submitted applications.
2. Application Forwarding (DD/AD/Inspector)
Assigns applications to the appropriate officials for detailed evaluation.
3. Inspector Application Review
Enables inspectors to review applications before calibration.
4. Shortfall Identification
Identifies missing documents, incorrect information, or compliance deficiencies.
5. Shortfall Notification
Automatically notifies applicants regarding identified shortfalls.
6. Customer Resubmission
Allows applicants to submit corrected information and supporting documents.
Module- 3: Calibration Scheduling (Total Feature - 4)
Feature Description:
1. Calibration Date Scheduling
Schedules calibration appointments based on operational requirements.
2. Calibration Date Rescheduling
Allows authorized officials to modify calibration schedules when necessary.
3. Multi-Level Calibration Date Approval (AD, DD, Director)
Supports hierarchical approval before confirming calibration schedules.

                                             277
```

## Page 279

```text
4. Calibration Schedule Notification
Sends calibration schedule notifications to applicants and inspectors.
Module- 4: Calibration Management (Total Feature - 4)
Feature Description:
1. Inspector Assignment
Assigns qualified inspectors to perform storage tank calibration.
2. Calibration / Inspection Execution
Enables inspectors to conduct calibration and inspection activities according to regulatory
standards.
3. Calibration Report Preparation
Allows inspectors to prepare structured digital calibration reports.
4. Calibration Findings Recording
Records calibration measurements, observations, and compliance findings.
Module- 5: Calibration Report Verification (Total Feature - 4)
Feature Description:
1. AD Report Verification
Enables the Assistant Director to verify calibration reports.
2. DD Report Verification
Allows the Deputy Director to review verified reports.
3. Additional Fee Assessment
Assesses additional calibration fees based on inspection findings or calibration outcomes.
4. Director Final Approval
Supports the Director in providing the final approval of calibration reports.
Module- 6: Additional Fee Management (Total Feature - 4)
Feature Description:
1. Additional Fee Calculation
Calculates additional fees according to applicable government regulations.
2. Additional Fee Approval
Enables authorized officials to approve additional fee assessments.
3. Additional Fee Request
Generates payment requests for additional fees.
4. Additional Fee Notification
Automatically notifies applicants regarding additional fee requirements.
Module- 7: Payment Processing (Total Feature - 6)
Feature Description:
1. Additional Fee Collection
Collects approved additional calibration fees.

                                             278
```

## Page 280

```text
2. Calibration Fee Based on Government Gazette
Calculates calibration fees according to the applicable government gazette.
3. Testing Fee Collection
Collects testing fees where applicable.
4. Payment Verification
Verifies successful payment before certificate issuance.
5. Payment Confirmation
Confirms payment completion and updates application status.
6. Payment Receipt
Generates digital payment receipts for applicants.
Module- 8: Calibration Certificate (Total Feature - 4)
Feature Description:
1. License Generation
Automatically generates the calibration certificate/license after successful approval.
2. License Issuance
Issues the approved calibration certificate to the applicant.
3. License Download
Allows applicants to download the calibration certificate online.
4. License Record Management
Maintains a centralized repository of issued calibration certificates.
Module- 9: Re-calibration Management (Total Feature - 4)
Feature Description:
1. Re-calibration Request
Initiates repeat calibration when corrective action is required.
2. Re-calibration Scheduling
Schedules follow-up calibration activities.
3. Repeat Calibration Workflow
Manages the complete workflow for repeat calibration.
4. Updated Calibration Report
Generates revised calibration reports after re-calibration.
Module-10: Rejection Management (Total Feature - 3)
Feature Description:
1. Rejection Decision
Records the final rejection decision.
2. Rejection Note Generation
Generates documented reasons supporting the rejection.
3. Customer Notification
Notifies applicants regarding the rejection decision.

                                              279
```

## Page 281

```text
Module- 11: Notification Management (Total Feature - 5)
Feature Description:
1. Shortfall Notification:
Alerts applicants regarding missing information or required corrections.
2. Calibration Schedule Notification:
Sends notifications regarding scheduled calibration dates.
3. Additional Fee Notification:
Informs applicants about approved additional fee requirements.
4. License Issued Notification:
Notifies applicants after calibration certificate issuance.
5, Rejection Notification:
Sends notifications regarding application rejection.
Module-12. Workflow & Task Management (Total Feature - 5)
Feature Description:
1. Multi-Level Workflow:
Supports sequential processing through multiple approval authorities.
2. Role-based Task Assignment:
Assigns workflow activities according to user roles and responsibilities.
3. Application Status Tracking:
Tracks application progress throughout the calibration lifecycle.
4. Workflow Remarks:
Allows officials to record comments and observations during processing.
5. Audit Trail:
Maintains a complete history of workflow activities for transparency and accountability.
Module 13: Document Management (Total Feature - 4)
Feature Description:
1 Application Document Management:
Securely stores and manages submitted application documents.
2. Calibration Report Management:
Maintains digital calibration reports and related records.
3. License Repository:
Provides centralized storage for issued calibration certificates.
4. Rejection Note Management:
Stores rejection notes and supporting documents for future reference.

                                               280
```

## Page 282

```text
  SERVICE        INDUSTRIAL AND                          SCIENTIFIC             METROLOGY
    31
                 CALIBRATION
                 Instrument Calibration • Onsite / Offsite • Certificate & Sticker Release

Service Profile
Domain                                Service Type                   Primary Users
Industrial & Scientific Metrology     Calibration Service            Applicants • OSS • Director • DD
                                                                     • AD • Inspectors / Examiners
Core Scope                      Modules                              Features
Complete Instrument Calibration
Lifecycle
                                14                                   59

Functional Coverage
APPLICATION                         REVIEW & PAYMENT                   CALIBRATION MODE
• Online Application                • Application Review               • Onsite Calibration
• Initial Questionnaire             • Shortfall                        • Offsite Instrument Submission
• Document Upload                   • Payment Processing               • Instrument Receiving
• Tracking

CALIBRATION                    & CERTIFICATE & RELEASE                 CONTROL
VERIFICATION                     • Certificate & Sticker               • Rejection
• Scheduling                     • Instrument Release                  • Notifications
• Calibration & Inspection       • Re-calibration                      • Workflow
• Report Verification                                                  • Documents

Module Catalogue
Sl. Module                                 No. of       Sl.   Module                             No. of
No.                                       Features      No.                                     Features

 01 Application Submission                    4         07    Calibration & Inspection             4
 02 Application Review & Shortfall            6         08    Report Verification & Approval       3
    Management
 03 Payment Processing                        4         09    Re-calibration / Re-inspection       4
 04 Calibration Type Selection                3         10    Calibration Certificate Release      4
 05 Instrument Receiving (OSS)                4         11    Rejection Management                 3
 06 Calibration Scheduling                    4         12    Notification Module                  6

                                                  281
```

## Page 283

```text
Service-31: Industrial and Scientific Metrology Calibration
The Industrial and Scientific Metrology Calibration Service is a comprehensive digital
platform designed to manage the complete calibration lifecycle for industrial and scientific
measuring instruments. The system enables applicants to submit calibration requests online,
complete an initial questionnaire, upload required documents, and track application progress.
Applications are reviewed through a role-based workflow where authorized officials assess
submissions, identify deficiencies, and request corrections when necessary. Applicants can
choose between onsite calibration or offsite calibration by submitting instruments through
the One Stop Service (OSS) center. The platform manages instrument receiving,
acknowledgement, scheduling, calibration execution, inspection report preparation, and
multi-level verification and approval of calibration results. Where instruments fail to meet
required standards, the system supports re-calibration and re-inspection workflows with
updated reports. Following successful approval, the system generates calibration certificates
and calibration stickers, allowing applicants to download certificates and collect released
instruments. The solution also includes payment processing, workflow management,
automated notifications, document management, audit trails, and centralized record keeping
to ensure transparency, operational efficiency, traceability, and compliance with national
metrology standards.

                                            282
```

## Page 284

```text
Figure Name: Industrial and Scientific Metrology Calibration

                            283
```

## Page 285

```text
Module- 1: Application Submission (Total Feature - 4)
Feature Description:
1. Online Application Submission
Enables applicants to submit calibration applications electronically through the online portal.
2. Initial Questionnaire
Collects preliminary information about the instrument, calibration requirements, and
applicant details.
3. Required Document Upload
Allows applicants to upload all mandatory supporting documents for verification.
4. Application Tracking
Enables applicants to monitor the current status and progress of their submitted applications.

Module- 2: Application Review & Shortfall Management (Total
Feature - 6)
Feature Description:
1. Director Application Review
Allows the Director to perform the initial review of submitted applications.
2. Application Forwarding (DD/AD/Inspector/Examiner)
Forwards applications to the appropriate officials for detailed evaluation.
3. AD Application Review
Enables the Assistant Director to verify application completeness and compliance.
4. Shortfall Identification
Identifies missing documents, incomplete information, or compliance deficiencies.
5. Shortfall Notification
Automatically notifies applicants regarding identified shortfalls.
6. Customer Resubmission
Allows applicants to submit corrected information and supporting documents.
Module- 3: Payment Processing (Total Feature - 4)
Feature Description:
1. Calibration Fee Request
Generates calibration fee requests based on the selected service.
2. Payment Collection
Collects calibration fees through approved payment channels.
3. Payment Verification
Verifies successful payment before calibration processing.
4. Payment Confirmation
Confirms payment completion and updates the application status.

                                             284
```

## Page 286

```text
Module- 4: Calibration Type Selection (Total Feature - 3)
Feature Description:
1. Onsite Calibration Selection
Allows applicants to request calibration at their own premises.
2. Offsite (Instrument Submission) Selection
Allows applicants to choose laboratory calibration by submitting instruments.
3. Calibration Mode Management
Manages and records the selected calibration method throughout the workflow.
Module- 5: Instrument Receiving (OSS) (Total Feature - 4)
Feature Description:
1. Instrument Submission
Records the submission of instruments for laboratory calibration.
2. OSS Instrument Receiving
Enables OSS personnel to receive and register submitted instruments.
3. Instrument Acknowledgement
Generates acknowledgement receipts confirming instrument submission.
4. Instrument Tracking
Tracks instrument movement throughout the calibration process.
Module- 6: Calibration Scheduling (Total Feature - 4)
Feature Description:
1. Onsite Calibration Date Scheduling
Schedules onsite calibration based on availability and operational requirements.
2. Date Rescheduling
Allows authorized officials to revise scheduled calibration dates when necessary.
3. DD Approval of Calibration Date
Enables the Deputy Director to approve proposed calibration schedules.
4. Customer Notification
Sends calibration schedule notifications to applicants.
Module- 7: Calibration & Inspection (Total Feature - 4)
Feature Description:
1. Inspector Assignment
Assigns qualified inspectors or calibration engineers to calibration tasks.
2. Calibration/Inspection Execution
Enables execution of calibration and inspection activities according to standards.
3. Inspection/Calibration Report Preparation
Allows preparation of structured digital calibration reports.

                                             285
```

## Page 287

```text
4. Findings Recording
Records calibration measurements, observations, and compliance findings.
Module- 8: Report Verification & Approval (Total Feature - 3)
Feature Description:
1. DD Report Verification
Enables the Deputy Director to verify submitted calibration reports.
2. Director Final Approval
Supports final approval of calibration results by the Director.
3. Approval History
Maintains a complete history of report verification and approval activities.
Module- 9: Re-calibration / Re-inspection (Total Feature - 4)
Feature Description:
1. Re-calibration Request
Initiates repeat calibration when corrective actions are required.
2. Re-inspection Workflow
Manages the approval and execution process for repeat inspections.
3. Re-scheduling
Schedules follow-up calibration activities after corrections are completed.
4. Updated Report Generation
Produces revised calibration reports after re-calibration or re-inspection.
Module- 10: Calibration Certificate Release (Total Feature - 4)
Feature Description:
1. Calibration Certificate and Sticker Generation
Automatically generates calibration certificates and instrument calibration stickers.
2. Calibration Certificate and Sticker Download
Allows applicants to download approved certificates and stickers.
3. Instrument Release
Records the release of calibrated instruments to applicants.
4. Calibration Certificate Record Management
Maintains a centralized repository of issued calibration certificates.
Module- 11: Rejection Management (Total Feature - 3)
Feature Description:
1. Rejection Decision
Records the final rejection decision for unsuccessful applications.
2. Rejection Note Generation
Generates official rejection notes with documented reasons.

                                              286
```

## Page 288

```text
3. Customer Notification
Notifies applicants regarding rejection decisions and supporting reasons.
Module- 12: Notification Module (Total Feature - 6)
Feature Description:
1. Shortfall Notification
Alerts applicants regarding missing information or documentation.
2. Payment Request Notification
Notifies applicants when calibration fee payment is required.
3. Calibration Schedule Notification
Sends scheduled calibration date notifications.
4. Instrument Submission Notification
Confirms successful instrument submission and receipt.
5. License Issued Notification
Notifies applicants when calibration certificates have been issued.
6. Rejection Notification
Send rejection notifications with decision details.
Module- 13: Workflow & Task Management (Total Feature - 5)
Feature Description:
1. Multi-Level Workflow
Supports sequential processing across multiple approval authorities.
2. Role-based Task Assignment
Assigns workflow activities according to user roles and responsibilities.
3. Application Status Tracking
Tracks application progress throughout the calibration lifecycle.
4. Workflow Remarks
Allows officials to record comments and review observations.
5. Audit Trail
Maintains a complete history of workflow activities for accountability and transparency.
Module- 14: Document Management (Total Feature - 5)
Feature Description:
1. Application Document Management
Securely stores and manages submitted application documents.
2. Questionnaire Management
Maintains completed applicant questionnaires and related records.
3. Inspection/Calibration Report Management
Stores calibration reports and inspection records digitally.
4. License Repository
Provides centralized storage for issued calibration certificates and related documents.

                                              287
```

## Page 289

```text
5. Rejection Note Management
Maintains rejection notes and supporting documents for future reference.

                                           288
```

## Page 290

```text
  SERVICE
                VERIFICATION SERVICE
    32
                Verification Application • Inspection • Approval • Certificate / Sticker

Service Profile
Domain                                 Service Type                    Primary Users
Verification / Metrology               Verification Service            Applicants • Director • DD • AD •
                                                                       Inspectors • System Admin
Core Scope                             Modules                         Features
Verification    &      Certification
Lifecycle
                                       12                              48

Functional Coverage
APPLICATION                        REVIEW                                INSPECTION
• Application Submission           • Application Review                  • Calibration Scheduling
• Category-wise Application        • Assignment                          • Calibration Management
• Fee Payment                      • Shortfall Management                • Re-inspection

VERIFICATION                       CERTIFICATE                           CONTROL
• Report Verification              • Certificate & Sticker               • Rejection
• DD Approval                      • Certificate Download                • Notifications
• Director Final Approval          • Record Management                   • Workflow
                                                                         • Documents

Module Catalogue
Sl. Module                                    No. of      Sl.   Module                             No. of
No.                                          Features     No.                                     Features

 01 Application Submission Module               4         07    Calibration   Certificate   and      3
                                                                Sticker Module
 02 Application Review & Assignment             4         08    Re-inspection / Re-calibration       4
    Module                                                      Management Module
 03 Shortfall Management Module                 5         09    Rejection Management Module          3
 04 Calibration Scheduling Module               4         10    Notification Module                  5
 05 Calibration Management Module               3         11    Workflow & Task Management           5
                                                                Module
 06 Calibration     Report    Verification      4         12    Document Management Module           4
    Module

                                                    289
```

## Page 291

```text
Service-32: Verification Service
The Verification Service is a comprehensive digital solution designed to automate the
complete verification process from application submission to certificate and sticker issuance.
The system enables applicants to submit verification applications online based on General
and Samiti/Bazar/Association/Malik categories, upload required documents, pay application
fees, and monitor application status through a centralized digital portal. Applications are
processed through a configurable role-based workflow where authorized officials review
submissions, assign applications to relevant officers, identify deficiencies, request
corrections, schedule verification activities, and conduct field verification. The platform
supports   verification   report   preparation,   multi-level   report   verification,   approval
management, re-inspection or re-calibration where required, and issuance of verification
certificates and stickers. Upon successful completion, the system generates and issues digital
certificates while maintaining centralized records of applications, reports, certificates, and
supporting documents. Automated notifications, workflow tracking, audit trails, and secure
document management ensure transparency, regulatory compliance, operational efficiency,
traceability, and accurate verification record management.

                                             290
```

## Page 292

```text
291
```

## Page 293

```text
Module-1: Application Submission Module (Total Feature - 4)
Feature Description:
1. Online Application Submission Based on General and
Samiti/Bazar/Association/Malik Category
Enables applicants to submit verification applications online based on the applicable
applicant category through the digital portal.
2. Required Document Upload
Allows applicants to upload all mandatory documents required for the verification process.
3. Application Fee Payment
Facilitates secure online payment of the prescribed verification application fee.
4. Application Tracking
Enables applicants to monitor the progress and current status of their submitted applications.
Module-2: Application Review & Assignment Module (Total Feature -
4)
Feature Description:
1. Director Application Review
Allows the Director to perform the initial review of submitted verification applications.
2. Application Forwarding/Assignment (DD/AD/Inspector)
Assigns applications to the appropriate Deputy Director, Assistant Director, or Inspector for
further processing.
3. Role-based Assignment
Automatically assigns verification tasks according to predefined user roles and
responsibilities.
4. Workflow Remarks
Allows reviewing officials to record comments, observations, and processing notes during
application review.

Module-3: Shortfall Management Module (Total Feature - 5)
Feature Description:
1. Application Review
Enables assigned officials to review submitted applications and supporting documents for
completeness.
2. Shortfall Identification
Identifies missing documents, incorrect information, or compliance deficiencies.
3. Shortfall Notification
Automatically notifies applicants regarding identified deficiencies requiring correction.
4. Customer Correction
Allows applicants to update application information and correct identified deficiencies.

                                             292
```

## Page 294

```text
5. Application Resubmission
Enables applicants to resubmit corrected applications along with updated supporting
documents.
Module-4: Calibration Scheduling Module (Total Feature - 4)
Feature Description:
1. Calibration Date Scheduling
Schedules verification or calibration appointments based on operational availability.
2. Calibration Date Rescheduling
Allows authorized officials to modify scheduled verification dates when necessary.
3. Multi-Level Calibration Date Approval (AD, DD, Director)
Supports hierarchical approval before confirming verification schedules.
4. Calibration Schedule Notification
Automatically notifies applicants and assigned inspectors regarding scheduled verification
dates.
Module-5: Calibration Management Module (Total Feature - 3)
Feature Description:
1. Calibration Execution
Enables inspectors to perform field verification and calibration activities according to
applicable standards.
2. Calibration Report Preparation
Allows inspectors to prepare structured digital verification and calibration reports.
3. Calibration Findings Recording
Records inspection measurements, observations, verification results, and compliance
findings.
Module-6: Calibration Report Verification Module (Total Feature - 4)
Feature Description:
1. AD Report Verification
Allows the Assistant Director to verify submitted verification reports.
2. DD Report Verification
Enables the Deputy Director to review and validate verified reports.
3. Director Final Approval
Supports the Director in providing the final approval of verification reports.
4. Approval History
Maintains a complete history of report verification and approval activities.

Module-7: Calibration Certificate and Sticker Module (Total Feature -
3)

                                             293
```

## Page 295

```text
Feature Description:
1. Certificate and Sticker Issuance
Generates and issues approved verification certificates and verification stickers upon
successful completion.
2. Certificate and Sticker Download
Allows applicants to download issued verification certificates and related documents online.
3. Certificate Record Management
Maintains a centralized repository of issued verification certificates and stickers.
Module-8: Re-inspection / Re-calibration Management Module (Total
Feature - 4)
Feature Description:
1. Re-inspection / Re-calibration Request
Initiates repeat verification or calibration when corrective action is required.
2. Re-scheduling
Schedules follow-up verification or calibration activities after approval.
3. Repeat Calibration Workflow
Manages the complete workflow for repeat verification and calibration activities.
4. Updated Calibration Report
Generates revised verification reports following successful re-inspection or re-calibration.
Module-9: Rejection Management Module (Total Feature - 3)
Feature Description:
1. Rejection Decision
Records the final rejection decision for applications that fail verification requirements.
2. Rejection Letter Generation
Generates official rejection letters specifying the reasons for application rejection.
3. Customer Notification
Automatically notifies applicants regarding the rejection decision.
Module-10: Notification Module (Total Feature - 5)
Feature Description:
1. Shortfall Notification
Alerts applicants regarding missing information or required corrections.
2. Calibration Schedule Notification
Sends notifications regarding scheduled verification or calibration dates.
3. Approval Notification
Notifies applicants when verification reports receive final approval.
4. License Issued Notification
Informs applicants after successful issuance of the verification certificate and sticker.

                                              294
```

## Page 296

```text
5. Rejection Notification
Sends notifications regarding application rejection.
Module-11: Workflow & Task Management Module (Total Feature -
5)
Feature Description:
1. Multi-Level Workflow
Supports sequential processing through multiple approval authorities.
2. Role-based Task Assignment
Assigns workflow activities according to user roles and organizational responsibilities.
3. Application Status Tracking
Tracks application progress throughout the complete verification lifecycle.
4. Workflow Remarks
Allows officials to record comments and observations during workflow processing.
5. Audit Trail
Maintains a complete history of workflow activities for transparency and accountability.
Module-12: Document Management Module (Total Feature - 4)
Feature Description:
1. Application Document Management
Securely stores and manages submitted application documents throughout the verification
process.
2. Calibration Report Management
Maintains digital verification and calibration reports along with supporting records.
3. License Repository
Provides centralized storage and retrieval of issued verification certificates and related
documents.
4. Rejection Letter Management
Stores rejection letters and supporting documents for future reference and audit purposes.

                                             295
```

## Page 297

```text
  SERVICE
                 MOBILE COURT                             &     SURVEILLANCE                       e-
    33
                 SERVICE
                 Mobile Court • Surveillance • Product & Sample Records • Tracking

Service Profile
Domain                               Service Type             Primary Users
Field Enforcement & Surveillance     Operational / Regulatory Field Officials • Magistrates •
                                     Service                  BSTI Offices • Authorized Users
Core Scope                           Modules                        Features
Mobile Court      &   Surveillance
Operations
                                     8                              49

Functional Coverage
MOBILE COURT                       SURVEILLANCE                        SAMPLE
• Court Entry                      • Surveillance Entry                • Sample Information
• Product & Company Details        • Team Management                   • Batch / Serial
• Offence                          • Product Details                   • BDS Result
• Fine / DCR                       • DCR                               • CA Field
• Imprisonment

TEST REPORT                        TRACKING                            ADMIN & WORKFLOW
• Report Upload                    • Mobile Court Tracking ID          • Magistrate Management
• Report Attachment                • Surveillance Tracking ID          • Product Master
                                   • Status Tracking                   • Office Configuration
                                                                       • Workflow

Module Catalogue
Sl. Module                                  No. of      Sl.   Module                             No. of
No.                                        Features     No.                                     Features

 01 Mobile Court Management                  18         05    Test Report Management               2
 02 Product Management                        5         06    Tracking & Monitoring                3
 03 Surveillance Management                  10         07    Administration                       2
 04 Sample Management                         7         08    Workflow Management (Future          2
                                                              Phase)

                                                  296
```

## Page 298

```text
Service-33: Mobile Court & Surveillance e-Service
The Mobile Court & Surveillance e-Service is a comprehensive digital platform designed to
streamline, centralize, and modernize BSTI’s Mobile Court and Surveillance operations for
both Certification Mark (CM) and Metrology activities. The system provides an end-to-end
digital environment for recording field operations, managing products, capturing case
information, tracking samples, uploading test reports, and monitoring operational activities.
The Mobile Court Management module enables authorized users to create court records,
select court types, manage multiple products, record product sources, fines, company
information, offences, DCR details, imprisonment information, and remarks. The Product
Management module maintains product categories, product masters, CM/Metrology
mappings, and dynamic product filtering. The Surveillance Management module supports
surveillance entry, inspection team management, product selection, observations, DCR
information, case counts, and remarks. The Sample Management module records collected
samples, brand names, batch/serial numbers, quantities, BDS test results, and CA-related
information. Test reports and supporting documents can also be uploaded and attached to
respective records. The platform further provides unique Tracking IDs and status tracking for
Mobile Court and Surveillance activities. Administrative capabilities include Magistrate
Management,     Product    Master   Administration,    Office   Configuration,   and   Lookup
Management. In the future phase, configurable approval workflows and automated routing,
notifications, and approvals will further enhance operational efficiency. Overall, the solution
will reduce manual paperwork, improve transparency and traceability, standardize field
operations, and provide BSTI with a secure and efficient digital management system.

                                             297
```

## Page 299

```text
298
```

## Page 300

```text
Module 1: Mobile Court Management (Total Feature - 18)
Features Description
1: Mobile Court Entry
Allows authorized users to create a new Mobile Court operation.
2: Court Type Selection
Select one or multiple Court Types using multi-select dropdown.
3: Product Type Selection
Allows selection of Product Type (CM or Metrology). The system dynamically loads relevant
product categories and products based on the selected type.
4: Product Category Selection
Displays category list according to selected Product Type.
5: Product Name Selection
Product Name dropdown automatically loads products under the selected category.
6: Multiple Product Selection
Supports adding multiple products within a single Mobile Court operation.
7: Dynamic Product Box
Users can add multiple Product Information sections using the Add (+) button.
8: Fine Entry
Separate Fine Amount field for every product included in the Mobile Court.
9: Product Source
Specify whether the product is Imported or Local through checkbox selection.
10: Office Information
Automatically retrieves Office Information from a logged-in user's profile.
11: Mobile Court Details
Description
Capture Mobile Court details including:
   ●   Office
   ●   Memo Number
   ●   Date
   ●   Court Type
   ●   Address
   ●   Team Information
12: Company Information
Capture Company Name and Address for each Mobile Court case.
13: Product Details
Maintain detailed product information associated with each Mobile Court.
14: Offence Description
Large text area to record offence details.

                                             299
```

## Page 301

```text
15: DCR Information
Capture DCR Number and Date.
16: Number of Cases
Record total number of legal cases initiated.
17: Imprisonment Information
Record imprisonment duration (if applicable).
18: Remarks
General remarks section for additional notes.
Module 2: Product Management (Total Feature - 5)
Features Description
1: Product Category Management
Maintain Product Categories for CM and Metrology.
2: Product Master
Create and manage a master list of products.
3: Product Type Mapping
Map products with CM or Metrology.
4: Product Category Mapping
Associate products with categories.
5: Dynamic Product Filtering
Automatically filter available products according to selected Product Type and Category.
Module 3: Surveillance Management (Total Feature - 10)
Features Description
1: Surveillance Entry
Create Surveillance records for CM and Metrology separately.
2: Surveillance Type
Select surveillance category.
3: Office Details
Auto-populate office information based on login.
4: Memo Information
Capture Memo Number and Date.
5: Team Member Management
Maintain inspection team members including:
   ●   Name
   ●   Designation
6: Product Selection
Select products for surveillance.
7: Product Description
Record surveillance observations for each product.

                                            300
```

## Page 302

```text
8: DCR Information
Capture DCR Number (if applicable).
9: Number of Cases
Record total number of cases detected during surveillance.
10: Remarks
Maintain additional comments.
Module 4: Sample Management (Total Feature - 7)
Features Description
1: Sample Information Entry
Capture sample details collected during Mobile Court or Surveillance.
2: Brand Name
Record Brand Name.
3: Batch/Serial Number
Capture Batch or Serial Number.
4: Quantity
Record collected sample quantity.
5: Sample Remarks
Maintain remarks for each sample.
6: BDS Result Recording
Capture laboratory/BDS test result.
7: CA Field
Maintain CA-related information based on laboratory outcome.
Module 5: Test Report Management (Total Feature - 2)
Features Description
1: Test Report Upload
Upload laboratory test reports against Mobile Court or Surveillance records.
2: Report Attachment
Support multiple document attachments.
Module 6: Tracking & Monitoring (Total Feature - 3)
Features Description
1: Mobile Court Tracking ID
Generate a unique Tracking ID for every Mobile Court.
2: Surveillance Tracking ID
Generate a unique Tracking ID for every Surveillance record.
3: Status Tracking
Track progress of Mobile Court and Surveillance activities.
Module 7: Administration (Total Feature - 2)

                                            301
```

## Page 303

```text
Features Description
1: Magistrate Management
Manage Magistrate information with dropdown selection.
2: Product Master Administration
Admin can Add, Edit, Update, and Maintain Product Master.
3: Office Configuration
Manage office-specific configurations.
4: Lookup Management
Maintain Court Types, Categories, Product Types, and other master data.
Module 8: Workflow Management (Future Phase) (Total Feature - 2)
Features Description
1: Mobile Court Approval Workflow
Configurable approval workflow for Mobile Court records.
2: Surveillance Approval Workflow
Approval workflow for Surveillance records.
3: Automated Workflow
Automated routing, approval, and notification process for Mobile Court and Surveillance
activities.

                                          302
```
