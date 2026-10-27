# 614B EWOD Firmware Change Log

此文件記錄 614B EWOD Firmware 各版本主要修改內容。

---

## 2026-10-1

### 基本資訊

- Hardware: YXT000614B / YXT000615B
- MCU: STM32H7B0ZBT6
- STM32 HEX: 614B_STM32H7B0ZBT6_EWOD_20260904.hex
- FPGA POF: FPGA_EWOD_V971F.pof
- Version: test-20261001-01 
- Version Type: Test

### 新增功能

- 增加 I2C1 控制 YXT000634A 板功能。
- 增加 UI 指令控制面板上板 8 Zone 開關功能。

### 修改內容

- NA

### 修正問題

- NA

### 測試內容

- [V] Keil Build PASS
- [V] MCU Programming PASS
- [V] UI Command Test PASS
- [V] EWOD Panel Test PASS

### 已知問題

- 其他問題：無

### 備註

TP 8-Zone 功能測試使用，非正式 Release Firmware。
提供CTC工廠測試使用。

---
