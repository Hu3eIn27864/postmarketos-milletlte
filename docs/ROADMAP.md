# milletlte Roadmap

Target: Samsung Galaxy Tab 4 8.0 LTE, SM-T335. Current reports indicate the system reaches a graphical interface and display, touch and Wi-Fi work. This is partial user-reported validation, not a complete port certification.

Estimates assume access to the exact device and a recoverable test setup.

## M0 — Reproducible build record (1–2 weeks)
- [ ] Record exact image, build commit, firmware and installation method.
- [ ] Record kernel source, configuration and device tree revisions.
- [ ] Preserve recovery instructions and stock backups offline.
**Exit:** another developer can reproduce the build.

## M1 — Package and boot reproducibility (2–4 weeks)
- [ ] Validate deviceinfo and kernel package metadata.
- [ ] Build in clean pmbootstrap environment.
- [ ] Confirm repeated boots and collect logs.
**Exit:** repeatable boot on SM-T335.

## M2 — Hardware validation (4–8 weeks)
- [ ] Internal storage and filesystem mounting.
- [ ] Bluetooth, LTE modem, SIM and mobile data.
- [ ] Audio, cameras, sensors and rotation.
- [ ] Battery, charging and suspend/resume.
**Exit:** published test matrix with logs and pass/fail/unknown states.

## M3 — Upstream readiness (2–4 weeks)
- [ ] Check package naming, deviceinfo and kernel configuration against current postmarketOS conventions.
- [ ] Review licensing and source provenance.
- [ ] Document known limitations and recovery path.
**Exit:** reproducible patch series suitable for review.

## Schedule

| Period | Focus |
|---|---|
| Weeks 1–2 | M0 |
| Weeks 3–6 | M1 |
| Months 2–3 | M2 |
| Month 4 | M3 |

Hardware availability and kernel compatibility can extend these estimates. LTE and Wi-Fi variants are not interchangeable.
