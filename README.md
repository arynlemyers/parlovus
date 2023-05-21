# Parvus  
Free Roblox Script Hub designed for shooters.  
Made With :heart: By ***AlexR32#0157***

- ***This script is still in beta stage of development, so expect some bugs or lack of features.***  
- ***This script only officially supports Synapse X, since I'm making this script with Synapse, so if you have problems running this script on other executors, just remember that it might be your executor.***  
- ***Please do not modify this script without my permission, or redistribute it without any credit to me.***  

### Loadstring
```lua
local IsDevelopmentBranch,NotificationTime = false,5
local Branch = IsDevelopmentBranch and "development" or "main"
local Source = "https://raw.githubusercontent.com/AlexR32/Parvus/" .. Branch .. "/"
loadstring(game:HttpGet(Source .. "Loader.lua"),"Loader")(Branch,NotificationTime)

```
