# Luaddon
Usage:
In the root directory of the target process there will be a folder named "Lua" and inside that folder there will be a file named "modules_list.txt" which will contain the
relative path to all of the modules that are to be loaded once the cheat is injected, these modules can only be unloaded along the dll.

Module list example:
```
test.lua
```

Module example (test.lua):
```lua
Client.SetLuaEventCallback("on_inject", function()
	Client.Log("The boogieman is coming for you")
end)
```
