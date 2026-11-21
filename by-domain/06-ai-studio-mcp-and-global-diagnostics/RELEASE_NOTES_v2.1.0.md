# Creative Liberation Engine v2.1.0 Release Notes

## Overview
The Creative Liberation Engine has been unified under a single-home architecture, consolidating all community gifts and core functionality into one canonical repository.

## What's New
- **Unified Single-Home Architecture**: **[`WholeTroutMedia/creative-liberation-engine`](https://github.com/WholeTroutMedia/creative-liberation-engine)** is now the sole canonical repository for the Creative Liberation Engine and its 7 standalone Python stdlib community gifts (`gifts/`)
- **Retired Legacy Duplicate**: The legacy duplicate seed folder (`apps/000-cle-foundation-seed-os`) inside `WholeTroutMedia/open-source-micro-tools` has been retired
- **New SDK Location**: Replaced by **[`apps/000-stir-iescs-protocol-sdk`](https://github.com/WholeTroutMedia/open-source-micro-tools/tree/main/apps/000-stir-iescs-protocol-sdk)**

## Quick Start
1. Update your local clone:
   ```bash
   git fetch --all --tags
   git pull origin main
   ```
2. Access the Creative Liberation Engine at: **[`WholeTroutMedia/creative-liberation-engine`](https://github.com/WholeTroutMedia/creative-liberation-engine)**
3. Run community gifts using:
   ```bash
   ./bin/cle gifts --run <gift-name>
   ```

## Migration Path
### For Existing Users
1. If you previously cloned from `WholeTroutMedia/open-source-micro-tools/apps/000-cle-foundation-seed-os`, update to the new canonical location
2. Update any local references to point to the unified repository
3. Continue using the same gift commands with the updated path

### For New Users
1. Clone directly from **[`WholeTroutMedia/creative-liberation-engine`](https://github.com/WholeTroutMedia/creative-liberation-engine)**
2. Follow the standard setup instructions in the repository

## Technical Details
- **Canonical Repository**: Single source of truth for all Creative Liberation Engine components
- **Community Gifts**: 7 standalone Python stdlib implementations available in the `gifts/` directory
- **Backward Compatibility**: Existing gift functionality remains unchanged
- **Enhanced Discovery**: Unified structure makes it easier to find and use community gifts

## Resources
- [Creative Liberation Engine Repository](https://github.com/WholeTroutMedia/creative-liberation-engine)
- [Community Gifts Documentation](https://github.com/WholeTroutMedia/creative-liberation-engine/tree/main/gifts)
- [Full Release Notes](../../UPGRADE_NOTICE.md)