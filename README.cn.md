# osv-scanner

[English version](./README.md)

Vulnerability scanner written in Go which uses the data provided by https://osv.dev

[![x-cmd/install — osv-scanner Code Quality Monitoring Repo Card](https://x-cmd.com/repo-card/osv-scanner.svg?lang=zh)](https://x-cmd.com/install/osv-scanner)

## 安装

```sh
x install osv-scanner
```

## 代码洞察

合计: **670,516** 行代码（覆盖前 5 种语言、共 **708** 个文件）。

| 语言 | 代码 | 注释 | 空行 | 文件数 |
|------|-----:|-----:|-----:|------:|
| Yaml | 566,616 | 74 | 8 | 349 |
| Go | 35,465 | 2,691 | 4,481 | 220 |
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
- **最近提交**: 2026-11-09
- **Release 含资产**: 8 个

## 流行度

- **Star**: 11,460 · **Fork**: 843 · **开放 issue**: 608 · **贡献者**: 133

## 累计统计

- **发布数**: 57 · **已合并 PR**: 2154 · **开放 PR**: 21 · **已关闭 issue**: 510 · **开放 issue**: 98 · **提交数**: 2130

## 最近活动

| 时间窗口 | 起始 | 发布 | 已合并 PR | 开放 PR | 已关闭 issue | 开放 issue | 提交 |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-10-10 | 2 | 51 | 14 | 20 | 24 | 49 |
| last60d | 2026-09-10 | 3 | 88 | 16 | 29 | 27 | 91 |
| 90d | 2026-08-11 | 4 | 139 | 19 | 41 | 32 | 147 |
| last180d | 2026-05-13 | 6 | 226 | 19 | 70 | 35 | 228 |
| 360d | 2025-11-14 | 13 | 544 | 21 | 108 | 39 | 535 |
| last720d | 2024-11-19 | 27 | 1205 | 21 | 249 | 56 | 1210 |

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

在 [repology.org](https://repology.org/project/osv-scanner) 上共有 **36** 个发行版报告此项目。**15** 个 ✅ 已是最新上游版本，**20** 个 ⚠️ 使用旧版本。

| 发行版 | 版本 | 状态 |
|--------|------|------|
| Arch | `2.7.0` | ✅ latest |
| Homebrew | `2.7.0` | ✅ latest |
| Nix unstable | `2.7.0` | ✅ latest |
| Void | `2.7.0` | ✅ latest |
| Alpine edge | `2.7.0` | ✅ latest |
| openSUSE Tumbleweed | `2.7.0` | ✅ latest |

## 改进这些数据

osv-scanner 的安装元数据由 [x-cmd/install](https://github.com/x-cmd/install) 索引维护——这是一份由 x-cmd 在安装时读取的精选 YAML 包列表。如果 `osv-scanner` 缺失、过期，或安装行为有问题，欢迎在该 repo 提 issue 或 PR：

- **提交 issue**: <https://github.com/x-cmd/install/issues/new>
- **编辑包条目**: <https://github.com/x-cmd/install/edit/main/osv-scanner.yml>（或索引实际使用的路径）

本页面的数据（card / loc / scorecard / release）由 [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) 自动采集，每日重新生成。**安装行为**（版本选择、平台差异、依赖处理）的改进应提交到上游索引。

_数据快照: `data/card/261109.yml` · 2026-11-09T05:44:31Z._
