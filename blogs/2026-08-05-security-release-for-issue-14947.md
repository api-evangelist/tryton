---
title: "Security Release for issue #14947"
url: "https://discuss.tryton.org/t/security-release-for-issue-14947/9302"
date: "2026-08-05"
author: "ced"
feed_url: "https://discuss.tryton.org/c/news/25.rss"
---
Cédric Krier has discovered that Tryton does not prevent weasyprint to access local files when rendering HTML report to PDF. Impact CVSS v3.0 Base Score: 4.9 Attack Vector: Network Attack Complexity: Low Privileges Required: High User Interaction: None Scope: Unchanged Confidentiality: High Integrity: None Availability: None Workaround There is no workaround. Resolution All affected users should upgrade trytond to the latest version.
