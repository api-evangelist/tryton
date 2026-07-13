---
title: "Security Release for issue #14220"
url: "https://discuss.tryton.org/t/security-release-for-issue-14220/8823"
date: "2025-09-15"
author: "ced"
feed_url: "https://discuss.tryton.org/c/news/25.rss"
---
Luis Falcon has found that trytond may log sensitive data like passwords when the logging level is set to INFO . Impact CVSS v3.0 Base Score: 4.2 Attack Vector: Network Attack Complexity: Low Privileges Required: High User Interaction: None Scope: Unchanged Confidentiality: High Integrity: None Availability: None Workaround Increasing the logging level above INFO prevents logging of the sensitive data. Resolution All affected users should upgrade trytond to the latest version.
