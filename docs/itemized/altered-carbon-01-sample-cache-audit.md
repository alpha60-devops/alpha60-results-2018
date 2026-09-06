---
layout: default
title: "altered-carbon-01 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# altered-carbon-01 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Altered Carbon |
| Collection key | `altered-carbon-01` |
| imdb_id | [tt2261227](https://www.imdb.com/title/tt2261227/) |
| wikipedia_url | [Altered Carbon (TV series)](https://en.wikipedia.org/wiki/Altered_Carbon_(TV_series)) |
| Sample dates | 2018-02-02-to-2018-03-31 |
| Sample days | 58 |
| BTIH count | 237 |
| Unique BTIH count | 223 |
| Downloaders total | 6,673,016 |
| Uploaders total | 3,356,461 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-06T17:18:29Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Selected archive: cache.20180331.tar.xz
- Required sample span: 2018-02-02 to 2018-03-31 (58 days)
- Cache Day products: 58
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![Altered Carbon collection size histogram](figures/altered-carbon-01-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/altered-carbon-01-downloads-by-week-altered-carbon-01-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![altered-carbon-01 downloads by day](figures/altered-carbon-01-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 6.06 | 16.27 | 33.81 | 30.93 | 3.07 | 0.70 |

### Cumulative network infrastructure

[![Altered Carbon cumulative map](figures/altered-carbon-01-carto.png)](figures/altered-carbon-01-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/altered-carbon-01-data-ge-1080p.webp)](figures/altered-carbon-01-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/altered-carbon-01-data-lt-1080p.webp)](figures/altered-carbon-01-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
