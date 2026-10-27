# 614B EWOD Firmware Change Log

此文件記錄 614B EWOD Firmware 各版本主要修改內容。

---

## 2026-10-12

### 基本資訊

- Hardware: YXT000614B / YXT000615B
- MCU: STM32H7B0ZBT6
- STM32 HEX: 614B_STM32H7B0ZBT6_EWOD_20261012.hex
- FPGA POF: FPGA_EWOD_V9723.pof
- Version: V0.2.0
- Version Type: release

### 新增功能

- FPGA 整合 array test timing。
- FPGA 增加面板 Hybrid mode 寫入 timing。

### 修改內容

- 增加 ArrayTest1 / ArrayTest2 / ArrayTest3 / ArrayTest4 功能函數。

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
