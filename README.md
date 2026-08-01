# Nadine

Static thank-you page for the short film `Nadine`.

## Render

Use this as a Render Static Site:

- Root directory: leave empty
- Build command: leave empty
- Publish directory / build output path: `.`
- Root page: `index.html`

The gallery images live in `photos/` and are referenced with relative paths, so the site works both locally and on Render.

## Video

The page streams and downloads the movie from this GitHub Release asset URL:

`https://github.com/JannickBontenbal/nadine/releases/download/movie/Nadine.mp4`

Upload the video through GitHub Releases:

1. Go to the `nadine` repository on GitHub.
2. Open **Releases**.
3. Choose **Draft a new release**.
4. Set **Tag** to `movie`.
5. Set the release title to `Nadine movie`.
6. Attach `Nadine.mp4`.
7. Publish the release.

After Render redeploys, the embedded player and download button will use that public release asset.
