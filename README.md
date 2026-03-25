# TMU-Battlebots-Updated-Site
Updated Static Site for the TMU Battlebots Team

## To Run Locally

1. Start the dev server from the project root:
	`hugo server -D`
2. Open `http://localhost:1313/`.

Note: Keep `hugo.yaml` as the active config file (done to avoid incorrect config loaded; removed `hugo.toml`)

## Additional URL Notes

- Actions uses the repo variable `SITE_URL` as baseURL

- For GitHub Pages user site, set `SITE_URL` to `https://TMU-BattleBots.github.io/`
	-> Note: Prev URL was `https://tmu-battlebots.github.io/TMU-Battlebots/` - NO LONGER ACTIVE!

If `SITE_URL` is not set, workflow gets set to default GitHub Pages URL.
