# Discord Devtools Filters

Filters for the devtools in Discord to clean it up.

## Discord Loggers

| | |
|:-:|:-:|
| `-/Hold\sUp!/ -/11\/10\schance\syou're\sbeing\sscammed/ -/attackers\saccess/ -/understand\sexactly/ -/discord\.com\/jobs/` ![](https://github.com/Kyza/discord-devtools-filters/blob/master/media/DiscordDevelopment_8SzhkAcAWa.png) | `-/\[Spellchecker\]/` |
| `-/\[Spotify\]/` | `-/\[Flux\]/` |
| `-/\[GatewaySocket\]/` | `-/\[RTCLatencyTestManager\]/` |
| `-/\[Logger\.tsx\]/` | `-/\[default\]\s\[.+\]/` |
| `-/\[MessageActionCreators\]/` | `-/\[RPCServer:IPC\]/` ![](https://github.com/Kyza/discord-devtools-filters/blob/master/media/RPCServerIPC.png) |

## Discord Errors

| | |
|:-:|:-:|
| `-/WebSocket\sconnection/` ![](https://github.com/Kyza/discord-devtools-filters/blob/master/media/Discord_kEQ9HvoxiO.png) | `-/status\sof\s\d{3}/` |
| `-/SourceMap/` | `-/SET_ACTIVITY/` |
| `-/DISCORD_NATIVE_MODULES_INSTALL/` | `-/EADDRINUSE/` |
| `-/The\sconnection\shas\sbeen\srevoked/` ![](https://github.com/Kyza/discord-devtools-filters/blob/master/media/DiscordCanary_gOz21e3NMf.png) | `-/GET\s.+\d{3}/` |

## Client Mod Crap

|  |  |
|:-:|:-:|
| `-/"pc-sdk"/` ![](https://github.com/Kyza/discord-devtools-filters/blob/master/media/DiscordCanary_wqy6WuWcKX.png) |
| `-/\[BdApi\]\sgetPlugin/` ![](https://github.com/Kyza/discord-devtools-filters/blob/master/media/getPlugin.png) |

All of them.

```regex
-/WebSocket\sconnection/ -/"pc-sdk"/ -/\[Spellchecker\]/ -/status\sof\s\d{3}/ -/The\sconnection\shas\sbeen\srevoked/ -/GET\s.+\d{3}/ -/\[Spotify\]/ -/\[Flux\]/ -/SourceMap/ -/\[RTCLatencyTestManager\]/ -/DISCORD_NATIVE_MODULES_INSTALL/ -/EADDRINUSE/ -/\[MessageActionCreators\]/ -/\[BdApi\]\sgetPlugin/ -/Hold\sUp!/ -/11\/10\schance\syou're\sbeing\sscammed/ -/attackers\saccess/ -/understand\sexactly/ -/discord\.com\/jobs/ -/SET_ACTIVITY/ -/\[RPCServer:IPC\]/
```
