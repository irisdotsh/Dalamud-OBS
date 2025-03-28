# Dalamud-OBS

A Dalamud plugin that communicates with OBS by websocket.

## Requirements

You need to install two plugins to your OBS:

### OBS 30+

You only need the OBS Composite Blur plugin to be installed into your OBS.

- [OBS Composite Blur](https://github.com/FiniteSingularity/obs-composite-blur): for the blur function.

### OBS 28

Besides OBS Composite Blur, you still need to use OBS-websocket plugin 4.9.1-compat instead of the built-in one because the api 5 is not backward compatible and it lacks some of the APIs in api 4.

- [OBS Composite Blur](https://github.com/FiniteSingularity/obs-composite-blur): for the blur function.
- [OBS-websocket 4.9.1-compat](https://github.com/obsproject/obs-websocket/releases/tag/4.9.1-compat): for communication with this plugin.

### OBS 27

Please upgrade to OBS 28+

## Installation

You can add my [repository](https://raw.githubusercontent.com/irisdotsh/DalamudPlugins/refs/heads/main/pluginmaster.json) in Dalamud.
