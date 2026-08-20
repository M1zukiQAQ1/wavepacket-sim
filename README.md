# Wavepacket Simulator

Standalone web app for simulating time propagation of wavepacket superpositions, including presets and button-built custom expressions.

Example form:

```text
sum A(k_i) cos(k_i x - ω(k_i)t + φ_i)
```

The spectral amplitude A(k) is selectable in preset mode:

- `A(k) = 1` (uniform)
- `A(k) = 1/(2π√σ) exp(-(k - k0)^2 / 2σ^2)` (Gaussian, with adjustable width σ)

A small inset on the plot shows the sampled A(k) spectrum of the current superposition.

## Run

Open `index.html` directly in a browser, or run the local preview server:

```bash
python3 app.py
```

Then visit `http://127.0.0.1:8765`.

## Deploy To GitHub Pages

GitHub Pages is available for this app. Push this folder to GitHub, then enable Pages from the repository root. GitHub Pages will serve `index.html`.

## Files

- `index.html`: standalone web app
- `app.py`: optional local preview server
- `.nojekyll`: keeps GitHub Pages simple
