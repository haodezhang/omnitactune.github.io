# OmniTacTune — Project Page

Static academic project page (no build step). Open `index.html` in a browser, or deploy to GitHub Pages.

## Deploy to GitHub Pages
1. Create a repo (e.g. `omnitactune.github.io` or any repo with Pages enabled).
2. Copy the contents of this folder (`index.html` + `static/`) to the repo root.
3. Settings → Pages → Source = `main` / root.
4. Visit `https://<user>.github.io/<repo>/`.

## Structure
- `index.html` — the page.
- `static/paper.pdf` — compiled paper (linked by the "Paper" button).
- `static/videos/` + `static/posters/` — web-optimized MP4 demos and poster frames.
- `static/figs/` — paper figures, the four ablation charts, and `insight.svg`.
- `static/tables/` — Table 1 and Table 2 images.

## Links
- **Paper** → active, points to `static/paper.pdf`.
- **arXiv / Video** → greyed-out placeholders. To activate, replace the
  `<span class="btn disabled">…</span>` with `<a class="btn" href="URL" target="_blank">…</a>`.

## Video → role mapping
| File | Role |
|------|------|
| full_video.mp4 | Full overview (2×) |
| task_peg / charger / cap / box .mp4 | Four tasks (10×) |
| training.mp4 | One-take training |
| base_flow.mp4 (IMG_2473_4_3X) | Flow Policy |
| base_act.mp4 (IMG_2951_3X) | ACT |
| base_dp.mp4 (IMG_2951_2_3X) | DP |
| base_pi05.mp4 (IMG_2951_3_3X) | π0.5 |
| datasrc_human.mp4 (3×) | Human Video |
| datasrc_teleop.mp4 (10×) | Teleoperation Data |
