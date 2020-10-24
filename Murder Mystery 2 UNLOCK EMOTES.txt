local emote = require(game:GetService("ReplicatedStorage").Modules.EmoteModule).GeneratePage

  local target = game:GetService("Players").LocalPlayer.PlayerGui.MainGUI.Game:FindFirstChild("Emotes")
  local emotelist = {"headless","zombie","zen","ninja","floss","dab"}
  emote(emotelist,target,'I Hacked Your Emotes')