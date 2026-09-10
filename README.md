# osv-scanner

[中文版本](./README.cn.md)

Vulnerability scanner written in Go which uses the data provided by https://osv.dev

![osv-scanner](https://repo.x-cmd.io/osv-scanner.svg)

## Install

```sh
x install osv-scanner
```

## Source

- **Upstream**: <https://github.com/google/osv-scanner>
- **Homepage**: <https://google.github.io/osv-scanner/>
- **License**: Apache-2.0

## Release

- **Latest**: `v2.5.1` (2026-08-17)
- **Last commit**: 2026-09-10
- **Assets in release**: 8

## Release assets

| Asset | Size | Target |
|-------|-----:|--------|
| [multiple.intoto.jsonl](https://github.com/google/osv-scanner/releases/download/v2.5.1/multiple.intoto.jsonl) | 23.9 KiB | `other` |
| [osv-scanner_darwin_amd64](https://github.com/google/osv-scanner/releases/download/v2.5.1/osv-scanner_darwin_amd64) | 56.2 MiB | `native/darwin/x64` |
| [osv-scanner_darwin_arm64](https://github.com/google/osv-scanner/releases/download/v2.5.1/osv-scanner_darwin_arm64) | 52.9 MiB | `native/darwin/arm64` |
| [osv-scanner_linux_amd64](https://github.com/google/osv-scanner/releases/download/v2.5.1/osv-scanner_linux_amd64) | 55.1 MiB | `native/linux/x64` |
| [osv-scanner_linux_arm64](https://github.com/google/osv-scanner/releases/download/v2.5.1/osv-scanner_linux_arm64) | 51.4 MiB | `native/linux/arm64` |
| [osv-scanner_SHA256SUMS](https://github.com/google/osv-scanner/releases/download/v2.5.1/osv-scanner_SHA256SUMS) | 554 B | `other` |
| [osv-scanner_windows_amd64.exe](https://github.com/google/osv-scanner/releases/download/v2.5.1/osv-scanner_windows_amd64.exe) | 56.2 MiB | `native/win/x64` |
| [osv-scanner_windows_arm64.exe](https://github.com/google/osv-scanner/releases/download/v2.5.1/osv-scanner_windows_arm64.exe) | 51.9 MiB | `native/win/arm64` |

## Popularity

- **Stars**: 11,002 · **Forks**: 789 · **Open issues**: 551 · **Contributors**: 123

## Totals (cumulative)

- **Releases**: 54 · **Merged PRs**: 2054 · **Open PRs**: 16 · **Closed issues**: 453 · **Open issues**: 98 · **Commits**: 2030

## Recent activity

| Window | Since | Releases | Merged PRs | Open PRs | Closed issues | Open issues | Commits |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-11 | 1 | 46 | 6 | 7 | 9 | 49 |
| 90d | 2026-06-12 | 3 | 88 | 9 | 20 | 16 | 90 |
| 360d | 2025-09-15 | 12 | 535 | 16 | 75 | 27 | 537 |

## Code size

Total: **210,348** lines of code across **351** files in the top 5 languages.

| Language | Code | Comments | Blanks | Files |
|----------|-----:|---------:|-------:|------:|
| Yaml | 123,179 | 74 | 8 | 38 |
| Go | 32,685 | 2,580 | 4,033 | 216 |
| Json | 17,031 | 0 | 1 | 57 |
| CHeader | 10,975 | 1,955 | 407 | 13 |
| C | 10,553 | 3,817 | 1,680 | 27 |

## OpenSSF Scorecard

Overall score: **8.6 / 10**

Lowest-scoring checks:

- **CII-Best-Practices** (0/10) — no effort to earn an OpenSSF best practices badge detected
- **Fuzzing** (0/10) — project is not fuzzed
- **Branch-Protection** (4/10) — branch protection is not maximal on development and all release branches

## Improve this data

Install metadata for osv-scanner lives in the [x-cmd/install](https://github.com/x-cmd/install) index — a curated YAML package list that x-cmd consumes at install time. If `osv-scanner` is missing, out of date, or installs incorrectly, please open an issue or PR there:

- **Open an issue**: <https://github.com/x-cmd/install/issues/new>
- **Edit the package entry**: <https://github.com/x-cmd/install/edit/main/osv-scanner.yml> (or whichever path the index uses)

The data on this page (card / loc / scorecard / release) is auto-collected by [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) and is regenerated daily. Improvements to *install behaviour* (which version gets installed, platform-specific quirks, dependencies) belong upstream in the index.

_Snapshot: `data/card/260910.yml` · 2026-09-10T15:56:42Z._
