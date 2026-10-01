# CVPR Oral Atlas · 2024–2026

Interactive reading atlas of 326 CVPR oral papers: 90 from 2024, 95 from 2025, and 141 from 2026.

Website: https://samxiexs.github.io/paper-oral-atlas/

## Explore

Search and filter papers, inspect citation and topic graphs, compare years and papers, browse reading routes, and keep personal reading notes. PDF links point to official CVF files. APA references are available as a text download.

Citation edges are matched from paper reference sections; semantic similarity and keyword tags are exploratory signals, not official classifications. Chinese reading notes cover a selected subset of papers. Personal notes are stored in your browser; export JSON to back them up or transfer them.

## Run locally

```sh
python3 -m http.server 8000
```

Open http://localhost:8000/. No build step is required.

## Typography

OpenDyslexic fonts are bundled locally under `fonts/`, with their SIL Open Font License 1.1 and upstream source commit. Chinese characters use the system Chinese font fallback.

## Hosting

GitHub Pages publishes the `main` branch root. All asset paths are relative, including fonts, so the site works under `/paper-oral-atlas/`.
