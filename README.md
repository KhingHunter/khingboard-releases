# KhingBoard releases

Public distribution for [KhingBoard](https://github.com/KhingHunter/KhingBoard),
an AI-first infinite whiteboard for macOS.

This repository holds two things:

- `appcast.xml`, the Sparkle update feed the shipped app reads once a day.
- One GitHub Release per version, with the notarised `.dmg` attached.

Both must stay reachable while logged out: the app carries no GitHub token, so a
private URL would return 404 to the updater with no useful error.

Download the current version from the
[latest release](https://github.com/KhingHunter/khingboard-releases/releases/latest).

Source lives in a separate, private repository. Issues and discussion belong there.
