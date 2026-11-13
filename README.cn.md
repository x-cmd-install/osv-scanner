# osv-scanner

[English version](./README.md)

Vulnerability scanner written in Go which uses the data provided by https://osv.dev

[![x-cmd/install — osv-scanner Code Quality Monitoring Repo Card](https://x-cmd.com/repo-card/osv-scanner.svg?lang=zh)](https://x-cmd.com/install/osv-scanner)

## 安装

```sh
x install osv-scanner
```

## 代码洞察

合计: **670,509** 行代码（覆盖前 5 种语言、共 **708** 个文件）。

| 语言 | 代码 | 注释 | 空行 | 文件数 |
|------|-----:|-----:|-----:|------:|
| Yaml | 566,615 | 74 | 8 | 349 |
| Go | 35,459 | 2,691 | 4,480 | 220 |
| Json | 30,896 | 0 | 1 | 99 |
| CHeader | 10,975 | 1,955 | 407 | 13 |
| C | 10,553 | 3,817 | 1,680 | 27 |

## OpenSSF Scorecard 评分

总评分: **8.6 / 10**

评分最低的几项:

- **CII-Best-Practices** (0/10) — no effort to earn an OpenSSF best practices badge detected
- **Branch-Protection** (4/10) — branch protection is not maximal on development and all release branches
- **Fuzzing** (0/10) — project is not fuzzed

## 源代码

- **上游仓库**: <https://github.com/google/osv-scanner>
- **官网**: <https://google.github.io/osv-scanner/>
- **许可证**: Apache-2.0

## 发布

- **最新版本**: `v2.7.1` (2026-11-09)
- **最近提交**: 2026-11-12
- **Release 含资产**: 8 个

## 流行度

- **Star**: 11,505 · **Fork**: 848 · **开放 issue**: 612 · **贡献者**: 133

## 累计统计

- **发布数**: 57 · **已合并 PR**: 2159 · **开放 PR**: 21 · **已关闭 issue**: 512 · **开放 issue**: 100 · **提交数**: 2135

## 最近活动

| 时间窗口 | 起始 | 发布 | 已合并 PR | 开放 PR | 已关闭 issue | 开放 issue | 提交 |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-10-14 | 1 | 51 | 14 | 21 | 26 | 54 |
| last60d | 2026-09-14 | 3 | 84 | 16 | 29 | 29 | 96 |
| 90d | 2026-08-15 | 4 | 139 | 19 | 42 | 33 | 152 |
| last180d | 2026-05-17 | 6 | 224 | 19 | 71 | 37 | 233 |
| 360d | 2025-11-18 | 13 | 542 | 21 | 109 | 41 | 540 |
| last720d | 2024-11-23 | 27 | 1209 | 21 | 249 | 58 | 1205 |

## Release 资产

| 资产 | 大小 | 目标平台 |
|------|-----:|----------|
| [multiple.intoto.jsonl](https://github.com/google/osv-scanner/releases/download/v2.7.1/multiple.intoto.jsonl) | 22.8 KiB | `other` |
| [osv-scanner_darwin_amd64](https://github.com/google/osv-scanner/releases/download/v2.7.1/osv-scanner_darwin_amd64) | 56.6 MiB | `native/darwin/x64` |
| [osv-scanner_darwin_arm64](https://github.com/google/osv-scanner/releases/download/v2.7.1/osv-scanner_darwin_arm64) | 53.2 MiB | `native/darwin/arm64` |
| [osv-scanner_linux_amd64](https://github.com/google/osv-scanner/releases/download/v2.7.1/osv-scanner_linux_amd64) | 55.5 MiB | `native/linux/x64` |
| [osv-scanner_linux_arm64](https://github.com/google/osv-scanner/releases/download/v2.7.1/osv-scanner_linux_arm64) | 51.7 MiB | `native/linux/arm64` |
| [osv-scanner_SHA256SUMS](https://github.com/google/osv-scanner/releases/download/v2.7.1/osv-scanner_SHA256SUMS) | 554 B | `other` |
| [osv-scanner_windows_amd64.exe](https://github.com/google/osv-scanner/releases/download/v2.7.1/osv-scanner_windows_amd64.exe) | 56.7 MiB | `native/win/x64` |
| [osv-scanner_windows_arm64.exe](https://github.com/google/osv-scanner/releases/download/v2.7.1/osv-scanner_windows_arm64.exe) | 52.2 MiB | `native/win/arm64` |

## 发行版状态

在 [repology.org](https://repology.org/project/osv-scanner) 上共有 **36** 个发行版报告此项目。**3** 个 ✅ 已是最新上游版本，**32** 个 ⚠️ 使用旧版本。

| 发行版 | 版本 | 状态 |
|--------|------|------|
| Arch | `2.7.0` | ⚠️ outdated |
| Homebrew | `HEAD` | 🔄 rolling |
| Nix unstable | `2.7.0` | ⚠️ outdated |
| Void | `2.7.0` | ⚠️ outdated |
| Alpine edge | `2.7.0` | ⚠️ outdated |
| openSUSE Tumbleweed | `2.7.0` | ⚠️ outdated |

## 改进这些数据

osv-scanner 的安装元数据由 [x-cmd/install](https://github.com/x-cmd/install) 索引维护——这是一份由 x-cmd 在安装时读取的精选 YAML 包列表。如果 `osv-scanner` 缺失、过期，或安装行为有问题，欢迎在该 repo 提 issue 或 PR：

- **提交 issue**: <https://github.com/x-cmd/install/issues/new>
- **编辑包条目**: <https://github.com/x-cmd/install/edit/main/osv-scanner.yml>（或索引实际使用的路径）

本页面的数据（card / loc / scorecard / release）由 [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) 自动采集，每日重新生成。**安装行为**（版本选择、平台差异、依赖处理）的改进应提交到上游索引。

_数据快照: `data/card/261113.yml` · 2026-11-13T06:04:55Z._
