local Player = game.Players.LocalPlayer

Player.Chatted:connect(function(cht)
    if cht:match(":trollinggui") then
        loadstring(game:HttpGet("https://raw.githubusercontent.com/Blukez/Scripts/main/UTG%20V3%20RAW"))() -- make sure you add in the script too
    elseif cht:match(":admin") then -- add what you want to say for the script to execute so i put "admin" because i want it to load an admin script
        loadstring(game:HttpGet(('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'),true))()
    end
end)


game:GetService("StarterGui"):SetCore("SendNotification",{
    Title = "Credit To";
    Text = "Kai7k#1125";
})

