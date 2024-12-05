

Run from repo root to launch a hugo development server.

```bash
podman run -it -v ./site:/src -p 127.0.0.1:1313:1313 --rm ghcr.io/hugomods/hugo:base-0.133.1 hugo server --disableFastRender -D
```
