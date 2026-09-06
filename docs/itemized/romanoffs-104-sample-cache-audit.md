---
layout: default
title: "romanoffs-104 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# romanoffs-104 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | The Romanoffs |
| Collection key | `romanoffs-104` |
| imdb_id | [tt6599482](https://www.imdb.com/title/tt6599482/) |
| wikipedia_url | [The Romanoffs](https://en.wikipedia.org/wiki/The_Romanoffs) |
| Sample dates | 2018-10-26-to-2018-11-17 |
| Sample days | 23 |
| BTIH count | 54 |
| Unique BTIH count | 38 |
| Downloaders total | 182,516 |
| Uploaders total | 69,518 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-06T17:18:29Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Selected archive: cache.20181117.tar.xz
- Required sample span: 2018-10-26 to 2018-11-17 (23 days)
- Cache Day products: 23
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![The Romanoffs collection size histogram](figures/romanoffs-104-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/romanoffs-104-downloads-by-week-romanoffs-104-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![romanoffs-104 downloads by day](figures/romanoffs-104-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 2.89 | 31.21 | 16.24 | 34.91 | 3.16 | 3.13 |

### Cumulative network infrastructure

[![The Romanoffs cumulative map](figures/romanoffs-104-carto.png)](figures/romanoffs-104-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/romanoffs-104-data-ge-1080p.webp)](figures/romanoffs-104-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/romanoffs-104-data-lt-1080p.webp)](figures/romanoffs-104-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
