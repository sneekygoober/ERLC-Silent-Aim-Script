# ERLC-Silent-Aim-Script
Sorry to anyone wanting to view the source, I've obfuscated it so that the ERLC developers don't patch this too quickly.
This script is not open-source. You can also view this script over at [scriptblox.com](https://scriptblox.com/script/Emergency-Response:-Liberty-County-Silent-Aim-Keyless-110687) or [haxhell.com](https://haxhell.com/scripts/emergency-response-liberty-county-emergency-response-liberty-county-silent-aim-keyless) or [rscripts.net](https://rscripts.net/script/emergency-response-liberty-county-silent-aim-keyless-VK4r).

Default Team settings:
```lua
--[[
2 = Silent aim doesn't target at all,
1 = Silent aim only targets 0 if you're on 1,
0 = Silent aim targets both 0 and 1 if you're on 0.
]]
getgenv().teams = {
    ["Civilian"] = 0,
    ["DOT"] = 2,
    ["Fire"] = 2,
    ["Jail"] = 2,
    ["Police"] = 1,
    ["Sheriff"] = 1
};
loadstring(game:HttpGet("https://raw.githubusercontent.com/sneekygoober/ERLC-Silent-Aim-Script/refs/heads/main/main.luau"))();
```
