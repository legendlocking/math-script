local z = Instance.new("ScreenGui")
local x = Instance.new("Frame")
local q = Instance.new("TextLabel")

z.Name = "z"
z.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
z.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

x.Name = "x"
x.Parent = z
x.BackgroundColor3 = Color3.fromRGB(83, 83, 83)
x.BackgroundTransparency = 0.300
x.BorderColor3 = Color3.fromRGB(0, 0, 0)
x.BorderSizePixel = 0
x.Position = UDim2.new(0.408136487, 0, 0.654618502, 0)
x.Size = UDim2.new(0, 451, 0, 163)

q.Name = "q"
q.Parent = x
q.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
q.BackgroundTransparency = 1.000
q.BorderColor3 = Color3.fromRGB(0, 0, 0)
q.BorderSizePixel = 0
q.Position = UDim2.new(0.152993351, 0, 0.138860404, 0)
q.Size = UDim2.new(0, 314, 0, 117)
q.Font = Enum.Font.ArialBold
if mathz == 0 + 0 then
	q.Text = "nil question has found."
end
q.TextColor3 = Color3.fromRGB(255, 255, 255)
q.TextScaled = true
q.TextSize = 14.000
q.TextWrapped = true
q.Text = mathz
