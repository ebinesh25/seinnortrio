# Siennor Trio

The official website for Siennor Trio, built with Astro.

## Development

```sh
npm ci
npm run dev
```

## Build

```sh
npm run build
npm run preview
```

## GitHub Pages

Pushing to `work` or `main` triggers the GitHub Actions Pages deployment workflow. It builds this project for `https://ebinesh25.github.io/seinnortrio/`. The first time, enable Pages in repository Settings → Pages by setting the build source to **GitHub Actions**. The workflow then builds and deploys updates automatically. The repository's Actions settings must allow Pages deployments.

## Pages

- `/` — music and official links
- `/artist-profile/` — artist profile and press kit
- `/tech-rider/` — technical rider

The profile and rider pages embed the PDFs linked from the band's Linktree. Replace the remote PDF URLs in `src/pages/artist-profile.astro` and `src/pages/tech-rider.astro` with local copies when they are available.
