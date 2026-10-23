# XAS Merged Tools

A self-contained, offline, single-file HTML toolkit for planning and pre-checking
transmission XAS / XES measurements. Double-click the `.html` file — no install,
no server, no network. UI is bilingual (简体中文 / English, remembers your choice).

**Current version: v5.14.1** — `XAS_XES_merged_precheck_tools v5.14.1.html`

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

## Credits and third-party data

- **Henke f″ tables** (Sample Mass tab and the tube/filter advisor) are converted from
  [XAFSmass](https://github.com/kklmn/XAFSmass) `data/Henke.npz` — MIT licence,
  © 2015 Konstantin Klementiev, Roman Chernikov. The Sample Mass method follows
  XAFSmass. Original data: B. L. Henke, E. M. Gullikson and J. C. Davis,
  *At. Data Nucl. Data Tables* **54**, 181 (1993); CXRO/LBNL.
- **Edge and emission-line data** come from [XrayDB](https://github.com/xraypy/XrayDB)
  (CC0 1.0 public domain).

Full notices: [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md).

## Licence

Copyright (c) 2026 by Dr. GENG Xun. Directly copy is prohibited.
Third-party data listed above keep their own licences.
