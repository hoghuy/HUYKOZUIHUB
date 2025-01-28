local Window = MakeWindow({
    Hub = {
    Title = "HUYKOZUI",
    Animation = "2001"
    },
   Key = {
   KeySystem = false,
   Title = "Key System",
   Description = "chơi cố",
   KeyLink = "",
   Keys = {"1234"},
   Notifi = {
   Notifications = true,
   CorrectKey = "Running the Script...",
  Incorrectkey = "The key is incorrect",
  CopyKeyLink = "Copied to Clipboard"
 }
}
})

  MinimizeButton({
  Image = "http://www.roblox.com/asset/?id=128933802535491",
  Size = {60, 60},
  Color = Color3.fromRGB(10, 10, 10),
  Corner = true,
  Stroke = false,
  StrokeColor = Color3.fromRGB(255, 0, 0)
 })
 
------ Tab
local Tab1o = MakeTab({Name = "MAIN"})
local Tab2o = MakeTab({Name = "QUEST&ITEM"})
local Tab3o = MakeTab({Name = "FRUIT&raid"})
local Tab4o = MakeTab({Name = "Race v4"})
local Tab5o = MakeTab({Name = "travel"})
local Tab6o = MakeTab({Name = "stats"})
local Tab7o = MakeTab({Name = "shop"})
local Tab8o = MakeTab({Name = "visual"})
local Tab9o = MakeTab({Name = "misc"})


-------TOGGLE 

Toggle = AddToggle(Tab1o, {
 Name = "Farm level",
 Default = true,
 Callback = function()
  local islands = {
    Starter Pirate island/Starter Marine island = CFrame.new
    Jungle = CFrame.new
    Pirate Village = CFrame.new
    Desert = CFrame.new
    Frozen Village = CFrame.new
    Marine Fortress = CFrame.new
    Skylands = CFrame.new
    Prison = CFrame.new
    Colosseum = CFrame.new
    Magma Village = CFrame.new
    Underwater City = .new
    Upper Skylands = CFrame.new
    Fountain City = CFrame.new


  }
  local function tween(v, speed)
    if character and humanoidRootPart then
      local cf = CFrame.new(v);
      local distance = (humanoidRootPart.position - v).Magnitude
      local time = distance / speed;
      local tweeninfo = TweenInfo.ner(time, Enum.Easingstye.Linear, Enum.EasingDirection.Out);
      local start_tween = tweens:Create(humanoidRootPart, tweeninfo, {
        CFrame = cf
      });
      start_tween:Play();
      return start_tween;
    end
end
})

local questDes,questEnemy,questIsland

local function checkQuest()
  questDes = nil
  questEnemy = nil
  questIsland = nil
  local level = tonumber(lp.PlayerStats.lvl.value)
  if level < 10 then
    questDes = "Kill 5 Bandits / Kill 5 Tranee"
    questEnemy = "Bandit [lv. 1] / Tranee [lv. 1]"
    questIsland = islands.Starter Pirate island/Starter Marine island
  elself level >= 10 and level < 15 then
    questDes = "Kill 6 Monkeys"
    questEnemy = "Monkey [lv. 10]"
    questIsland = islands.Jungle
  elself level >= 15 and level < 20 then
    questDes = "kill 8 Gorillas"
    questEnemy = "Gorilla [lv. 15]"
    questIsland = islands.Jungle
  elself level >= 20 and level < 30 then
    questDes = "Kill 1 Gorilla King"; spawntick = 15 minute
    questEnemy = "Gorilla King [lv. 20]"
    questIsland = islands.Jungle
  elself level >= 30 and level < 45 then
    questDes = "kill 8 Pirates"
    questEnemy = "Pirates [lv. 30]"
    questIsland = islands.Pirate Village
