# WIP Proprietary Vendor Blobs for north korean E12
DO NOT USE THIS THESE VENDOR BLOBS ARE COOKED I AM WORKING ON IT 
This repository contains the extracted proprietary vendor binaries and HALs required to build LineageOS 24 (Android 17) for the **north korean E12** (`E12`).

## Device Specifications
- **Device**: north korean E12
- **SoC**: MediaTek MT6761 (Helio A22)
- **Architecture**: `arm64` (64-bit binder, 32-bit execution support)
- **Stock Android Version**: Android 12 (S)
- **VNDK Version**: 31

## Extraction Details
- **Extraction Method**: `extract-files.sh` using `lineage-18.1` shell-based `extract-utils`
- **Extracted Components**:
  - MediaTek Graphics & Hardware Composer (`hwcomposer.mt6761.so`, `allocator@4.0`)
  - Primary Audio HAL (`audio.primary.mt6761.so`)
  - Telephony & RIL stack (`mtkfusionrild`, `libmtk-ril.so`)
