local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("Cat Hub V 1.0.0 | This Gui Made By Cat#2728", "DarkTheme")

local Main = Window:NewTab("Npc")
local MainSection = Main:NewSection("Npc Stuff")
--script
MainSection:NewButton("Santa", "Gives Santa Present", function()
    workspace.Merchants.SantaMerchant.Clickable.Retum:FireServer()
end)

MainSection:NewButton("Open Sam", "Open Sam", function() 
fireclickdetector(game:GetService("Workspace").Merchants.QuestMerchant.Clickable.ClickDetector) 
end)

local Main = Window:NewTab("Teleport")
local MainSection = Main:NewSection("Teleport Npc")

--script
MainSection:NewButton("Sam", "Teleports you to Sam", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1302, 218, -1353)
end)

MainSection:NewButton("Drink", "Teleports you to Drink Merchant", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1282, 218, -1367)
end)

MainSection:NewButton("Better Drink", "Teleports you to Better Drink Merchant", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1493, 260, 2171)
end)

MainSection:NewButton("Flail", "Teleports you to flail Sword Seller", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1110, 217, 3366)
end)

MainSection:NewButton("Rod Quest", "Teleports you to Fish Quest", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1699, 216, -326)
end)

MainSection:NewButton("Krizma Seller", "Teleports you to Krizma Seller", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1074, 361, 1670)
end)

MainSection:NewButton("Sword Seller", "Teleports you to Sword Seller", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1007, 224, -3338)
end)

MainSection:NewButton("Gun Seller", "Teleports you to Gun Seller", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1843, 222, 3408)
end)

MainSection:NewButton("Emote", "Teleports you to Emote Seller", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1517, 260, 2166)
end)

MainSection:NewButton("Affinity", "Teleports you to Affinity Merchant", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(117, 278, 4948)
end)

MainSection:NewButton("Mixer", "Teleports you to Mixer and Fish Merchant", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1991, 218, 566)
end)

MainSection:NewButton("Mission Assignment", "Teleports you to Mission Assignment", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(901, 270, 1219)
end)

MainSection:NewButton("Santa", "Teleports you to Santa", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(711, 241, 1249)
end)

local Main = Window:NewTab("Island")
local MainSection = Main:NewSection("Island")
MainSection:NewButton("Orange House Island", "Teleports you to Orange House Island", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(729, 241, 1192)
end)

MainSection:NewButton("Windmill Island", "Teleports you to Windmill Island", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-8, 224, -91)
end)

MainSection:NewButton("Money Farm Island", "Teleports you to Money Farm Island", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1110, 218, 1673)
end)

MainSection:NewButton("Cave Island", "Teleports you to Cave Island", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-68, 216, -893)
end)

MainSection:NewButton("Pursuer Island", "Teleports you to Pursuer Island", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(4847, 570, -7143)
end)

MainSection:NewButton("Bar Island", "Teleports you to Bar Island", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1494, 264, 2133)
end)

MainSection:NewButton("Snow Mountain", "Teleports you to Snow Mountain", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(6654, 418, -1468)
end)

MainSection:NewButton("Vokun Island", "Teleports you to Vokun Island", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(4574, 217, 4962)
end)

MainSection:NewButton("Green Island", "Teleports you to Green Island", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-2727, 253, 1041)
end)

MainSection:NewButton("Flail Island", "Teleports you to Flail Island", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1068, 217, 3351)
end)

MainSection:NewButton("Sam Island", "Teleports you to Sam Island", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1283, 218, -1348)
end)

MainSection:NewButton("Pyramid Island", "Teleports you to Pyramid Island", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(118, 216, 4773)
end)

MainSection:NewButton("Fish Quest Island", "Teleports you to Boar Island", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1668, 217, -300)
end)

MainSection:NewButton("Mountain", "Teleports you to Mountain", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1896, 222, 3385)
end)

MainSection:NewButton("Snowy Island", "Teleports you to Snowy Island", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(2053, 488, -700)
end)

MainSection:NewButton("Marine Ford", "Teleports you to Marine Ford", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-3164, 296, -3780)
end)

