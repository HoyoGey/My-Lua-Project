<p align="center">
  <img src="https://github.com/HoyoGey/My-Lua-Project/blob/main/asset/hababa.png?raw=true" width="380" height="100">
</p>	
<img src="https://raw.githubusercontent.com/matfantinel/matfantinel/master/waves.svg" width="100%" height="150">
<img src="https://media.discordapp.net/attachments/1036352264765448283/1040255090394673212/image.png" width="100%" height="100%">

# Info
Key System Libary Documetation 

Join our discord server https://discord.gg/cn7HAncu55 <img src="https://cdn.discordapp.com/emojis/1038875387826020352.webp?size=96&quality=lossless" width="2%" height="2%">


## English

```lua
local key = loadstring(game:HttpGet("https://raw.githubusercontent.com/HoyoGey/My-Lua-Project/main/UiLibs/KeySysUiLib.lua%22))()
key:MakeUI({
  Title = "Ur Title",
  KeyLinkName = "CocoNigga",
  DiscordLink = "discord.gg/123123123",
  ScriptLink = "link"
  FileKey = "Sex.lua"
})
```

How find KeyLinkName
<img src="https://media.discordapp.net/attachments/1035523592630308927/1040630995684171878/image.png" width="100%" height="100%">

How to use ScriptLink
Add link on next script and add on ur script this code

```lua
local notif = loadstring(game:HttpGet("https://raw.githubusercontent.com/HoyoGey/My-Lua-Project/main/UiLibs/NotifyLib.lua"))()

local is_key_present = isfile("Sex.lua");
if is_key_present == true then
    local kery = readfile("Sex.lua");
    local onl_key = game:HttpGet("https://keysystem.ml/name?verify_key=" .. kery)
    if kery == onl_key then
        print("Executed script!");
        notif:Notification("Secceful", "Key Valid", 5)
-- full script here:)
    end
else
    --wrong key
    notif:Notification("Wrong", "Key InValid", 5)
end
```
