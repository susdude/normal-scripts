



-- Instances:

local ScreenGui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local UICorner = Instance.new("UICorner")
local TextLabel = Instance.new("TextLabel")

--Properties:

ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")

Frame.Parent = ScreenGui
Frame.BackgroundColor3 = Color3.fromRGB(61, 61, 61)
Frame.Position = UDim2.new(0.5, 0, 0.5, 0)
Frame.Size = UDim2.new(0, 1, 0, 1)

UICorner.CornerRadius = UDim.new(9, 9)
UICorner.Parent = Frame

TextLabel.Parent = Frame
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.Position = UDim2.new(0.140983611, 0, 0.114285715, 0)
TextLabel.Size = UDim2.new(0, 233, 0, 80)
TextLabel.Font = Enum.Font.SourceSans
TextLabel.LineHeight = 1
TextLabel.Text = "Loading..."
TextLabel.TextTransparency = 1
TextLabel.TextColor3 = Color3.fromRGB(93, 93, 93)
TextLabel.TextScaled = true
TextLabel.TextSize = 64.000
TextLabel.TextWrapped = true

wait(2)
Frame:TweenSizeAndPosition(UDim2.new(0,205,0,205), UDim2.new(0.45,0,0.4,0))
wait(1.5)
UICorner.CornerRadius = UDim.new(0, 15)
TextLabel.TextTransparency = 0
Frame:TweenSizeAndPosition(UDim2.new(0,305,0,105), UDim2.new(0.42,0,0.45,0))

wait(1)
pcall(function()
    ScreenGui:Destroy()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/susdude/normal-scripts/main/" .. tostring(game.PlaceId) .. ".lua"))()
end)
