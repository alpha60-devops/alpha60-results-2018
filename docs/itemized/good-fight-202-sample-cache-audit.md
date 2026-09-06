---
layout: default
title: "good-fight-202 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# good-fight-202 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | The Good Fight |
| Collection key | `good-fight-202` |
| imdb_id | [tt5853176](https://www.imdb.com/title/tt5853176/) |
| wikipedia_url | [The Good Fight](https://en.wikipedia.org/wiki/The_Good_Fight) |
| Sample dates | 2018-03-11-to-2018-03-31 |
| Sample days | 21 |
| BTIH count | 50 |
| Unique BTIH count | 44 |
| Downloaders total | 339,615 |
| Uploaders total | 182,350 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-06T17:18:29Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Selected archive: cache.20180331.tar.xz
- Required sample span: 2018-03-11 to 2018-03-31 (21 days)
- Cache Day products: 21
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![The Good Fight collection size histogram](figures/good-fight-202-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/good-fight-202-downloads-by-week-good-fight-202-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![good-fight-202 downloads by day](figures/good-fight-202-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 3.55 | 20.50 | 10.59 | 24.80 | 2.73 | 0.73 |

### Cumulative network infrastructure

[![The Good Fight cumulative map](figures/good-fight-202-carto.png)](figures/good-fight-202-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/good-fight-202-data-ge-1080p.webp)](figures/good-fight-202-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/good-fight-202-data-lt-1080p.webp)](figures/good-fight-202-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
