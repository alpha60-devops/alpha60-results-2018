---
layout: default
title: "into-the-badlands-308 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# into-the-badlands-308 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Into The Badlands |
| Collection key | `into-the-badlands-308` |
| imdb_id | [tt3865236](https://www.imdb.com/title/tt3865236/) |
| wikipedia_url | [Into the Badlands (TV series)](https://en.wikipedia.org/wiki/Into_the_Badlands_(TV_series)) |
| Sample dates | 2018-06-18-to-2018-06-25 |
| Sample days | 8 |
| BTIH count | 69 |
| Unique BTIH count | 53 |
| Downloaders total | 477,290 |
| Uploaders total | 157,484 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-06T17:18:29Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Selected archive: cache.20180625.tar.xz
- Required sample span: 2018-06-18 to 2018-06-25 (8 days)
- Cache Day products: 8
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![Into The Badlands collection size histogram](figures/into-the-badlands-308-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/into-the-badlands-308-downloads-by-week-into-the-badlands-308-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![into-the-badlands-308 downloads by day](figures/into-the-badlands-308-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 8.31 | 23.38 | 12.48 | 24.92 | 2.51 | 1.68 |

### Cumulative network infrastructure

[![Into The Badlands cumulative map](figures/into-the-badlands-308-carto.png)](figures/into-the-badlands-308-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/into-the-badlands-308-data-ge-1080p.webp)](figures/into-the-badlands-308-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/into-the-badlands-308-data-lt-1080p.webp)](figures/into-the-badlands-308-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
