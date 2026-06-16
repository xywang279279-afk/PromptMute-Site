# PromptMute Public Pages

This folder contains static pages for public launch URLs:

- `index.html` -> `https://promptmute.app/`
- `privacy.html` -> `https://promptmute.app/privacy`
- `support.html` -> `https://promptmute.app/support`
- `styles.css` -> shared styling
- `assets/promptmute-icon.png` -> site-local app icon

The pages are static and can be deployed as a small standalone site.

Current GitHub Pages deployment:

```text
https://xywang279279-afk.github.io/PromptMute-Site/
https://xywang279279-afk.github.io/PromptMute-Site/privacy.html
https://xywang279279-afk.github.io/PromptMute-Site/support.html
```

The source app repository is private. The public Pages deployment uses a
separate public repository named `PromptMute-Site` that contains only this
static folder.

## Deployment Notes

If the static host supports clean URLs, map:

```text
/privacy  -> /privacy.html
/support  -> /support.html
```

If it does not, use:

```text
https://promptmute.app/privacy.html
https://promptmute.app/support.html
```

Update `docs/STORE_LISTING.md`, `src-tauri/tauri.conf.json`, and App Store Connect URLs if the final public paths differ.
