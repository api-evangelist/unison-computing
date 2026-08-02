---
title: "Designing a typed batch storage API"
url: "https://www.unison-lang.org/blog/batch-storage-api/"
date: "2024-12-06"
author: "Rebecca Mark"
feed_url: "https://www.unison-lang.org/feed.xml"
---
The 20.1.0 release of the Cloud client introduces Storage.Batch, a new API for bulk database reads. The design of the Batch ability involved balancing the need for type-safety and the ability to query across multiple tables of different types. Here's where we landed with it.
