---
title: Privacy policy — Field History for Jira
---

# Privacy policy — Field History for Jira

Vendor: **Upgrades** · Contact: [admin@upgrades.co.il](mailto:admin@upgrades.co.il) · Last updated: 25 November 2026

## What the app does

Field History for Jira adds a read-only **Field history** panel to a Jira issue. It shows previous values of the issue description and selected multi-line text custom fields, lets a user compare two versions, and remembers the last field that user viewed. It never edits issues.

## Data we access

When a licensed user opens the panel, the app reads, through Jira's REST API on that user's behalf:

- the issue key and the available field metadata;
- the issue's changelog entries, including field names, old and new values, author display names and change timestamps;
- the current value of the fields shown in the picker.

This data is used only to show the panel. Diffing and formatting happen in the user's browser. We do not copy issue content, changelog values, author names or timestamps into any store of our own.

The app also receives the user's Atlassian account ID and licence state from Atlassian. The account ID is used only to key the stored preference described below.

## Data we store

| Data | Location | Purpose | Retention |
|---|---|---|---|
| Atlassian account ID (as part of a storage key) and the last field ID the user selected | Atlassian Forge storage, scoped to the app installation | Remember the field picker selection | While the app is installed. Atlassian keeps Forge storage for 28 days after uninstall for recovery, then removes it. |

The stored record contains no issue content. We do not store changelog text, issue keys, author names, email addresses, analytics or advertising identifiers, credentials, or logs containing user data. We never collect Atlassian passwords or API tokens.

## Where data is processed

All compute and storage run on Atlassian's Forge platform. Forge storage is encrypted, isolated per installation, and follows the data-residency location of your Jira site. The app has no backend of its own, no external database, and no analytics or error-reporting services. No data is transferred outside Atlassian, including outside the EEA.

## Sharing

We do not share user data with third parties, sub-processors, advertisers or analytics providers. Atlassian hosts the app under its own terms, and the [Atlassian Data Processing Addendum](https://www.atlassian.com/legal/data-processing-addendum) applies.

## Your rights and our role

For the account ID and field preference stored on your behalf, Upgrades acts as a **processor** under the GDPR and a **service provider** under the CCPA; your organisation is the controller. To ask about, access or delete this data, email [admin@upgrades.co.il](mailto:admin@upgrades.co.il). Uninstalling the app also removes it, as described above.

## Changes

We will update this policy if the app's data handling changes and change the date above.
