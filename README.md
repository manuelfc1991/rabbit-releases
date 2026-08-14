# rabbit-releases

The public release channel for Rabbit Downloader. The app polls
`version.json` here for updates and downloads APKs from this repo's
releases; `site-rules.json` feeds the extractor's site rules; the
`python-pack-*` release hosts the optional Python runtime. The source
lives in a private repository — this repo exists so a private codebase
can still ship public updates.
