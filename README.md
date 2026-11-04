# postmarketOS for Samsung Galaxy Tab 4 8.0 LTE (milletlte)

**Status: experimentally booted; partial hardware functionality reported by user testing.**

Target device: Samsung Galaxy Tab 4 8.0 LTE, model **SM-T335**, codename `milletlte`.

## Device identity

- Device: Samsung Galaxy Tab 4 8.0 LTE
- Model: SM-T335
- Codename: `milletlte`
- Architecture: ARM 32-bit family; confirm exact kernel/userspace configuration during bring-up

## Current test status

The tester reports that postmarketOS reaches a graphical interface and that display, touchscreen and Wi-Fi work. These are initial user-reported results; the exact image/build and broader hardware support still need reproducible validation.

- [x] Graphical interface appears (reported)
- [x] Display works (reported)
- [x] Touchscreen works (reported)
- [x] Wi-Fi works (reported)
- [ ] Internal storage
- [ ] Bluetooth
- [ ] LTE/modem and mobile data
- [ ] Audio
- [ ] Rotation
- [ ] Suspend/resume

See [docs/bring-up-checklist.md](docs/bring-up-checklist.md) and [docs/ROADMAP.md](docs/ROADMAP.md).

## Next priorities

1. Record exact image/build, firmware and installation method.
2. Establish reproducible kernel source, configuration and device tree.
3. Validate remaining hardware features individually.
4. Prepare a reviewable device/kernel package and document limitations.

## Variant warning

Do not confuse `milletlte` (LTE) with `milletwifi` (Wi-Fi). Device trees, kernels, partition layouts and flashing instructions are not interchangeable without verification.

## Safety

Confirm the exact model before device operations and keep a known recovery method available. Do not flash images intended for another Tab 4 variant.

## Licensing

Document license and provenance for every imported file or patch before redistribution or upstream submission.
