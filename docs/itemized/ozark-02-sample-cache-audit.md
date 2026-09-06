---
layout: default
title: "ozark-02 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# ozark-02 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Ozark |
| Collection key | `ozark-02` |
| imdb_id | [tt5071412](https://www.imdb.com/title/tt5071412/) |
| wikipedia_url | [Ozark (TV series)](https://en.wikipedia.org/wiki/Ozark_(TV_series)) |
| Sample dates | 2018-08-31-to-2018-10-11 |
| Sample days | 42 |
| BTIH count | 252 |
| Unique BTIH count | 239 |
| Downloaders total | 2,357,489 |
| Uploaders total | 1,132,560 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-06T17:18:29Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Selected archive: cache.20181011.tar.xz
- Required sample span: 2018-08-31 to 2018-10-11 (42 days)
- Cache Day products: 42
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![Ozark collection size histogram](figures/ozark-02-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/ozark-02-downloads-by-week-ozark-02-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![ozark-02 downloads by day](figures/ozark-02-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 6.27 | 23.09 | 21.75 | 36.39 | 3.83 | 1.18 |

### Cumulative network infrastructure

[![Ozark cumulative map](figures/ozark-02-carto.png)](figures/ozark-02-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/ozark-02-data-ge-1080p.webp)](figures/ozark-02-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/ozark-02-data-lt-1080p.webp)](figures/ozark-02-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
