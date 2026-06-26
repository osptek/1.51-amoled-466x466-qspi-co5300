# 1.51" 466×466 round AMOLED QSPI module (CO5300) — documentation & samples

**简体中文：** [`README.md`](README.md)

---

> This repository provides **sample projects**, datasheets, specifications, and interface documentation for integration and evaluation.

## Product overview

| Item | Description |
|:--|:--|
| Module | 1.51-inch **round AMOLED** panel, **466×466** resolution |
| Interface | **QSPI** |
| Driver IC | **CO5300** |
| Spec ID | **`1.51-amoled-466x466-qspi-co5300`** is the common product designation in documentation |

---

## Repository layout

### Top-level

| Path | Contents |
|:--|:--|
| `assets/` | Demo screenshots for sample projects (when available) |
| `docs/` | Datasheets, specifications, panel init codes, adapter-board schematics |
| `examples/` | **Sample projects** by category |

### `examples/` layout

| Location | Description (internal folder name) |
|:--|:--|
| `examples/` root | **esp-lvgl-adapter** **LVGL8 / LVGL9** samples (ESP-IDF5 / ESP-IDF6) |
| `with-te/` | **屏幕防撕裂代码** (tear-free / TE-aware samples) |

### Sample project paths

#### Baseline & esp-lvgl-adapter

| Description | Path |
|:--|:--|
| ESP-IDF5 + esp-lvgl-adapter + LVGL8 | `examples/esp32s3-idf5_co5300-qspi_esp-lvgl-adapter_lvgl8/` |
| ESP-IDF5 + esp-lvgl-adapter + LVGL9 | `examples/esp32s3-idf5_co5300-qspi_esp-lvgl-adapter_lvgl9/` |
| ESP-IDF6 + esp-lvgl-adapter + LVGL9 | `examples/esp32s31-idf6_co5300-qspi_esp-lvgl-adapter_lvgl9/` |

#### Tear-free samples (`with-te/`)

| Description | Path |
|:--|:--|
| ESP-IDF5 + LVGL8 + AMOLED, with TE | `examples/with-te/esp32s3-idf5_co5300-qspi_esp-lvgl-adapter_lvgl8_amoled-with-te/` |
| ESP-IDF5 + LVGL9 + AMOLED, with TE | `examples/with-te/esp32s3-idf5_co5300-qspi_esp-lvgl-adapter_lvgl9_amoled-with-te/` |
| ESP-IDF6 + LVGL9 + AMOLED, with TE | `examples/with-te/esp32s31-idf6_co5300-qspi_esp-lvgl-adapter_lvgl9_amoled-with-te/` |
