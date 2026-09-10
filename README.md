# kube-linter

[中文版本](./README.cn.md)

KubeLinter is a static analysis tool that checks Kubernetes YAML files and Helm charts to ensure the applications represented in them adhere to best practices.

![kube-linter](https://repo.x-cmd.io/kube-linter.svg)

## Install

```sh
x install kube-linter
```

## Source

- **Upstream**: <https://github.com/stackrox/kube-linter>
- **Homepage**: <https://docs.kubelinter.io/>
- **License**: Apache-2.0

## Release

- **Latest**: `v0.8.3` (2026-03-10)
- **Last commit**: 2026-09-09
- **Assets in release**: 18

## Release assets

| Asset | Size | Target |
|-------|-----:|--------|
| [kube-linter-darwin](https://github.com/stackrox/kube-linter/releases/download/v0.8.3/kube-linter-darwin) | 48.2 MiB | `native/darwin/x64` |
| [kube-linter-darwin.sigstore.json](https://github.com/stackrox/kube-linter/releases/download/v0.8.3/kube-linter-darwin.sigstore.json) | 3.7 KiB | `native/darwin/x64` |
| [kube-linter-darwin.tar.gz](https://github.com/stackrox/kube-linter/releases/download/v0.8.3/kube-linter-darwin.tar.gz) | 16.0 MiB | `native/darwin/x64` |
| [kube-linter-darwin_arm64](https://github.com/stackrox/kube-linter/releases/download/v0.8.3/kube-linter-darwin_arm64) | 45.5 MiB | `native/darwin/arm64` |
| [kube-linter-darwin_arm64.sigstore.json](https://github.com/stackrox/kube-linter/releases/download/v0.8.3/kube-linter-darwin_arm64.sigstore.json) | 3.6 KiB | `native/darwin/arm64` |
| [kube-linter-darwin_arm64.tar.gz](https://github.com/stackrox/kube-linter/releases/download/v0.8.3/kube-linter-darwin_arm64.tar.gz) | 14.5 MiB | `native/darwin/arm64` |
| [kube-linter-linux](https://github.com/stackrox/kube-linter/releases/download/v0.8.3/kube-linter-linux) | 47.1 MiB | `other` |
| [kube-linter-linux.sigstore.json](https://github.com/stackrox/kube-linter/releases/download/v0.8.3/kube-linter-linux.sigstore.json) | 3.7 KiB | `other` |
| [kube-linter-linux.tar.gz](https://github.com/stackrox/kube-linter/releases/download/v0.8.3/kube-linter-linux.tar.gz) | 15.7 MiB | `native/unknown` |
| [kube-linter-linux_arm64](https://github.com/stackrox/kube-linter/releases/download/v0.8.3/kube-linter-linux_arm64) | 44.2 MiB | `native/linux/arm64` |
| [kube-linter-linux_arm64.sigstore.json](https://github.com/stackrox/kube-linter/releases/download/v0.8.3/kube-linter-linux_arm64.sigstore.json) | 3.6 KiB | `native/linux/arm64` |
| [kube-linter-linux_arm64.tar.gz](https://github.com/stackrox/kube-linter/releases/download/v0.8.3/kube-linter-linux_arm64.tar.gz) | 13.9 MiB | `native/linux/arm64` |
| [kube-linter-windows.tar.gz](https://github.com/stackrox/kube-linter/releases/download/v0.8.3/kube-linter-windows.tar.gz) | 16.1 MiB | `native/win/x64` |
| [kube-linter-windows_arm64.tar.gz](https://github.com/stackrox/kube-linter/releases/download/v0.8.3/kube-linter-windows_arm64.tar.gz) | 14.0 MiB | `native/win/arm64` |
| [kube-linter.exe](https://github.com/stackrox/kube-linter/releases/download/v0.8.3/kube-linter.exe) | 48.3 MiB | `other` |
| [kube-linter.exe.sigstore.json](https://github.com/stackrox/kube-linter/releases/download/v0.8.3/kube-linter.exe.sigstore.json) | 3.8 KiB | `other` |
| [kube-linter_arm64.exe](https://github.com/stackrox/kube-linter/releases/download/v0.8.3/kube-linter_arm64.exe) | 44.7 MiB | `other` |
| [kube-linter_arm64.exe.sigstore.json](https://github.com/stackrox/kube-linter/releases/download/v0.8.3/kube-linter_arm64.exe.sigstore.json) | 3.7 KiB | `other` |

## Popularity

- **Stars**: 3,504 · **Forks**: 275 · **Open issues**: 252 · **Contributors**: 96

## Totals (cumulative)

- **Releases**: 41 · **Merged PRs**: 854 · **Open PRs**: 14 · **Closed issues**: 171 · **Open issues**: 81 · **Commits**: 867

## Recent activity

| Window | Since | Releases | Merged PRs | Open PRs | Closed issues | Open issues | Commits |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-11 | 0 | 12 | 4 | 1 | 5 | 11 |
| 90d | 2026-06-12 | 0 | 34 | 12 | 1 | 6 | 39 |
| 360d | 2025-09-15 | 3 | 177 | 14 | 8 | 16 | 173 |

## Code size

Total: **42,787** lines of code across **561** files in the top 5 languages.

| Language | Code | Comments | Blanks | Files |
|----------|-----:|---------:|-------:|------:|
| Go | 21,403 | 2,014 | 3,045 | 377 |
| Json | 14,523 | 0 | 0 | 3 |
| Yaml | 5,626 | 95 | 35 | 178 |
| Sh | 955 | 13 | 294 | 2 |
| Css | 113 | 8 | 19 | 1 |

## OpenSSF Scorecard

Overall score: **7.4 / 10**

Lowest-scoring checks:

- **Token-Permissions** (0/10) — detected GitHub workflow tokens with excessive permissions
- **CII-Best-Practices** (0/10) — no effort to earn an OpenSSF best practices badge detected
- **Pinned-Dependencies** (2/10) — dependency not pinned by hash detected -- score normalized to 2

## Improve this data

Install metadata for kube-linter lives in the [x-cmd/install](https://github.com/x-cmd/install) index — a curated YAML package list that x-cmd consumes at install time. If `kube-linter` is missing, out of date, or installs incorrectly, please open an issue or PR there:

- **Open an issue**: <https://github.com/x-cmd/install/issues/new>
- **Edit the package entry**: <https://github.com/x-cmd/install/edit/main/kube-linter.yml> (or whichever path the index uses)

The data on this page (card / loc / scorecard / release) is auto-collected by [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) and is regenerated daily. Improvements to *install behaviour* (which version gets installed, platform-specific quirks, dependencies) belong upstream in the index.

_Snapshot: `data/card/260910.yml` · 2026-09-10T16:50:07Z._
