# MCU tools crawl summary

Generated: 2026-09-10 16:18 CST (Asia/Shanghai)

## Totals
- In-scope catalog entries: **139** (success criterion ≥60)
- Papers: **25** (criterion ≥20)
- Vulns: **12** (criterion ≥10)
- Datasets: **8** (criterion ≥5)
- Stars/last_push/license/language: live `gh api` metadata (**no clones**)
- Seeds: hexsecs/awesome-embedded-security, emproof-com/workshop_firmware_reverse_engineering, frizb/FirmwareReverseEngineering
- Expansion queries: cortex-m reverse, CMSIS-SVD, probe-rs, OpenOCD, ghidra cortex-m, unicorn mcu, ESP-IDF, qemu system arm, MCU firmware fuzz, HALucinator, Fuzzware, pyOCD, Renode, …

## Counts by closed_loop_stage
| stage | count |
|-------|------:|
| spec | 24 |
| acquire | 20 |
| parse | 11 |
| static_re | 12 |
| emulate_fuzz | 21 |
| runtime_assess | 10 |
| offense_poc | 16 |
| defend_harden | 4 |
| vuln_intel | 0 |
| dataset | 5 |
| paper_map | 3 |
| lab_teaching | 13 |
| **total** | **139** |

## Top 15 must-have tools

- **probe-rs** (2932★) — `acquire` — Modern Rust embedded debug/flash toolkit (SWD/JTAG) — https://github.com/probe-rs/probe-rs
- **openocd** (2318★) — `acquire` — Open On-Chip Debugger — https://github.com/openocd-org/openocd
- **pyOCD** (1456★) — `acquire` — Python Cortex-M programming/debug library — https://github.com/pyocd/pyOCD
- **cmsis-svd** (1204★) — `parse` — Python CMSIS-SVD parser and utilities — https://github.com/cmsis-svd/cmsis-svd
- **ghidra** (74728★) — `static_re` — NSA Software Reverse Engineering suite — https://github.com/NationalSecurityAgency/ghidra
- **GhidraSVD** (51★) — `static_re` — Ghidra SVD importer for peripheral registers — https://github.com/antoniovazquezblanco/GhidraSVD
- **unicorn** (9315★) — `emulate_fuzz` — Lightweight multi-arch CPU emulator — https://github.com/unicorn-engine/unicorn
- **renode** (2868★) — `emulate_fuzz` — Antmicro hardware simulation framework — https://github.com/renode/renode
- **fuzzware** (384★) — `emulate_fuzz` — MMIO modeling + coverage-guided Cortex-M firmware fuzzing — https://github.com/fuzzware-fuzzer/fuzzware
- **halucinator** (166★) — `emulate_fuzz` — HAL replacement for MCU firmware re-hosting — https://github.com/embedded-sec/halucinator
- **uEmu** (151★) — `emulate_fuzz` — μEmu peripheral inference + MCU fuzzing — https://github.com/MCUSec/uEmu
- **esp-idf** (18983★) — `spec` — Espressif IoT Development Framework for ESP32-family MCUs — https://github.com/espressif/esp-idf
- **mcuboot** (2098★) — `defend_harden` — Secure bootloader for 32-bit MCUs — https://github.com/mcu-tools/mcuboot
- **qemu** (13698★) — `emulate_fuzz` — QEMU full-system and user emulator — https://github.com/qemu/qemu
- **blackmagic** (3718★) — `acquire` — Black Magic Probe (embedded GDB server) — https://github.com/blackmagic-debug/blackmagic

## Top 15 by stars (in-catalog)

- **ghidra** (74728★) — `static_re` — https://github.com/NationalSecurityAgency/ghidra
- **radare2** (24772★) — `static_re` — https://github.com/radareorg/radare2
- **lvgl** (24652★) — `spec` — https://github.com/lvgl/lvgl
- **micropython** (22054★) — `spec` — https://github.com/micropython/micropython
- **esp-idf** (18983★) — `spec` — https://github.com/espressif/esp-idf
- **flipperzero-firmware** (16565★) — `lab_teaching` — https://github.com/flipperdevices/flipperzero-firmware
- **binwalk** (14328★) — `parse` — https://github.com/ReFirmLabs/binwalk
- **qemu** (13698★) — `emulate_fuzz` — https://github.com/qemu/qemu
- **ESP32Marauder** (12290★) — `offense_poc` — https://github.com/justcallmekoko/ESP32Marauder
- **embassy** (9811★) — `spec` — https://github.com/embassy-rs/embassy
- **platformio-core** (9451★) — `lab_teaching` — https://github.com/platformio/platformio-core
- **unicorn** (9315★) — `emulate_fuzz` — https://github.com/unicorn-engine/unicorn
- **Awesome-Embedded** (9093★) — `paper_map` — https://github.com/nhivp/Awesome-Embedded
- **angr** (9078★) — `static_re` — https://github.com/angr/angr
- **capstone** (9007★) — `static_re` — https://github.com/capstone-engine/capstone

