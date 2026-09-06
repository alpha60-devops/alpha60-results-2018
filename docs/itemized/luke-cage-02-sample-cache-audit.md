---
layout: default
title: "luke-cage-02 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# luke-cage-02 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Luke Cage |
| Collection key | `luke-cage-02` |
| imdb_id | [tt3322314](https://www.imdb.com/title/tt3322314/) |
| wikipedia_url | [Luke Cage (TV series)](https://en.wikipedia.org/wiki/Luke_Cage_(TV_series)) |
| Sample dates | 2018-06-22-to-2018-10-04 |
| Sample days | 105 |
| BTIH count | 273 |
| Unique BTIH count | 229 |
| Downloaders total | 18,069,714 |
| Uploaders total | 3,148,401 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-06T17:18:29Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Selected archive: cache.20181004.tar.xz
- Required sample span: 2018-06-22 to 2018-10-04 (105 days)
- Cache Day products: 105
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![Luke Cage collection size histogram](figures/luke-cage-02-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/luke-cage-02-downloads-by-week-luke-cage-02-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![luke-cage-02 downloads by day](figures/luke-cage-02-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 5.44 | 36.27 | 20.87 | 22.31 | 2.35 | 10.57 |

### Cumulative network infrastructure

[![Luke Cage cumulative map](figures/luke-cage-02-carto.png)](figures/luke-cage-02-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/luke-cage-02-data-ge-1080p.webp)](figures/luke-cage-02-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/luke-cage-02-data-lt-1080p.webp)](figures/luke-cage-02-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
