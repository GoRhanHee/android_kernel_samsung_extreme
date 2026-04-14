# GoRhanHee Kernel for Extreme ROM

* A specialized **KernelSU-Next (KSUN)** integrated kernel optimized specifically for Extreme ROM users. This project supports Samsung Exynos 9820 and 990 lineups, with a primary focus on gaming performance and system stability.

## 🚀 Features
* **KernelSU-Next Integration**: Native support for the **latest** kernel-based root solution (KSUN) out of the box.
* **Extreme ROM Optimization**: Tailored system tuning and scheduler adjustments to maximize ROM performance.
* **Gaming Performance**: Prioritizes frame rate stability and thermal management over non-essential features like camera post-processing or high-resolution overhead.
* **CI/CD Automation**: Regular builds via GitHub Actions ensuring the latest kernel upstreaming and security patches.

## ❗ PREREQUISITE

### ⚠️ This kernel is working ONLY for Extreme ROM.

* **Extreme ROM v2.6.1 must be installed** on your device before flashing this kernel.
* Flashing this on other ROMs (Stock, LineageOS, etc.) may lead to bootloops or system instability.

## 📱 Supported Devices

### ⚠️ This kernel doesn't support 🐉 Snapdrangon Devices

| Chipset | Series | Supported Models (Codenames) |
| :--- | :--- | :--- |
| **Exynos 9820** | Galaxy S10 Series | S10e, S10, S10+, S10 5G |
| | Galaxy Note 10 Series | Note 10, Note 10 5G, Note 10+, Note 10+ 5G (Korean) |
| **Exynos 990** | Galaxy S20 Series | S20, S20+, S20 Ultra |
| | Galaxy Note 20 Series | Note 20, Note 20 Ultra |
| | Galaxy S20 FE | S20 FE |


## 🛠 How to Build

This project is cooked to be built automatically using GitHub Actions.

### Using GitHub Actions
1. **Fork** this repository.
2. Navigate to the **Actions** tab and select the `Build ExtremeKRNL` workflow.
3. Click **Run workflow**.
   * You can choose to build for all devices or select a specific branch/chipset.

### Local Build
To build in a local environment :
```bash
./build.sh -m [device_codename] -k Y -r N
```
