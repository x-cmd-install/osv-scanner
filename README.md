# osv-scanner

[中文版本](./README.cn.md)

Vulnerability scanner written in Go which uses the data provided by https://osv.dev

[![x-cmd/install — osv-scanner Code Quality Monitoring Repo Card](https://x-cmd.com/repo-card/osv-scanner.svg)](https://x-cmd.com/install/osv-scanner)

## Install

```sh
x install osv-scanner
```

## Code insight

Total: **904,546** lines of code across **707** files in the top 5 languages.

| Language | Code | Comments | Blanks | Files |
|----------|-----:|---------:|-------:|------:|
| Yaml | 801,618 | 74 | 8 | 348 |
| Go | 35,449 | 2,691 | 4,477 | 220 |
| Json | 29,961 | 0 | 1 | 99 |
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

- **Latest**: `v2.7.0` (2026-10-12)
- **Last commit**: 2026-11-04
- **Assets in release**: 8

## Popularity

- **Stars**: 11,387 · **Forks**: 834 · **Open issues**: 581 · **Contributors**: 131

## Totals (cumulative)

- **Releases**: 56 · **Merged PRs**: 2141 · **Open PRs**: 14 · **Closed issues**: 502 · **Open issues**: 79 · **Commits**: 2117

## Recent activity

| Window | Since | Releases | Merged PRs | Open PRs | Closed issues | Open issues | Commits |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-10-05 | 1 | 49 | 8 | 13 | 4 | 50 |
| last60d | 2026-09-05 | 2 | 91 | 10 | 24 | 9 | 100 |
| 90d | 2026-08-06 | 4 | 133 | 12 | 36 | 14 | 140 |
| last180d | 2026-05-08 | 6 | 215 | 12 | 64 | 17 | 225 |
| 360d | 2025-11-09 | 12 | 537 | 14 | 100 | 20 | 539 |
| last720d | 2024-11-14 | 26 | 1198 | 14 | 245 | 37 | 1201 |

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

## Distribution status

Reported by **36** distros on [repology.org](https://repology.org/project/osv-scanner). **14** are ✅ on the latest upstream release, **21** are ⚠️ on an older version.

| Distro | Version | Status |
|--------|---------|--------|
| Arch | `2.7.0` | ✅ latest |
| Homebrew | `2.7.0` | ✅ latest |
| Nix unstable | `2.7.0` | ✅ latest |
| Void | `2.7.0` | ✅ latest |
| Alpine edge | `2.7.0` | ✅ latest |
| openSUSE Tumbleweed | `2.7.0` | ✅ latest |

## Improve this data

Install metadata for osv-scanner lives in the [x-cmd/install](https://github.com/x-cmd/install) index — a curated YAML package list that x-cmd consumes at install time. If `osv-scanner` is missing, out of date, or installs incorrectly, please open an issue or PR there:

- **Open an issue**: <https://github.com/x-cmd/install/issues/new>
- **Edit the package entry**: <https://github.com/x-cmd/install/edit/main/osv-scanner.yml> (or whichever path the index uses)

The data on this page (card / loc / scorecard / release) is auto-collected by [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) and is regenerated daily. Improvements to *install behaviour* (which version gets installed, platform-specific quirks, dependencies) belong upstream in the index.

_Snapshot: `data/card/261104.yml` · 2026-11-04T05:48:05Z._
