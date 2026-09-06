---
layout: default
title: "chilling-adventures-of-sabrina-01 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# chilling-adventures-of-sabrina-01 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | The Chilling Adventures of Sabrina |
| Collection key | `chilling-adventures-of-sabrina-01` |
| imdb_id | [tt7569592](https://www.imdb.com/title/tt7569592/) |
| wikipedia_url | [Chilling Adventures of Sabrina (TV series)](https://en.wikipedia.org/wiki/Chilling_Adventures_of_Sabrina_(TV_series)) |
| Sample dates | 2018-10-26-to-2018-11-01 |
| Sample days | 7 |
| BTIH count | 195 |
| Unique BTIH count | 187 |
| Downloaders total | 912,011 |
| Uploaders total | 390,545 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-06T17:18:29Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Selected archive: cache.20181101.tar.xz
- Required sample span: 2018-10-26 to 2018-11-01 (7 days)
- Cache Day products: 7
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![The Chilling Adventures of Sabrina collection size histogram](figures/chilling-adventures-of-sabrina-01-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/chilling-adventures-of-sabrina-01-downloads-by-week-chilling-adventures-of-sabrina-01-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![chilling-adventures-of-sabrina-01 downloads by day](figures/chilling-adventures-of-sabrina-01-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 5.78 | 18.99 | 28.48 | 31.70 | 3.84 | 0.71 |

### Cumulative network infrastructure

[![The Chilling Adventures of Sabrina cumulative map](figures/chilling-adventures-of-sabrina-01-carto.png)](figures/chilling-adventures-of-sabrina-01-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/chilling-adventures-of-sabrina-01-data-ge-1080p.webp)](figures/chilling-adventures-of-sabrina-01-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/chilling-adventures-of-sabrina-01-data-lt-1080p.webp)](figures/chilling-adventures-of-sabrina-01-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
