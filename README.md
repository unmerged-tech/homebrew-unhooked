<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/logo-dark.svg">
  <img src="assets/logo.svg" alt="unhooked" width="320">
</picture>

### Homebrew tap for `hx` — the unhooked harness CLI

[![License](https://img.shields.io/badge/license-Apache--2.0-blue.svg)](https://www.apache.org/licenses/LICENSE-2.0)
![Platforms](https://img.shields.io/badge/platforms-macOS%20%7C%20Linux-informational)
![Homebrew](https://img.shields.io/badge/homebrew-tap-orange)

</div>

---

## Install

```bash
brew install unmerged-tech/unhooked/unhooked
```

Or tap once, then install by name:

```bash
brew tap unmerged-tech/unhooked
brew install unhooked
```

Check it works:

```bash
hx --version
hx doctor
```

## Update

```bash
brew update && brew upgrade unhooked
```

## Uninstall

```bash
brew uninstall unhooked
brew untap unmerged-tech/unhooked
```

## First steps

```bash
cd your-project
hx init        # install the harness into .agents/ and manage AGENTS.md
hx doctor      # verify the setup, with an exact fix for every failing check
```

## Other ways to install

| Channel | Command |
| --- | --- |
| Install script | `curl -fsSL https://github.com/unmerged-tech/unhooked/releases/latest/download/install.sh \| sh` |
| Cargo | `cargo install unhooked` |
| Binaries | [GitHub Releases](https://github.com/unmerged-tech/unhooked/releases) — macOS, Linux (glibc and musl), Windows, with `SHA256SUMS` |

## About this tap

`Formula/unhooked.rb` is generated and pushed automatically by the unhooked release workflow for every tagged release, with checksums for each prebuilt binary. Please don't edit it by hand — open issues and pull requests in the [main repository](https://github.com/unmerged-tech/unhooked).

## License

Apache-2.0
