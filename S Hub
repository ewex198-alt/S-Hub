local UserInputService = game:GetService("UserInputService")
local Players = game:GetService("Players")
local StarterGui = game:GetService("StarterGui")
local player = Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoid = character:WaitForChild("Humanoid")

local jumping = false

task.spawn(function()
    local userId = Players:GetUserIdFromNameAsync("EWEX222")
    local thumbType = Enum.ThumbnailType.HeadShot
    local thumbSize = Enum.ThumbnailSize.Size420x420
    local content = Players:GetUserThumbnailAsync(userId, thumbType, thumbSize)
    StarterGui:SetCore("SendNotification", {
        Title = "EWEX222",
        Text = "RX Hub Hacker Roblox 🔨EWEX222👑",
        Icon = content,
        Duration = 15
    })
end)




local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/ZeianRussell/Kavo-UI-Library/main/Movable.source.lua"))()
local Window = Library.CreateLib("RX Hub v1.9 Hacker Roblox 🔨 EWEX222👑", colors)
local Tab = Window:NewTab("Keyboard")
local Section = Tab:NewSection("Keyboard")

Section:NewButton("Keyboard", "ButtonInfo", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Xxtan31/Ata/main/deltakeyboardcrack.txt", true))()
end)

local Tab = Window:NewTab("Hacker")
local Section = Tab:NewSection("Hacker")

Section:NewTextBox("Speed", "Speed", function(txt)
	game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = txt
end)

Section:NewTextBox("jump", "jump", function(txt)
	game.Players.LocalPlayer.Character.Humanoid.JumpPower = txt
end)

Section:NewButton("infjump", "ButtonInfo", function()
    local InfiniteJumpEnabled = true
game:GetService("UserInputService").JumpRequest:connect(function()
	if InfiniteJumpEnabled then
		game:GetService"Players".LocalPlayer.Character:FindFirstChildOfClass'Humanoid':ChangeState("Jumping")
	end
end)
end)

Section:NewButton("Fly", "ButtonInfo", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/XNEOFF/FlyGuiV3/main/FlyGuiV3.txt"))()
end)

Section:NewButton("Esp", "ButtonInfo", function()
    loadstring(game:HttpGet("https://pastebin.com/raw/5Q5yC3VZ"))()
end)

Section:NewButton("invincible", "ButtonInfo", function()
    loadstring(game:HttpGet('https://pastebin.com/raw/3Rnd9rHf'))()
end)

Section:NewButton("Hitbox", "ButtonInfo", function()
    loadstring(game:HttpGet("https://pastefy.app/ItfO0tdg/raw"))()
end)


local Section = Tab:NewSection("Aimbot 👑")
Section:NewButton("Aimbot", "ButtonInfo", function()
    loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-Aimbot-Universal-For-Mobile-and-PC-29153"))()
end)


local Section = Tab:NewSection("FOV")
Section:NewTextBox("FOV 1-120", "FOV", function(txt)
	local FovNumber = txt --Enter your FOV number here
local Camera = workspace.CurrentCamera
Camera.FieldOfView = FovNumber
end)


local Tab = Window:NewTab("🔨")
local Section = Tab:NewSection("Hacker Roblox 🔨 EWEX222👑")

Section:NewButton("Auto jump", "ButtonInfo", function()
    loadstring(game:HttpGet("https://pastebin.com/raw/6DeJkxac"))()
end)





local ScreenGui = Instance.new("ScreenGui")
ScreenGui.Name = "ScreenGui"
ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
ScreenGui.ResetOnSpawn = false

local Toggle = Instance.new("TextButton")
Toggle.Name = "Toggle"
Toggle.Parent = ScreenGui
Toggle.BackgroundColor3 = Color3.fromRGB(248, 248, 248)
Toggle.Position = UDim2.new(0, 0, 0.454706937, 0)
Toggle.Size = UDim2.new(0, 90, 0, 38)
Toggle.Font = Enum.Font.SourceSans
Toggle.Text = "OFF"
Toggle.TextColor3 = Color3.fromRGB(50,150,255)
Toggle.TextSize = 28.000
Toggle.Draggable = true
Toggle.MouseButton1Click:Connect(function()
    if Toggle.Text == "ON" then
        Toggle.Text = "OFF"
    else
        Toggle.Text = "ON"
    end
    Library:ToggleUI()
end)

local Corner = Instance.new("UICorner")
Corner.Name = "Corner"
Corner.Parent = Toggle
