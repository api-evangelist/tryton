---
title: "Security Release for issue #14364"
url: "https://discuss.tryton.org/t/security-release-for-issue-14364/8952"
date: "2025-11-21"
author: "ced"
feed_url: "https://discuss.tryton.org/c/news/25.rss"
---
Mahdi Afshar has found that trytond does not enforce access rights for the route of the HTML editor (since version 6.0). Impact CVSS v3.0 Base Score: 7.1 Attack Vector: Network Attack Complexity: Low Privileges Required: Low User Interaction: None Scope: Unchanged Confidentiality: High Integrity: Low Availability: None Workaround A possible workaround is to block access to the html editor. Resolution All affected users should upgrade trytond to the latest version.
