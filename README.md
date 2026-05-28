# NUDGE — Project Page

Project page for **Zero-Shot Reactive Obstacle Avoidance for Generative Robot Policies**
(NUDGE: Nudge Update via Differentiable GEometry), submitted to CoRL 2026.

The site is a static page (`index.html` + `static/`) and is served as-is by GitHub Pages
(`.nojekyll` is present).

## Local preview

```bash
python3 -m http.server 8765
# open http://localhost:8765/index.html
```

## Layout

- `index.html` — all page content
- `static/images/` — figures extracted from the paper (`method_pipeline.png`, `denoising_viz.png`, `libero_setup.png`)
- `static/videos/` — real-robot demo clips (`real_baseline.mp4`, `real_nudge.mp4`)
- `static/videos/libero_baseline/`, `static/videos/libero_nudge/` — LIBERO-Object rollouts
  (`rollout_tXX_eYYY_{success,failure}.mp4`, 10 tasks × 10 episodes), driven by the interactive
  comparison viewer; the task/outcome map lives inline in `index.html`
- `static/pdfs/paper.pdf` — the paper
- `static/css/`, `static/js/` — Bulma + helper scripts

## TODO before publishing

- Replace `Anonymous Author(s)` with the author list and add personal/institution links.
- Add arXiv / OpenReview / Code buttons in the hero (placeholder comment marks the spot).
- Set `og:url` in `<head>` to the deployed URL.
- Confirm/relabel the two demo video captions.

## Acknowledgments

Built on the [Academic Project Page Template](https://github.com/eliahuhorwitz/Academic-project-page-template),
adopted from the [Nerfies](https://nerfies.github.io/) page. Licensed under
[CC BY-SA 4.0](http://creativecommons.org/licenses/by-sa/4.0/).
