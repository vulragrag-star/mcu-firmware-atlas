# TAXONOMY — mcu-firmware-atlas

Sibling of [uefi-firmware-atlas](https://github.com/vulragrag-star/uefi-firmware-atlas). Same closed-loop stages and use-tags.

## Inclusion
Bare-metal MCU/SoC firmware: Cortex-M/RISC-V MCU, CMSIS-SVD, Ghidra/IDA loaders, Unicorn/QEMU machine models, OpenOCD/probe-rs, ESP-IDF as MCU platform.

## Exclusion
Linux kernel, OpenWrt device images, UEFI, full Zephyr app ecosystems as primary (link to rtos atlas).

## Stages
spec | acquire | parse | static_re | emulate_fuzz | runtime_assess | offense_poc | defend_harden | vuln_intel | dataset | paper_map | lab_teaching

## Series
See [uefi docs/SERIES.md](https://github.com/vulragrag-star/uefi-firmware-atlas/blob/main/docs/SERIES.md).
