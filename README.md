_G.Key = "123"

local keychecked = false
local hwid = nil
local hwidplr = game:GetService("RbxAnalyticsService"):GetClientId()

if _G.Key == "123" then
    hwid = "b80f9593-3951-4e39-a5d5-0bc98c4f234e"
    keychecked = true
end

if keychecked == true then
    if hwidplr == hwid then
        loadstring(game:HttpGet(('https://raw.githubusercontent.com/juhub12/gggaaa/main/README.md')))()
    else
        print("incorrect hwid")
    end
else
    print("incorrect Key")
end 
