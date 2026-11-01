# Timesheet Redesign — Reference Gathering Report

Date: 1 Nov 2026

## Goal
Gather references for remaking the SELISE MBM **Timesheet** app and place them in Figma.

## Sources
- Current app: SELISE portal (Corteza), namespace STS — https://myportal.selise.biz/compose/ns/STS/pages/449970382880309249
- Outside patterns: Mobbin (web screens)
- Figma (final): https://www.figma.com/design/iX9bhukr9B1Ya2dVomGaMT/Timesheet — page **References**
- Figma (first draft): https://www.figma.com/design/sY6UJOjA3BZb1Ikoo4FX8J/UX-Daily---Saadman — page **TIMESHEET**

## What was done
1. **Captured the current app (read-only, no entries made).** Pages visited: Home, All Task, Report, Customer & Project List, Feedback. Nothing was clicked that would create or submit data. A "Workflow prompt" (date + Submit) opened by itself on Home and was left untouched.
2. **Collected 18 outside references** from Mobbin in four groups.
3. **Built a reference board in Figma.** It has labelled sections with a card for each screen (image, app name, one-line takeaway).
4. **Migrated the board** from UX Daily to the new Timesheet file, on a new **References** page. The old capture frame was copied over as a flat image.

## Current app — observations
| Page | What's there | Issues noted |
|---|---|---|
| Home | "Create Timesheet for Today", "Add Logs for Past Days", Date/Total Hours/Undertime table, 4 stat cards (Month, YTD, Billable YTD, Non-billable YTD), billable/non-billable/total chart per client | Stat card titles cut off; slow loading spinners; workflow prompt covers the chart |
| All Task | 11 columns: Date, Start, End, Client, Project, Description, Billable Unit, Billable Hrs, General Admin, Sales & Marketing, Total | Scrolls sideways; dates wrap to 3 lines; 401 records |
| Report | Saved ranges: Start date, End date, Billable/Non-billable | No preview or chart |
| Customer & Project List | Customer / Project / Business Unit, 1,160 rows, search | Lookup only |
| Feedback | List + Add | Empty |

## Reference board contents
- **00 Current app:** Home full capture, Home, Home stats & chart, All Task, Report, Customer & Project List, Feedback
- **01 Weekly time entry:** ClickUp, Toggl Track, Wrike, Aboard (review/submit week), Midday
- **02 Dashboard & summaries:** Aboard, Xero, Bonsai, Toggl Track
- **03 Log a time entry:** Xero (modal with quick-duration chips), Bonsai, Programa (drawer), Toggl (project picker), Midday
- **04 Reports:** Toggl (breakdown), Aboard (approval status), Bonsai (printable report), Deputy

## Patterns worth carrying into the redesign
- A weekly grid that shows day totals and the shortfall against expected hours
- A "Submit week" step instead of per-day creation
- Quick-duration chips and "Save & add another" for fast entry
- A searchable project picker grouped by client, which would replace scrolling a 1,160-row list
- KPI cards with full labels (billable vs non-billable), with charts under them
- Reports with a live preview and breakdown, not just saved date ranges

## Open items
- **Xero "New time entry" image:** its upload timed out repeatedly, so the slot in the new file is still empty.
- **"Home — full capture" card:** the slot was added, but the image upload was interrupted. It's not confirmed.
- **Old capture frame:** in the new file it's a flat image. For editable layers, copy-paste the frame from UX Daily.
- **UX Daily draft board:** still there (one Xero slot empty). It hasn't been deleted.
- **Git:** the "GIT" link given was the same as the portal page, so no code repo was reviewed.
