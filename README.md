LoadingScreen = true
LoadingText1 = "Loading Library"
LoadingText2 = "Updating Library"
LoadingText3 = "Getting Script"
LoadingText4 = "Executing Script"
LoadingText5 = "Error: Execution Failed, re-trying!"

local ScriptTitle = "Pet Simulator 99: Script Loading"

-- LOADING SCREEN
if LoadingScreen ~= false then
    local Loading = Instance.new("ScreenGui")
    local MainFrame = Instance.new("Frame")
    local Title = Instance.new("TextLabel")
    local Dots = Instance.new("Frame")
    local Dot1 = Instance.new("Frame")
    local UICorner = Instance.new("UICorner")
    local InsideDot = Instance.new("Frame")
    local UICorner_2 = Instance.new("UICorner")
    local Dot2 = Instance.new("Frame")
    local UICorner_3 = Instance.new("UICorner")
    local InsideDot_2 = Instance.new("Frame")
    local UICorner_4 = Instance.new("UICorner")
    local Dot3 = Instance.new("Frame")
    local UICorner_5 = Instance.new("UICorner")
    local InsideDot_3 = Instance.new("Frame")
    local UICorner_6 = Instance.new("UICorner")
    local Bar = Instance.new("Frame")
    local Bar2 = Instance.new("Frame")
    local UICorner_7 = Instance.new("UICorner")
    local UICorner_8 = Instance.new("UICorner")
    local Percentage = Instance.new("TextLabel")
    local Tip = Instance.new("TextLabel")
    local EndSequence = Instance.new("Frame")
    Loading.Name = "kokoska1234577"
    Loading.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
    Loading.ZIndexBehavior = Enum.ZIndexBehavior.Sibling
    Loading.DisplayOrder = 999999999
    MainFrame.Name = "kokoska1234577"
    MainFrame.Parent = Loading
    MainFrame.BackgroundColor3 = Color3.fromRGB(20, 20, 20)
    MainFrame.BorderSizePixel = 0
    MainFrame.Position = UDim2.new(-0.125662372, 0, -0.125935167, 0)
    MainFrame.Size = UDim2.new(1.25, 0, 1.25, 0)
    Title.Name = "kokoska1234577"
    Title.Parent = MainFrame
    Title.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
    Title.BackgroundTransparency = 1.000
    Title.Position = UDim2.new(0.183329239, 0, 0.246382296, 0)
    Title.Size = UDim2.new(0.632528603, 0, 0.232815996, 0)
    Title.Font = Enum.Font.FredokaOne
    Title.Text = ScriptTitle
    Title.TextColor3 = Color3.fromRGB(255, 255, 255)
    Title.TextScaled = true
    Title.TextSize = 14.000
    Title.TextWrapped = true
    Dots.Name = "kokoska1234577"
    Dots.Parent = MainFrame
    Dots.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
    Dots.BackgroundTransparency = 1.000
    Dots.Position = UDim2.new(0.470970035, 0, 0.818612278, 0)
    Dots.Size = UDim2.new(0.0571707934, 0, 0.0360675976, 0)
    Dot1.Name = "kokoska1234577"
    Dot1.Parent = kokoska1234577
    Dot1.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
    Dot1.Position = UDim2.new(0.0611661971, 0, 0.234447539, 0)
    Dot1.Size = UDim2.new(0.159291148, 0, 0.51158762, 0)
    UICorner.CornerRadius = UDim.new(0.5, 0)
    UICorner.Parent = kokoska1234577
    InsideDot.Name = "kokoska1234577"
    InsideDot.Parent = kokoska1234577
    InsideDot.AnchorPoint = Vector2.new(0.5, 0.5)
    InsideDot.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
    InsideDot.Position = UDim2.new(0.5, 0, 0.5, 0)
    UICorner_2.CornerRadius = UDim.new(0.5, 0)
    UICorner_2.Parent = kokoska1234577
    Dot2.Name = "kokoska1234577"
    Dot2.Parent = kokoska1234577
    Dot2.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
    Dot2.Position = UDim2.new(0.419989735, 0, 0.234447539, 0)
    Dot2.Size = UDim2.new(0.159291148, 0, 0.51158762, 0)
    UICorner_3.CornerRadius = UDim.new(0.5, 0)
    UICorner_3.Parent = kokoska1234577
    InsideDot_2.Name = "kokoska1234577"
    InsideDot_2.Parent = kokoska1234577
    InsideDot_2.AnchorPoint = Vector2.new(0.5, 0.5)
    InsideDot_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
    InsideDot_2.Position = UDim2.new(0.5, 0, 0.5, 0)
    UICorner_4.CornerRadius = UDim.new(0.5, 0)
    UICorner_4.Parent = kokoska1234577
    Dot3.Name = "kokoska1234577"
    Dot3.Parent = kokoska1234577
    Dot3.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
    Dot3.Position = UDim2.new(0.778813243, 0, 0.234447539, 0)
    Dot3.Size = UDim2.new(0.159291148, 0, 0.51158762, 0)
    UICorner_5.CornerRadius = UDim.new(0.5, 0)
    UICorner_5.Parent = kokoska1234577
    InsideDot_3.Name = "kokoska1234577"
    InsideDot_3.Parent = kokoska1234577
    InsideDot_3.AnchorPoint = Vector2.new(0.5, 0.5)
    InsideDot_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
    InsideDot_3.Position = UDim2.new(0.5, 0, 0.5, 0)
    UICorner_6.CornerRadius = UDim.new(0.5, 0)
    UICorner_6.Parent = kokoska1234577
    Bar.Name = "kokoska1234577"
    Bar.Parent = MainFrame
    Bar.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
    Bar.BorderSizePixel = 0
    Bar.Position = UDim2.new(0.219547689, 0, 0.764966607, 0)
    Bar.Size = UDim2.new(0.560904443, 0, 0.0365853645, 0)
    Bar2.Name = "kokoska1234577"
    Bar2.Parent = kokoska1234577
    Bar2.BackgroundColor3 = Color3.fromRGB(60, 60, 60)
    Bar2.BorderSizePixel = 0
    Bar2.Size = UDim2.new(0, 0, 1, 0)
    UICorner_7.CornerRadius = UDim.new(0.5, 0)
    UICorner_7.Parent = kokoska1234577
    UICorner_8.CornerRadius = UDim.new(0.5, 0)
    UICorner_8.Parent = kokoska1234577
    Percentage.Name = "kokoska1234577"
    Percentage.Parent = kokoska1234577
    Percentage.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
    Percentage.BackgroundTransparency = 1.000
    Percentage.Position = UDim2.new(0.280816972, 0, 0.0909090936, 0)
    Percentage.Size = UDim2.new(0.438366145, 0, 0.787879348, 0)
    Percentage.Font = Enum.Font.FredokaOne
    Percentage.Text = "0%"
    Percentage.TextColor3 = Color3.fromRGB(255, 255, 255)
    Percentage.TextScaled = true
    Percentage.TextSize = 14.000
    Percentage.TextWrapped = true
    Tip.Name = "kokoska1234577"
    Tip.Parent = kokoska1234577
    Tip.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
    Tip.BackgroundTransparency = 1.000
    Tip.Position = UDim2.new(0.280816913, 0, 0.717294872, 0)
    Tip.Size = UDim2.new(0.438366145, 0, 0.0299334861, 0)
    Tip.Font = Enum.Font.SourceSansItalic
    Tip.Text = "kokoska1234577"
    Tip.TextColor3 = Color3.fromRGB(138, 138, 138)
    Tip.TextScaled = true
    Tip.TextSize = 14.000
    Tip.TextWrapped = true
    EndSequence.Name = "kokoska1234577"
    EndSequence.Parent = Loading
    EndSequence.BackgroundColor3 = Color3.fromRGB(20, 20, 20)
    EndSequence.BorderSizePixel = 0
    EndSequence.Position = UDim2.new(1, 0, 0, 0)
    EndSequence.Size = UDim2.new(1, 0, 1, 0)
    local function NGZQAMK_fake_script()
        local script = Instance.new("LocalScript", kokoska1234577)
        while true do
            wait(0.25)
            script.Parent.kokoska1234577.InsideDot:TweenSize(UDim2.new(1, 0, 1, 0), "In", "Sine", 0.25, true)
            wait(0.25)
            script.Parent.kokoska1234577.InsideDot:TweenSize(UDim2.new(1, 0, 1, 0), "In", "Sine", 0.25, true)
            wait(0.25)
            script.Parent.kokoska1234577.InsideDot:TweenSize(UDim2.new(1, 0, 1, 0), "In", "Sine", 0.25, true)
            wait(0.25)
            script.Parent.kokoska1234577.InsideDot:TweenSize(UDim2.new(0, 0, 0, 0), "In", "Sine", 0.25, true)
            wait(0.25)
            script.Parent.kokoska1234577.InsideDot:TweenSize(UDim2.new(0, 0, 0, 0), "In", "Sine", 0.25, true)
            wait(0.25)
            script.Parent.kokoska1234577.InsideDot:TweenSize(UDim2.new(0, 0, 0, 0), "In", "Sine", 0.25, true)
        end
    end

    coroutine.wrap(NGZQAMK_fake_script)()
    local function NDID_fake_script()
        local script = Instance.new("LocalScript", MainFrame)
        local bar = script.Parent.Bar
        local insidebar = bar.Bar2
        local percentage = bar.Percentage
        wait(5)
        insidebar:TweenSize(UDim2.new(1, 0, 1, 0), "In", "Linear", 200, true)
    end
    coroutine.wrap(NDID_fake_script)()
    local function OVSBNB_fake_script()
        local script = Instance.new("LocalScript", Percentage)
        wait(5)
        for i = 1, 100 do
            script.Parent.Text = i .. "%"
            wait(2)
        end
    end
    coroutine.wrap(OVSBNB_fake_script)()
    local function SNUMK_fake_script()
        local script = Instance.new("LocalScript", Tip)
        local tip = script.Parent
        while true do
            wait(5)
            tip.Text = LoadingText1
            wait(5)
            tip.Text = LoadingText2
            wait(5)
            tip.Text = LoadingText3
            wait(5)
            tip.Text = LoadingText4
            wait(5)
            tip.Text = LoadingText5
        end
    end
    coroutine.wrap(SNUMK_fake_script)()
    local function LSNGUH_fake_script()
        local script = Instance.new("LocalScript", Loading)
        game.StarterGui:SetCoreGuiEnabled(Enum.CoreGuiType.Backpack, false)
        game.StarterGui:SetCoreGuiEnabled(Enum.CoreGuiType.PlayerList, false)
        game.StarterGui:SetCoreGuiEnabled(Enum.CoreGuiType.Chat, false)
        game.StarterGui:SetCoreGuiEnabled(Enum.CoreGuiType.EmotesMenu, false)
    end
    coroutine.wrap(LSNGUH_fake_script)()
end

game.StarterGui:SetCoreGuiEnabled(Enum.CoreGuiType.Backpack, false)
game.StarterGui:SetCoreGuiEnabled(Enum.CoreGuiType.PlayerList, false)
game.StarterGui:SetCoreGuiEnabled(Enum.CoreGuiType.Chat, false)
game.StarterGui:SetCoreGuiEnabled(Enum.CoreGuiType.EmotesMenu, false)
