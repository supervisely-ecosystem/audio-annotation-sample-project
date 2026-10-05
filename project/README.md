This project uses Supervisely JSON format for audio projects.

## Structure

- `meta.json` — project meta: tag definitions and project settings, `"projectType": "audio"`
- `ds0/audio/` — the recordings (`.wav`, `.flac`, `.mp3`, `.ogg`, `.m4a`)
- `ds0/ann/` — one annotation per recording, named `<recording>.json`: `sampleCount`, `sampleRate`, `channels`, `description` and `tags` (time segments and whole-recording tags)

## Useful links

- [Supervisely Developer Portal](https://developer.supervisely.com/)
- [Supervisely JSON format](https://docs.supervisely.com/data-organization/00_ann_format_navi)
- [Supervisely Ecosystem](https://ecosystem.supervisely.com/)
