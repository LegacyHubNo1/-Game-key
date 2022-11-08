game.StarterGui:SetCore("SendNotification", {
      Title = "Legacy Hub", 
      Text = "Whitelist✅",
  })
  
  -- New example script written by wally
-- You can suggest changes with a pull request or something

local repo = 'https://raw.githubusercontent.com/wally-rblx/LinoriaLib/main/'

local Library = loadstring(game:HttpGet(repo .. 'Library.lua'))()
local ThemeManager = loadstring(game:HttpGet(repo .. 'addons/ThemeManager.lua'))()
local SaveManager = loadstring(game:HttpGet(repo .. 'addons/SaveManager.lua'))()

local Window = Library:CreateWindow({
    -- Set Center to true if you want the menu to appear in the center
    -- Set AutoShow to true if you want the menu to appear when it is created
    -- Position and Size are also valid options here
    -- but you do not need to define them unless you are changing them :)

    Title = 'LegacyHub Script',
    Center = true, 
    AutoShow = true,
})

-- You do not have to set your tabs & groups up this way, just a prefrence.
local Tabs = {
    -- Creates a new tab titled Main
    Main = Window:AddTab('Main'), 
    ['UI Settings'] = Window:AddTab('UI Settings'),
}

-- Groupbox and Tabbox inherit the same functions
-- except Tabboxes you have to call the functions on a tab (Tabbox:AddTab(name))
local LeftGroupBox = Tabs.Main:AddLeftGroupbox('Natural Disaster Survival')

LeftGroupBox:AddLabel('Teleport')

local MyButton = LeftGroupBox:AddButton('Natural Disaster', function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-109.402374, 47.3999901, 21.2869263, 0.69302851, -1.26104027e-09, 0.720910132, 4.78341922e-10, 1, 1.2893917e-09, -0.720910132, -5.48743717e-10, 0.69302851)
end)

local MyButton = LeftGroupBox:AddButton('Lobby', function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-279.14328, 179.499954, 340.541046, -0.742916226, -4.47895854e-09, 0.66938442, -3.39616406e-08, 1, -3.10011607e-08, -0.66938442, -4.57646578e-08, -0.742916226)
end)

local LeftGroupBox = Tabs.Main:AddLeftGroupbox('Build to Survive')

LeftGroupBox:AddLabel('Teleport')

local MyButton = LeftGroupBox:AddButton('Save Zone', function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-181.674545, 48.9528389, -120.558723, 0.972822428, -8.06887979e-09, 0.231552348, 2.29864678e-08, 1, -6.17263112e-08, -0.231552348, 6.53713172e-08, 0.972822428)
end)

local LeftGroupBox = Tabs.Main:AddLeftGroupbox('[UPDATE 4☀️⚫️] King Legacy')

LeftGroupBox:AddLabel('New World')

local MyButton = LeftGroupBox:AddButton('Floresco', function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-3658.23608, 57.3348122, 164.358841, 0.682591915, 5.4886268e-08, -0.730799735, 2.86835906e-08, 1, 1.01895843e-07, 0.730799735, -9.05152433e-08, 0.682591915)
end)

local MyButton = LeftGroupBox:AddButton('PirateSkulllsland', function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-9291.79004, 57.7262154, -5020.65186, 0.607958317, -1.810435e-08, -0.793968916, 5.05802555e-09, 1, -1.89293079e-08, 0.793968916, 7.49231521e-09, 0.607958317)
end)

local MyButton = LeftGroupBox:AddButton('SoldierHeadauater', function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-10276.4375, 99.7206955, 1277.05713, 0.795757055, 0, -0.605615973, 0, 1, 0, 0.605615973, 0, 0.795757055)
end)

local MyButton = LeftGroupBox:AddButton('Skulllsland', function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-6496.14795, 58.0217972, 6121.37549, -0.973301768, 0, -0.229529262, 0, 1, 0, 0.229529262, 0, -0.973301768)
end)

