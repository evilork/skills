# skills

Behavioral specs for Claude Code. Copy any file as `CLAUDE.md` to your project root and Claude will follow these rules in every session.

## Available skills

- [solidity-audit.md](./solidity-audit.md) - paranoid auditor mode for Solidity reviews. Distilled from Immunefi bug bounty work on Diamond proxies, ERC4626 vaults, and stablecoin protocols.

## Usage

```bash
curl -O https://raw.githubusercontent.com/evilork/skills/main/solidity-audit.md
mv solidity-audit.md CLAUDE.md
```

Or include as a sub-skill referenced from your project's main `CLAUDE.md`.

## Coming soon

- `rust-hft.md` - high-frequency trading rules for Rust
- `vless-reality.md` - VLESS Reality VPN deployment and hardening
- `python-async.md` - async Python without footguns

## Contributing

PRs welcome. Each skill file must be a behavioral spec - rules Claude follows - not a tutorial.

---

Maintained by [evilork](https://github.com/evilork).
