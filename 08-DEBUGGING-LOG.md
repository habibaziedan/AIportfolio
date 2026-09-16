# Debugging & Testing Log

## 8.1 Bug Report Template

| Field | What to Record |
|---|---|
| Bug ID | BUG-XXX |
| Related PRD Task | TASK-XX-XX |
| Description | What went wrong |
| Expected Behavior | What should happen |
| Actual Behavior | What actually happened |
| Steps to Reproduce | Exact steps to reproduce |
| Evidence | Screenshot, console error, or error message |
| Investigation | Likely causes and analysis |
| AI Assistance | Actual debugging prompt |
| AI Suggestion | Summary of proposed solution |
| Evaluation | Whether the suggestion was correct and why |
| Fix | Actual change implemented |
| Retest | Repeat reproduction steps |
| Result | PASS / FAIL |
| Related Commit | `fix: ...` |

## 8.2 Example Debugging Record

| Field | Example |
|---|---|
| Bug ID | BUG-001 |
| Related Task | TASK-07-05 |
| Description | Mobile navigation overlaps page content. |
| Expected Behavior | Navigation opens without covering or breaking content. |
| Investigation | Inspect mobile navigation positioning and layout rules. |
| AI Assistance | Provide error/relevant CSS and ask for likely root cause and minimal fix. |
| Evaluation | Review and test the proposed solution rather than applying it automatically. |
| Fix | Adjust navigation layout. |
| Retest | Test multiple mobile viewport sizes. |
| Result | PASS |
| Commit | `fix: improve mobile navigation` |

---

## Log

_New bugs found during real testing go here, one table per entry, following the template above. Do not fabricate entries — only add a record once a bug has actually been found, investigated, and fixed._
