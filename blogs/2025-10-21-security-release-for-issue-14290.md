---
title: "Security Release for issue #14290"
url: "https://discuss.tryton.org/t/security-release-for-issue-14290/8895"
date: "2025-10-21"
author: "ced"
feed_url: "https://discuss.tryton.org/c/news/25.rss"
---
Brandon Da Costa and Mahdi Afshar have found that sao executes JavaScript included in HTML documents (such as attachments). These documents may be uploaded by any authenticated user. The JavaScript is executed in the same context as sao which gives access to sensitive data such as the session.
