-- Gui to Lua
-- Version: 3.2

-- Instances:

local Frame = Instance.new("Frame")
local Creditsl = Instance.new("TextLabel")
local FastPunch = Instance.new("TextButton")
local FastWeight = Instance.new("TextButton")
local FastPushups = Instance.new("TextButton")
local AutoPunch = Instance.new("TextButton")
local AutoWeight = Instance.new("TextButton")
local AutoPushups = Instance.new("TextButton")
local AutoKill = Instance.new("TextButton")
local StopAutoKill = Instance.new("TextButton")
local AutoKillPlayer = Instance.new("TextButton")
local TextBox = Instance.new("TextBox")
local TitleOfScript = Instance.new("TextLabel")
local WalkOnWater = Instance.new("TextButton")

--Properties:

Frame.Parent = game.StarterGui.ScreenGui
Frame.BackgroundColor3 = Color3.fromRGB(213, 0, 4)
Frame.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame.BorderSizePixel = 0
Frame.Position = UDim2.new(0.273747206, 0, 0.0557851233, 0)
Frame.Size = UDim2.new(0, 555, 0, 361)

Creditsl.Name = "Creditsl"
Creditsl.Parent = Frame
Creditsl.BackgroundColor3 = Color3.fromRGB(204, 3, 17)
Creditsl.BorderColor3 = Color3.fromRGB(0, 0, 0)
Creditsl.BorderSizePixel = 0
Creditsl.Size = UDim2.new(0, 555, 0, 50)
Creditsl.Font = Enum.Font.Unknown
Creditsl.Text = "Made By KingSkillsYT"
Creditsl.TextColor3 = Color3.fromRGB(0, 255, 0)
Creditsl.TextScaled = true
Creditsl.TextSize = 14.000
Creditsl.TextWrapped = true

FastPunch.Name = "Fast Punch"
FastPunch.Parent = Frame
FastPunch.BackgroundColor3 = Color3.fromRGB(20, 51, 255)
FastPunch.BorderColor3 = Color3.fromRGB(0, 0, 0)
FastPunch.BorderSizePixel = 0
FastPunch.Position = UDim2.new(0.048648648, 0, 0.267881274, 0)
FastPunch.Size = UDim2.new(0, 148, 0, 25)
FastPunch.Font = Enum.Font.Unknown
FastPunch.Text = "Fast Punch"
FastPunch.TextColor3 = Color3.fromRGB(0, 0, 0)
FastPunch.TextScaled = true
FastPunch.TextSize = 14.000
FastPunch.TextWrapped = true

FastWeight.Name = "Fast Weight"
FastWeight.Parent = Frame
FastWeight.BackgroundColor3 = Color3.fromRGB(20, 51, 255)
FastWeight.BorderColor3 = Color3.fromRGB(0, 0, 0)
FastWeight.BorderSizePixel = 0
FastWeight.Position = UDim2.new(0.567567587, 0, 0.265111178, 0)
FastWeight.Size = UDim2.new(0, 148, 0, 25)
FastWeight.Font = Enum.Font.Unknown
FastWeight.Text = "Fast Weight "
FastWeight.TextColor3 = Color3.fromRGB(0, 0, 0)
FastWeight.TextScaled = true
FastWeight.TextSize = 14.000
FastWeight.TextWrapped = true

FastPushups.Name = "Fast Pushups"
FastPushups.Parent = Frame
FastPushups.BackgroundColor3 = Color3.fromRGB(14, 18, 255)
FastPushups.BorderColor3 = Color3.fromRGB(0, 0, 0)
FastPushups.BorderSizePixel = 0
FastPushups.Position = UDim2.new(0.567567587, 0, 0.361380458, 0)
FastPushups.Size = UDim2.new(0, 148, 0, 25)
FastPushups.Font = Enum.Font.Unknown
FastPushups.Text = "Fast Pushups"
FastPushups.TextColor3 = Color3.fromRGB(0, 0, 0)
FastPushups.TextScaled = true
FastPushups.TextSize = 14.000
FastPushups.TextWrapped = true

AutoPunch.Name = "Auto Punch"
AutoPunch.Parent = Frame
AutoPunch.BackgroundColor3 = Color3.fromRGB(31, 23, 255)
AutoPunch.BorderColor3 = Color3.fromRGB(0, 0, 0)
AutoPunch.BorderSizePixel = 0
AutoPunch.Position = UDim2.new(0.048648648, 0, 0.381365836, 0)
AutoPunch.Size = UDim2.new(0, 148, 0, 25)
AutoPunch.Font = Enum.Font.Unknown
AutoPunch.Text = "Auto Punch"
AutoPunch.TextColor3 = Color3.fromRGB(0, 0, 0)
AutoPunch.TextScaled = true
AutoPunch.TextSize = 14.000
AutoPunch.TextWrapped = true

AutoWeight.Name = "Auto Weight"
AutoWeight.Parent = Frame
AutoWeight.BackgroundColor3 = Color3.fromRGB(8, 12, 255)
AutoWeight.BorderColor3 = Color3.fromRGB(0, 0, 0)
AutoWeight.BorderSizePixel = 0
AutoWeight.Position = UDim2.new(0.048648648, 0, 0.492515445, 0)
AutoWeight.Size = UDim2.new(0, 148, 0, 25)
AutoWeight.Font = Enum.Font.Unknown
AutoWeight.Text = "Auto Weight "
AutoWeight.TextColor3 = Color3.fromRGB(0, 0, 0)
AutoWeight.TextScaled = true
AutoWeight.TextSize = 14.000
AutoWeight.TextWrapped = true

