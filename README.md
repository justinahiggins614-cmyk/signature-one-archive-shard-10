# signature-one-archive-shard-10

Frozen storage shard for Manon's Signature Spec Catalog (Pending Patents).

- Holds spec chunks `data/volumes/specs-c01419.jsonl.gz` … `specs-c01537.jsonl.gz`
  (JAH-SPEC-212701 … JAH-SPEC-230550 — 17850 original draft specs).
- Served to the main catalog page at
  https://justinahiggins614-cmyk.github.io/signature-one-archive/specs.html
  via its `data/index/shards.json` registry (lazy-loaded on demand).
- FROZEN: never write new chunks here; new drip chunks always land in the main repo.
