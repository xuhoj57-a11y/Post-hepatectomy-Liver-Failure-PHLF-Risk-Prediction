# PHLF Predictor English Package

Download the three files into the same folder:
- `phlf_predictor.html`
- `model_rf_integrated.json`
- `README.md`

Run the tool through a local HTTP server:

```bash
python -m http.server 8765
```

Then open:

```text
http://127.0.0.1:8765/phlf_predictor.html
```

The prediction runs locally in the browser and does not upload patient data. Opening the HTML file directly by double-clicking may be blocked by some browsers because the page reads the local JSON model file.
