# scoop-bucket
[![日本語](https://img.shields.io/badge/lang-日本語-red)](README.md)
[![English](https://img.shields.io/badge/lang-English-blue)](README.en.md)
[![Update](https://github.com/aviscaerulea/scoop-bucket/actions/workflows/update.yml/badge.svg)](https://github.com/aviscaerulea/scoop-bucket/actions/workflows/update.yml)

Scoop の標準 bucket が扱っていないアプリケーションを配布する、個人用の Scoop bucket です。
日本製のソフトウェアや、標準 bucket に載りにくいニッチなツールを中心に収録しています。

## 収録アプリケーション

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
| [Reduce Memory](https://www.sordum.org/9197/) | Reduce working set memory of processes to free up RAM |
| [redntfy](https://github.com/aviscaerulea/redntfy) | Redmine ticket update notifier daemon with Windows Toast notifications |
| [**sysmeters**](https://github.com/aviscaerulea/sysmeters) | Real-time system resource monitoring HUD for Windows 11 (CPU, GPU, memory, disk I/O, network) |
| [tally](https://github.com/aviscaerulea/tally) | Detect web meetings by monitoring microphone and camera usage |
| [UDEV Gothic](https://github.com/yuru7/udev-gothic) | Programming font combining BIZ UD Gothic and JetBrains Mono |
| [VOICEVOX](https://github.com/VOICEVOX/voicevox) | Open-source Japanese text-to-speech software |
| [winfocus](https://github.com/aviscaerulea/winfocus) | Restore and gather all visible windows to the primary monitor on Windows 11 |
| [winhandles](https://github.com/aviscaerulea/winhandles) | CLI tool to investigate Windows handle consumption by process |

バージョン更新は毎日 1 回、自動で確認します。

## インストール

### 動作要件

- Windows 10/11
- Scoop が導入済みであること

### 手順

bucket を追加します。次にアプリケーションを個別にインストールします。

```powershell
scoop bucket add aviscaerulea https://github.com/aviscaerulea/scoop-bucket
scoop install aviscaerulea/<app>
```

`<app>` には「収録アプリケーション」の App 列の名前を指定します。

## 免責事項

収録アプリケーションの提供元は、本リポジトリと関係ありません。
本 bucket の利用によって生じた不利益について、一切保証しません。
