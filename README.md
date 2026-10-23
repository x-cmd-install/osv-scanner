# osv-scanner

[中文版本](./README.cn.md)

Vulnerability scanner written in Go which uses the data provided by https://osv.dev

[![x-cmd/install — osv-scanner Code Quality Monitoring Repo Card](https://x-cmd.com/repo-card/osv-scanner.svg)](https://x-cmd.com/install/osv-scanner)

## Install

```sh
x install osv-scanner
```

## Code insight

Total: **893,664** lines of code across **690** files in the top 5 languages.

| Language | Code | Comments | Blanks | Files |
|----------|-----:|---------:|-------:|------:|
| Yaml | 791,452 | 74 | 8 | 336 |
| Go | 35,011 | 2,717 | 4,401 | 219 |
| Json | 29,747 | 0 | 1 | 95 |
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
- **Last commit**: 2026-10-22
- **Assets in release**: 8

## Popularity

- **Stars**: 11,246 · **Forks**: 820 · **Open issues**: 565 · **Contributors**: 128

## Totals (cumulative)

- **Releases**: 56 · **Merged PRs**: 2109 · **Open PRs**: 17 · **Closed issues**: 480 · **Open issues**: 85 · **Commits**: 2086

## Recent activity

| Window | Since | Releases | Merged PRs | Open PRs | Closed issues | Open issues | Commits |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-09-23 | 1 | 31 | 10 | 6 | 2 | 39 |
| last60d | 2026-08-24 | 2 | 81 | 15 | 16 | 7 | 90 |
| 90d | 2026-07-25 | 4 | 116 | 15 | 25 | 12 | 130 |
| last180d | 2026-04-26 | 7 | 211 | 15 | 54 | 19 | 223 |
| 360d | 2025-10-28 | 13 | 529 | 17 | 87 | 22 | 530 |
| last720d | 2024-11-02 | 26 | 1185 | 17 | 229 | 41 | 1183 |

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

Reported by **36** distros on [repology.org](https://repology.org/project/osv-scanner). **12** are ✅ on the latest upstream release, **23** are ⚠️ on an older version.

| Distro | Version | Status |
|--------|---------|--------|
| Arch | `2.7.0` | ✅ latest |
| Homebrew | `2.7.0` | ✅ latest |
| Nix unstable | `2.7.0` | ✅ latest |
| Void | `2.4.0` | ⚠️ outdated |
| Alpine edge | `2.7.0` | ✅ latest |
| openSUSE Tumbleweed | `2.7.0` | ✅ latest |

## Improve this data

Install metadata for osv-scanner lives in the [x-cmd/install](https://github.com/x-cmd/install) index — a curated YAML package list that x-cmd consumes at install time. If `osv-scanner` is missing, out of date, or installs incorrectly, please open an issue or PR there:

- **Open an issue**: <https://github.com/x-cmd/install/issues/new>
- **Edit the package entry**: <https://github.com/x-cmd/install/edit/main/osv-scanner.yml> (or whichever path the index uses)

The data on this page (card / loc / scorecard / release) is auto-collected by [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) and is regenerated daily. Improvements to *install behaviour* (which version gets installed, platform-specific quirks, dependencies) belong upstream in the index.

_Snapshot: `data/card/261023.yml` · 2026-10-23T04:17:56Z._
