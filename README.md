# osv-scanner

[中文版本](./README.cn.md)

Vulnerability scanner written in Go which uses the data provided by https://osv.dev

[![x-cmd/install — osv-scanner Code Quality Monitoring Repo Card](https://x-cmd.com/repo-card/osv-scanner.svg)](https://x-cmd.com/install/osv-scanner)

## Install

```sh
x install osv-scanner
```

## Code insight

Total: **892,850** lines of code across **687** files in the top 5 languages.

| Language | Code | Comments | Blanks | Files |
|----------|-----:|---------:|-------:|------:|
| Yaml | 791,452 | 74 | 8 | 336 |
| Go | 34,197 | 2,671 | 4,292 | 216 |
| Json | 29,747 | 0 | 1 | 95 |
| CHeader | 10,975 | 1,955 | 407 | 13 |
| C | 10,553 | 3,817 | 1,680 | 27 |

## OpenSSF Scorecard

Overall score: **8.6 / 10**

Lowest-scoring checks:

- **CII-Best-Practices** (0/10) — no effort to earn an OpenSSF best practices badge detected
- **Branch-Protection** (4/10) — branch protection is not maximal on development and all release branches
- **Fuzzing** (0/10) — project is not fuzzed

## Source

- **Upstream**: <https://github.com/google/osv-scanner>
- **Homepage**: <https://google.github.io/osv-scanner/>
- **License**: Apache-2.0

## Release

- **Latest**: `v2.7.0` (2026-10-12)
- **Last commit**: 2026-10-12
- **Assets in release**: 8

## Popularity

- **Stars**: 11,166 · **Forks**: 809 · **Open issues**: 565 · **Contributors**: 127

## Totals (cumulative)

- **Releases**: 56 · **Merged PRs**: 2098 · **Open PRs**: 15 · **Closed issues**: 478 · **Open issues**: 87 · **Commits**: 2075

## Recent activity

| Window | Since | Releases | Merged PRs | Open PRs | Closed issues | Open issues | Commits |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-09-12 | 2 | 30 | 9 | 8 | 4 | 34 |
| last60d | 2026-08-13 | 3 | 81 | 13 | 19 | 10 | 89 |
| 90d | 2026-07-14 | 4 | 112 | 13 | 26 | 15 | 123 |
| last180d | 2026-04-15 | 7 | 214 | 13 | 55 | 20 | 218 |
| 360d | 2025-10-17 | 13 | 535 | 15 | 90 | 24 | 529 |
| last720d | 2024-10-22 | 27 | 1202 | 15 | 230 | 43 | 1190 |

## Release assets

| Asset | Size | Target |
|-------|-----:|--------|
| [multiple.intoto.jsonl](https://github.com/google/osv-scanner/releases/download/v2.7.0/multiple.intoto.jsonl) | 23.1 KiB | `other` |
| [osv-scanner_darwin_amd64](https://github.com/google/osv-scanner/releases/download/v2.7.0/osv-scanner_darwin_amd64) | 56.2 MiB | `native/darwin/x64` |
| [osv-scanner_darwin_arm64](https://github.com/google/osv-scanner/releases/download/v2.7.0/osv-scanner_darwin_arm64) | 52.8 MiB | `native/darwin/arm64` |
| [osv-scanner_linux_amd64](https://github.com/google/osv-scanner/releases/download/v2.7.0/osv-scanner_linux_amd64) | 55.1 MiB | `native/linux/x64` |
| [osv-scanner_linux_arm64](https://github.com/google/osv-scanner/releases/download/v2.7.0/osv-scanner_linux_arm64) | 51.4 MiB | `native/linux/arm64` |
| [osv-scanner_SHA256SUMS](https://github.com/google/osv-scanner/releases/download/v2.7.0/osv-scanner_SHA256SUMS) | 554 B | `other` |
| [osv-scanner_windows_amd64.exe](https://github.com/google/osv-scanner/releases/download/v2.7.0/osv-scanner_windows_amd64.exe) | 56.3 MiB | `native/win/x64` |
| [osv-scanner_windows_arm64.exe](https://github.com/google/osv-scanner/releases/download/v2.7.0/osv-scanner_windows_arm64.exe) | 51.8 MiB | `native/win/arm64` |

## Improve this data

Install metadata for osv-scanner lives in the [x-cmd/install](https://github.com/x-cmd/install) index — a curated YAML package list that x-cmd consumes at install time. If `osv-scanner` is missing, out of date, or installs incorrectly, please open an issue or PR there:

- **Open an issue**: <https://github.com/x-cmd/install/issues/new>
- **Edit the package entry**: <https://github.com/x-cmd/install/edit/main/osv-scanner.yml> (or whichever path the index uses)

The data on this page (card / loc / scorecard / release) is auto-collected by [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) and is regenerated daily. Improvements to *install behaviour* (which version gets installed, platform-specific quirks, dependencies) belong upstream in the index.

_Snapshot: `data/card/261012.yml` · 2026-10-12T05:28:04Z._
