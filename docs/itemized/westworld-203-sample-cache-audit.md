---
layout: default
title: "westworld-203 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# westworld-203 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Westworld |
| Collection key | `westworld-203` |
| imdb_id | [tt0475784](https://www.imdb.com/title/tt0475784/) |
| wikipedia_url | [Westworld (TV series)](https://en.wikipedia.org/wiki/Westworld_(TV_series)) |
| Sample dates | 2018-05-07-to-2018-05-21 |
| Sample days | 15 |
| BTIH count | 70 |
| Unique BTIH count | 62 |
| Downloaders total | 2,796,464 |
| Uploaders total | 841,278 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-06T17:18:29Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Selected archive: cache.20180521.tar.xz
- Required sample span: 2018-05-07 to 2018-05-21 (15 days)
- Cache Day products: 15
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![Westworld collection size histogram](figures/westworld-203-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/westworld-203-downloads-by-week-westworld-203-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![westworld-203 downloads by day](figures/westworld-203-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 2.57 | 19.47 | 20.16 | 32.03 | 4.05 | 0.48 |

### Cumulative network infrastructure

[![Westworld cumulative map](figures/westworld-203-carto.png)](figures/westworld-203-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/westworld-203-data-ge-1080p.webp)](figures/westworld-203-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/westworld-203-data-lt-1080p.webp)](figures/westworld-203-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
