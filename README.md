# XAS Merged Tools

A self-contained, offline, single-file HTML toolkit for planning and pre-checking
transmission XAS / XES measurements. Double-click the `.html` file — no install,
no server, no network. UI is bilingual (简体中文 / English, remembers your choice).

**Current version: v4.32.2** — `XAS_XES_merged_precheck_tools v4.32.2.html`

## Tabs

- **Sample Mass** — XAFSmass-style pellet/film planner: required sample mass,
  total μd and edge step Δμd with OK bands, per-variant pass/fail, lab-tube SNR /
  dead-time / pre-edge count-rate estimates. X-ray sources: Lab (kV/mA/window flux
  model), Synchrotron (direct Φ), Custom flux — and custom setups can be saved as
  named **machine presets** (stored locally, selectable from the source dropdown,
  deletable).
- **Analyzer by Element** — find analyzer crystals / Bragg geometries per edge.
- **Crystal Detail** — per-crystal Bragg math, stocked-analyzer catalogue.
- **Harmonic Collision** — harmonic/emission-line collision check plus a lab
  X-ray tube emission & filter advisor.

## Notes

- Physics: Henke/CXRO scattering factors, Kramers continuum model, non-paralyzable
  dead-time. Instrument-specific constants were calibrated against measured lab
  data; they are order-of-magnitude engineering estimates, not specifications.
- All data stays in the browser (localStorage only).

Copyright (c) 2026 by Dr. GENG Xun. Directly copy is prohibited.
