local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))() --This Will Load The Script Code
local Player = game.Players.LocalPlayer --This Will Reveal The Player Name
  local Window = OrionLib:MakeWindow({
		Name = "Waffles Key",
		HidePremium = false,
		SaveConfig = true,
		ConfigFolder = "OrionTest",
        IntroText = "Waffles Key"       
}) --This Will Load The Script Hub

function MakeScriptHub()
        loadstring(game:HttpGet(("https://raw.githubusercontent.com/Lucashgdhhyy/Load/main/README.md"))() --Put The Script That Will Load If The Key Is Correct Here
end

OrionLib:MakeNotification({
	Name = "Logged In!",
	Content = "You need key "..Player.Name..".",
	Image = "rbxassetid://4483345998",
	Time = 5
}) --Notification

getgenv().Key = "Tubaro142" --Put The Correct Key Here
getgenv().KeyInput = "string" --Require For The Key To Work

local Tab = Window:MakeTab({
	Name = "Key",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
}) --Making A Tab

Tab:AddTextbox({
	Name = "Key",
	Default = "Enter Key.",
	TextDisappear = true,
	Callback = function(Value)
		getgenv().KeyInput = Value
	end	  
}) --You Will Enter The Key Here

Tab:AddButton({
    Name = "Check Key",
    Callback = function()
        if getgenv().KeyInput == getgenv().Key then
            OrionLib:MakeNotification({
                Name = "Checking Key",
                Content = "Checking The Key You Entered",
                Image = "rbxassetid://4483345998",
                Time = 5
            })
            wait(2)
            OrionLib:MakeNotification({
                Name = "Correct Key!",
                Content = "The key you entered is Correct.",
                Image = "rbxassetid://4483345998",
                Time = 5
            })
            wait(1)
            OrionLib:Destroy()
            wait(.3)
            MakeScriptHub()
        else
           OrionLib:MakeNotification({
                Name = "Checking Key",
                Content = "Checking The Key You Entered",
                Image = "rbxassetid://4483345998",
                Time = 5
            })
            wait(2)
            OrionLib:MakeNotification({
                Name = "Incorrect Key!",
                Content = "The key you entered is incorrect.",
                Image = "rbxassetid://4483345998",
                Time = 5
            })
        end
    end
}) --This Will Check The Key You Entered

Tab:AddButton({
	Name = "Copy Key",
	Callback = function()
      		setclipboard("https://tubaroscripts.blogspot.com/2024/03/blog-post.html") --This Will Copy The Link Of The Key
  	end    
}) 
    
OrionLib:Init() --Require If The Script Is Done
