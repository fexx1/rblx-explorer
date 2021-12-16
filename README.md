# rblxexplorer
A basic explorer meant to VIEW the structure of the game. Does not show all object properties and lacks many features expected in a full explorer but is very lightweight.
```
-- Modified/fixed by the uploader [I did not make the original; unknown source]
-- A simple lightweight explorer meant sheerly for exploring the layout/structure. Does detect Ancestry and ChildAdded/Removed , but does not auto-update properties.

-- Color override example: (NOTE: colors will appear darker because BackgroundTransparency over a black background)
--[[_G.DrakExplorerColors = { -- Color override by class
["Workspace"] = Color3.new(0,1,0), ["Players"] = Color3.new(0,1,0), ["ReplicatedStorage"] = Color3.new(0,1,0),
["Script"] = Color3.new(0.5, 0.5, 0.8), ["LocalScript"] = Color3.new(1, 0, 0), ["CoreScript"] = Color3.new(0.5, 0.5, 0.8),
["Model"] = Color3.new(1, 1, 0), ["BasePart"] = Color3.new(0.4, 0.4, 0.4)
}
_G.DrakExplorerColors2 = { -- Color override by inheritance 
["BasePart"] = Color3.new(0.4, 0.4, 0.4)
}]]

loadstring(game:HttpGet(("https://raw.githubusercontent.com/drakker33/rblxexplorer/main/Explorer.lua"), true))()
```
