# osv-scanner

[中文版本](./README.cn.md)

Vulnerability scanner written in Go which uses the data provided by https://osv.dev

![osv-scanner](https://repo.x-cmd.io/osv-scanner.svg)

## Install

```sh
x install osv-scanner
```

## Code insight

Total: **211,352** lines of code across **352** files in the top 5 languages.

| Language | Code | Comments | Blanks | Files |
|----------|-----:|---------:|-------:|------:|
| Yaml | 124,034 | 74 | 8 | 38 |
| Go | 32,834 | 2,584 | 4,049 | 217 |
| Json | 17,031 | 0 | 1 | 57 |
| CHeader | 10,975 | 1,955 | 407 | 13 |
| C | 10,553 | 3,817 | 1,680 | 27 |

## OpenSSF Scorecard

Overall score: **8.5 / 10**

Lowest-scoring checks:

- **CII-Best-Practices** (0/10) — no effort to earn an OpenSSF best practices badge detected
- **Fuzzing** (0/10) — project is not fuzzed
- **Branch-Protection** (4/10) — branch protection is not maximal on development and all release branches

## Source

- **Upstream**: <https://github.com/google/osv-scanner>
- **Homepage**: <https://google.github.io/osv-scanner/>
- **License**: Apache-2.0

## Release

- **Latest**: `v2.6.0` (2026-09-14)
- **Last commit**: 2026-09-17
- **Assets in release**: 8

## Popularity

- **Stars**: 11,042 · **Forks**: 792 · **Open issues**: 555 · **Contributors**: 126

## Totals (cumulative)

- **Releases**: 55 · **Merged PRs**: 2065 · **Open PRs**: 17 · **Closed issues**: 464 · **Open issues**: 91 · **Commits**: 2041

## Recent activity

| Window | Since | Releases | Merged PRs | Open PRs | Closed issues | Open issues | Commits |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-18 | 1 | 47 | 8 | 9 | 7 | 53 |
| last60d | 2026-07-19 | 3 | 82 | 9 | 17 | 13 | 87 |
| 90d | 2026-06-19 | 3 | 92 | 10 | 23 | 14 | 93 |
| last180d | 2026-03-21 | 7 | 213 | 13 | 52 | 20 | 217 |
| 360d | 2025-09-22 | 13 | 539 | 17 | 82 | 24 | 536 |
| last720d | 2024-09-27 | 27 | 1208 | 17 | 228 | 47 | 1193 |

## Release assets

| Asset | Size | Target |
|-------|-----:|--------|
| [multiple.intoto.jsonl](https://github.com/google/osv-scanner/releases/download/v2.6.0/multiple.intoto.jsonl) | 22.9 KiB | `other` |
| [osv-scanner_darwin_amd64](https://github.com/google/osv-scanner/releases/download/v2.6.0/osv-scanner_darwin_amd64) | 56.0 MiB | `native/darwin/x64` |
| [osv-scanner_darwin_arm64](https://github.com/google/osv-scanner/releases/download/v2.6.0/osv-scanner_darwin_arm64) | 52.6 MiB | `native/darwin/arm64` |
| [osv-scanner_linux_amd64](https://github.com/google/osv-scanner/releases/download/v2.6.0/osv-scanner_linux_amd64) | 54.9 MiB | `native/linux/x64` |
| [osv-scanner_linux_arm64](https://github.com/google/osv-scanner/releases/download/v2.6.0/osv-scanner_linux_arm64) | 51.1 MiB | `native/linux/arm64` |
| [osv-scanner_SHA256SUMS](https://github.com/google/osv-scanner/releases/download/v2.6.0/osv-scanner_SHA256SUMS) | 554 B | `other` |
| [osv-scanner_windows_amd64.exe](https://github.com/google/osv-scanner/releases/download/v2.6.0/osv-scanner_windows_amd64.exe) | 56.0 MiB | `native/win/x64` |
| [osv-scanner_windows_arm64.exe](https://github.com/google/osv-scanner/releases/download/v2.6.0/osv-scanner_windows_arm64.exe) | 51.6 MiB | `native/win/arm64` |

## Improve this data

Install metadata for osv-scanner lives in the [x-cmd/install](https://github.com/x-cmd/install) index — a curated YAML package list that x-cmd consumes at install time. If `osv-scanner` is missing, out of date, or installs incorrectly, please open an issue or PR there:

- **Open an issue**: <https://github.com/x-cmd/install/issues/new>
- **Edit the package entry**: <https://github.com/x-cmd/install/edit/main/osv-scanner.yml> (or whichever path the index uses)

The data on this page (card / loc / scorecard / release) is auto-collected by [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) and is regenerated daily. Improvements to *install behaviour* (which version gets installed, platform-specific quirks, dependencies) belong upstream in the index.

_Snapshot: `data/card/260917.yml` · 2026-09-17T04:28:38Z._
