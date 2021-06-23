# Discord Devtools Filters

Filters for the devtools in Discord to clean it up.

```regex
-/^\[.+\]/ 
-/Failed\sto\sload\sresource:/ 
-/Websocket\sconnection\sto\s'.+'\sfailed:/ 
-/DevTools\sfailed\sto\sload\ssource\smap:/ 
-/(GET|PUT).+\d{3}/ 
-/Initializing\svoice\sengine\swith\saudio\ssubsystem:\s(true|false)/ 
-/ConnectionEventFramerateReducer:\s(true|false)./ 
-/updateVideoQuality:\s.+/ 
-/(GET|POST).+net::(ERR_NAME_NOT_RESOLVED|ERR_NETWORK_CHANGED)/ 
-/Possible\scauses:\sthe\snetwork\sis\soffline/ 
-/\d+\slog\sentries\sare\snot\sshown\./ 
```
