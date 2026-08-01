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

The page expects the movie at:

`Nadine.mp4`

The movie file is intentionally not included in the normal site push because it is about 794 MB. GitHub's browser upload and normal Git uploads are not suitable for a file that large.

To upload the video through GitHub, use Git LFS from this folder:

```powershell
git lfs install
git add -f Nadine.mp4
git commit -m "Add Nadine movie file"
git push
```

Render is already configured to run `git lfs pull` during deploy, so after that push the video should become available to the embedded player and download button.