AutoPushups.Name = "Auto Pushups"
AutoPushups.Parent = Frame
AutoPushups.BackgroundColor3 = Color3.fromRGB(23, 35, 255)
AutoPushups.BorderColor3 = Color3.fromRGB(0, 0, 0)
AutoPushups.BorderSizePixel = 0
AutoPushups.Position = UDim2.new(0.567567587, 0, 0.464814633, 0)
AutoPushups.Size = UDim2.new(0, 148, 0, 25)
AutoPushups.Font = Enum.Font.Unknown
AutoPushups.Text = "Auto Pushups"
AutoPushups.TextColor3 = Color3.fromRGB(0, 0, 0)
AutoPushups.TextScaled = true
AutoPushups.TextSize = 14.000
AutoPushups.TextWrapped = true

AutoKill.Name = "Auto Kill"
AutoKill.Parent = Frame
AutoKill.BackgroundColor3 = Color3.fromRGB(31, 15, 255)
AutoKill.BorderColor3 = Color3.fromRGB(0, 0, 0)
AutoKill.BorderSizePixel = 0
AutoKill.Position = UDim2.new(0.048648648, 0, 0.594484627, 0)
AutoKill.Size = UDim2.new(0, 148, 0, 25)
AutoKill.Font = Enum.Font.Unknown
AutoKill.Text = "Auto Kill"
AutoKill.TextColor3 = Color3.fromRGB(0, 0, 0)
AutoKill.TextScaled = true
AutoKill.TextSize = 14.000
AutoKill.TextWrapped = true

StopAutoKill.Name = "Stop Auto Kill"
StopAutoKill.Parent = Frame
StopAutoKill.BackgroundColor3 = Color3.fromRGB(17, 33, 255)
StopAutoKill.BorderColor3 = Color3.fromRGB(0, 0, 0)
StopAutoKill.BorderSizePixel = 0
StopAutoKill.Position = UDim2.new(0.567567587, 0, 0.559556723, 0)
StopAutoKill.Size = UDim2.new(0, 148, 0, 25)
StopAutoKill.Font = Enum.Font.Unknown
StopAutoKill.Text = "Stop Auto Kill "
StopAutoKill.TextColor3 = Color3.fromRGB(0, 0, 0)
StopAutoKill.TextScaled = true
StopAutoKill.TextSize = 14.000
StopAutoKill.TextWrapped = true

AutoKillPlayer.Name = "Auto Kill Player"
AutoKillPlayer.Parent = Frame
AutoKillPlayer.BackgroundColor3 = Color3.fromRGB(8, 8, 255)
AutoKillPlayer.BorderColor3 = Color3.fromRGB(0, 0, 0)
AutoKillPlayer.BorderSizePixel = 0
AutoKillPlayer.Position = UDim2.new(0.048648648, 0, 0.692520797, 0)
AutoKillPlayer.Size = UDim2.new(0, 148, 0, 25)
AutoKillPlayer.Font = Enum.Font.Unknown
AutoKillPlayer.Text = "Auto Kill Player"
AutoKillPlayer.TextColor3 = Color3.fromRGB(0, 0, 0)
AutoKillPlayer.TextScaled = true
AutoKillPlayer.TextSize = 14.000
AutoKillPlayer.TextWrapped = true

TextBox.Parent = Frame
TextBox.BackgroundColor3 = Color3.fromRGB(90, 255, 19)
TextBox.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextBox.BorderSizePixel = 0
TextBox.Position = UDim2.new(0.236036032, 0, 0.817174494, 0)
TextBox.Size = UDim2.new(0, 269, 0, 27)
TextBox.Font = Enum.Font.Unknown
TextBox.Text = "Enter Player Name"
TextBox.TextColor3 = Color3.fromRGB(0, 0, 0)
TextBox.TextScaled = true
TextBox.TextSize = 14.000
TextBox.TextWrapped = true

TitleOfScript.Name = "Title Of Script"
TitleOfScript.Parent = Frame
TitleOfScript.BackgroundColor3 = Color3.fromRGB(199, 0, 0)
TitleOfScript.BorderColor3 = Color3.fromRGB(0, 0, 0)
TitleOfScript.BorderSizePixel = 0
TitleOfScript.Position = UDim2.new(0, 0, 0.127423823, 0)
TitleOfScript.Size = UDim2.new(0, 555, 0, 50)
TitleOfScript.Font = Enum.Font.Unknown
TitleOfScript.Text = "Muscle Legends Main"
TitleOfScript.TextColor3 = Color3.fromRGB(245, 110, 255)
TitleOfScript.TextSize = 30.000

WalkOnWater.Name = "Walk On Water"
WalkOnWater.Parent = Frame
WalkOnWater.BackgroundColor3 = Color3.fromRGB(24, 16, 255)
WalkOnWater.BorderColor3 = Color3.fromRGB(0, 0, 0)
WalkOnWater.BorderSizePixel = 0
WalkOnWater.Position = UDim2.new(0.567567587, 0, 0.66204989, 0)
WalkOnWater.Size = UDim2.new(0, 148, 0, 25)
WalkOnWater.Font = Enum.Font.Unknown
WalkOnWater.Text = "Walk On Water"
WalkOnWater.TextColor3 = Color3.fromRGB(0, 0, 0)
WalkOnWater.TextScaled = true
WalkOnWater.TextSize = 14.000
WalkOnWater.TextWrapped = true
