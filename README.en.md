# scoop-bucket
[![日本語](https://img.shields.io/badge/lang-日本語-red)](README.md)
[![English](https://img.shields.io/badge/lang-English-blue)](README.en.md)
[![Update](https://github.com/aviscaerulea/scoop-bucket/actions/workflows/update.yml/badge.svg)](https://github.com/aviscaerulea/scoop-bucket/actions/workflows/update.yml)

This is a personal Scoop bucket that distributes applications not covered by the official Scoop buckets.
It mainly collects Japanese software and niche tools that are unlikely to be listed in the official buckets.

## Applications

| App | Description |
|-----|-------------|
| [**avply**](https://github.com/aviscaerulea/avply) | Windows video preview, trimming and AV1 conversion tool |
| [busybox-nt](https://github.com/aviscaerulea/busybox-nt) | BusyBox for Windows with UTF-8 support and performance optimizations (fork by @aviscaerulea) |
| [**gcalntfy**](https://github.com/aviscaerulea/gcalntfy) | Calendar event notifier daemon with Windows Toast notifications |
| [GoAWK](https://benhoyt.com/writings/goawk/) | POSIX-compliant AWK interpreter written in Go, with CSV support |
| [HackGen](https://github.com/yuru7/HackGen) | Programming font combining Hack and Gen Jyuu Gothic |
| [秀丸エディタ](https://hide.maruo.co.jp/software/hidemaru.html) | Japanese text editor (秀丸エディタ) |
| [秀丸ファイラー](https://hide.maruo.co.jp/software/hmfilerclassic.html) | Japanese two-pane file manager (秀丸ファイラー) |
| [JPEGView-nt](https://github.com/aviscaerulea/jpegview-nt) | Fast image viewer/editor with HEIC/PDF/AVX2 support (fork by @aviscaerulea) |
| [keypress](https://github.com/aviscaerulea/keypress) | Lightweight CLI tool to automate key input |
| [minply](https://github.com/aviscaerulea/minply) | Ultra-lightweight CLI audio player with Bluetooth guard tone support |
| [Monitor Off](https://github.com/aviscaerulea/monitor-off) | Lock desktop and turn off monitor power |
| [myacts](https://github.com/aviscaerulea/myacts-releases) | Google Workspace activity CLI tool and MCP server (Chat, Calendar, Gmail, Drive) |
| [Reduce Memory](https://www.sordum.org/9197/) | Reduce working set memory of processes to free up RAM |
| [redntfy](https://github.com/aviscaerulea/redntfy) | Redmine ticket update notifier daemon with Windows Toast notifications |
| [**sysmeters**](https://github.com/aviscaerulea/sysmeters) | Real-time system resource monitoring HUD for Windows 11 (CPU, GPU, memory, disk I/O, network) |
| [tally](https://github.com/aviscaerulea/tally) | Detect web meetings by monitoring microphone and camera usage |
| [UDEV Gothic](https://github.com/yuru7/udev-gothic) | Programming font combining BIZ UD Gothic and JetBrains Mono |
| [VOICEVOX](https://github.com/VOICEVOX/voicevox) | Open-source Japanese text-to-speech software |
| [winfocus](https://github.com/aviscaerulea/winfocus) | Restore and gather all visible windows to the primary monitor on Windows 11 |
| [winhandles](https://github.com/aviscaerulea/winhandles) | CLI tool to investigate Windows handle consumption by process |

Version updates are checked automatically once a day.

## Installation

### Requirements

- Windows 10/11
- Scoop already installed

### Steps

Add the bucket first. Then install each application individually.

```powershell
scoop bucket add aviscaerulea https://github.com/aviscaerulea/scoop-bucket
scoop install aviscaerulea/<app>
```

For `<app>`, specify a name from the App column in "Applications".

## Disclaimer

The application providers are not affiliated with this repository.
No guarantee is made regarding any disadvantage arising from the use of this bucket.
