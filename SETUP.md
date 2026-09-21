# Profile repository setup

This repository is the profile README for [@divyanshj25604-arch](https://github.com/divyanshj25604-arch).

## 3D contribution chart

The uploaded `github-profile-3d-contrib` project is used through `.github/workflows/profile-3d-contrib.yml`. The workflow runs on pushes, on demand, and once per day. It generates a light chart (`day.svg`) and a dark chart (`night.svg`) from `conf/github-profile-3d-contrib.json`, then publishes both files to the `output-3d-contrib` branch.

The README uses GitHub's `<picture>` element so visitors automatically receive the chart that matches their color scheme.

## Local edits

1. Update `README.md` with current projects, links, and contact details.
2. Keep `conf/github-profile-3d-contrib.json` valid JSON if changing chart colors.
3. Push to `main` or run **Actions → Generate profile contribution visuals → Run workflow**.

The generated SVGs are intentionally kept in a separate branch so the main branch stays readable.
