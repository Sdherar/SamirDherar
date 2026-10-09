# Portfolio improvement review

Prepared on `portfolio-improvements` from main commit `070bca0b6483cd69a555f61ec7451e7739c1b5cf`. Main and GitHub Pages are unchanged pending approval.

## Before / after

- General introduction and uneven project emphasis → requested hardware-focused introduction, clearer résumé action, and Aegis / RK3399 / HFSS featured hierarchy.
- Useful results hidden in disclosures → visible Aegis, HFSS, measured interconnect, solar, CMOS, and LED target highlights.
- Narrative descriptions → explicit ownership, calibration workflow, thermal tradeoff, and observation-to-resolution debugging story.
- RF details grouped unevenly → five experimental areas, with match, polarization, gain, and ranging caveats.
- Underused existing evidence → inverter scope image, baseline via geometry, and additional ADS plots with full-size links.
- Sparse sharing metadata → canonical and Open Graph metadata on both pages, plus an authentic CAD-based social preview.
- Original portrait served at full size → smaller faithful preview; original retained. Image dimensions, alt text, figure containment, table keyboard access, dark-section contrast, and narrow-screen wrapping improved.

## Accuracy and evidence

- Aegis ≈0.1 dB comes from the existing résumé. It is explicitly **reported** calibration accuracy, not independently verified accuracy across the full band. Raw calibration data and uncertainty budget are absent.
- HFSS 4.84 GHz / 10 Gb/s / 25 Gb/s remain simulated. Existing exploratory 30 Gb/s language remains qualified, not validated performance. Geometry images are not substitutes for transmission or eye-comparison plots.
- Cable and termination values retain existing measured/fitted distinctions and team credit.
- RF additions follow the supplied project brief. Raw thermistor, antenna, amplifier, and 0.40 m / 0.426 m example records are not in the repository, so they could not be independently recalculated here. The existing ranging SVG is retained unchanged.
- Solar values remain recorded output measurements; distortion is unresolved. No efficiency or sinusoidal-compliance claim was added.
- CMOS and resonant results remain saved simulations; no fabricated IC or verified ZVS claim was added.
- Radar calculations, estimates, completed design status, and unmeasured runtime/detection performance remain distinguished. LED values are requirements only. RK3399 bring-up is not claimed.

## Checks actually completed

- All local HTML image, stylesheet, script, page, fragment, and enlargement targets exist.
- All twelve projects and eleven native disclosure sections retained.
- Existing engineering image references retained; original assets and `.nojekyll` untouched. The portrait now uses a smaller derivative.
- Site JavaScript exercised with a DOM test double: top/bottom image, alt text, caption, link, and pressed state; Aegis opening link.
- Responsive CSS reviewed for 1440, 1024, 768, 390, and 360 px. **These sizes were not browser-rendered or visually verified.**
- Keyboard semantics, focus rules, skip target, table scrolling, and reduced-motion styles inspected statically. Native keyboard interaction and contrast were not audited with a browser accessibility tool.
- Existing GitHub Pages homepage and résumé returned HTTP 200 before changes. LinkedIn destination and mailto syntax preserved; external LinkedIn profile availability and mail delivery were not tested.
- No original ChatGPT-hosted resource or navigation dependency remains.

## Browser limitation / approval gate

The local Chromium download failed; the cloud browser could not reach localhost. Native disclosure interaction, image enlargement, print dialog, final visual layout, horizontal overflow, and viewport checks still need real-browser validation before merging. No live deployment is claimed.

## Useful original materials to add later

- RK3399 layout, stackup, or board render.
- Aegis calibration residuals, frequency/power coverage, and measurement uncertainty.
- HFSS baseline/backdrilled S21 and 10/25 Gb/s eye plots.
- RF horn patterns, amplifier gain plot, and lab photographs.
- Radar layout or schematic and future bring-up results.
