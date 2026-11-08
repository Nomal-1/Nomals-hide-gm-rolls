> **Nomal's personal build of [sPOiDar/fvtt-module-hide-gm-rolls](https://github.com/sPOiDar/fvtt-module-hide-gm-rolls) 0.15.4** (MIT, see LICENSE).
> Kept only until upstream supports Foundry 14, then switch back to the original. Published so Foundry can install it from the manifest URL. Changes: the v13/v14 chat API fixes from upstream PR #52 (`renderChatMessageHTML`, `ChatLog.notify` path)
> plus `foundry.utils.isNewerVersion` (the global `isNewerVersion` no longer exists in Foundry 14), and the manifest range is raised to 14.

# Foundry VTT - Hide GM Rolls

![Release](https://github.com/sPOiDar/fvtt-module-hide-gm-rolls/workflows/Release/badge.svg)
![Forge Users](https://img.shields.io/badge/dynamic/json?color=blue&label=Forge%20Users&query=package.installs&suffix=%25&url=https%3A%2F%2Fforge-vtt.com%2Fapi%2Fbazaar%2Fpackage%2Fhide-gm-rolls)
![Foundry Version](https://img.shields.io/badge/dynamic/json?color=blue&label=Foundry%20Version&prefix=v&query=%24.compatibleCoreVersion&url=https%3A%2F%2Fgithub.com%2FsPOiDar%2Ffvtt-module-hide-gm-rolls%2Fraw%2Fmaster%2Fmodule.json)

Some GMs prefer to limit the information that players receive, to maintain the mystery. For example you may wish to hide the bonuses that your legendary creature gets on its rolls, or to roll truly in the blind when an event occurs, without alerting your players to it.

This module allows sanitizing public GM rolls by hiding formulas and breakdowns from players, showing just the total instead. It can also hide private GM rolls from players entirely.

## Acknowledgements

- **BlueSkyBlackBird** German translation
