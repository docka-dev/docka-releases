# Docka Releases

Official binary releases for [Docka](https://docka.dev) - Self-hosted cloud management platform.

## Quick Install

### Linux / macOS

```bash
curl -fsSL https://get.docka.dev | bash
```

### Package Managers

```bash
# Homebrew (macOS/Linux)
brew install docka-dev/tap/docka

# APT (Debian/Ubuntu)
curl -fsSL https://get.docka.dev | bash

# Scoop (Windows)
scoop bucket add docka https://github.com/docka-dev/scoop-docka
scoop install docka
```

## Direct Downloads

| Platform | Architecture | Download |
|----------|-------------|----------|
| Linux | amd64 | [docka-linux-amd64.tar.gz](https://github.com/docka-dev/docka-releases/releases/latest/download/docka-linux-amd64.tar.gz) |
| Linux | arm64 | [docka-linux-arm64.tar.gz](https://github.com/docka-dev/docka-releases/releases/latest/download/docka-linux-arm64.tar.gz) |
| macOS | Apple Silicon | [docka-darwin-arm64.tar.gz](https://github.com/docka-dev/docka-releases/releases/latest/download/docka-darwin-arm64.tar.gz) |
| macOS | Intel | [docka-darwin-amd64.tar.gz](https://github.com/docka-dev/docka-releases/releases/latest/download/docka-darwin-amd64.tar.gz) |
| Windows | x64 | [docka-windows-amd64.zip](https://github.com/docka-dev/docka-releases/releases/latest/download/docka-windows-amd64.zip) |
| Windows | ARM64 | [docka-windows-arm64.zip](https://github.com/docka-dev/docka-releases/releases/latest/download/docka-windows-arm64.zip) |

## Distributed Edition

This repository contains the **distributed edition** of Docka with:

- **docka** - CLI tool for managing Docka
- **docka-server** - Self-hosted server component
- **docka-agent** - Agent for managed servers

### Included Features

- Server management
- App deployments
- Database management
- Core infrastructure features

For the full SaaS platform with team collaboration, billing, and premium features, visit [docka.dev](https://docka.dev).

## Repository Structure

This repository contains SHA256 checksums for release verification:

```
v0.0.1/SHA256SUMS.txt
v0.0.2/SHA256SUMS.txt
v0.0.3/SHA256SUMS.txt
v0.0.4/SHA256SUMS.txt
v0.0.5/SHA256SUMS.txt
v0.0.6/SHA256SUMS.txt
```

Binary releases are available from the [Releases](https://github.com/docka-dev/docka-releases/releases) page.

## Verify Downloads

```bash
# Download the checksum file for your version
curl -fsSL https://github.com/docka-dev/docka-releases/releases/download/v0.0.6/SHA256SUMS.txt -o SHA256SUMS.txt

# Verify downloaded binary
sha256sum -c SHA256SUMS.txt --ignore-missing
```

## Documentation

- [Getting Started](https://docka.dev/docs)
- [Installation Guide](https://docka.dev/docs/installation)
- [Configuration](https://docka.dev/docs/configuration)

## License

See [LICENSE](LICENSE) for details.
