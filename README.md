# Android device tree for motorola cyprus64 (cyprus64)

This repository contains the base device tree for the Motorola `cyprus64`, with the goal of preparing an environment to build and test a TWRP recovery for this device.

## Project goal

My goal is to create a functional device tree for this model, organizing the files needed for Android and TWRP, while also adjusting hardware and partition settings as required so the system can boot correctly.

In this project, I am trying to:

- adapt the device tree for the `cyprus64` model;
- align hardware definitions and system mounting;
- prepare the structure needed to compile a TWRP recovery;
- test and fix boot and compatibility issues;
- evolve toward a first working version.

## Current status

This project is still in its early development stage. I am building the base of the device tree and testing compatibility of the required files so that, in the future, it may be possible to obtain a functional build.

This stage requires constant adjustments, testing, and fixes, because any mistake in configuration can prevent the recovery from building or the device from booting correctly.

## Important notice

Warning: until I manage to create a first version that works for boot, I will keep this project in an experimental development state.

In other words, this repository may contain incomplete files, partial adjustments, settings under test, or builds that are not yet stable. The goal is to evolve gradually until a first functional and reliable version is reached.

## How I am working

The idea is to follow a simple process:

1. adjust the device tree for the correct model;
2. validate partition and hardware definitions;
3. compile the recovery in a suitable environment;
4. fix boot and mounting errors;
5. release a first functional version once everything is stable.

# Project Status

## Current state
The project is in the early development phase.

## Recent updates
- the firsts two .img were created but can't boot
- two workflows was successful
- I am working to get the boot


## Important notice
This repository is not yet a stable build. Until a first boot-capable version is achieved, this project remains experimental and may change frequently


# License

```text
#
# Copyright (C) 2026 The Android Open Source Project
# Copyright (C) 2026 SebaUbuntu's TWRP device tree generator
#
# SPDX-License-Identifier: Apache-2.0
