---
title: "Security Release for issue #14363"
url: "https://discuss.tryton.org/t/security-release-for-issue-14363/8951"
date: "2025-11-21"
author: "ced"
feed_url: "https://discuss.tryton.org/c/news/25.rss"
---
Abdulfatah Abdillahi has found that sao does not escape the completion values . The content of completion is generally the record name which may be edited in many ways depending on the model. The content may include some JavaScript which is executed in the same context as sao which gives access to sensitive data such as the session.
