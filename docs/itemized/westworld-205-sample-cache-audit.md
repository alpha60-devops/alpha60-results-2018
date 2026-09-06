---
layout: default
title: "westworld-205 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# westworld-205 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Westworld |
| Collection key | `westworld-205` |
| imdb_id | [tt0475784](https://www.imdb.com/title/tt0475784/) |
| wikipedia_url | [Westworld (TV series)](https://en.wikipedia.org/wiki/Westworld_(TV_series)) |
| Sample dates | 2018-05-21-to-2018-06-04 |
| Sample days | 15 |
| BTIH count | 73 |
| Unique BTIH count | 58 |
| Downloaders total | 2,885,607 |
| Uploaders total | 904,295 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-06T17:18:29Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Selected archive: cache.20180604.tar.xz
- Required sample span: 2018-05-21 to 2018-06-04 (15 days)
- Cache Day products: 15
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![Westworld collection size histogram](figures/westworld-205-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/westworld-205-downloads-by-week-westworld-205-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![westworld-205 downloads by day](figures/westworld-205-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 2.24 | 19.11 | 19.16 | 33.71 | 3.86 | 0.49 |

### Cumulative network infrastructure

[![Westworld cumulative map](figures/westworld-205-carto.png)](figures/westworld-205-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/westworld-205-data-ge-1080p.webp)](figures/westworld-205-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/westworld-205-data-lt-1080p.webp)](figures/westworld-205-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
