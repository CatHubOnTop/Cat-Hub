local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()

local Window = Library.CreateLib("Cat Hub V1.0", "Midnight")

--Main

local Main = Window:NewTab("Main")

local MainSection = Main:NewSection("Character")

MainSection:NewButton("Speed Boost", "Makes you speedy dont combine with walkspeed", function()

    game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 200

end)

MainSection:NewButton("Speed Normal", "Makes your speed normal", function()

    game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 16

end)

MainSection:NewButton("Inf Jump", "Makes you jump inf time heigh.", function()

    loadstring(game:HttpGet("https://pastebin.com/raw/Q0F1njnh"))()

end)

local MainSection = Main:NewSection("Advanced Character")

MainSection:NewSlider("JumpPower", "Changes your Jumping Power.", 250, 20, function(s) -- 500 (MaxValue) | 0 (MinValue)

    game.Players.LocalPlayer.Character.Humanoid.JumpPower = s

   end)

   

   MainSection:NewSlider("WalkSpeed", "Changes your Speed.", 500, 16, function(s) -- 500 (MaxValue) | 0 (MinValue)

    game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = s

   end)