MainSection:NewButton("Desert Island", "Teleports you to Desert Island", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(896, 224, -3275)
end)

MainSection:NewButton("Trees Island", "Teleports you to Trees Island", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-5781, 216, 114)
end)

MainSection:NewButton("Purple Island", "Teleports you to Purple Island", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-5168, 523, -7800)
end)

MainSection:NewButton("Mini Mountain", "Teleports you to Mini Mountain", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(3193, 357, 1670)
end)

MainSection:NewButton("Islands", "Teleports you to Islands", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-4329, 245, 5252)
end)

MainSection:NewButton("Town", "Teleports you to Town", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1818, 218, 755)
end)

MainSection:NewButton("Rocky", "Teleports you to Rocky Island", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-37, 229, 2149)
end)

MainSection:NewButton("Palm", "Teleports you to Palm Island", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(766, 216, -1374)
end)

MainSection:NewButton("Sand", "Teleports you to Sand Island", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-2747, 216, -942)
end)

MainSection:NewButton("Sand2", "Teleports you to Another Sand Island", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(162, 226, -2265)
end)

MainSection:NewButton("Small", "Teleports you to Small Island", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1237, 240, -244)
end)

MainSection:NewButton("Tiny", "Teleports you to Tiny Island", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1229, 227, 623)
end)

MainSection:NewButton("Super Tiny", "Teleports you to Super Tiny Island", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-4007, 216, -2189)
end)

MainSection:NewButton("Grass", "Teleports you to Small Grass Island touch some grass", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(2147, 217, -1911)
end)

local Main = Window:NewTab("Misc")
local MainSection = Main:NewSection("Random Stuffs")

MainSection:NewButton("Go to compass", "go to compass", function() 
local CharacterName = game.Players.LocalPlayer.Character
local pl2 = game:GetService("Players").LocalPlayer
local pl3 = pl2.Backpack.Compass.Poser.Value
local ply = game.Players.LocalPlayer.Character.HumanoidRootPart 
ply.CFrame = CFrame.new(pl3) 
end)


MainSection:NewButton("Go To Package", "Go To Package", function()
local CharacterName = game.Players.LocalPlayer.Character
local pl2 = game:GetService("Players").LocalPlayer
local pl3 = pl2.Backpack.Package.Poser.Value
local ply = game.Players.LocalPlayer.Character.HumanoidRootPart 
ply.CFrame = CFrame.new(pl3) 
end)

MainSection:NewToggle("Auto Bring Fruit", "Auto Bring Fruit", function(state) 
if state then Fbring = state 
while Fbring == true do 
wait() 
local placeF = game:GetService("Workspace").Trees 
for i, v in pairs(placeF:GetDescendants()) do 
if v.Name == "ClickDetector" then 
fireclickdetector(v) 
end 
end 
end 
else 
Fbring = state 
while Fbring == true do 
print('Repeat Stopped') 
end 
end 
end)

local Main = Window:NewTab("Auto Farm")
local MainSection = Main:NewSection("Auto farm")

