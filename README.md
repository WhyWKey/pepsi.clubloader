local loader = Instance.new("ScreenGui")
local main = Instance.new("Frame")
local name = Instance.new("TextLabel")
local welcome = Instance.new("TextLabel")
local load = Instance.new("TextButton")

loader.Name = "loader"
loader.Parent = game.CoreGui

main.Name = "main"
main.Parent = loader
main.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
main.BorderSizePixel = 3
main.Position = UDim2.new(0.359201193, 0, 0.345679015, 0)
main.Size = UDim2.new(0, 392, 0, 174)

name.Name = "name"
name.Parent = main
name.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
name.BackgroundTransparency = 1.000
name.Position = UDim2.new(0.244148552, 0, 0.0746518224, 0)
name.Size = UDim2.new(0, 200, 0, 14)
name.Font = Enum.Font.Code
name.Text = "pepsi.club"
name.TextColor3 = Color3.fromRGB(0, 89, 149)
name.TextSize = 14.000

welcome.Name = "welcome"
welcome.Parent = main
welcome.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
welcome.BackgroundTransparency = 1.000
welcome.Position = UDim2.new(0.329081625, 0, 0.42522648, 0)
welcome.Size = UDim2.new(0, 134, 0, 14)
welcome.Font = Enum.Font.Code
welcome.Text = "welcome"
welcome.TextColor3 = Color3.fromRGB(255, 255, 255)
welcome.TextSize = 14.000

load.Name = "load"
load.Parent = main
load.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
load.BorderColor3 = Color3.fromRGB(0, 89, 149)
load.Position = UDim2.new(0.244897962, 0, 0.827586234, 0)
load.Size = UDim2.new(0, 200, 0, 17)
load.Font = Enum.Font.Code
load.Text = "load"
load.TextColor3 = Color3.fromRGB(255, 255, 255)
load.TextSize = 14.000
load.MouseButton1Click:Connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/WhyWKey/pepsi.club/main/README.md", true))()
	main.Visible = false
end)

-- Scripts:

local function PRLATDT_fake_script() -- name.LocalScript 
	local script = Instance.new('LocalScript', name)
	wait(3)
	script.Parent.Text = "p epsi.club"
	wait(1)
	script.Parent.Text = "p e psi.club"
	wait(1)
	script.Parent.Text = "p e p si.club"
	wait(1)
	script.Parent.Text = "p e p s i.club"
	wait(1)
	script.Parent.Text = "p e p s i .club"
	wait(1)
	script.Parent.Text = "p e p s i . club"
	wait(1)
	script.Parent.Text = "p e p s i . c lub"
	wait(1)
	script.Parent.Text = "p e p s i . c l ub"
	wait(1)
	script.Parent.Text = "p e p s i . c l u b"
	wait(1)
	script.Parent.Text = "$ pepsi.club $"
	wait(1)
	script.Parent.Text = "p e p s i . c l u b"
	wait(1)
	script.Parent.Text = "$ pepsi.club $"
end
coroutine.wrap(PRLATDT_fake_script)()
local function IPHCOT_fake_script() -- welcome.LocalScript 
	local script = Instance.new('LocalScript', welcome)

	local plr = game.Players.LocalPlayer
	
	script.Parent.Text = "welcome, "..plr.Name.."."
end
coroutine.wrap(IPHCOT_fake_script)()
