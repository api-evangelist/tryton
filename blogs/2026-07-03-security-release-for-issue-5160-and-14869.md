---
title: "Security Release for issue #5160 and #14869"
url: "https://discuss.tryton.org/t/security-release-for-issue-5160-and-14869/9266"
date: "2026-07-03"
author: "ced"
feed_url: "https://discuss.tryton.org/c/news/25.rss"
---
The user titou has discovered that the administrator group can execute Python code on the server which is hidden inside an uploaded report template . And Dan Shallom has discovered that the same can also be accomplished by the marketing group when uploading marketing email templates . Impact CVSS v3.0 Base Score: 6.5 Attack Vector: Network Attack Complexity: Low Privileges Required: Low User Interaction: None Scope: Unchanged Confidentiality: High Integrity: None Availability: None Workaround There is no workaround.
