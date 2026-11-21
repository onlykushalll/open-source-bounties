# WholeTroutMedia Open-Source Bounties & Maintainer Bot-Shield · Release Notice `v2.1.0`

If you previously cloned **`WholeTroutMedia/open-source-bounties`**, run `git pull origin main` to receive the `v2.1.0` updates:

1. **Free Maintainer Bot-Shield (`v2.1`) Live at Both Standard Paths**:
   - Copy **[`.github/workflows/open-source-bot-shield.yml`](./.github/workflows/open-source-bot-shield.yml)** (or **[`templates/open-source-bot-shield.yml`](./templates/open-source-bot-shield.yml)**) into any repository's `.github/workflows/` folder to automatically block automated bounty-farming and duplicate spam PRs using split-horizon SHA-256 + CI-salted handle verification.
2. **7 Free Zero-Dependency Public Defense Kits (`kits/`) + `STIR + IESCS` Agentic Protocol SDK**:
   - Added **[`kits/stir-iescs-agent-protocol/stir_iescs.py`](./kits/stir-iescs-agent-protocol/stir_iescs.py)** alongside our 6 domain verification kits (`asgi-lifespan-state-shield`, `utf8-sse-boundary-guard`, `graphql-relay-cursor-coalescer`, `sqlalchemy-nested-savepoint-guard`, `go-slice-pointer-merge-guard`, and `zod-iso-offset-validator`).
   - Full standalone SDK also available at **[`WholeTroutMedia/open-source-micro-tools/apps/000-stir-iescs-protocol-sdk`](https://github.com/WholeTroutMedia/open-source-micro-tools/tree/main/apps/000-stir-iescs-protocol-sdk)**.
3. **Unified Single-Home Creative Liberation Engine**:
   - **[`WholeTroutMedia/creative-liberation-engine`](https://github.com/WholeTroutMedia/creative-liberation-engine)** is the sole canonical home for the Creative Liberation Engine and its 7 community gifts.

## Quick Upgrade Commands for Existing Clones
```bash
git fetch --all --tags
git pull origin main
python3 kits/stir-iescs-agent-protocol/stir_iescs.py --json
```

## Domain-Specific Release Notes
For detailed information about each component, see the domain-specific release notes:
- **[Maintainer Bot-Shield v2.1](./by-domain/01-agent-security-and-bot-shield/RELEASE_NOTES_v2.1.0.md)**: Zero-dependency GitHub Actions workflow for PR spam protection
- **[Creative Liberation Engine v2.1.0](./by-domain/06-ai-studio-mcp-and-global-diagnostics/RELEASE_NOTES_v2.1.0.md)**: Unified single-home architecture for the engine and community gifts
- **[STIR + IESCS SDK v2.1.0](./by-domain/03-scientific-materials-bio-and-6g-rf/RELEASE_NOTES_v2.1.0.md)**: Zero-dependency Python implementation of the agentic wire protocol
