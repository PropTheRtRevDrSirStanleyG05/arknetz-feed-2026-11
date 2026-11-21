# arknetz-feed-2026-11

ArkNetzWebWeaver global feed shard for 2026-11 (MIT). Monthly time shards are
append-only: a new month never rewrites last month's file (PROTOCOL.md §3.7).

- `feed-2026-11.json.zst` — canonical file (live empty state: no pointers,
  22 bytes). `feed-2026-11.json` is the plain mirror.
- `feed-index.json(.zst)` — lists the months that exist.

Live state: no posts yet. The first published post adds the first pointer
here — an empty feed is the live starting state, not test data.
