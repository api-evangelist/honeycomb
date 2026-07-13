---
title: "Managing OpenTelemetry Semantic Convention Migrations With the Collector"
url: "https://www.honeycomb.io/blog/managing-opentelemetry-semantic-convention-migrations-collector"
date: "2026-04-23"
author: "Mike Goldsmith"
feed_url: "https://www.honeycomb.io/rss/blog.xml"
---
This is what a semantic convention migration looks like in practice: not a clean cutover, but months of coexistence where old and new attribute names overlap. In this post, I'll explain why this happens, how the OpenTelemetry Collector's schema processor is designed to automate migrations in both directions, and what we're actively working on to get it into a state where everyone can use it.
