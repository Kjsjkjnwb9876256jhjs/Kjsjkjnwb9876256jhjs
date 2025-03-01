local Rayfield = loadstring(game:HttpGet('https://sirius.menu/rayfield'))()
local Window = Rayfield:CreateWindow({
   Name = "🐉 سڪربت دراقـون هوب || DR HOBE 🐉",
   Icon = 0, -- Icon in Topbar. Can use Lucide Icons (string) or Roblox Image (number). 0 to use no icon (default).
   LoadingTitle = "يا هـلاا منور سڪربتي قناتـي تيك توك  || lun.59",
   LoadingSubtitle = "by Sirius",
   Theme = "Default", -- Check https://docs.sirius.menu/rayfield/configuration/themes
   DisableRayfieldPrompts = true,
   DisableBuildWarnings = true, -- Prevents Rayfield from warning when the script has a version mismatch with the interface
   ConfigurationSaving = {
      Enabled = true,
      FolderName = nil, -- Create a custom folder for your hub/game
      FileName = "Jeno hub"
   },
   Discord = {
      Enabled = true, -- Prompt the user to join your Discord server if their executor supports it
      Invite = "noinvitelink", -- The Discord invite code, do not include discord.gg/. E.g. discord.gg/ ABCD would be ABCD
      RememberJoins = true -- Set this to false to make them join the discord every time they load it up
   },
   KeySystem = true, -- Set this to true to use our key system
   KeySettings = {
      Title = "lun.59 دخـل المفتاح || المفـتاح ببايو قناتي ",
      Subtitle = "هـاا جاي تدور سڪربتات تعال عندي ✨😘",
      Note = "No method of obtaining the key is provided", -- Use this to tell the user how to get a key
      FileName = "Key", -- It is recommended to use something unique as other scripts using Rayfield may overwrite your key file
      SaveKey = true, -- The user's key will be saved, but if you change the key, they will be unable to use your script
      GrabKeyFromSite = false, -- If this is true, set Key below to the RAW site you would like Rayfield to get the key from
      Key = {"My happy"} -- List of keys that will be accepted by the system, can be RAW file links (pastebin, github etc) or simple strings ("hello","key22")
   }
})
local Tab = Window:CreateTab("سڪربتاتي || MASA", 4483362458) -- Title, Image
local Button = Tab:CreateButton({
   Name = "سڪربت الحـنيةه للافعال الچنسيةه ✨",
   Callback = function()
   loadstring(game:HttpGet('https://raw.githubusercontent.com/Ndora1/Ndora1/main/Nokia%20Hub.lua'))()
   end,
})
local Button = Tab:CreateButton({
   Name = "يوهـان || احلى سڪربت ✨",
   Callback = function()
   loadstring(game:HttpGet("https://raw.githubusercontent.com/yohan-iq/YohanTheBest/refs/heads/main/Protected_7098282954511331.txt"))()
   end,
})
local Button = Tab:CreateButton({
   Name = "سڪربت علي الدمـاء 🍷|| نـمط العضماء",
   Callback = function()
   -- The function that takes place when the button is pressed
   end,
})
local Button = Tab:CreateButton({
   Name = "جـيون اساسـي || سڪربت جيون الاساسـي",
   Callback = function()
   loadstring(game:HttpGet("https://raw.githubusercontent.com/joygril/RP-Brookhaven-JG-Hub/refs/heads/main/De.Jeon.txt"))()
   end,
})
local Button = Tab:CreateButton({
   Name = "جيون مابـات || سڪربت من صنع جيون فقط للسكربتات",
   Callback = function()
   loadstring(game:HttpGet("https://pastefy.app/tG0bhxHp/raw"))()
   end,
})
local Button = Tab:CreateButton({
   Name = "سڪربت يطير الي يفعل عـليك || مضاد للافعال الجنسيةه",
   Callback = function()
   loadstring(game:HttpGet("https://raw.githubusercontent.com/ADSKerOffical/FlingPlayers/main/FlingGUI"))()
   end,
})
local Button = Tab:CreateButton({
   Name = "سڪربت كنبةه || المعروف لا يعرف يابه",
   Callback = function()
   loadstring(game:HttpGet("https://raw.githubusercontent.com/0Ben1/fe./main/Fling%20GUI"))()
   end,
})
local Button = Tab:CreateButton({
   Name = "سڪربت صملات عربي || VR7 للمصلحچيةه ✨",
   Callback = function()
   loadstring(game:HttpGet("https://raw.githubusercontent.com/VR7ss/OMK/refs/heads/main/VR7-ON-TOP"))()
   end,
})
local Button = Tab:CreateButton({
   Name = "سڪربت سيف || عـربي والنمط حلو مثل ريدز",
   Callback = function()
   loadstring(game:HttpGet("https://raw.githubusercontent.com/blxdzxb7/how/refs/heads/main/VIP%20Vison"))()
   end,
})
local Button = Tab:CreateButton({
   Name = "سڪربت الجودةه || يابةه احله سكربت للتصوير ✨",
   Callback = function()
   loadstring(game:HttpGet('https://raw.githubusercontent.com/randomstring0/pshade-ultimate/refs/heads/main/src/cd.lua'))()
--PShade Ultimate web : https://randomstring0.github.io/pshade.github.io/
   end,
})
Window.ModifyTheme('AmberGlow')
local Slider = Tab:CreateSlider({
   Name = "سرعـةه",
   Range = {0, 300},
   Increment = 10,
   Suffix = "Bananas",
   CurrentValue = 10,
   Flag = "Slider1", -- A flag is the identifier for the configuration file, make sure every element has a different flag if you're using configuration saving to ensure no overlaps
   Callback = function(Value)
   game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = (Value)
   end,
})

