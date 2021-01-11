# Discord Devtools Filters

Filters for the devtools in Discord to clean it up.

## Discord Loggers

| | |
|:-:|:-:|
| `-/Hold\sUp!/ -/11\/10\schance\syou're\sbeing\sscammed/ -/attackers\saccess/ -/understand\sexactly/ -/discord\.com\/jobs/` ![](https://github.com/Kyza/discord-devtools-filters/blob/master/media/DiscordDevelopment_8SzhkAcAWa.png) | `-/\[RPCServer:IPC\]/` ![](https://github.com/Kyza/discord-devtools-filters/blob/master/media/RPCServerIPC.png) |
| `-/\[Spotify\]/` | `-/\[Flux\]/` |
| `-/\[GatewaySocket\]/` | `-/\[RTCLatencyTestManager\]/` |
| `-/\[Logger\.tsx\]/` | `-/\[default\]/` |
| `-/\[MessageActionCreators\]/` | `-/\[MessageStore\]/` |
| `-/\[FAST\sCONNECT\]/ -/Initializing\svoice/` | `-/\[GatewayDiscovery\]/` |
| `-/\[ConnectionStore\]/` | `-/\[RPCServer:WSS\]/ -/EADDRINUSE/` |
| `-/\[AuthenticationStore\]/` | `-/\[GuildAvailabilityStore\]/` |
| `-/\[NativeDispatchUtils\]/` | `-/\[Spellchecker\]/` |
| `-/\[RouterUtils\]/` |

```regex
-/Hold\sUp!/ -/11\/10\schance\syou're\sbeing\sscammed/ -/attackers\saccess/ -/understand\sexactly/ -/discord\.com\/jobs/ -/\[Spellchecker\]/ -/\[Spotify\]/ -/\[Flux\]/ -/\[GatewaySocket\]/ -/\[RTCLatencyTestManager\]/ -/\[Logger\.tsx\]/ -/\[default\]/ -/\[MessageActionCreators\]/ -/\[RPCServer:IPC\]/ -/\[FAST\sCONNECT\]/ -/Initializing\svoice/ -/\[GatewayDiscovery\]/ -/\[ConnectionStore\]/ -/\[RPCServer:WSS\]/ -/EADDRINUSE/  -/\[AuthenticationStore\]/ -/\[GuildAvailabilityStore\]/ -/\[NativeDispatchUtils\]/ -/\[RouterUtils\]/ -/\[MessageStore\]/
```

## Discord Errors

| | |
|:-:|:-:|
| `-/WebSocket\sconnection/` ![](https://github.com/Kyza/discord-devtools-filters/blob/master/media/Discord_kEQ9HvoxiO.png) | `-/The\sconnection\shas\sbeen\srevoked/` ![](https://github.com/Kyza/discord-devtools-filters/blob/master/media/DiscordCanary_gOz21e3NMf.png) |
| `-/SourceMap/` | `-/SET_ACTIVITY/` |
| `-/DISCORD_NATIVE_MODULES_INSTALL/` | `-/status\sof\s\d{3}/` |
| `-/GET\s.+\d{3}/` | `-/iterable\.length/` |
| `-/react-spring:\sThe\s"interpolate"/` | `-/(S|Uns)ubscribing\s(to|from)\sframes.+\d+/` |

```regex
-/WebSocket\sconnection/ -/status\sof\s\d{3}/ -/SourceMap/ -/SET_ACTIVITY/ -/DISCORD_NATIVE_MODULES_INSTALL/ -/The\sconnection\shas\sbeen\srevoked/ -/GET\s.+\d{3}/ -/iterable\.length/ -/react-spring:\sThe\s"interpolate"/ -/(S|Uns)ubscribing\s(to|from)\sframes.+\d+/
```

## Client Mod Crap

|  |  |
|:-:|:-:|
| `-/"pc-sdk"/` ![](https://github.com/Kyza/discord-devtools-filters/blob/master/media/DiscordCanary_wqy6WuWcKX.png) | `-/\[BdApi\]\sgetPlugin/` ![](https://github.com/Kyza/discord-devtools-filters/blob/master/media/getPlugin.png) |

```regex
-/"pc-sdk"/ -/\[BdApi\]\sgetPlugin/
```

## Everything

```regex
-/Hold\sUp!/ -/11\/10\schance\syou're\sbeing\sscammed/ -/attackers\saccess/ -/understand\sexactly/ -/discord\.com\/jobs/ -/\[Spellchecker\]/ -/\[Spotify\]/ -/\[Flux\]/ -/\[GatewaySocket\]/ -/\[RTCLatencyTestManager\]/ -/\[Logger\.tsx\]/ -/\[default\]/ -/\[MessageActionCreators\]/ -/\[RPCServer:IPC\]/ -/\[FAST\sCONNECT\]/ -/Initializing\svoice/ -/\[GatewayDiscovery\]/ -/\[ConnectionStore\]/ -/\[RPCServer:WSS\]/ -/EADDRINUSE/ -/\[AuthenticationStore\]/ -/\[GuildAvailabilityStore\]/ -/\[NativeDispatchUtils\]/ -/\[RouterUtils\]/ -/\[MessageStore\]/ -/WebSocket\sconnection/ -/status\sof\s\d{3}/ -/SourceMap/ -/SET_ACTIVITY/ -/DISCORD_NATIVE_MODULES_INSTALL/ -/The\sconnection\shas\sbeen\srevoked/ -/GET\s.+\d{3}/ -/iterable\.length/ -/react-spring:\sThe\s"interpolate"/ -/(S|Uns)ubscribing\s(to|from)\sframes.+\d+/ -/"pc-sdk"/ -/\[BdApi\]\sgetPlugin/
```
