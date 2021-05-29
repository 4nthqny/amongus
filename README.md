game.Players.LocalPlayer.Chatted:connect(function(msg)
if msg == "/e Hips" then
AnimationId = "6797919579"
local Anim = Instance.new("Animation")
Anim.AnimationId = "rbxassetid://"..AnimationId
local k = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
k:Play(0)
k:AdjustSpeed(1)
game.Players.LocalPlayer.Character.Animate.Disabled = true
game.Players.LocalPlayer.Character.Humanoid.Running:connect(function(speed)
if speed > 0 then
game.Players.LocalPlayer.Character.Animate.Disabled = false
k:Stop(0)
end
end)
end
end)

game.Players.LocalPlayer.Chatted:connect(function(msg)
if msg == "/e Take" then
AnimationId = "6797938823"
local Anim = Instance.new("Animation")
Anim.AnimationId = "rbxassetid://"..AnimationId
local k = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
k:Play(0)
k:AdjustSpeed(1)
game.Players.LocalPlayer.Character.Animate.Disabled = true
game.Players.LocalPlayer.Character.Humanoid.Running:connect(function(speed)
if speed > 0 then
game.Players.LocalPlayer.Character.Animate.Disabled = false
k:Stop(0)
end
end)
end
end)

game.Players.LocalPlayer.Chatted:connect(function(msg)
if msg == "/e Fault" then
AnimationId = "6797948622"
local Anim = Instance.new("Animation")
Anim.AnimationId = "rbxassetid://"..AnimationId
local k = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
k:Play(0)
k:AdjustSpeed(1)
game.Players.LocalPlayer.Character.Animate.Disabled = true
game.Players.LocalPlayer.Character.Humanoid.Running:connect(function(speed)
if speed > 0 then
game.Players.LocalPlayer.Character.Animate.Disabled = false
k:Stop(0)
end
end)
end
end)

