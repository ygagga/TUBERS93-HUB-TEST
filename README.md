-carregar biblioteca
local Fluent = loadstring(game:HttpGet("https://github.com/dawid-scripts/Fluent/releases/latest/download/main.lua"))()

local Window = Fluent:CreateWindow({
    Title = "Fluent " .. Fluent.Version,
    TabWidth = 160, Size = UDim2.fromOffset(580, 460), Theme = "Dark"
})


local Tabs = {
    Main = Window:AddTab({ Title = "scipts" }),
    Settings = Window:AddTab({ Title = "Settings", Icon = "settings" })
}

--paragrafos
Tabs.Main:AddParagraph({ Title = "hub tubers", Content = "Scipts aqui.\nSecond line!" })

--botões
Tabs.Main:AddButton({ Title = "esp name", Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/ygagga/ESP-NAME-kkkk/refs/heads/main/README.md"))()  end })
