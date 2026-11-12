# Units 8/9 Day 2 — Choosing Insurance Coverage

Student HTML for high school Personal Financial Literacy. The separate 16-question vocabulary quiz belongs in Google Forms and is not reproduced here.

## Configuration
- Lesson ID: `PF-U8U9-D2-INSURANCE-COVERAGE`
- Contract: `U89D2-v1`
- Data tab: `U89_D2_Responses`
- Web App URL: `https://script.google.com/macros/s/AKfycbzzw6074u4LYYssEJM0gMDSuhy4P76IZG4yS0eWivqcQgBemeebzfzs6G91lQyJoren/exec`
- PDF library: local `assets/jspdf.umd.min.js` (jsPDF 2.5.2), license in `assets/JSPDF-LICENSE.txt`

## Class sequence
Vocabulary Forms quiz (0–15), Insurance Detective (15–35), Health Comparison (35–55), Auto Comparison (55–75), MOVE (75–85), Final Protection Plan (85–90), Submission (90–100).

## Release status
**Pre-live build: NOT YET CLASSROOM READY.** Code syntax and repository paths audited. The following live checks are still required before student use:
1. From the deployed exact Web App endpoint, confirm diagnostic returns `ok:true`, correct lesson and tab.
2. With a disposable test alias, save and verify the actual Google Sheet row.
3. Refresh and recover the complete response; test a second browser/device.
4. Simulate network loss and check local retention and eventual sync.
5. Open two tabs and verify stale changes cannot overwrite newer work.
6. Generate primary and Emergency PDFs with a complete response, 1,000+ characters, every input type, alias and completion grade at top.
7. Confirm the published PDF library and any images/assets load in the school environment.
8. Review browser console and submission flow.

Do not modify existing student Sheet records during testing. Source code is provided without embedded keys or spreadsheet IDs. The Apps Script deployed code is maintained separately by the teacher. Alias-only access is not authenticated identity.