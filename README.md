# Discord Devtools Filters

Filters for the devtools in Discord to clean it up.

|  |  |
|:-:|:-:|
| `-/WebSocket\sconnection/` ![](https://github.com/Kyza/discord-devtools-filters/blob/master/media/Discord_kEQ9HvoxiO.png) | `-/"pc-sdk"/` ![](https://github.com/Kyza/discord-devtools-filters/blob/master/media/DiscordCanary_wqy6WuWcKX.png) |
| `-/\[Spellchecker\]\ssh/` | `-/status\sof\s\d{3}/` |
| `-/The\sconnection\shas\sbeen\srevoked/` ![](https://github.com/Kyza/discord-devtools-filters/blob/master/media/DiscordCanary_gOz21e3NMf.png) | `-/GET\s.+\d{3}/` |
| `-/\[Spotify\]/` | `-/\[Flux\]/` |
| `-/SourceMap/` | `-/\[RTCLatencyTestManager\]/` |
| `-/DISCORD_NATIVE_MODULES_INSTALL/` | `-/EADDRINUSE/` |
| `-/\[MessageActionCreators\]/` | `-/\[BdApi\]\sgetPlugin/` ![](https://github.com/Kyza/discord-devtools-filters/blob/master/media/getPlugin.png) |
| `-/Hold\sUp!/ -/11\/10\schance\syou're\sbeing\sscammed/ -/attackers\saccess/ -/understand\sexactly/ -/discord\.com\/jobs/` ![](https://github.com/Kyza/discord-devtools-filters/blob/master/media/DiscordDevelopment_8SzhkAcAWa.png) | `-/SET_ACTIVITY/` |
| `-/\[RPCServer:IPC\]/` ![](https://github.com/Kyza/discord-devtools-filters/blob/master/media/RPCServerIPC.png) |  |

All of them.

```regex
-/WebSocket\sconnection/ -/"pc-sdk"/ -/\[Spellchecker\]\ssh/ -/status\sof\s\d{3}/ -/The\sconnection\shas\sbeen\srevoked/ -/GET\s.+\d{3}/ -/\[Spotify\]/ -/\[Flux\]/ -/SourceMap/ -/\[RTCLatencyTestManager\]/ -/DISCORD_NATIVE_MODULES_INSTALL/ -/EADDRINUSE/ -/\[MessageActionCreators\]/ -/\[BdApi\]\sgetPlugin/ -/Hold\sUp!/ -/11\/10\schance\syou're\sbeing\sscammed/ -/attackers\saccess/ -/understand\sexactly/ -/discord\.com\/jobs/ -/SET_ACTIVITY/ -/\[RPCServer:IPC\]/
```
