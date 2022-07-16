## Simple Spawn No Block Plugin

Hello everyone i searched a long time for some decent working spawn no block plugin but haven't found anything that would satisfy me so i created my own plugin that works just as simple as i could imagine it should

## FEATURES
- On Player Spawn gives everyone noblock for specified amount of time and then automatically turns it off.
- It is configurable via cvars (Notifications, durations, from which round should noblock start).

## INSTALLATION AND CONFIGURATION

- Upload files to the sourcemod directory of your server and i hope it should work. Cvars are always generated in csgo/cfg/sourcemod directory 

## DEFAULT CVARS

```
// Toggle chat announcements.
// (1 - Enabled | 0 - Disabled)
// -
// Default: "1"
// Minimum: "0.000000"
// Maximum: "1.000000"
noblock_notification "1"

// Toggle noblock from specific round
// (1 - Enabled | 0 - Disabled)
// -
// Default: "0"
// Minimum: "0.000000"
// Maximum: "1.000000"
noblock_round_mode "0"

// From which round noblock should start working
// -
// Default: "1"
// Minimum: "0.000000"
// Maximum: "30.000000"
noblock_start_round "1"

// For how long noblock should be active after round starts
// -
// Default: "8.0"
// Minimum: "0.000000"
// Maximum: "20.000000"
noblock_time "8.0"
```

## 3RD PARTY INCLUDE IS USED!
I used MultiColors Snippet to make it work the way i wanted so there is a link just if you want to change something in the code ^.^

Multicolors - [CLICK HERE](https://forums.alliedmods.net/showthread.php?t=247770 "CLICK HERE")

## CURRENT LANGUAGES SUPPORT
- ENGLISH
- POLISH
