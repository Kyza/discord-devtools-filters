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
```
