---
title: Field History for Jira
---

# Field History for Jira

By **Upgrades** · Support: [admin@upgrades.co.il](mailto:admin@upgrades.co.il) · [Privacy policy](privacy/)

Field History for Jira adds a read-only **Field history** panel to Jira Cloud issues. It shows how an issue's description, and long text custom fields, changed over time, and compares any two versions with a word-level diff.

## Getting started

1. Install the app from the Atlassian Marketplace. No configuration is needed.
2. Open any Jira issue and choose **Field history** from the app actions under the issue title.
3. The panel lists every recorded change, newest first, with the author and time. Hover over a time to see the exact date.

## Comparing versions

- Pick two versions in **From** and **To**. By default the panel compares the latest change with the one before it.
- The **inline diff** underlines added words and strikes through removed ones.
- Choose **Side-by-side diff** to see the old and new text in two columns.

## Custom fields

Use the **Field** picker to switch from the description to any multi-line text custom field that has history on the issue. The panel remembers your last choice.

## What the app does not do

- It does not edit issues or restore old values.
- It sends no data outside Atlassian: everything runs on Atlassian's Forge platform.
- Only plain text is compared. Jira stores past values without formatting, so bold, links and tables are not shown in the diff.

## Licensing

The app is paid via the Atlassian Marketplace, with a 30-day free trial. Without an active licence, the panel shows a short message with a link to the listing.

## Support

Email [admin@upgrades.co.il](mailto:admin@upgrades.co.il). We aim to reply within two business days. For security issues, use the same address and mark the subject **Security**.