## Exclusion notes (tempting misses)
- `tianocore/edk2` — UEFI — uefi-firmware-atlas
- `LongSoft/UEFITool` — UEFI — uefi-firmware-atlas
- `chipsec/chipsec` — Platform/UEFI — uefi-firmware-atlas
- `firmadyne/firmadyne` — Linux IoT images — iot-firmware-atlas
- `pr0v3rbs/FirmAE` — Linux IoT images — iot-firmware-atlas
- `e-m-b-a/emba` — Embedded Linux firmware analysis — iot-firmware-atlas
- `fkie-cad/FACT_core` — FACT firmware analysis — iot-firmware-atlas
- `ucsb-seclab/karonte` — Embedded Linux inter-binary taint — iot-firmware-atlas
- `NSSL-SJTU/SaTC` — Embedded Linux taint — iot-firmware-atlas
- `zephyrproject-rtos/zephyr` — RTOS primary — rtos-firmware-atlas
- `FreeRTOS/FreeRTOS-Kernel` — RTOS primary — rtos-firmware-atlas
- `apache/nuttx` — RTOS primary — rtos-firmware-atlas
- `RIOT-OS/RIOT` — RTOS primary — rtos-firmware-atlas
- `FirmWire/FirmWire` — Cellular baseband — out of Cortex-M bare-metal focus
- `intel/linux-sgx` — SGX TEE — not bare MCU
- `OWASP/IoTGoat` — RPi/x86 insecure IoT image — iot
- `attify/firmware-analysis-toolkit` — IoT Linux FAT — iot
- `open5gs/open5gs` — 5G core — out
- `EFForg/rayhunter` — IMSI catcher detect — out
- `Samsung/cotopaxi` — IoT protocol suite — iot

## Fringe (included with notes)
Entries with `fringe: true` include Arduino/MicroPython/LVGL/Embassy/Mbed (MCU platforms but not security-first), Flipper/Proxmark/ESP Marauder/Bruce (MCU-hosted offensive gadgets), OpenTitan (silicon RoT), binwalk/unblob/OFRAK (general firmware unpackers), and wireless BT research tooling that rides on MCU controllers.

## Gaps
- **Trusted Firmware-M GitHub mirror unstable** — primary lives on trustedfirmware.org; PSA Arch Tests included, TF-M tree not stably linked via gh.
- **vuln_intel stage empty/thin** — few dedicated MCU CVE trackers (no FwHunt equivalent); mostly paper PoCs + vendor PSIRTs.
- **Public MCU firmware corpora scarce** — paper experiment repos (Fuzzware/uEmu/SAFIREFUZZ) + SVD corpora; few redistributable commercial dumps.
- **Vendor SVD licensing** — cmsis-svd-data useful but per-vendor redistribution constraints remain.
- **Ghidra MCU loaders beyond SVD** — GhidraSVD covered; dedicated Cortex-M loader plugins sparse vs UEFI efiXplorer.
- **QEMU STM32 trees fragmented** — beckus/qemu_stm32 + Espressif/Xilinx forks; no single upstream MCU machine set.
- **Search API rate-limited mid-crawl** — finished via direct `gh api repos/...` enrichment.
- **RTOS overlap** — Zephyr/FreeRTOS/NuttX/RIOT excluded to rtos-firmware-atlas; CMSIS-FreeRTOS/Mbed kept as fringe bridges.
- **Baseband/IoT Linux** — FirmWire/EMBA/FirmAE/KARONTE excluded to other atlases.

## Scope reminders
- **IN**: Bare-metal MCU/SoC (Cortex-M/RISC-V MCU), CMSIS-SVD, Ghidra loaders, Unicorn/QEMU MCU, OpenOCD/probe-rs/pyOCD, ESP-IDF as MCU platform, MCU fuzzers (Fuzzware/P2IM/uEmu/HALucinator/SAFIREFUZZ), MCUboot/wolfBoot, ChipWhisperer/FI.
- **OUT**: Linux kernel, OpenWrt device images, UEFI/BIOS, Zephyr/FreeRTOS-as-primary (see rtos atlas).

## Smoke notes
- Crawl is metadata + curated classification; full in-VM smoke not executed this pass.
- Practical starters: probe-rs or pyOCD + CMSIS-DAP, OpenOCD, Ghidra+GhidraSVD, Renode or Espressif QEMU, Fuzzware docker, MCUboot docs, ChipWhisperer Jupyter.
