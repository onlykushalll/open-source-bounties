# Maintainer Bot-Shield v2.1 Release Notes

## Overview
The Maintainer Bot-Shield v2.1 is now available at both standard paths for one-step copy-paste protection against automated PR spam rings.

## What's New
- **Dual Path Deployment**: Available at both **[`.github/workflows/open-source-bot-shield.yml`](../../.github/workflows/open-source-bot-shield.yml)** and **[`templates/open-source-bot-shield.yml`](../../templates/open-source-bot-shield.yml)**
- **Zero-Dependency GitHub Actions Workflow**: Blocks automated bounty-farming and duplicate spam PRs using split-horizon SHA-256 + CI-salted handle verification

## Quick Start
1. Copy either **[`.github/workflows/open-source-bot-shield.yml`](../../.github/workflows/open-source-bot-shield.yml)** or **[`templates/open-source-bot-shield.yml`](../../templates/open-source-bot-shield.yml)** into any repository's `.github/workflows/` folder
2. Commit and push the file
3. The workflow will automatically activate and protect your repository from spam PRs

## Technical Details
- Uses split-horizon SHA-256 verification
- Implements CI-salted handle verification
- Zero-dependency implementation
- Compatible with standard GitHub Actions workflow patterns

## Migration Path
If you're upgrading from v2.0:
1. Replace your existing bot-shield workflow with either the new `.github/workflows/open-source-bot-shield.yml` or `templates/open-source-bot-shield.yml`
2. No configuration changes required - the new version maintains backward compatibility

## Resources
- [Main Bot-Shield Documentation](../../.github/workflows/open-source-bot-shield.yml)
- [Template Version](../../templates/open-source-bot-shield.yml)
- [Full Release Notes](../../UPGRADE_NOTICE.md)