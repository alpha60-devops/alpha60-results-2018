---
layout: default
title: "romanoffs-108 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# romanoffs-108 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | The Romanoffs |
| Collection key | `romanoffs-108` |
| imdb_id | [tt6599482](https://www.imdb.com/title/tt6599482/) |
| wikipedia_url | [The Romanoffs](https://en.wikipedia.org/wiki/The_Romanoffs) |
| Sample dates | 2018-11-23-to-2018-12-20 |
| Sample days | 28 |
| BTIH count | 77 |
| Unique BTIH count | 54 |
| Downloaders total | 1,704,544 |
| Uploaders total | 118,312 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-06T17:18:29Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Selected archive: cache.20181220.tar.xz
- Required sample span: 2018-11-23 to 2018-12-20 (28 days)
- Cache Day products: 28
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![The Romanoffs collection size histogram](figures/romanoffs-108-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/romanoffs-108-downloads-by-week-romanoffs-108-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![romanoffs-108 downloads by day](figures/romanoffs-108-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 2.36 | 39.26 | 19.26 | 19.62 | 1.51 | 12.28 |

### Cumulative network infrastructure

[![The Romanoffs cumulative map](figures/romanoffs-108-carto.png)](figures/romanoffs-108-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/romanoffs-108-data-ge-1080p.webp)](figures/romanoffs-108-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/romanoffs-108-data-lt-1080p.webp)](figures/romanoffs-108-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