local Tab = Window:CreateTab("حـزمةه Blox Fruit || 🐉", 4483362458) -- Title, Image

local Button = Tab:CreateButton({
   Name = "REDZ HUB || 🐉",
   Callback = function()
   loadstring(game:HttpGet("https://raw.githubusercontent.com/realredz/BloxFruits/refs/heads/main/Source.lua"))
   end,
})

local Button = Tab:CreateButton({
   Name = "Cokka HUB || القمـر 🌑",
   Callback = function()
   loadstring(game:HttpGet"https://codeberg.org/CokkaHub/Loadstring/raw/branch/main/CokkaHub.lua")()
   end,
})

local Button = Tab:CreateButton({
   Name = "W-azur HUB || 🐉",
   Callback = function()
   --[[
	WARNING: Heads up! This script has not been verified by ScriptBlox. Use at your own risk!
]]
getgenv().Team = "Pirates"
getgenv().FixCrash = false -- Turn it On For Hopping Server, Improve Performance But Silent Aim On Mob And Player
getgenv().FixCrash2 = false -- Turn it On For Hopping Server, Improve Performance But Will Remove Speed Changer
loadstring(game:HttpGet("https://api.luarmor.net/files/v3/loaders/3b2169cf53bc6104dabe8e19562e5cc2.lua"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "HoHo HUB || 🐉",
   Callback = function()
   --[[
	WARNING: Heads up! This script has not been verified by ScriptBlox. Use at your own risk!
]]
_G.HohoVersion = "v3"
loadstring(game:HttpGet('https://raw.githubusercontent.com/acsu123/HOHO_H/main/Loading_UI'))()
   end,
})

local Button = Tab:CreateButton({
   Name = "سڪربت الاصفر || Andepzai 🐉",
   Callback = function()
   --[[
	WARNING: Heads up! This script has not been verified by ScriptBlox. Use at your own risk!
]]
loadstring(game:HttpGet("https://raw.githubusercontent.com/AnDepZaiHub/AnDepZaiHubBeta/main/AnDepZaiHubBeta.lua"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "MaMa HUB || 🐉",
   Callback = function()
   --[[
	WARNING: Heads up! This script has not been verified by ScriptBlox. Use at your own risk!
]]
--[[ discord link for solara help:https://discord.gg/nJSv3kGtHw 
IF INVITE EXPIRED MAKE SURE TO TELL ME IN THE COMMENTS --]]
loadstring(game:HttpGet("https://raw.githubusercontent.com/MAMAhub1/Mmahub/main/README.md"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Vector HUB || 🐉",
   Callback = function()
   loadstring(game:HttpGet("https://raw.githubusercontent.com/AAwful/VectorHub/main/Loader.lua"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Raito HUB || 🐉",
   Callback = function()
   loadstring(game:HttpGet("https://raw.githubusercontent.com/Efe0626/RaitoHub/main/Script"))()
   end,
})

local Tab = Window:CreateTab("حـزمةه MM2 || ☁", 4483362458) -- Title, Image

local Button = Tab:CreateButton({
   Name = "X HUB MM2 || ☁",
   Callback = function()
   --[[
	WARNING: Heads up! This script has not been verified by ScriptBlox. Use at your own risk!
]]
loadstring(game:HttpGet("https://raw.githubusercontent.com/Au0yX/Community/main/XhubMM2"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Nexus HUB MM2 || ☁",
   Callback = function()
   loadstring(game:HttpGet("https://raw.githubusercontent.com/CrazyHub123/NexusHubMain/main/Main.lua", true))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Y HUB MM2 || ☁",
   Callback = function()
   loadstring(game:HttpGet("https://raw.githubusercontent.com/Luarmor123/YHUB-Community/refs/heads/main/Murder-Mystery2"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Forge HUB MM2 || ☁",
   Callback = function()
   loadstring(game:HttpGet("https://raw.githubusercontent.com/Skzuppy/forge-hub/main/loader.lua"))()
   end,
})
