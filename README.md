# mcu-firmware-atlas

Living map of **bare-metal MCU/SoC firmware** RE & tooling — SVD, probes, emulators — closed-loop taxonomy.

Sibling of [`uefi-firmware-atlas`](https://github.com/vulragrag-star/uefi-firmware-atlas) / [`oss-atlas`](https://github.com/vulragrag-star/oss-atlas).

## Why another list?
We first survey existing awesome/index repos (see `data/seeds/SOURCES.md`), then build a **machine-readable closed-loop atlas** that those lists are not: JSONL schema, use-tags, setting book, smoke notes, explicit domain fences.

## Inclusion / exclusion
- **IN:** Bare-metal MCU/SoC firmware: Cortex-M/RISC-V MCU, CMSIS-SVD, Ghidra/IDA loaders, Unicorn/QEMU machine models, OpenOCD/probe-rs, ESP-IDF as MCU platform.
- **OUT:** Linux kernel, OpenWrt device images, UEFI, full Zephyr app ecosystems as primary (link to rtos atlas).

## Closed-loop map
See [`docs/MAP.md`](docs/MAP.md), [`docs/TAXONOMY.md`](docs/TAXONOMY.md), [`docs/SETTING.md`](docs/SETTING.md), [`docs/SMOKE.md`](docs/SMOKE.md).

## Status (crawl merge 2026-09-10)
- Tools: **139** (fringe flagged: **35**)
- Papers / vulns / datasets: **25** / **12** / **8**
- Seeds first: hexsecs / emproof workshop / … — `data/seeds/SOURCES.md` · `docs/CRAWL_SUMMARY.md`
- Known gap: `vuln_intel` thin (no MCU FwHunt analog)

### Tool counts by stage

| Stage | n |
|---|---|
| acquire | 20 |
| dataset | 5 |
| defend_harden | 4 |
| emulate_fuzz | 21 |
| lab_teaching | 13 |
| offense_poc | 16 |
| paper_map | 3 |
| parse | 11 |
| runtime_assess | 10 |
| spec | 24 |
| static_re | 12 |
| **total** | **139** |


## Quick start
```bash
python scripts/validate_catalog.py
python scripts/render_catalogs.py
```

## License
Docs: CC BY 4.0. Scripts: MIT. Upstream projects keep their licenses.
