---
layout: default
title: "house-of-cards-06 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# house-of-cards-06 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | House of Cards |
| Collection key | `house-of-cards-06` |
| imdb_id | [tt1856010](https://www.imdb.com/title/tt1856010/) |
| wikipedia_url | [House of Cards (American TV series)](https://en.wikipedia.org/wiki/House_of_Cards_(American_TV_series)) |
| Sample dates | 2018-11-02-to-2018-11-29 |
| Sample days | 28 |
| BTIH count | 267 |
| Unique BTIH count | 249 |
| Downloaders total | 2,417,399 |
| Uploaders total | 1,091,455 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-06T17:18:29Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Selected archive: cache.20181129.tar.xz
- Required sample span: 2018-11-02 to 2018-11-29 (28 days)
- Cache Day products: 28
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![House of Cards collection size histogram](figures/house-of-cards-06-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/house-of-cards-06-downloads-by-week-house-of-cards-06-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![house-of-cards-06 downloads by day](figures/house-of-cards-06-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 8.31 | 16.82 | 26.91 | 39.09 | 2.68 | 1.18 |

### Cumulative network infrastructure

[![House of Cards cumulative map](figures/house-of-cards-06-carto.png)](figures/house-of-cards-06-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/house-of-cards-06-data-ge-1080p.webp)](figures/house-of-cards-06-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/house-of-cards-06-data-lt-1080p.webp)](figures/house-of-cards-06-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
