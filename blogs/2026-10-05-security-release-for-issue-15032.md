---
title: "Security Release for issue 15032"
url: "https://discuss.tryton.org/t/security-release-for-issue-15032/9411"
date: "2026-10-05"
author: "ced"
feed_url: "https://discuss.tryton.org/c/news/25.rss"
---
Jaisurya has discovered that the content of the HTML editor was not escaped . Impact CVSS v3.0 Base Score: 5.4 Attack Vector: Network Attack Complexity: Low Privileges Required: Low User Interaction: Required Scope: Changed Confidentiality: Low Integrity: Low Availability: None Workaround Setup restrictive CSP without unsafe inline script may prevent the attack. Resolution All affected users should upgrade trytond to the latest version.
