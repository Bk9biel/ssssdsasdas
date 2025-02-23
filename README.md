local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()

if character and character:FindFirstChild("HumanoidRootPart") then
    character.HumanoidRootPart.CFrame = CFrame.new(
        19769.4492, 72.8617172, 13161.9346, 
        1.13844872e-05, 0.766070843, -0.642756104, 
        1, -1.13248825e-05, 4.14252281e-06, 
        -4.14252281e-06, -0.642756104, -0.766070843
    )
end
