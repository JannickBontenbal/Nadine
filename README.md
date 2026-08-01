# Nadine

Static thank-you page for the short film `Nadine`.

## Render

Use this as a Render Static Site:

- Root directory: leave empty
- Build command: `git lfs install && git lfs pull`
- Publish directory / build output path: `.`
- Root page: `index.html`

The gallery images live in `photos/` and are referenced with relative paths, so the site works both locally and on Render.

## Video

`Nadine.mp4` is tracked with Git LFS because the movie is larger than GitHub's normal file size limit. Make sure Git LFS is enabled before pushing:

```powershell
git lfs install
git push
```
