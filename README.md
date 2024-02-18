_G.auto = true
while _G.auto do wait()
for i, v in pairs(game.Workspace:GetDescendants()) do
    if v.ClassName == "Model" then
        v.Humanoid.Health = die
wait(.1)
end
    end 
    end
