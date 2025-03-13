# XFuck Manuals/Tutorials
> XHOOK - Script
### FIRST PASTE LOADSTRING:
```lua
local XFUCK = loadstring(game:HttpGet("https://raw.githubusercontent.com/RobloxTurboX/XFuckProjects/refs/heads/main/XHOOK"),true)();
```
### HOW TO USE:
### "EventName" - Write RemoteEvent name
### "FireType" - Write or FireServer or InvokeServer (RemoteEvent/RemoteFunction)
```lua
XFUCK:XHOOK("RemoteEventName", "FireServer")
```
### HOW TO DISABLE:
```lua
XFUCK:XUNHOOK("RemoteEventName", "FireServer")
```
----------------------------------
> XINFO - Script
### COPY AND PASTE:
### TO EDIT CHOOSE OPTION THAT I WROTE IN CODE
```lua
getgenv().RemoteEvent = true -- set true or false
getgenv().Scripts = true -- set true or false
getgenv().ALL = true -- set true or false (Checking for scripts and RE)
loadstring(game:HttpGet("https://raw.githubusercontent.com/RobloxTurboX/XFuckProjects/refs/heads/main/XINFO"),true)()
```