MainSection:NewButton("Auto Farm Npc", "This Only Works With Candy Body Or Magma Body Or Other Fruit Skills Or Use Gun", function()
funaction(state)
Auto Farm = state
while state true
wait()
    game:GetService("Workspace").Enemies["Lv8000 Gunner Captain"].HumanoidRootPart.CFrame = CFrame.new(6654, 418, -1468)
    game:GetService("Workspace").Enemies["Lv500 Bucky"].HumanoidRootPart.CFrame = CFrame.new(6654, 418, -1468)
    game:GetService("Workspace").Enemies["Lv360 Bruno"].HumanoidRootPart.CFrame = CFrame.new(6654, 418, -1468)
    game:GetService("Workspace").Enemies["Lv32 Fredric"].HumanoidRootPart.CFrame = CFrame.new(6654, 418, -1468)
    game:GetService("Workspace").Enemies["Lv28 Friedrich"].HumanoidRootPart.CFrame = CFrame.new(6654, 418, -1468)
    game:GetService("Workspace").Enemies["Lv36 Gunslinger"].HumanoidRootPart.CFrame = CFrame.new(6654, 418, -1468)
    game:GetService("Workspace").Enemies["Lv14 Bandit"].HumanoidRootPart.CFrame = CFrame.new(6654, 418, -1468)
    game:GetService("Workspace").Enemies["Lv15 Bandit"].HumanoidRootPart.CFrame = CFrame.new(6654, 418, -1468)
    game:GetService("Workspace").Enemies["Lv14 Boar"].HumanoidRootPart.CFrame = CFrame.new(6654, 418, -1468)
    game:GetService("Workspace").Enemies["Lv29 Frued"].HumanoidRootPart.CFrame = CFrame.new(6654, 418, -1468)
    game:GetService("Workspace").Enemies["Lv22 Thug"].HumanoidRootPart.CFrame = CFrame.new(6654, 418, -1468)
    game:GetService("Workspace").Enemies["Lv34 Freddi"].HumanoidRootPart.CFrame = CFrame.new(6654, 418, -1468)
    game:GetService("Workspace").Enemies["Lv17 Thug"].HumanoidRootPart.CFrame = CFrame.new(6654, 418, -1468)
    game:GetService("Workspace").Enemies["Lv24 Gunslinger"].HumanoidRootPart.CFrame = CFrame.new(6654, 418, -1468)
    game:GetService("Workspace").Enemies["Lv35 Angry Bobb"].HumanoidRootPart.CFrame = CFrame.new(6654, 418, -1468)
    game:GetService("Workspace").Enemies["Lv50 Gunslinger"].HumanoidRootPart.CFrame = CFrame.new(6654, 418, -1468)
    game:GetService("Workspace").Enemies["Lv9 Bandit"].HumanoidRootPart.CFrame = CFrame.new(6654, 418, -1468)
    game:GetService("Workspace").Enemies["Lv24 Fred"].HumanoidRootPart.CFrame = CFrame.new(6654, 418, -1468)
    game:GetService("Workspace").Enemies["Lv4 Freddy"].HumanoidRootPart.CFrame = CFrame.new(6654, 418, -1468)
    game:GetService("Workspace").Enemies["Lv11 Boar"].HumanoidRootPart.CFrame = CFrame.new(6654, 418, -1468)
    game:GetService("Workspace").Enemies["Lv28 Fredde"].HumanoidRootPart.CFrame = CFrame.new(6654, 418, -1468)
    game:GetService("Workspace").Enemies["Lv40 Cave Demon"].HumanoidRootPart.CFrame = CFrame.new(6654, 418, -1468)
    game:GetService("Workspace").Enemies["Lv4 Boar"].HumanoidRootPart.CFrame = CFrame.new(6654, 418, -1468)
    game:GetService("Workspace").Enemies["Lv24 Thug"].HumanoidRootPart.CFrame = CFrame.new(6654, 418, -1468)
    game:GetService("Workspace").Enemies["Lv30 Thug"].HumanoidRootPart.CFrame = CFrame.new(6654, 418, -1468)
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(6654, 418, -1468)
end)

local Main = Window:NewTab("Spam Skill")
local MainSection = Main:NewSection("Spam Full Charged Skill")

MainSection:NewButton("Light", "Light Spam", function()
     local plr = 
game:GetService("Players").LocalPlayer 	
plr.Character.Powers.Light.RemoteEvent:FireServer("LightPower2","StopCharging",plr.Character.HumanoidRootPart.CFrame,workspace.IslandSnowyMountains.Stone.Stone,100) 
end)
MainSection:NewButton("Magma", "Magma Spam", function()
     local plr = game:GetService("Players").LocalPlayer 	
plr.Character.Powers.Magma.RemoteEvent:FireServer("MagmaPower1","StopCharging",plr.Character.HumanoidRootPart.CFrame,workspace.IslandSnowyMountains.Stone.Stone,100) 
end)
MainSection:NewButton("Chilly", "Chilly Spam", function()
     local plr =
game:GetService("Players").LocalPlayer
plr.Character.Powers.Chilly.RemoteEvent:FireServer("ChillyPower2","StopCharging",plr.Character.HumanoidRootPart.CFrame,workspace.IslandSnowyMountains.Stone.Stone,100)
end)
