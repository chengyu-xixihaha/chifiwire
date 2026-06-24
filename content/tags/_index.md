---
title: "Tags"
# Noindex the 259 thin tag pages (≈1 post each) + drop them from the sitemap
# (see layouts/sitemap.xml). On a new, low-authority site these were eating
# Google's limited crawl budget while real articles sat un-crawled. Categories
# stay indexed. PaperMod emits a single noindex meta via robotsNoIndex.
robotsNoIndex: true
cascade:
  - robotsNoIndex: true
---
