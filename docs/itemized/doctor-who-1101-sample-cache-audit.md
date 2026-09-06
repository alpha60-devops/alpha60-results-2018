---
layout: default
title: "doctor-who-1101 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# doctor-who-1101 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Doctor Who 2005 |
| Collection key | `doctor-who-1101` |
| imdb_id | [tt0436992](https://www.imdb.com/title/tt0436992/) |
| wikipedia_url | [Doctor Who (series 11)](https://en.wikipedia.org/wiki/Doctor_Who_(series_11)) |
| Sample dates | 2018-10-07-to-2018-11-03 |
| Sample days | 28 |
| BTIH count | 97 |
| Unique BTIH count | 75 |
| Downloaders total | 4,342,624 |
| Uploaders total | 393,834 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-06T17:18:29Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Selected archive: cache.20181103.tar.xz
- Required sample span: 2018-10-07 to 2018-11-03 (28 days)
- Cache Day products: 28
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![Doctor Who 2005 collection size histogram](figures/doctor-who-1101-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/doctor-who-1101-downloads-by-week-doctor-who-1101-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![doctor-who-1101 downloads by day](figures/doctor-who-1101-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 2.47 | 39.29 | 19.36 | 20.64 | 1.97 | 12.22 |

### Cumulative network infrastructure

[![Doctor Who 2005 cumulative map](figures/doctor-who-1101-carto.png)](figures/doctor-who-1101-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/doctor-who-1101-data-ge-1080p.webp)](figures/doctor-who-1101-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/doctor-who-1101-data-lt-1080p.webp)](figures/doctor-who-1101-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
