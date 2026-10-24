# Capstone 27: AI Business Plan Draft Assistant

**Project question:** Can AI help write a first-draft business plan, and which parts are most likely to be wrong?

**Fictional business:** Sweet Crumbs Bakery (small neighbourhood bakery near a college)

**Submitted by:** Arsha J Albert

## Submission contents

| Folder / file | Description |
|---------------|-------------|
| `06_Final_Demo/index.html` | Final demo website (no backend, runs in any browser) |
| `PDF_Exports/SweetCrumbs_Business_Plan_Draft.pdf` | 1. Business plan |
| `PDF_Exports/SweetCrumbs_Revenue_Model.pdf` | 2. Revenue model with Google Sheets formulas |
| `PDF_Exports/SweetCrumbs_6_Slide_Summary.pdf` | 3. 6-slide summary deck |
| `PDF_Exports/AI_Error_Log_and_Verification_Report.pdf` | 4. Error log and verification report |
| `PDF_Exports/Prompt_Library_Before_After_Time_Comparison.pdf` | 5. Prompt library, before/after analysis, time comparison |
| `PDF_Exports/Peer_Review_Feedback_Report.pdf` | 6. Peer review feedback |
| `PDF_Exports/Final_Demo_Script.pdf` | 7. Final demo script |

## Demo website

A single HTML page with **no backend**. Everything runs in the browser, with no install and no sign-in.

**Steps:** introduction, drafting with prompts, revenue model (sliders), error log, verification, time comparison, before/after, peer feedback, conclusion.

**Run it:** open `06_Final_Demo/index.html` in a browser, or right-click it in VS Code and choose **Open with Live Server**. Use **Next** and **Back** or the arrow keys.

**GitHub Pages (optional):** Settings, Pages, choose branch `main` and the root folder, then open `.../06_Final_Demo/`.

## Key results
- Base case: 80 customers a day at Rs. 140, 26 days a month gives net profit of about Rs. 41,720 a month (margin about 14%).
- Break-even: about 61 customers a day. Setup cost payback: about 14.4 months.
- AI's first draft claimed a 45% margin and break-even in month 2. Both were unrealistic and were corrected.
- Student-reported drafting time: about 8.5 hours without AI, about 52 minutes with AI.

## Tools used
ChatGPT (free), Gemini (free), Claude (free), Google Sheets, Google Docs, Gamma (free plan).

## Notes
- All business figures are assumptions for a fictional business, not real data.
- The demo page loads two fonts from Google Fonts; offline it falls back to standard fonts.
