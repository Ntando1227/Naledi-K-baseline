# Spreadsheet Skills Baseline — Render deployment

This package contains the current public assessment and the completed example workbook. The example download remains hidden on the page until the student confirms she has attempted Part 2.

## Deploy with Render

1. Extract this ZIP into a Git repository so `render.yaml` and the `dist` folder are at the repository root.
2. Push the files to your Git provider.
3. In Render, create a new Blueprint deployment from that repository, or create a Static Site manually.
4. For a manual Static Site, leave the build command blank and set the publish directory to `dist`.

The included `render.yaml` configures a static site with `dist` as its publish directory. The current ChatGPT-hosted assessment is public; Render will create a separate public URL for this deployment.
