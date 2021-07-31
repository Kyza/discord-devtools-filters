# Discord Devtools Filters

Filters for the devtools in Discord to clean it up.

```regex
-/^\[(?!BetterDiscord|Powercord).+\]/ 
-/^Failed\sto\sload\sresource:/ 
-/^Websocket\sconnection\sto\s'.+'\sfailed:/ 
-/^DevTools\sfailed\sto\sload\s(source\smap|SourceMap):/ 
-/^(GET|PUT|POST|DELETE).+\d{3}/ 
-/^Initializing\svoice\sengine\swith\saudio\ssubsystem:\s(true|false)$/ 
-/^ConnectionEventFramerateReducer:\s(true|false)\.$/ 
-/^Starting\sASRP$/ 
-/^updateVideoQuality:\s.+/ 
-/^(GET|POST).+net::(ERR_NAME_NOT_RESOLVED|ERR_NETWORK_CHANGED|ERR_CONNECTION_CLOSED)/ 
-/Possible\scauses:\sthe\snetwork\sis\soffline/ 
-/^\d+\slog\sentries\sare\snot\sshown\./ 
-/^(Uns|s)ubscribing\s(from|to)\sframes\sfor\sstreamId\s\d+$/ 
-/^Hold\sUp!$/ 
-/^Uncaught\sError:\slisten\sEADDRINUSE:\saddress\salready\sin\suse\s127\.0\.0\.1:\d+/ 
-/^If\ssomeone\stold\syou\sto\scopy/paste\ssomething\shere\syou\shave\san\s11/10\schance\syou're\sbeing\sscammed\.$/ 
-/^Pasting\sanything\sin\shere\scould\sgive\sattackers\saccess\sto\syour\sDiscord\saccount\.$/ 
-/^Unless\syou\sunderstand\sexactly\swhat\syou\sare\sdoing,\sclose\sthis\swindow\sand\sstay\ssafe\.$/ 
-/^If\syou\sdo\sunderstand\sexactly\swhat\syou\sare\sdoing,\syou\sshould\scome\swork\swith\sus\shttps://(canary.d|ptb.d|d)iscord.com/jobs$/ 
-/Failed\sto\sconstruct\s'PresentationRequest':/ 
-/^react-spring:.+deprecated/ 
-/The\splay\(\)\srequest\swas\sinterrupted\sby\sa\scall\sto\spause\(\)\./ 
-/Uncaught\s\(in\spromise\)/ 
-/BaseConnection\.userSpeakingChange:\s/ 
-/BaseWebRTCConnection/ 
```

Single line for old Chrome devtools.

```regex
-/^\[(?!BetterDiscord|Powercord).+\]/ -/^Failed\sto\sload\sresource:/ -/^Websocket\sconnection\sto\s'.+'\sfailed:/ -/^DevTools\sfailed\sto\sload\s(source\smap|SourceMap):/ -/^(GET|PUT|POST|DELETE).+\d{3}/ -/^Initializing\svoice\sengine\swith\saudio\ssubsystem:\s(true|false)$/ -/^ConnectionEventFramerateReducer:\s(true|false)\.$/ -/^Starting\sASRP$/ -/^updateVideoQuality:\s.+/ -/^(GET|POST).+net::(ERR_NAME_NOT_RESOLVED|ERR_NETWORK_CHANGED|ERR_CONNECTION_CLOSED)/ -/Possible\scauses:\sthe\snetwork\sis\soffline/ -/^\d+\slog\sentries\sare\snot\sshown\./ -/^(Uns|s)ubscribing\s(from|to)\sframes\sfor\sstreamId\s\d+$/ -/^Hold\sUp!$/ -/^Uncaught\sError:\slisten\sEADDRINUSE:\saddress\salready\sin\suse\s127\.0\.0\.1:\d+/ -/^If\ssomeone\stold\syou\sto\scopy/paste\ssomething\shere\syou\shave\san\s11/10\schance\syou're\sbeing\sscammed\.$/ -/^Pasting\sanything\sin\shere\scould\sgive\sattackers\saccess\sto\syour\sDiscord\saccount\.$/ -/^Unless\syou\sunderstand\sexactly\swhat\syou\sare\sdoing,\sclose\sthis\swindow\sand\sstay\ssafe\.$/ -/^If\syou\sdo\sunderstand\sexactly\swhat\syou\sare\sdoing,\syou\sshould\scome\swork\swith\sus\shttps://(canary.d|ptb.d|d)iscord.com/jobs$/ -/Failed\sto\sconstruct\s'PresentationRequest':/ -/^react-spring:.+deprecated/ -/The\splay\(\)\srequest\swas\sinterrupted\sby\sa\scall\sto\spause\(\)\./ -/Uncaught\s\(in\spromise\)/ -/BaseConnection\.userSpeakingChange:\s/ -/BaseWebRTCConnection/ 
```
