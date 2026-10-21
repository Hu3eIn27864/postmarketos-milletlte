# postmarketOS for Samsung Galaxy Tab 4 8.0 LTE (milletlte)

**Status: experimentally booted; partial hardware functionality confirmed by user testing.**

This repository is intended for porting postmarketOS to the Samsung Galaxy Tab 4 8.0 LTE, model **SM-T335**, codename **milletlte**.

## Device identity

- Device: Samsung Galaxy Tab 4 8.0 LTE
- Model: SM-T335
- Codename: `milletlte`
- Architecture: ARM 32-bit family; confirm the exact userspace and kernel configuration during bring-up

## Important distinction

Do not confuse `milletlte` (LTE) with `milletwifi` (Wi-Fi). Device trees, kernels, partition layouts, and flashing instructions are not automatically interchangeable between variants.

An Android/LineageOS device tree is useful reference material, but it is not by itself a postmarketOS port. The user reports that postmarketOS reaches the graphical interface on their Galaxy Tab 4 LTE and that the display, touchscreen and Wi-Fi work. This is an initial, user-reported test result; the image/build details and broader hardware support have not yet been independently verified.

## Current test status

Reported on 2026-10-21 by the device tester:

- [x] Graphical interface appears
- [x] Display works
- [x] Touchscreen works
- [x] Wi-Fi works
- [ ] Internal storage — not yet confirmed
- [ ] Bluetooth — not yet confirmed
- [ ] LTE/modem and mobile data — not yet confirmed
- [ ] Audio — not yet confirmed
- [ ] Rotation — not yet confirmed
- [ ] Suspend/resume — not yet confirmed

See [the bring-up checklist](docs/bring-up-checklist.md) for remaining validation. The report confirms partial functionality, not that every feature works or that the port is ready for general use.

## Next steps

- Record the exact image/build, firmware and installation method used.
- Establish and document the kernel source, configuration and device tree.
- Keep the device package and kernel package reproducible.
- Test storage, Bluetooth, LTE/modem, audio, rotation and suspend/resume individually.

## Safety

Do not flash images or partition layouts intended for another Tab 4 variant. Confirm the exact model number before any device operation, and keep a known recovery method available.

## Reference

An Android device-tree repository for the LTE variant may be useful for research:
https://github.com/milletwifi/android_device_samsung_milletlte

It is a reference source, not proof that a working postmarketOS port exists.

## License

Document the license and provenance of every imported file or patch before redistribution or upstream submission.
