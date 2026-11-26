# osv-scanner

[中文版本](./README.cn.md)

Vulnerability scanner written in Go which uses the data provided by https://osv.dev

[![x-cmd/install — osv-scanner Code Quality Monitoring Repo Card](https://x-cmd.com/repo-card/osv-scanner.svg)](https://x-cmd.com/install/osv-scanner)

## Install

```sh
x install osv-scanner
```

## Code insight

Total: **554,117** lines of code across **580** files in the top 5 languages.

| Language | Code | Comments | Blanks | Files |
|----------|-----:|---------:|-------:|------:|
| Yaml | 449,763 | 74 | 8 | 223 |
| Go | 35,846 | 2,719 | 4,631 | 216 |
| Json | 30,934 | 0 | 1 | 101 |
| CHeader | 10,975 | 1,955 | 407 | 13 |
| C | 10,553 | 3,817 | 1,680 | 27 |

## OpenSSF Scorecard

Overall score: **8.6 / 10**

Lowest-scoring checks:

- **CII-Best-Practices** (0/10) — no effort to earn an OpenSSF best practices badge detected
- **Fuzzing** (0/10) — project is not fuzzed
- **Branch-Protection** (4/10) — branch protection is not maximal on development and all release branches

## Source

- **Upstream**: <https://github.com/google/osv-scanner>
- **Homepage**: <https://google.github.io/osv-scanner/>
- **License**: Apache-2.0

## Release

- **Latest**: `v2.7.1` (2026-11-09)
- **Last commit**: 2026-11-23
- **Assets in release**: 8

## Popularity

- **Stars**: 11,633 · **Forks**: 865 · **Open issues**: 620 · **Contributors**: 134

## Totals (cumulative)

- **Releases**: 57 · **Merged PRs**: 2189 · **Open PRs**: 18 · **Closed issues**: 521 · **Open issues**: 99 · **Commits**: 2165

## Recent activity

| Window | Since | Releases | Merged PRs | Open PRs | Closed issues | Open issues | Commits |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-10-27 | 1 | 62 | 12 | 24 | 25 | 65 |
| last60d | 2026-09-27 | 2 | 104 | 15 | 31 | 28 | 115 |
| 90d | 2026-08-28 | 3 | 155 | 16 | 42 | 30 | 165 |
| last180d | 2026-05-30 | 6 | 234 | 16 | 75 | 36 | 231 |
| 360d | 2025-12-01 | 12 | 547 | 18 | 116 | 40 | 546 |
| last720d | 2024-12-06 | 27 | 1228 | 18 | 255 | 57 | 1231 |

## Release assets

| Asset | Size | Target |
|-------|-----:|--------|
| [multiple.intoto.jsonl](https://github.com/google/osv-scanner/releases/download/v2.7.1/multiple.intoto.jsonl) | 22.8 KiB | `other` |
| [osv-scanner_darwin_amd64](https://github.com/google/osv-scanner/releases/download/v2.7.1/osv-scanner_darwin_amd64) | 56.6 MiB | `native/darwin/x64` |
| [osv-scanner_darwin_arm64](https://github.com/google/osv-scanner/releases/download/v2.7.1/osv-scanner_darwin_arm64) | 53.2 MiB | `native/darwin/arm64` |
| [osv-scanner_linux_amd64](https://github.com/google/osv-scanner/releases/download/v2.7.1/osv-scanner_linux_amd64) | 55.5 MiB | `native/linux/x64` |
| [osv-scanner_linux_arm64](https://github.com/google/osv-scanner/releases/download/v2.7.1/osv-scanner_linux_arm64) | 51.7 MiB | `native/linux/arm64` |
| [osv-scanner_SHA256SUMS](https://github.com/google/osv-scanner/releases/download/v2.7.1/osv-scanner_SHA256SUMS) | 554 B | `other` |
| [osv-scanner_windows_amd64.exe](https://github.com/google/osv-scanner/releases/download/v2.7.1/osv-scanner_windows_amd64.exe) | 56.7 MiB | `native/win/x64` |
| [osv-scanner_windows_arm64.exe](https://github.com/google/osv-scanner/releases/download/v2.7.1/osv-scanner_windows_arm64.exe) | 52.2 MiB | `native/win/arm64` |

## Improve this data

Install metadata for osv-scanner lives in the [x-cmd/install](https://github.com/x-cmd/install) index — a curated YAML package list that x-cmd consumes at install time. If `osv-scanner` is missing, out of date, or installs incorrectly, please open an issue or PR there:

- **Open an issue**: <https://github.com/x-cmd/install/issues/new>
- **Edit the package entry**: <https://github.com/x-cmd/install/edit/main/osv-scanner.yml> (or whichever path the index uses)

The data on this page (card / loc / scorecard / release) is auto-collected by [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) and is regenerated daily. Improvements to *install behaviour* (which version gets installed, platform-specific quirks, dependencies) belong upstream in the index.

_Snapshot: `data/card/261126.yml` · 2026-11-26T07:51:42Z._
