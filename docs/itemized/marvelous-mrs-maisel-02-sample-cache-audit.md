---
layout: default
title: "marvelous-mrs-maisel-02 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# marvelous-mrs-maisel-02 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Marvelous Mrs. Maisel |
| Collection key | `marvelous-mrs-maisel-02` |
| imdb_id | [tt5788792](https://www.imdb.com/title/tt5788792/) |
| wikipedia_url | [The Marvelous Mrs. Maisel](https://en.wikipedia.org/wiki/The_Marvelous_Mrs._Maisel) |
| Sample dates | 2018-12-05-to-2019-02-12 |
| Sample days | 70 |
| BTIH count | 216 |
| Unique BTIH count | 200 |
| Downloaders total | 11,708,694 |
| Uploaders total | 1,105,064 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-06T17:18:29Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Selected archive: cache.20190212.tar.xz
- Required sample span: 2018-12-05 to 2019-02-12 (70 days)
- Cache Day products: 70
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![Marvelous Mrs. Maisel collection size histogram](figures/marvelous-mrs-maisel-02-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/marvelous-mrs-maisel-02-downloads-by-week-marvelous-mrs-maisel-02-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![marvelous-mrs-maisel-02 downloads by day](figures/marvelous-mrs-maisel-02-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 2.61 | 38.92 | 22.87 | 20.11 | 1.72 | 12.32 |

### Cumulative network infrastructure

[![Marvelous Mrs. Maisel cumulative map](figures/marvelous-mrs-maisel-02-carto.png)](figures/marvelous-mrs-maisel-02-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/marvelous-mrs-maisel-02-data-ge-1080p.webp)](figures/marvelous-mrs-maisel-02-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/marvelous-mrs-maisel-02-data-lt-1080p.webp)](figures/marvelous-mrs-maisel-02-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
