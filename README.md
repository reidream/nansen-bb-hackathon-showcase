# showcase-public

Static publish bundle for the showcase page, prepared from `my_work/showcase-ui/index2.html`.

## Purpose

- Provide a review-ready, static-only artifact.
- Run without npm/build steps.
- Keep runtime paths relative so the same files work on local static server and GitHub Pages project path.

## Local Preview

```bash
cd my_work/showcase-public
python3 -m http.server 8080
```

Open `http://127.0.0.1:8080/`.

## GitHub Pages Notes

- Publish the contents of this directory as-is.
- Keep `index.html` at the publish root.
- Do not inject `<base>` or rewrite relative paths.
- External CDN links (Google Fonts and external URLs) are intentionally unchanged.

## Included Runtime Assets

- `index.html`
- `assets/bot_avatars/alpha-hunter-bot.png`
- `assets/bot_avatars/alphacat.png`
- `assets/bot_avatars/bb-nansenbot.png`
- `assets/bot_avatars/bb-native-alpha-radar.png`
- `assets/bot_avatars/dd-signal-bot.png`
- `assets/bot_avatars/moltbot.png`
- `assets/bot_avatars/omikuji-bot.png`
- `assets/bot_avatars/siestan-bot.png`
- `assets/bot_avatars/tag-along-lens.png`
- `emoji/Nansen_Logo_Icon_GreenDark_RGB.svg`
- `emoji/nansen_green.png`
- `emoji/icon2.svg`
- `remotion-app/out/panel.mp4`
