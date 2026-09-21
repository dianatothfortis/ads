# ads

UA ad creatives (statics, videos, playables) for Fortis games. Public repo so files are reachable by ad networks and embeddable in Notion creative reports.

## Structure

```
ads/
├── demeter/
│   ├── static/     PNG/JPG images
│   ├── video/      MP4 videos
│   └── playables/  HTML playable ads
├── mergemon/
│   ├── static/
│   ├── video/
│   └── playables/
└── twilighttowers/
    ├── static/
    ├── video/
    └── playables/
```

## Notes

- Legacy playables also live at `dianatothfortis/playables` — that repo is being kept for backwards-compatible embeds in existing Notion reports. New assets go here.
- File naming follows the Fortis creative filename anatomy: `{GAME}_{Concept}_{Variant}_{Date}_{Channel}_{Lang}_{Type}_{Size}[_{Network}].{ext}`
