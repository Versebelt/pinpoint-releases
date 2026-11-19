# Pinpoint

**Broadcast software for GeoGuessr tournaments, by Adillo Productions.**

Pinpoint gives you:
- a control room in your browser;
- live graphics that follow the GeoGuessr presenter mode;
- outputs for vMix and OBS;
- tournaments you can run right in the app: players, knockouts, leagues and groups.

This repository only holds the installers and release notes.

## Download

Get the latest `Pinpoint-Setup-<version>-algemeen.exe` from [Releases](../../releases/latest) and run it. You need Windows 10 or 11.

Pinpoint installs to `C:\Program Files\Adillo Productions\Pinpoint`. Your settings and data live in `%APPDATA%\Adillo Productions\Pinpoint` and stay there when you update. Pinpoint tells you in the control room when a new version is available.

The installer is not code-signed yet. Windows SmartScreen may show "Windows protected your PC": choose **More info → Run anyway**.

## Getting started

1. Start Pinpoint from the Start menu. The control room opens at `http://localhost:4646/control/`, and a short welcome wizard guides you through the first steps.
2. Add your players under **Setup → Players**. You can add them one by one, import a CSV, or paste a GeoGuessr profile link.
3. Create a tournament under **Setup → Tournament**: knockout, league, or groups followed by a knockout.
4. Add the outputs to vMix or OBS as a browser source (1920×1080). For example:
   - `http://localhost:4646/output/stream/` (all in one)
   - `http://localhost:4646/output/bracket/`
   - `http://localhost:4646/output/stand/`

## Basic and Pro

Pinpoint Basic is free and shows a small "Powered by Pinpoint" watermark.

Pinpoint Pro removes the watermark and adds:
- OMT output (with alpha and sound);
- your own stingers, with export;
- Make with AI and Claude (MCP);
- a second stream;
- the remote page for casters.

Pro licenses come from Adillo Productions.

---

GeoGuessr is a trademark of GeoGuessr AB. Pinpoint is not affiliated with or endorsed by GeoGuessr AB.
