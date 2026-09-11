# osv-scanner

[中文版本](./README.cn.md)

Vulnerability scanner written in Go which uses the data provided by https://osv.dev

![osv-scanner](https://repo.x-cmd.io/osv-scanner.svg)

## Install

```sh
x install osv-scanner
```

## Code insight

Total: **210,428** lines of code across **352** files in the top 5 languages.

| Language | Code | Comments | Blanks | Files |
|----------|-----:|---------:|-------:|------:|
| Yaml | 123,179 | 74 | 8 | 38 |
| Go | 32,765 | 2,584 | 4,040 | 217 |
| Json | 17,031 | 0 | 1 | 57 |
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

- **Latest**: `v2.5.1` (2026-08-17)
- **Last commit**: 2026-09-11
- **Assets in release**: 8

## Popularity

- **Stars**: 11,003 · **Forks**: 788 · **Open issues**: 552 · **Contributors**: 125

## Totals (cumulative)

- **Releases**: 54 · **Merged PRs**: 2058 · **Open PRs**: 16 · **Closed issues**: 454 · **Open issues**: 98 · **Commits**: 2034

## Recent activity

| Window | Since | Releases | Merged PRs | Open PRs | Closed issues | Open issues | Commits |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-12 | 1 | 49 | 7 | 8 | 9 | 53 |
| last60d | 2026-07-13 | 2 | 76 | 8 | 15 | 13 | 83 |
| 90d | 2026-06-13 | 3 | 92 | 9 | 21 | 16 | 94 |
| last180d | 2026-03-15 | 6 | 220 | 12 | 47 | 23 | 224 |
| 360d | 2025-09-16 | 12 | 538 | 16 | 76 | 27 | 541 |
| last720d | 2024-09-21 | 26 | 1209 | 16 | 224 | 55 | 1194 |

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

## Distribution status

Reported by **35** distros on [repology.org](https://repology.org/project/osv-scanner). **11** are ✅ on the latest upstream release, **23** are ⚠️ on an older version.

| Distro | Version | Status |
|--------|---------|--------|
| Arch | `2.5.1` | ✅ latest |
| Homebrew | `2.5.1` | ✅ latest |
| Nix unstable | `2.5.1` | ✅ latest |
| Void | `2.4.0` | ⚠️ outdated |
| Alpine edge | `2.5.0` | ⚠️ outdated |
| openSUSE Tumbleweed | `2.5.1` | ✅ latest |

## Improve this data

Install metadata for osv-scanner lives in the [x-cmd/install](https://github.com/x-cmd/install) index — a curated YAML package list that x-cmd consumes at install time. If `osv-scanner` is missing, out of date, or installs incorrectly, please open an issue or PR there:

- **Open an issue**: <https://github.com/x-cmd/install/issues/new>
- **Edit the package entry**: <https://github.com/x-cmd/install/edit/main/osv-scanner.yml> (or whichever path the index uses)

The data on this page (card / loc / scorecard / release) is auto-collected by [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) and is regenerated daily. Improvements to *install behaviour* (which version gets installed, platform-specific quirks, dependencies) belong upstream in the index.

_Snapshot: `data/card/260911.yml` · 2026-09-11T04:08:00Z._
