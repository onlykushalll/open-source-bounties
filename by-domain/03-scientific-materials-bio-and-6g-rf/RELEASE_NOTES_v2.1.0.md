# STIR + IESCS SDK v2.1.0 Release Notes

## Overview
The runnable STIR + IESCS Agentic Wire Protocol & Plain-English Receipt SDK is now available across multiple repositories with zero-dependency Python stdlib implementation.

## What's New
- **Zero-Dependency Implementation**: Complete Python stdlib implementation of STIR-1.0 and IESCS
- **STIR-1.0**: Strong Three-Valued Kleene Logic `{-1, 0, +1}` with Base-27 trit glyphs and Castagnoli CRC32C wire framing
- **IESCS**: Compact `&domain:op{...}` call-words that automatically expand into plain-English audit receipts
- **Rosetta Handshake**: `X-Inception-Rosetta-Upgrade: STIR-IESCS/1.0`

## Available Locations
1. **[`WholeTroutMedia/open-source-micro-tools/apps/000-stir-iescs-protocol-sdk/engine.py`](https://github.com/WholeTroutMedia/open-source-micro-tools/blob/main/apps/000-stir-iescs-protocol-sdk/engine.py)**
2. **[`WholeTroutMedia/creative-liberation-engine/gifts/stir_iescs_rosetta_doctor.py`](https://github.com/WholeTroutMedia/creative-liberation-engine/blob/main/gifts/stir_iescs_rosetta_doctor.py)** (run with: `./bin/cle gifts --run stir-iescs-rosetta-doctor`)
3. **[`WholeTroutMedia/open-source-bounties/kits/stir-iescs-agent-protocol/stir_iescs.py`](https://github.com/WholeTroutMedia/open-source-bounties/blob/main/kits/stir-iescs-agent-protocol/stir_iescs.py)**
4. **[`WholeTroutMedia/oss-verification-sandbox/stir_iescs.py`](https://github.com/WholeTroutMedia/oss-verification-sandbox/blob/main/stir_iescs.py)** (run with: `python3 stir_iescs.py --self-test`)

## Quick Start
1. Update your local clone:
   ```bash
   git fetch --all --tags
   git pull origin main
   ```
2. Run the SDK:
   ```bash
   python3 kits/stir-iescs-agent-protocol/stir_iescs.py --json
   ```
3. For self-testing:
   ```bash
   python3 kits/stir-iescs-agent-protocol/stir_iescs.py --self-test
   ```

## Migration Path
### For Existing Users
1. If you were using the legacy SDK location, update to one of the new canonical locations
2. Update any import statements to reflect the new module structure
3. Continue using the same API - the interface remains backward compatible

### For New Users
1. Choose the appropriate SDK location based on your use case:
   - Agent Protocol: Use **[`kits/stir-iescs-agent-protocol/stir_iescs.py`](../../kits/stir-iescs-agent-protocol/stir_iescs.py)**
   - Standalone Engine: Use **[`WholeTroutMedia/open-source-micro-tools/apps/000-stir-iescs-protocol-sdk/engine.py`](https://github.com/WholeTroutMedia/open-source-micro-tools/blob/main/apps/000-stir-iescs-protocol-sdk/engine.py)**
   - Creative Liberation Gift: Use **[`WholeTroutMedia/creative-liberation-engine/gifts/stir_iescs_rosetta_doctor.py`](https://github.com/WholeTroutMedia/creative-liberation-engine/blob/main/gifts/stir_iescs_rosetta_doctor.py)**

## Technical Details
- **STIR-1.0**: Implements Strong Three-Valued Kleene Logic with `{-1, 0, +1}` values
- **Base-27 Trit Glyphs**: Uses `A-Z` + `_` for encoding
- **Castagnoli CRC32C**: Wire framing with error detection
- **IESCS**: Compiles structured verification gates into compact call-words
- **Plain-English Receipts**: Automatic expansion for human review

## Resources
- [STIR + IESCS Agent Protocol Kit](../../kits/stir-iescs-agent-protocol/README.md)
- [Full Release Notes](../../UPGRADE_NOTICE.md)
- [STIR + IESCS Standard](../../RFC-0001_STIR_IESCS_STANDARD.md)