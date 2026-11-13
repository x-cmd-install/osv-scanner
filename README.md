# osv-scanner

[中文版本](./README.cn.md)

Vulnerability scanner written in Go which uses the data provided by https://osv.dev

[![x-cmd/install — osv-scanner Code Quality Monitoring Repo Card](https://x-cmd.com/repo-card/osv-scanner.svg)](https://x-cmd.com/install/osv-scanner)

## Install

```sh
x install osv-scanner
```

## Code insight

Total: **670,509** lines of code across **708** files in the top 5 languages.

| Language | Code | Comments | Blanks | Files |
|----------|-----:|---------:|-------:|------:|
| Yaml | 566,615 | 74 | 8 | 349 |
| Go | 35,459 | 2,691 | 4,480 | 220 |
| Json | 30,896 | 0 | 1 | 99 |
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

- **Latest**: `v2.7.1` (2026-11-09)
- **Last commit**: 2026-11-12
- **Assets in release**: 8

## Popularity

- **Stars**: 11,505 · **Forks**: 848 · **Open issues**: 612 · **Contributors**: 133

## Totals (cumulative)

- **Releases**: 57 · **Merged PRs**: 2159 · **Open PRs**: 21 · **Closed issues**: 512 · **Open issues**: 100 · **Commits**: 2135

## Recent activity

| Window | Since | Releases | Merged PRs | Open PRs | Closed issues | Open issues | Commits |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-10-14 | 1 | 51 | 14 | 21 | 26 | 54 |
| last60d | 2026-09-14 | 3 | 84 | 16 | 29 | 29 | 96 |
| 90d | 2026-08-15 | 4 | 139 | 19 | 42 | 33 | 152 |
| last180d | 2026-05-17 | 6 | 224 | 19 | 71 | 37 | 233 |
| 360d | 2025-11-18 | 13 | 542 | 21 | 109 | 41 | 540 |
| last720d | 2024-11-23 | 27 | 1209 | 21 | 249 | 58 | 1205 |

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

## Distribution status

Reported by **36** distros on [repology.org](https://repology.org/project/osv-scanner). **3** are ✅ on the latest upstream release, **32** are ⚠️ on an older version.

| Distro | Version | Status |
|--------|---------|--------|
| Arch | `2.7.0` | ⚠️ outdated |
| Homebrew | `HEAD` | 🔄 rolling |
| Nix unstable | `2.7.0` | ⚠️ outdated |
| Void | `2.7.0` | ⚠️ outdated |
| Alpine edge | `2.7.0` | ⚠️ outdated |
| openSUSE Tumbleweed | `2.7.0` | ⚠️ outdated |

## Improve this data

Install metadata for osv-scanner lives in the [x-cmd/install](https://github.com/x-cmd/install) index — a curated YAML package list that x-cmd consumes at install time. If `osv-scanner` is missing, out of date, or installs incorrectly, please open an issue or PR there:

- **Open an issue**: <https://github.com/x-cmd/install/issues/new>
- **Edit the package entry**: <https://github.com/x-cmd/install/edit/main/osv-scanner.yml> (or whichever path the index uses)

The data on this page (card / loc / scorecard / release) is auto-collected by [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) and is regenerated daily. Improvements to *install behaviour* (which version gets installed, platform-specific quirks, dependencies) belong upstream in the index.

_Snapshot: `data/card/261113.yml` · 2026-11-13T06:04:54Z._
