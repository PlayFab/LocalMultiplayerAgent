# LocalMultiplayerAgent
An executable that mimics PlayFab Multiplayer Servers (Thunderhead) operations to aid in local debugging.

Check the [Releases](https://github.com/PlayFab/LocalMultiplayerAgent/releases) page to download the latest version and then follow the [Local Debug Instructions](https://docs.microsoft.com/en-us/gaming/playfab/features/multiplayer/servers/locally-debugging-game-servers-and-integration-with-playfab) for usage. Also check out the main [Multiplayer Server Documentation](https://docs.microsoft.com/en-us/gaming/playfab/features/multiplayer/servers/) for more information.

## Release notes
- Release 0.9.2: LocalMultiplayerAgent is now code-signed, plus fixes for [#8](https://github.com/PlayFab/LocalMultiplayerAgent/issues/8) and [#9](https://github.com/PlayFab/LocalMultiplayerAgent/issues/9)
- Release 0.9.1: Updates the PlayFab image version that gets pulled down to wsc-10.0.17763.973.1
- Release 0.9: Updates configuration format and supports settings resources constraints on containers
- Release 0.8: supporting running containerized Linux game servers on Windows. Download [here](https://github.com/PlayFab/LocalMultiplayerAgent/releases/tag/v0.8), instructions [here](linuxContainersOnWindows.md)
