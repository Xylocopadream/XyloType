# XyloType

Learn to type, or improve your typing speed and precision: pick an exercise, type it, then look at your statistics.
Every key plays a note (xylophone, marimba, piano, vibraphone, glockenspiel).

This repository holds the downloads and the issues of XyloType. The source code is private.

## Download

Each version is published on the [Releases](https://github.com/Xylocopadream/XyloType/releases) page. Nothing to
install: unzip and run.

| System | File | Run it |
| --- | --- | --- |
| Windows x64 | `XyloType-vX.Y-win-x64.zip` | unzip anywhere, run `XyloType.exe` (Windows 10 1809 or later) |
| Windows x64 (desktop version) | `XyloType.Desktop-vX.Y-win-x64.zip` | unzip anywhere, run `XyloType.Desktop.exe` |
| Linux x64 | `XyloType.Desktop-vX.Y-linux-x64.tar.gz` | `tar -xzf` it, then `XyloType/install.sh` (installed for the user, with an entry in the applications menu; `install.sh --uninstall` removes it) |
| macOS (Apple Silicon / Intel) | `XyloType.Desktop-vX.Y-osx-arm64.zip` / `-osx-x64.zip` | unzip, move `XyloType.app` to Applications |

The apps are not signed yet:

- on Windows, SmartScreen asks for a confirmation the first time: "More info", then "Run anyway";
- on macOS, the app is not notarized by Apple: the first time, right click > Open
  (or `xattr -dr com.apple.quarantine XyloType.app`).

## Word and exercise packs

The app downloads them itself, from the pre-releases [`words`](https://github.com/Xylocopadream/XyloType/releases/tag/words)
(the most frequent words of each language) and [`exercises`](https://github.com/Xylocopadream/XyloType/releases/tag/exercises)
(progressive exercises for the AZERTY keyboard). They are offered at the first start.

## Issues

Found a bug, or have an idea? Open an [issue](https://github.com/Xylocopadream/XyloType/issues).

## Licence

XyloType is free to use. It is proprietary software: copyright (c) 2026 Xylocopadream, all rights reserved. It may not
be resold or redistributed.

Credits: the recorded instrument sounds come from the
[University of Iowa Electronic Music Studios](https://theremin.music.uiowa.edu/MIS.html); the word packs are built from
public domain books.
