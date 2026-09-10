# kube-linter

[English version](./README.md)

KubeLinter is a static analysis tool that checks Kubernetes YAML files and Helm charts to ensure the applications represented in them adhere to best practices.

![kube-linter](https://repo.x-cmd.io/kube-linter.svg?lang=zh)

## 安装

```sh
x install kube-linter
```

## 代码洞察

合计: **42,787** 行代码（覆盖前 5 种语言、共 **561** 个文件）。

| 语言 | 代码 | 注释 | 空行 | 文件数 |
|------|-----:|-----:|-----:|------:|
| Go | 21,403 | 2,014 | 3,045 | 377 |
| Json | 14,523 | 0 | 0 | 3 |
| Yaml | 5,626 | 95 | 35 | 178 |
| Sh | 955 | 13 | 294 | 2 |
| Css | 113 | 8 | 19 | 1 |

## OpenSSF Scorecard 评分

总评分: **7.4 / 10**

评分最低的几项:

- **Token-Permissions** (0/10) — detected GitHub workflow tokens with excessive permissions
- **CII-Best-Practices** (0/10) — no effort to earn an OpenSSF best practices badge detected
- **Pinned-Dependencies** (2/10) — dependency not pinned by hash detected -- score normalized to 2

## 源代码

- **上游仓库**: <https://github.com/stackrox/kube-linter>
- **官网**: <https://docs.kubelinter.io/>
- **许可证**: Apache-2.0

## 发布

- **最新版本**: `v0.8.3` (2026-03-10)
- **最近提交**: 2026-09-09
- **Release 含资产**: 18 个

## 流行度

- **Star**: 3,504 · **Fork**: 275 · **开放 issue**: 252 · **贡献者**: 96

## 累计统计

- **发布数**: 41 · **已合并 PR**: 854 · **开放 PR**: 14 · **已关闭 issue**: 171 · **开放 issue**: 81 · **提交数**: 867

## 最近活动

| 时间窗口 | 起始 | 发布 | 已合并 PR | 开放 PR | 已关闭 issue | 开放 issue | 提交 |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-11 | 0 | 12 | 4 | 1 | 5 | 11 |
| last60d | 2026-07-12 | 0 | 21 | 5 | 1 | 5 | 21 |
| 90d | 2026-06-12 | 0 | 34 | 12 | 1 | 6 | 39 |
| last180d | 2026-03-14 | 0 | 93 | 14 | 3 | 13 | 93 |
| 360d | 2025-09-15 | 3 | 177 | 14 | 8 | 16 | 173 |
| last720d | 2024-09-20 | 10 | 314 | 14 | 17 | 21 | 312 |

## Release 资产

| 资产 | 大小 | 目标平台 |
|------|-----:|----------|
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

## 发行版状态

在 [repology.org](https://repology.org/project/kube-linter) 上共有 **28** 个发行版报告此项目。**13** 个 ✅ 已是最新上游版本，**6** 个 ⚠️ 使用旧版本。

| 发行版 | 版本 | 状态 |
|--------|------|------|
| Arch | `0.8.3` | ✅ latest |
| Homebrew | `0.8.3` | ✅ latest |
| Nix unstable | `0.8.3` | ✅ latest |
| openSUSE Tumbleweed | `0.8.3` | ✅ latest |

## 改进这些数据

kube-linter 的安装元数据由 [x-cmd/install](https://github.com/x-cmd/install) 索引维护——这是一份由 x-cmd 在安装时读取的精选 YAML 包列表。如果 `kube-linter` 缺失、过期，或安装行为有问题，欢迎在该 repo 提 issue 或 PR：

- **提交 issue**: <https://github.com/x-cmd/install/issues/new>
- **编辑包条目**: <https://github.com/x-cmd/install/edit/main/kube-linter.yml>（或索引实际使用的路径）

本页面的数据（card / loc / scorecard / release）由 [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) 自动采集，每日重新生成。**安装行为**（版本选择、平台差异、依赖处理）的改进应提交到上游索引。

_数据快照: `data/card/260910.yml` · 2026-09-10T22:51:35Z._
