# Alpha60 results: year 2018 campaign

This directory holds the in-progress year-2018 Alpha60 results dataset. The
frozen campaign inventory contains 49 media objects at SHA-256
`25095eaa1947db6677564c10021b41566dc50f2fdf56a5c84d50e07f378b49b8`.

## Campaign inputs

- `txt/year-2018-0-media-objects.txt`: canonical ordered inventory.
- `txt/year-2018-cache-aliases.tsv`: empty alias receipt; every canonical
  key maps directly to its same-named gold cache directory and member key.
- `txt/year-2018-cache-archive-overrides.json`: explicitly reviewed archive
  endpoint selections, if any.
- `txt/year-2018-cache-archive-map.json`: exact archive paths, sizes,
  SHA-256 identities, canonical sample contracts, sparse intervals, and
  byte-balanced ord/eureka ownership.

Cache archives and raw samples are immutable external campaign inputs and are
never committed to this repository. Generated data, figures, audit pages, and
the final checksum/release manifests are added only by the verified campaign
pipeline.
