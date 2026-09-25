# osv-scanner

[English version](./README.md)

Vulnerability scanner written in Go which uses the data provided by https://osv.dev

[![x-cmd/install — osv-scanner Code Quality Monitoring Repo Card](https://x-cmd.com/repo-card/osv-scanner.svg?lang=zh)](https://x-cmd.com/install/osv-scanner)

## 安装

```sh
x install osv-scanner
```

## 代码洞察

合计: **508,630** 行代码（覆盖前 5 种语言、共 **663** 个文件）。

| 语言 | 代码 | 注释 | 空行 | 文件数 |
|------|-----:|-----:|-----:|------:|
| Yaml | 409,233 | 74 | 8 | 318 |
| Go | 34,120 | 2,683 | 4,296 | 218 |
| Json | 27,815 | 0 | 1 | 87 |
| CHeader | 10,975 | 1,955 | 407 | 13 |
| C | 10,553 | 3,817 | 1,680 | 27 |

## OpenSSF Scorecard 评分

总评分: **8.5 / 10**

评分最低的几项:

- **CII-Best-Practices** (0/10) — no effort to earn an OpenSSF best practices badge detected
- **Fuzzing** (0/10) — project is not fuzzed
- **Branch-Protection** (4/10) — branch protection is not maximal on development and all release branches

## 源代码

- **上游仓库**: <https://github.com/google/osv-scanner>
- **官网**: <https://google.github.io/osv-scanner/>
- **许可证**: Apache-2.0

## 发布

- **最新版本**: `v2.6.0` (2026-09-14)
- **最近提交**: 2026-09-25
- **Release 含资产**: 8 个

## 流行度

- **Star**: 11,083 · **Fork**: 797 · **开放 issue**: 556 · **贡献者**: 127

## 累计统计

- **发布数**: 55 · **已合并 PR**: 2072 · **开放 PR**: 17 · **已关闭 issue**: 466 · **开放 issue**: 90 · **提交数**: 2048

## 最近活动

| 时间窗口 | 起始 | 发布 | 已合并 PR | 开放 PR | 已关闭 issue | 开放 issue | 提交 |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-26 | 1 | 46 | 9 | 6 | 4 | 52 |
| last60d | 2026-07-27 | 3 | 82 | 10 | 16 | 12 | 92 |
| 90d | 2026-06-27 | 3 | 96 | 11 | 23 | 15 | 100 |
| last180d | 2026-03-29 | 6 | 211 | 13 | 48 | 21 | 220 |
| 360d | 2025-09-30 | 13 | 538 | 16 | 82 | 25 | 532 |
| last720d | 2024-10-05 | 26 | 1202 | 17 | 226 | 44 | 1187 |

## Release 资产

| 资产 | 大小 | 目标平台 |
|------|-----:|----------|
| [multiple.intoto.jsonl](https://github.com/google/osv-scanner/releases/download/v2.6.0/multiple.intoto.jsonl) | 22.9 KiB | `other` |
| [osv-scanner_darwin_amd64](https://github.com/google/osv-scanner/releases/download/v2.6.0/osv-scanner_darwin_amd64) | 56.0 MiB | `native/darwin/x64` |
| [osv-scanner_darwin_arm64](https://github.com/google/osv-scanner/releases/download/v2.6.0/osv-scanner_darwin_arm64) | 52.6 MiB | `native/darwin/arm64` |
| [osv-scanner_linux_amd64](https://github.com/google/osv-scanner/releases/download/v2.6.0/osv-scanner_linux_amd64) | 54.9 MiB | `native/linux/x64` |
| [osv-scanner_linux_arm64](https://github.com/google/osv-scanner/releases/download/v2.6.0/osv-scanner_linux_arm64) | 51.1 MiB | `native/linux/arm64` |
| [osv-scanner_SHA256SUMS](https://github.com/google/osv-scanner/releases/download/v2.6.0/osv-scanner_SHA256SUMS) | 554 B | `other` |
| [osv-scanner_windows_amd64.exe](https://github.com/google/osv-scanner/releases/download/v2.6.0/osv-scanner_windows_amd64.exe) | 56.0 MiB | `native/win/x64` |
| [osv-scanner_windows_arm64.exe](https://github.com/google/osv-scanner/releases/download/v2.6.0/osv-scanner_windows_arm64.exe) | 51.6 MiB | `native/win/arm64` |

## 改进这些数据

osv-scanner 的安装元数据由 [x-cmd/install](https://github.com/x-cmd/install) 索引维护——这是一份由 x-cmd 在安装时读取的精选 YAML 包列表。如果 `osv-scanner` 缺失、过期，或安装行为有问题，欢迎在该 repo 提 issue 或 PR：

- **提交 issue**: <https://github.com/x-cmd/install/issues/new>
- **编辑包条目**: <https://github.com/x-cmd/install/edit/main/osv-scanner.yml>（或索引实际使用的路径）

本页面的数据（card / loc / scorecard / release）由 [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) 自动采集，每日重新生成。**安装行为**（版本选择、平台差异、依赖处理）的改进应提交到上游索引。

_数据快照: `data/card/260925.yml` · 2026-09-25T04:28:14Z._
