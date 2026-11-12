# Units 8/9 Day 2 — The Price of Protection

## Student lesson
Published HTML: https://mdhallman-bot.github.io/PF-Unit-8-9-Day-2-Insurance-Choices/

This is a complete revised high-school personal-finance lesson on insurance decisions, not a graded quiz. The separate 16-question vocabulary quiz remains in Google Forms.

### Learning phases
1. Rank coverage priorities and identify coverage across 12 scenarios.
2. Study auto, health, renters, life and disability: limits, premiums, deductibles, claims, exclusions and financial risk.
3. Choose one of the fully detailed fictional policies in five categories and justify the protection plan.
4. Reveal Jordan's 12-month financial ledger, including premiums every month, patient/driver expenses, insurer payments, remaining savings and funding gap. Eight months are ordinary.
5. Compare an alternative policy, re-rank priorities, and reconsider a $50,000 liability scenario.

All student writing is checked for **completion locally**. **No student responses are sent to an AI model.** No API key is needed. The preexisting Apps Script backend may still contain an unused optional AI endpoint, but this HTML never invokes it.

## Frozen backend configuration
- Google Apps Script URL: https://script.google.com/macros/s/AKfycbzzw6074u4LYYssEJM0gMDSuhy4P76IZG4yS0eWivqcQgBemeebzfzs6G91lQyJoren/exec
- Script Property: `SHEET_ID` (set only in Apps Script project, not HTML)
- Lesson: `PF-U8U9-D2-INSURANCE-COVERAGE`
- Contract: `U89D2-v1`
- Tab: `U89_D2_Responses`
- Local namespace: `PFL_U89D2_v1:`
- Local jsPDF: `assets/jspdf.umd.min.js` (v2.5.2; license included).

### Important state safeguards
Alias-first load; local-first persistence; cloud receipt with checksum verification; revision/conflict protection; previous-version saved responses preserved inside a legacy recovery field; emergency print/PDF export; primary PDF with all response fields and running monthly ledger.

### External source references
- Colorado minimum auto liability: https://dmv.colorado.gov/colorado-motorist-insurance-identification-database-miidb
- Colorado points: https://cdor.colorado.gov/hearings-homepage/motor-vehicle-hearings/point-suspensions
- Health age-26 provision: https://www.healthcare.gov/young-adults/children-under-26/
- Health full annual cost: https://www.healthcare.gov/choose-a-plan/your-total-costs/

**All classroom insurance quotations and repair costs are explicitly fictional teaching examples.** The simulation does not imply that family members automatically owe a driver's liabilities or that all unpaid bills immediately become loans.

## Release status
**NOT YET CLASSROOM READY.** Source content and JavaScript syntax have been reviewed, but the following live checks must be completed in the actual school browser using a disposable alias:
- Verify diagnostic, saving and actual spreadsheet row against the exact embedded deployment.
- Refresh and cross-device restore; simulate internet outage and retry.
- Two-browser stale revision conflict; confirm no silent overwriting.
- Test initial plan lock, year reveals, alternative comparison, all input-state coverage and final review after returning from homework.
- Open/read a primary PDF with a very long written answer; verify alias and completion grade prominent at top; test Emergency PDF.
- Verify locally hosted PDF library and source links from published site with Chromebook/network restrictions.

Never test against actual student records or call the lesson classroom-ready before these checks pass.
