# Wavepacket Simulator

Standalone web app for simulating time propagation of wavepacket superpositions, including presets and button-built custom expressions.

Example form:

```text
sum A_i cos(k_i x - ω(k_i)t + φ_i)
```

## Run

Open `index.html` directly in a browser, or run the local preview server:

```bash
python3 app.py
```

Then visit `http://127.0.0.1:8765`.

## Deploy To GitHub Pages

Push this folder to GitHub, then enable Pages from the repository root. GitHub Pages will serve `index.html`.

## Files

- `index.html`: standalone web app
- `app.py`: optional local preview server
- `.nojekyll`: keeps GitHub Pages simple
