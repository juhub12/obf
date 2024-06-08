_G.Key = "123"

local keychecked = false
local hwid = nil
local hwidplr = game:GetService("RbxAnalyticsService"):GetClientId()

if _G.Key == "123" then
    hwid = "5C2A2FE5-FA81-4801-B99D-DA4D8AD80F8C"
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
