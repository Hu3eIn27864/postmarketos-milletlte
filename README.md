# postmarketOS for Samsung Galaxy Tab 4 8.0 LTE (milletlte)

**Status: porting workspace; functionality not verified.**

This repository is intended for porting postmarketOS to the Samsung Galaxy Tab 4 8.0 LTE, model **SM-T335**, codename **milletlte**.

## Device identity

- Device: Samsung Galaxy Tab 4 8.0 LTE
- Model: SM-T335
- Codename: `milletlte`
- Architecture: ARM 32-bit family; confirm the exact userspace and kernel configuration during bring-up

## Important distinction

Do not confuse `milletlte` (LTE) with `milletwifi` (Wi-Fi). Device trees, kernels, partition layouts, and flashing instructions are not automatically interchangeable between variants.

An Android/LineageOS device tree is useful reference material, but it is not by itself a postmarketOS port. No successful postmarketOS boot or hardware validation is claimed here.

## Planned work

- Record exact hardware and firmware details for the SM-T335.
- Establish the correct kernel source, configuration and device tree.
- Create postmarketOS device and kernel packages.
- Verify the boot and flashing method for this exact variant.
- Test display, touch, storage, Wi-Fi, LTE/modem, audio and suspend individually.

## Safety

Do not flash images or partition layouts intended for another Tab 4 variant. Confirm the exact model number before any device operation, and keep a known recovery method available.

## Reference

An Android device-tree repository for the LTE variant may be useful for research:
https://github.com/milletwifi/android_device_samsung_milletlte

It is a reference source, not proof that a working postmarketOS port exists.

## License

Document the license and provenance of every imported file or patch before redistribution or upstream submission.
