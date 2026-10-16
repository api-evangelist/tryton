---
title: "Multiple custom modules with hatchling and tryton_dev"
url: "https://discuss.tryton.org/t/multiple-custom-modules-with-hatchling-and-tryton-dev/9430#post_2"
date: "2026-10-07"
author: "@ced Cédric Krier"
feed_url: "https://discuss.tryton.org/posts.rss"
---
This is because hatchling does not support “dev mode” with a path rewrite that is not replaced in the package directory. This is why the cookiecutter template adds a “loolback” symlink for module with prefix to provide the same path rewrite. We did not make such symlink in the standard module because usually core developers use the .hooks/link_modules script.
