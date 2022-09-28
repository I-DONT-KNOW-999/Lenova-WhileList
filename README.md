local LenovaWL = loadstring(game:HttpGet("https://pastebin.com/raw/Uhj2WPn4"))();
local LenovaID = game:GetService("RbxAnalyticsService"):GetClientId()
for i,v in pairs(LenovaWL) do
    if v == LenovaID then
        print("You can use this Script")
    else
        print("You Not Have WhiteList")
        wait(2)
        game.Players.localPlayer:kick("แม่มึงตายไอจนไม่มีScript")
        end
    end
