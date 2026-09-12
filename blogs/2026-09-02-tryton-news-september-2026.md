---
title: "Tryton News September 2026"
url: "https://discuss.tryton.org/t/tryton-news-september-2026/9356"
date: "2026-09-02"
author: "udono"
feed_url: "https://discuss.tryton.org/c/news/25.rss"
---
September brings a balance of trytond internals and business-module refinements. The server now retries queued tasks that were dropped because a worker died, enforces request timeouts for the whole request, and exposes routes so RPC endpoints can be registered declaratively. On the user side, European VAT numbers are now validated in the background, stock periods close themselves, and the IBAN editor formats the number as it is typed-in.
