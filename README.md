# ZeBeZo RSS Feed Files

This repository is a generated mirror of the RSS capture files from the Pi-hosted ZeBeZo site.

## Files

- `data/rss_feeds.json` - configured RSS feed registry.
- `data/rss_feed_items.json.gz` - compressed current public cache consumed by the webpage.
- `data/rss_feed_history.json.gz` - compressed retained per-feed capture history.
- `index/rss_feed_index.json` - compact lookup index for scripts and downstream fetchers.
- `captures/<slot>/rss_feed_items.json.gz` - immutable page-data snapshot for a capture slot.
- `captures/<slot>/rss_feed_history.json.gz` - immutable full-history snapshot for a capture slot.

## Latest Sync

- Source slot: `2026-07-31-QAM`
- Source generated at: `2026-07-31T13:00:00.058916+00:00`
- Feeds: `75`

Do not hand-edit these generated files. Update the Pi feed registry or capture worker, then run the sync.
