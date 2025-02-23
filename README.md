local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()

if character and character:FindFirstChild("HumanoidRootPart") then
    character.HumanoidRootPart.CFrame = CFrame.new(
        -47.4142876, 17.5670547, 437.601196, 
        -0.740636945, -0.666899979, -0.0818619132, 
        -0.63467288, 0.654389858, 0.411052614, 
        -0.2205614, 0.356396288, -0.907928586
    )
end
