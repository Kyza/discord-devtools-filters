# Discord Devtools Filters

Filters for the devtools in Discord to clean it up.

| `-/WebSocket\sconnection/` | `-/"pc-sdk"/` |
| -- | -- |
| ![](https://github.com/Kyza/discord-devtools-filters/blob/master/media/Discord_kEQ9HvoxiO.png) | ![](https://github.com/Kyza/discord-devtools-filters/blob/master/media/DiscordCanary_wqy6WuWcKX.png) |
| `-/\[Spellchecker\]\ssh/` | `-/status\sof\s\d{3}/` |
| `-/The\sconnection\shas\sbeen\srevoked/` | `-/GET\s.+\d{3}/` |
| `-/\[Spotify\]/` | `-/\[Flux\]/` |
| `-/SourceMap/` | `-/\[RTCLatencyTestManager\]/` |
| `-/DISCORD_NATIVE_MODULES_INSTALL/` | `-/EADDRINUSE/` |

All of them.

```regex
-/WebSocket\sconnection/ -/"pc-sdk"/ -/\[Spellchecker\]\ssh/ -/status\sof\s\d{3}/ -/The\sconnection\shas\sbeen\srevoked/ -/GET\s.+\d{3}/ -/\[Spotify\]/ -/\[Flux\]/ -/SourceMap/ -/\[RTCLatencyTestManager\]/ -/DISCORD_NATIVE_MODULES_INSTALL/ -/EADDRINUSE/
```
