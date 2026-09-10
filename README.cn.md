# osv-scanner

[English version](./README.md)

Vulnerability scanner written in Go which uses the data provided by https://osv.dev

![osv-scanner](https://repo.x-cmd.io/osv-scanner.svg?lang=zh)

## 安装

```sh
x install osv-scanner
```

## 代码洞察

合计: **210,348** 行代码（覆盖前 5 种语言、共 **351** 个文件）。

| 语言 | 代码 | 注释 | 空行 | 文件数 |
|------|-----:|-----:|-----:|------:|
| Yaml | 123,179 | 74 | 8 | 38 |
| Go | 32,685 | 2,580 | 4,033 | 216 |
| Json | 17,031 | 0 | 1 | 57 |
| CHeader | 10,975 | 1,955 | 407 | 13 |
| C | 10,553 | 3,817 | 1,680 | 27 |

## OpenSSF Scorecard 评分

总评分: **8.6 / 10**

评分最低的几项:

- **CII-Best-Practices** (0/10) — no effort to earn an OpenSSF best practices badge detected
- **Fuzzing** (0/10) — project is not fuzzed
- **Branch-Protection** (4/10) — branch protection is not maximal on development and all release branches

## 源代码

- **上游仓库**: <https://github.com/google/osv-scanner>
- **官网**: <https://google.github.io/osv-scanner/>
- **许可证**: Apache-2.0

## 发布

- **最新版本**: `v2.5.1` (2026-08-17)
- **最近提交**: 2026-09-10
- **Release 含资产**: 8 个

## 流行度

- **Star**: 11,002 · **Fork**: 788 · **开放 issue**: 552 · **贡献者**: 123

## 累计统计

- **发布数**: 54 · **已合并 PR**: 2054 · **开放 PR**: 17 · **已关闭 issue**: 453 · **开放 issue**: 99 · **提交数**: 2030

## 最近活动

| 时间窗口 | 起始 | 发布 | 已合并 PR | 开放 PR | 已关闭 issue | 开放 issue | 提交 |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-11 | 1 | 46 | 7 | 7 | 10 | 49 |
| last60d | 2026-07-12 | 2 | 73 | 8 | 14 | 14 | 79 |
| 90d | 2026-06-12 | 3 | 88 | 10 | 20 | 17 | 90 |
| last180d | 2026-03-14 | 6 | 218 | 13 | 46 | 24 | 220 |
| 360d | 2025-09-15 | 12 | 535 | 17 | 75 | 28 | 537 |
| last720d | 2024-09-20 | 26 | 1205 | 17 | 223 | 56 | 1192 |

## Release 资产

| 资产 | 大小 | 目标平台 |
|------|-----:|----------|
| [multiple.intoto.jsonl](https://github.com/google/osv-scanner/releases/download/v2.5.1/multiple.intoto.jsonl) | 23.9 KiB | `other` |
| [osv-scanner_darwin_amd64](https://github.com/google/osv-scanner/releases/download/v2.5.1/osv-scanner_darwin_amd64) | 56.2 MiB | `native/darwin/x64` |
| [osv-scanner_darwin_arm64](https://github.com/google/osv-scanner/releases/download/v2.5.1/osv-scanner_darwin_arm64) | 52.9 MiB | `native/darwin/arm64` |
| [osv-scanner_linux_amd64](https://github.com/google/osv-scanner/releases/download/v2.5.1/osv-scanner_linux_amd64) | 55.1 MiB | `native/linux/x64` |
| [osv-scanner_linux_arm64](https://github.com/google/osv-scanner/releases/download/v2.5.1/osv-scanner_linux_arm64) | 51.4 MiB | `native/linux/arm64` |
| [osv-scanner_SHA256SUMS](https://github.com/google/osv-scanner/releases/download/v2.5.1/osv-scanner_SHA256SUMS) | 554 B | `other` |
| [osv-scanner_windows_amd64.exe](https://github.com/google/osv-scanner/releases/download/v2.5.1/osv-scanner_windows_amd64.exe) | 56.2 MiB | `native/win/x64` |
| [osv-scanner_windows_arm64.exe](https://github.com/google/osv-scanner/releases/download/v2.5.1/osv-scanner_windows_arm64.exe) | 51.9 MiB | `native/win/arm64` |

## 发行版状态

在 [repology.org](https://repology.org/project/osv-scanner) 上共有 **35** 个发行版报告此项目。**11** 个 ✅ 已是最新上游版本，**23** 个 ⚠️ 使用旧版本。

| 发行版 | 版本 | 状态 |
|--------|------|------|
| Arch | `2.5.1` | ✅ latest |
| Homebrew | `2.5.1` | ✅ latest |
| Nix unstable | `2.5.1` | ✅ latest |
| Void | `2.4.0` | ⚠️ outdated |
| Alpine edge | `2.5.0` | ⚠️ outdated |
| openSUSE Tumbleweed | `2.5.1` | ✅ latest |

## 改进这些数据

osv-scanner 的安装元数据由 [x-cmd/install](https://github.com/x-cmd/install) 索引维护——这是一份由 x-cmd 在安装时读取的精选 YAML 包列表。如果 `osv-scanner` 缺失、过期，或安装行为有问题，欢迎在该 repo 提 issue 或 PR：

- **提交 issue**: <https://github.com/x-cmd/install/issues/new>
- **编辑包条目**: <https://github.com/x-cmd/install/edit/main/osv-scanner.yml>（或索引实际使用的路径）

本页面的数据（card / loc / scorecard / release）由 [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) 自动采集，每日重新生成。**安装行为**（版本选择、平台差异、依赖处理）的改进应提交到上游索引。

_数据快照: `data/card/260910.yml` · 2026-09-10T23:39:37Z._
