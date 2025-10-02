# TASK7_INTERNSHIP
Identify and Remove Suspicious Browser Extensions.
# Browser Extension Security Audit

## Objective
To identify, review, and remove suspicious browser extensions that could pose security risks.

## Steps Taken
1. Opened browser’s **extension/add-ons manager**:
   - Chrome: `chrome://extensions`
2. Reviewed all installed extensions for:
   - Unknown publishers
   - Excessive permissions
   - Poor user reviews
   - Unfamiliar or unused entries
3. Checked **permissions** for each extension (especially "Read and change all data on websites").
4. Marked suspicious or unused extensions for removal.
5. Removed unnecessary or risky extensions and restarted the browser.
6. Monitored browser performance post-removal.
7. Researched **how malicious extensions can harm users**, including:
   - Data theft
   - Ad injection
   - Tracking & profiling
   - Password/session hijacking
8. Documented findings and actions taken.

## Suspicious Permissions to Watch
- Read and change all website data
- Read browsing history
- Manage downloads
- Modify clipboard
- Access all tabs and cookies

## Findings
| Extension Name        | Publisher          | Reason Marked Suspicious                  | Action Taken |
|-----------------------|-------------------|--------------------------------------------|--------------|
| Search Manager Pro    | Unknown           | Changed default search engine without consent | Removed |
| Fast Coupon Finder    | Unverified Source | Injected ads and popups                    | Removed |
| (Others if any…)      | –                 | –                                          | – |

## Post-Action Notes
- Browser startup and page load speed improved after removal.
- No further pop-ups or search engine redirects observed.
- Security scan run: No malicious software detected.

## Key Learnings
- Install extensions only from official stores.
- Always check developer, permissions, and reviews before installing.
- Remove unused extensions to reduce attack surface.
- Extensions can steal sensitive data if given broad permissions.
- Keep extensions updated via browser’s official update mechanism.

## How to Report Malicious Extensions
- **Chrome Web Store:** "Report abuse" option on the extension page.
- **Firefox Add-ons:** "Report this add-on" option on the add-on page.
- **Edge Add-ons:** "Report abuse" option on the add-on page.


