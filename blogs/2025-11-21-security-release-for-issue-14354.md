---
title: "Security Release for issue #14354"
url: "https://discuss.tryton.org/t/security-release-for-issue-14354/8950"
date: "2025-11-21"
author: "ced"
feed_url: "https://discuss.tryton.org/c/news/25.rss"
---
Mahdi Afshar and Abdulfatah Abdillahi have found that trytond sends the trace-back to the clients for unexpected errors . This trace-back may leak information about the server setup . Impact CVSS v3.0 Base Score: 4.3 Attack Vector: Network Attack Complexity: Low Privileges Required: Low User Interaction: None Scope: Unchanged Confidentiality: Low Integrity: None Availability: None Workaround A possible workaround is to configure an error handler which would remove the trace-back from the response.
