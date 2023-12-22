# overlay-rpi5-openfyde

## Introduction
Same as Chromium OS, openFyde adopts the [Portage build and packaging system](https://wiki.gentoo.org/wiki/Portage) from Gentoo Linux. openFyde uses Portage with certain customisations to support building multiple targets (bootable OS system images) across different hardware architectures from a shared set of sources.

A **board** defines a target type, it can be either for a family of hardware devices or specifically for one type of device. For example, The board `amd64-openfyde` is a target type for an openFyde system image that aims to run on most recent PCs with amd64(x86_64) architecture; whilst the `rpi5-openfyde` board is a target type specifically for the infamous single-board computer [Raspberry Pi 5](https://www.raspberrypi.com/products/raspberry-pi-5/). We usually append `-openfyde` to the board name in openFyde to differentiate between its siblings for FydeOS. 

Each board has a corresponding **overlay** that defines the configuration for it. This includes details like CPU architecture, kernel configuration, as well as additional packages and USE flags.

<br>

## About the board `rpi5-openfyde`
This board specifically targets: 

- [Raspberry Pi 5](https://www.raspberrypi.com/products/raspberry-pi-5/):

 `rpi5-openfyde` is the foundation for [FydeOS for You - Raspberry Pi 5](https://fydeos.io/download/device/rpi5-fydeos) release.

<br>

###### Copyright (c) 2023 Fyde Innovations and the openFyde Authors. Distributed under the license specified in the root directory of this repository.
