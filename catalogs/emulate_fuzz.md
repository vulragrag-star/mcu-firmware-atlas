# emulate_fuzz

_37 entries_

- **[qemu](https://github.com/qemu/qemu)** ★13698 — QEMU full-system and user emulator  
  tags: `lab-usable, reference-impl`  
  smoke: qemu-system-arm

- **[unicorn](https://github.com/unicorn-engine/unicorn)** ★9315 — CPU emulator framework (MCU RE friendly).  
  tags: `lab-usable, paper-repro`  
  smoke: Python bindings

- **[AFLplusplus](https://github.com/AFLplusplus/AFLplusplus)** ★6750 — AFL++ coverage-guided fuzzer (QEMU/Unicorn modes)  
  tags: `lab-usable, paper-repro`  
  smoke: Unicorn/QEMU mode

- **[qiling](https://github.com/qilingframework/qiling)** ★6094 — Advanced binary emulation framework  
  tags: `lab-usable, paper-repro`  
  smoke: Hooks needed

- **[honggfuzz](https://github.com/google/honggfuzz)** ★3381 — Feedback-driven fuzzer with hardware coverage  
  tags: `lab-usable`  
  smoke: Linux host

- **[renode](https://github.com/renode/renode)** ★2868 — Antmicro hardware simulation framework  
  tags: `lab-usable, paper-repro, daily-ops`  
  smoke: Renode scripts

- **[panda](https://github.com/panda-re/panda)** ★2780 — Platform for Architecture-Neutral Dynamic Analysis  
  tags: `paper-repro`  
  smoke: QEMU-based

- **[avatar2](https://github.com/avatartwo/avatar2)** ★576 — Orchestrate emulation with real MCU hardware  
  tags: `paper-repro, lab-usable, hw-required`  
  smoke: Probe + QEMU/Unicorn

- **[qemu_stm32](https://github.com/beckus/qemu_stm32)** ★557 — QEMU STM32 machine models  
  tags: `lab-usable, paper-repro`  
  smoke: Build fork

- **[fuzzware](https://github.com/fuzzware-fuzzer/fuzzware)** ★384 — MMIO modeling + coverage-guided Cortex-M firmware fuzzing  
  tags: `paper-repro, lab-usable`  
  smoke: Docker experiments

- **[qemu](https://github.com/espressif/qemu)** ★350 — Espressif QEMU fork for ESP chips  
  tags: `lab-usable, reference-impl`  
  smoke: esp-idf qemu target

- **[icicle-emu](https://github.com/icicle-emu/icicle-emu)** ★310 — Rust grey-box fuzzer/emulator (MSP430/RISC-V)  
  tags: `paper-repro, lab-usable`  
  smoke: Rust toolchain

- **[qemu](https://github.com/Xilinx/qemu)** ★300 — Xilinx QEMU fork for SoC/FPGA platforms  
  tags: `lab-usable`  
  smoke: Vendor machines

- **[gdbfuzz](https://github.com/boschresearch/gdbfuzz)** ★196 — GDB hardware-breakpoint coverage fuzzer for MCUs  
  tags: `paper-repro, hw-required`  
  smoke: GDB-debuggable target; archived

- **[halucinator](https://github.com/embedded-sec/halucinator)** ★166 — HAL replacement for MCU firmware re-hosting  
  tags: `paper-repro, lab-usable`  
  smoke: Python + QEMU/avatar

- **[uEmu](https://github.com/MCUSec/uEmu)** ★151 — μEmu peripheral inference + MCU fuzzing  
  tags: `paper-repro, lab-usable`  
  smoke: QEMU/AFL setup

- **[p2im](https://github.com/RiS3-Lab/p2im)** ★148 — P2IM processor-peripheral interface modeling  
  tags: `paper-repro, lab-usable`  
  smoke: QEMU based

- **[SAFIREFUZZ](https://github.com/pr0me/SAFIREFUZZ)** ★130 — Dynamic binary rewriting to fuzz Cortex-M as Linux process  
  tags: `paper-repro, lab-usable`  
  smoke: ARM host preferred

- **[Pretender](https://github.com/ucsb-seclab/pretender)** ★89 — Automatic modeling of hardware to enable the rehosting of embedded firmware  
  tags: `paper-repro, lab-usable`  
  smoke: None

- **[Hoedur](https://github.com/fuzzware-fuzzer/hoedur)** ★73 — multi-stream MCU firmware fuzzing (Fuzzware lineage); currently only in rtos atlas; present_in_other_atlas={"rtos-firmware-atlas": [["hoedur", "https://github.c  
  tags: `paper-repro, lab-usable`  
  smoke: None

- **[DICE-DMA-Emulation](https://github.com/RiS3-Lab/DICE-DMA-Emulation)** ★67 — DICE: DMA channel identification/emulation for MCU fuzz  
  tags: `paper-repro`  
  smoke: Research prototype

- **[halucinator](https://github.com/halucinator/halucinator)** ★59 — HALucinator main/maintenance branch  
  tags: `paper-repro`  
  smoke: See docs

- **[Jetset](https://github.com/aerosec/jetset)** ★57 — Jetset from survey gap-fill  
  tags: `paper-repro, lab-usable`  
  smoke: None

- **[microAFL](https://github.com/MCUSec/microAFL)** ★48 — μAFL hardware-in-the-loop fuzzer via ARM ETM  
  tags: `paper-repro, hw-required`  
  smoke: ETM-capable board

- **[SEmu](https://github.com/MCUSec/SEmu)** ★45 — A Specification-Guided Approach for Firmware Emulation  
  tags: `paper-repro, lab-usable`  
  smoke: None

- **[MultiFuzz](https://github.com/MultiFuzz/MultiFuzz)** ★44 — MultiFuzz — multi-stream fuzzer for monolithic MCU firmware (USENIX Sec 2024).  
  tags: `paper-repro, lab-usable`  
  smoke: Rust fuzzer; config.yml; lab-usable with samples.

- **[AIM](https://github.com/bofeng17/AIM-Interrupt-Modeling)** ★33 — present_in_other_atlas={"iot-firmware-atlas": [["FirmAE-pro", "https://github.com/Blackhole23-Lab/FirmAE-pro"]]}  
  tags: `paper-repro, lab-usable`  
  smoke: None

- **[µSBS](https://github.com/pwnforce/uSBS)** ★33 — μSBS: Static Binary Sanitization of Bare-metal Embedded Devices  
  tags: `paper-repro, lab-usable`  
  smoke: None

- **[Perry](https://github.com/perry-emu/perry)** ★32 — Perry: automated peripheral modeling with symbolic execution  
  tags: `paper-repro, lab-usable`  
  smoke: None

- **[Laelaps](https://github.com/dongmu/Laelaps)** ★27 — Laelaps from survey gap-fill  
  tags: `paper-repro, lab-usable`  
  smoke: None

- **[SplITS](https://github.com/SplITS-Fuzzer/SplITS)** ★21 — SplITS from survey gap-fill  
  tags: `paper-repro, lab-usable`  
  smoke: None

- **[AutoMap](https://github.com/OSUSecLab/AutoMap)** ★11 — AutoMap from survey gap-fill  
  tags: `paper-repro, lab-usable`  
  smoke: None

- **[Ember-IO-Fuzzing](https://github.com/Ember-IO/Ember-IO-Fuzzing)** ★11 — Ember-IO — model-free cached MMIO fuzzing for embedded firmware.  
  tags: `paper-repro, lab-usable`  
  smoke: AFL++-QEMU based; research setup.

- **[Gerbil](https://github.com/daumbrella/Gerbil)** ★8 — A firmware analysis tool for lightweight IoT firmware  
  tags: `paper-repro, lab-usable`  
  smoke: None

- **[Conware](https://github.com/ucsb-seclab/conware)** ★6 — Framework for automatically modeling hardware peripherals.  
  tags: `paper-repro, lab-usable`  
  smoke: None

- **[FIDO](https://github.com/IoTS-P/FIDO)** ★4 — FIDO — on-demand input delivery to boost firmware fuzzing (S&P 2026).  
  tags: `paper-repro`  
  smoke: Research harness; check docs.

- **[Avatar2 (index)](https://github.com/search?q=avatar2+firmware+orchestration)** ★? — Avatar2 dynamic firmware analysis orchestration (index; org path unstable in search).  
  tags: `paper-repro, lab-usable`  
  smoke: INDEX ONLY — pin canonical org/repo on next refresh.
