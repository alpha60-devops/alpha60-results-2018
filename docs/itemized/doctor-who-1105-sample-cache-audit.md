---
layout: default
title: "doctor-who-1105 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# doctor-who-1105 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Doctor Who 2005 |
| Collection key | `doctor-who-1105` |
| imdb_id | [tt0436992](https://www.imdb.com/title/tt0436992/) |
| wikipedia_url | [Doctor Who (series 11)](https://en.wikipedia.org/wiki/Doctor_Who_(series_11)) |
| Sample dates | 2018-11-05-to-2018-11-18 |
| Sample days | 14 |
| BTIH count | 66 |
| Unique BTIH count | 55 |
| Downloaders total | 2,439,593 |
| Uploaders total | 198,036 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-06T17:18:29Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Selected archive: cache.20181118.tar.xz
- Required sample span: 2018-11-05 to 2018-11-18 (14 days)
- Cache Day products: 14
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![Doctor Who 2005 collection size histogram](figures/doctor-who-1105-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/doctor-who-1105-downloads-by-week-doctor-who-1105-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![doctor-who-1105 downloads by day](figures/doctor-who-1105-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 2.34 | 39.18 | 18.95 | 20.53 | 1.87 | 12.31 |

### Cumulative network infrastructure

[![Doctor Who 2005 cumulative map](figures/doctor-who-1105-carto.png)](figures/doctor-who-1105-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/doctor-who-1105-data-ge-1080p.webp)](figures/doctor-who-1105-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/doctor-who-1105-data-lt-1080p.webp)](figures/doctor-who-1105-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
