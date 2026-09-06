---
layout: default
title: "3-percent-02 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# 3-percent-02 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Three Percent |
| Collection key | `3-percent-02` |
| imdb_id | [tt4922804](https://www.imdb.com/title/tt4922804/) |
| wikipedia_url | [3%](https://en.wikipedia.org/wiki/3%25) |
| Sample dates | 2018-04-27-to-2018-06-02 |
| Sample days | 37 |
| BTIH count | 178 |
| Unique BTIH count | 167 |
| Downloaders total | 324,764 |
| Uploaders total | 142,384 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-06T17:18:29Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Selected archive: cache.20180602.tar.xz
- Required sample span: 2018-04-27 to 2018-06-02 (37 days)
- Cache Day products: 37
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![Three Percent collection size histogram](figures/3-percent-02-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/3-percent-02-downloads-by-week-3-percent-02-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![3-percent-02 downloads by day](figures/3-percent-02-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 4.70 | 24.97 | 20.14 | 34.99 | 2.24 | 2.71 |

### Cumulative network infrastructure

[![Three Percent cumulative map](figures/3-percent-02-carto.png)](figures/3-percent-02-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/3-percent-02-data-ge-1080p.webp)](figures/3-percent-02-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/3-percent-02-data-lt-1080p.webp)](figures/3-percent-02-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
