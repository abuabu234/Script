if game.PlaceId == 2753915549 then
    World1 = true

    game:GetService("Players").LocalPlayer:Kick("Do not Support, Please wait...")
end

function CheckQuest() 
    MyLevel = game:GetService("Players").LocalPlayer.Data.Level.Value
    if World1 then
        if MyLevel == 1 or MyLevel <= 9 then
            Mon = "Cute Thug :D
            LevelQuest = 1
            NameQuest = "CuteThug:D"
            NameMon = "Cute Thug :D"
            CFrameQuest = CFrame.new(1059.37195, 15.4495068, 1550.4231, 0.939700544, -0, -0.341998369, 0, 1, -0, 0.341998369, 0, 0.939700544)
            CFrameMon = CFrame.new(1045.962646484375, 27.00250816345215, 1560.8203125)
        elseif MyLevel == 10 or MyLevel <= 14 then
            Mon = "Slimy :D"
            LevelQuest = 10
            NameQuest = "Slimyquest"
            NameMon = "Slimy:D"
            CFrameQuest = CFrame.new(-1598.08911, 35.5501175, 153.377838, 0, 0, 1, 0, 1, -0, -1, 0, 0)
            CFrameMon = CFrame.new(-1448.51806640625, 67.85301208496094, 11.46579647064209)
      LevelQuest = 2
            NameQuest = "PrisonerQuest"
            NameMon = "Dangerous Prisoner"spawn(function()
if (v.HumanoidRootPart.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 10 then
    spawn(function()
        Z()
        X()
        C()
    end)
end
end)
v.HumanoidRootPart.CanCollide = false
TargetSelectHunt = v.Humanoid
until KillPlayer == false or v.Humanoid.Health == 0 or not v:FindFirstChild("HumanoidRootPart") or not v:FindFirstChild("Humanoid") or not v.Parent or NextplySelect == true
NextplySelect = false
StartCheckTarget = false
end
end
end
end
end)
end
end)

spawn(function()
    while wait() do
        pcall(function()
            if KillPlayer then
            if Distance < 10 then
            if useskilltrial then
                game:GetService("VirtualInputManager"):SendKeyEvent(true,"Z",false,game)
                wait(0.1)
                game:GetService("VirtualInputManager"):SendKeyEvent(false,"Z",false,game)
                wait(0.1)
                game:GetService("VirtualInputManager"):SendKeyEvent(true,"X",false,game)
                wait(0.1)
                game:GetService("VirtualInputManager"):SendKeyEvent(false,"X",false,game)
                wait(0.1)
                game:GetService("VirtualInputManager"):SendKeyEvent(false,"C",false,game)
                wait(0.1)
                game:GetService("VirtualInputManager"):SendKeyEvent(false,"C",false,game)
                wait(0.1)
                game:GetService("VirtualInputManager"):SendKeyEvent(false,"V",false,game)
                wait(0.1)
                game:GetService("VirtualInputManager"):SendKeyEvent(false,"V",false,game)
            end
            end
            end
        end)
        end
    end)

    spawn(function()
        while wait() do
            pcall(function()
                if _G.TurnKen then
                    repeat task.wait()
                        if not game:GetService("Players").LocalPlayer.PlayerGui.ScreenGui:FindFirstChild("ImageLabel") then
                            game:GetService('VirtualUser'):CaptureController()
                            game:GetService('VirtualUser'):SetKeyDown('0x65')
                            wait(2)
                            game:GetService('VirtualUser'):SetKeyUp('0x65')
                        end
                    until game:GetService("Players").LocalPlayer.PlayerGui.ScreenGui:FindFirstChild("ImageLabel") or not _G.AutoObservation
                end
            end)
        end
    end)

    spawn(function()
        while wait() do
        if _G.Hopfinddao then
            if game:GetService("Workspace").Map:FindFirstChild("MysticIsland") or game:GetService("Workspace").Map:FindFirstChild("MysticIsland") then
                if HighestPointRealCFrame and (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - HighestPointRealCFrame.Position).Magnitude > 10 then
                topos(getHighestPoint().CFrame * CFrame.new(0, 211.88, 0))
                    end
            elseif not game:GetService("Workspace").Map:FindFirstChild("MysticIsland") or not game:GetService("Workspace").Map:FindFirstChild("MysticIsland") then
                Hop()
                end
            end
        end
    end)

    spawn(function()
        while wait() do
            if _G.Hopfindmoon then
            if game:GetService("Lighting").Sky.MoonTextureId=="http://www.roblox.com/asset/?id=9709149052" or game:GetService("Lighting").Sky.MoonTextureId=="http://www.roblox.com/asset/?id=9709149431" then
                wait(2.0)
                OrionLib:MakeNotification({
                    Name = "pinguim hub",
                    Content = "Turn Off Hop Find Moon Please",
                    Image = "rbxassetid://119980140458596",
                    Time = 5
                })
            elseif game:GetService("Lighting").Sky.MoonTextureId=="http://www.roblox.com/asset/?id=9709143733" then
                Hop()
                OrionLib:MakeNotification({
                    Name = "pinguim hub",
                    Content = "Hop Server",
                    Image = "rbxassetid://119980140458596",
                    Time = 5
                })
            elseif game:GetService("Lighting").Sky.MoonTextureId=="http://www.roblox.com/asset/?id=9709150401" then
                Hop()
                OrionLib:MakeNotification({
                    Name = "pinguim hub",
                    Content = "Hop Server",
                    Image = "rbxassetid://119980140458596",
                    Time = 5
                })
            elseif game:GetService("Lighting").Sky.MoonTextureId=="http://www.roblox.com/asset/?id=9709149680" then
                Hop()
                OrionLib:MakeNotification({
                    Name = "Sla Hub",
                    Content = "Hop Server",
                    Image = "rbxassetid://119980140458596",
                    Time = 5
                })
            else
                Hop()
                end
            end
        end
    end)

OrionLib:MakeNotification({
        Name = "pinguim hub",
        Content = "Loading script complete!, You can now enable the function!",
        Image = "rbxassetid://119980140458596",
        Time = 5
    })

_G.Remove_Effect = true

spawn(function()
    while wait() do
    for i,v in pairs(game.Players:GetPlayers()) do
        if v.Name == "red_game43" or v.Name == "rip_indra" or v.Name == "Axiore" or v.Name == "Polkster" or v.Name == "wenlocktoad" or v.Name == "Daigrock" or v.Name == "toilamvidamme" or v.Name == "oofficialnoobie" or v.Name == "Uzoth" or v.Name == "Azarth" or v.Name == "arlthmetic" or v.Name == "Death_King" or v.Name == "Lunoven" or v.Name == "TheGreateAced" or v.Name == "rip_fud" or v.Name == "drip_mama" or v.Name == "layandikit12" or v.Name == "Hingoi" then
            Hop()
            end
        end
    end
end)

spawn(function()
    game:GetService('RunService').Stepped:Connect(function()
        if _G.Remove_Effect then
            for i, v in pairs(game:GetService("ReplicatedStorage").Effect.Container:GetChildren()) do
                if v.Name == "Death" then
                    v:Destroy() 
                end
            end
        end
    end)
end)

spawn(function()
    while wait() do
        for i,v in pairs(game.Players.LocalPlayer:GetChildren()) do
            if v.Name == "DataLoaded" or v.Name == "DataPreloaded" then
                v:Destroy()
            end
        end
    end
end)

OrionLib:Init()

OrionLib:MakeNotification({
    Name = "pinguim Hub",
    Content = "Loading Config Complete!!",
    Image = "rbxassetid://119980140458596",
    Time = 5
})
