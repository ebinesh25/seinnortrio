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

## Pages

- `/` — music and official links
- `/artist-profile/` — artist profile and press kit
- `/tech-rider/` — technical rider

The profile and rider pages embed the PDFs linked from the band's Linktree. Replace the remote PDF URLs in `src/pages/artist-profile.astro` and `src/pages/tech-rider.astro` with local copies when they are available.
