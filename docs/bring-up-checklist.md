# milletlte bring-up checklist

Target: Samsung Galaxy Tab 4 8.0 LTE, SM-T335.

This is a planning checklist, not a claim that any step has passed.

## Before packaging

- [ ] Confirm the tablet reports model SM-T335.
- [ ] Record Android firmware build and bootloader revision.
- [ ] Back up stock boot and recovery images; keep them private.
- [ ] Record PIT partition names and sizes without writing to the device.
- [ ] Identify a kernel source tree that matches the device/firmware.
- [ ] Identify the correct device tree and panel/touch configuration.
- [ ] Determine the supported postmarketOS flashing method for this exact model.

## postmarketOS package work

- [ ] Create a device package with accurate `deviceinfo` values.
- [ ] Create a kernel package with a reproducible configuration.
- [ ] Verify initramfs and root filesystem compatibility.
- [ ] Build packages in a clean pmbootstrap environment.
- [ ] Review package licensing and provenance.

## Hardware validation

- [ ] Boot and capture logs.
- [ ] Display and brightness
- [ ] Touchscreen and rotation
- [ ] Internal storage and partition mounting
- [ ] Wi-Fi and Bluetooth
- [ ] LTE modem, SIM detection and mobile data
- [ ] Audio, microphones and speakers
- [ ] Cameras
- [ ] Battery, charging and suspend/resume

## Variant warning

Do not copy device settings from `milletwifi` or another Galaxy Tab 4 model without checking the differences. LTE and Wi-Fi variants can differ in kernel configuration, device tree, partitions and firmware.
