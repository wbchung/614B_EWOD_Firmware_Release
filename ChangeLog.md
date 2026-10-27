# 614B EWOD Firmware Change Log

此文件記錄 614B EWOD Firmware 各版本主要修改內容。

---

## 2026-10-1

### 基本資訊

- Hardware: YXT000614B / YXT000615B
- MCU: STM32H7B0ZBT6
- STM32 HEX: 614B_STM32H7B0ZBT6_EWOD_20261007.hex
- FPGA POF: FPGA_EWOD_V971F.pof
- Version: V0.1.1
- Version Type: release

### 新增功能

- Grenade 液珠分離功能函數修改。

### 修改內容

- Grenade 中繼母體多餘液體分離移動時間參數, 由固定改為依 UI 指定時間參數。

### 修正問題

- NA

### 測試內容

- [V] Keil Build PASS
- [V] MCU Programming PASS
- [V] UI Command Test PASS
- [V] EWOD Panel Test PASS

### 已知問題

- 其他問題：NA

### 備註

NA

---