local MyButton = LeftGroupBox:AddButton('ShredEndanger', function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-186.430405, 397.694153, -2805.73901, -0.439078331, 0, -0.898448765, 0, 1, 0, 0.898448765, 0, -0.439078331)
end)

local MyButton = LeftGroupBox:AddButton('DeadTundra', function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1163.15161, 57.6705704, 927.798401, 0.477373719, -0.277713835, 0.833660245, -9.99867916e-06, 0.948740602, 0.316055804, -0.878700376, -0.150885046, 0.452901006)
end)

local MyButton = LeftGroupBox:AddButton('Loaflslant', function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1580.90686, 488.882782, 8473.06152, -0.978860736, 0, -0.204529539, 0, 1, 0, 0.204529539, 0, -0.978860736)
end)

LeftGroupBox:AddLabel('Old World')

local MyButton = LeftGroupBox:AddButton('Zombielslant', function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-2562.84644, 26.4662991, 3760.49561, -0.469741553, 6.65214239e-09, 0.882803977, -1.55230762e-09, 1, -8.36122815e-09, -0.882803977, -5.29799982e-09, -0.469741553)
end)

local MyButton = LeftGroupBox:AddButton('Warlslant', function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(2361.53589, 50.8705673, -2110.52271, -0.722530603, -3.87031141e-05, -0.691338897, 4.46237436e-06, 1, -6.06465437e-05, 0.691338897, -4.69039987e-05, -0.722530603)
end)

local MyButton = LeftGroupBox:AddButton('Snow', function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-5464.81934, 18.313633, -1323.65698, -0.328853548, 4.46959945e-08, 0.944380939, -8.83463969e-10, 1, -4.76359965e-08, -0.944380939, -1.64995928e-08, -0.328853548)
end)

 -- Sets keybind to MB2, mode to Hold

-- Library functions
-- Sets the watermark visibility
Library:SetWatermarkVisibility(true)

-- Sets the watermark text
Library:SetWatermark('This is a really long watermark to text the resizing')

Library.KeybindFrame.Visible = true; -- todo: add a function for this

Library:OnUnload(function()
    print('Unloaded!')
    Library.Unloaded = true
end)

-- UI Settings
local MenuGroup = Tabs['UI Settings']:AddLeftGroupbox('Menu')

-- I set NoUI so it does not show up in the keybinds menu
MenuGroup:AddButton('Unload', function() Library:Unload() end)
MenuGroup:AddLabel('Menu bind'):AddKeyPicker('MenuKeybind', { Default = 'G', NoUI = true, Text = 'Menu keybind' }) 

Library.ToggleKeybind = Options.MenuKeybind -- Allows you to have a custom keybind for the menu

-- Addons:
-- SaveManager (Allows you to have a configuration system)
-- ThemeManager (Allows you to have a menu theme system)

-- Hand the library over to our managers
ThemeManager:SetLibrary(Library)
SaveManager:SetLibrary(Library)

-- Ignore keys that are used by ThemeManager. 
-- (we dont want configs to save themes, do we?)
SaveManager:IgnoreThemeSettings() 

-- Adds our MenuKeybind to the ignore list 
-- (do you want each config to have a different menu key? probably not.)
SaveManager:SetIgnoreIndexes({ 'MenuKeybind' }) 

-- use case for doing it this way: 
-- a script hub could have themes in a global folder
-- and game configs in a separate folder per game
ThemeManager:SetFolder('MyScriptHub')
SaveManager:SetFolder('MyScriptHub/specific-game')

-- Builds our config menu on the right side of our tab
SaveManager:BuildConfigSection(Tabs['UI Settings']) 

-- Builds our theme menu (with plenty of built in themes) on the left side
-- NOTE: you can also call ThemeManager:ApplyToGroupbox to add it to a specific groupbox
ThemeManager:ApplyToTab(Tabs['UI Settings'])

-- You can use the SaveManager:LoadAutoloadConfig() to load a config 
-- which has been marked to be one that auto loads!
