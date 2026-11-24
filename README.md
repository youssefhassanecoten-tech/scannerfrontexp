# scannerfrontexp

Warm-premium **FootScaner** frontend — the same React application that runs on the Raspberry Pi hotspot.

This repository's root serves the built React app (`index.html` + `assets/`), so GitHub Pages shows the current production frontend. The previous static demo pages are kept, unchanged, in [`backup-static-demo/`](backup-static-demo/) as a rollback reference.

## What is active

- Warm-premium light theme and Espresso & Bronze dark theme
- Strict RU / EN separation
- Scan flow with progress, result page, and comparison modal
- TURBO pressure map produced from real scans by the Pi backend
- Service diagnostics, logs, SSH terminal, and Wi-Fi / Hotspot settings

The live device is served at `http://footscaner.local/` (also `192.168.1.221` and hotspot `10.42.0.1`).

## Demo mode

On GitHub Pages, pressing **начать сканирование** runs a 7-second simulated scan and then shows the bundled example result — no Pi backend required. The measurement table is filled with the values of that example image.
