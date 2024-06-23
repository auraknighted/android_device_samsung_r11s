TWRP Device configuration for the Samsung Galaxy S23 FE (Exynos)
=========================================

The Samsung Galaxy S23 FE (codenamed _"r11s"_) is a high-end phone that was released in October 2023.

## Device specifications

Basic   | Spec Sheet
-------:|:-------------------------
SoC     | Exynos 2200 (4 nm)
CPU     | Octa-core (1x2.8 GHz Cortex-X2 & 3x2.50 GHz Cortex-A710 & 4x1.8 GHz Cortex-A510)
GPU     | Xclipse 920
Memory  | 128GB 8GB RAM, 256GB 8GB RAM
Shipped Android Version | Android 13, upgradable to Android 14
Battery | Li-Ion 4500 mAh, non-removable
Display | Dynamic AMOLED 2X, 120Hz, HDR10+

## Build
```
source build/envsetup.sh; export ALLOW_MISSING_DEPENDENCIES=true; lunch twrp_r11s-eng; mka recoveryimage
```

## Device picture

![Samsung Galaxy S23 FE](https://images.samsung.com/is/image/samsung/p6pim/mx/feature/164868481/mx-feature--nbsp--538749287?$FB_TYPE_I_JPG$ "Samsung Galaxy S23 FE")
