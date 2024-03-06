local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()
local Player = game.Players.LocalPlayer
local Window = OrionLib:MakeWindow({Name = "Key System", HidePremium = false, SaveConfig = true, IntroEnabled = false})

OrionLib:MakeNotification({
	Name = "Logged in!",
	Content = "Welcome to Uppercut Hub"..Player.Name.." ",
	Image = "rbxassetid://11915607895",
	Time = 5
})

_G.Key = "EntsVglad1fgauwu1"
_G.KeyInput = "string"

function MakeScriptHub()
print("key is correct")
end

function CorrectKeyNotification()
    OrionLib:MakeNotification({
	Name = "Correct Key!",
	Content = "Wait Script",
	Image = "rbxassetid://11915607895",
	Time = 5
})
wait(3)
if wait(3) then
    loadstring(game:HttpGet("https://raw.githubusercontent.com/PeomPokkao/ScriptLastedButinUikeySystem/main/README.md"))();
    end
end

function IncorrectKeyNotification()
    OrionLib:MakeNotification({
	Name = "Incorrect Key!",
	Content = "You have entered the Incorrectcorrect key!",
	Image = "rbxassetid://11915607895",
	Time = 5
})
end


local Tab = Window:MakeTab({
	Name = "Key",
	Icon = "rbxassetid://11915607895",
	PremiumOnly = false
})

Tab:AddTextbox({
	Name = "Enter Key",
	Default = "",
	TextDisappear = true,
	Callback = function(Value)
		_G.KeyInput = Value
	end	  
})

Tab:AddButton({
	Name = "Check Key!",
	Callback = function()
      		if _G.KeyInput == _G.Key then
      		MakeScriptHub()
      		CorrectKeyNotification()    
      		else
      		    IncorrectKeyNotification()
      		end
  	end
})

