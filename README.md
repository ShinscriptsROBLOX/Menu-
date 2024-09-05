local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()
local Window = OrionLib:MakeWindow({Name = "Shinkai Scripts [1.0] ⭐", HidePremium = false, SaveConfig = true, ConfigFolder = "OrionTest"})
local Tab = Window:MakeTab({
	Name = "Adopt me 🌷",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})
OrionLib:MakeNotification({
	Name = "Loading Script...",
	Content = "Please wait.. Timer: 30seconds.",
	Image = "rbxassetid://4483345998",
	Time = 30
}) 
--Slider:Set(2)
 Tab:AddLabel("Adoptme By Shinkaiscripts")
--CoolLabel:Set("Label New!")
Tab:AddParagraph("Info ⭐","Script does not work on private servers")
-- CoolParagraph:Set("Paragraph New!")

Tab:AddTextbox({
	Name = "Input Player name",
	Default = "Player",
	TextDisappear = true,
	Callback = function(Value)
		print(Value)
	end	  
})
Tab:AddToggle({
	Name = "Force Accept",
	Default = false,
	Callback = function(Value)
		print(Value)
	end    
})
Tab:AddButton({
	Name = "Break trade [Hide trade from Victim]",
	Callback = function()
      		print("button pressed")
  	end    
})
 --Slider:Set(2)
 Tab:AddLabel("Other features")
--CoolLabel:Set("Label New!")
Tab:AddParagraph("Info ⭐","unlock all pets, execute again if u have locked pets")
-- CoolParagraph:Set("Paragraph New!")

Tab:AddTextbox({
	Name = "Pet Unlock",
	Default = "Pet name",
	TextDisappear = true,
	Callback = function(Value)
		print(Value)
	end	  
})
Tab:AddButton({
	Name = "click to unlock [Use after tradescam]",
	Callback = function()
      		print("button pressed")
  	end    
})
OrionLib:Init()
-- destroying the interface: OrionLib:Destroy()

local Tab = Window:MakeTab({
	Name = "MM2🔪",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})
--Slider:Set(2)
 Tab:AddLabel("Murdery mystery 2 By Shinkaiscripts")
--CoolLabel:Set("Label New!")
Tab:AddParagraph("Info ⭐","Script does not work on private servers")
-- CoolParagraph:Set("Paragraph New!")

Tab:AddTextbox({
	Name = "Input playername",
	Default = "Player",
	TextDisappear = true,
	Callback = function(Value)
		print(Value)
	end	  
})
Tab:AddToggle({
	Name = "Enable MM2 Tradescam",
	Default = false,
	Callback = function(Value)
		print(Value)
	end    
})
Tab:AddButton({
	Name = "Break trade [Hide trade from Victim]",
	Callback = function()
      		print("button pressed")
  	end    
})
 --Slider:Set(2)
 Tab:AddLabel("Other features")
--CoolLabel:Set("Label New!")
Tab:AddParagraph("Info ⭐","Execute again if it doesn't work.")
-- CoolParagraph:Set("Paragraph New!")

Tab:AddTextbox({
	Name = "Item Unlocker",
	Default = "Item name",
	TextDisappear = true,
	Callback = function(Value)
		print(Value)
	end	  
})
Tab:AddButton({
	Name = "click to unlock [Use after testing Tradescam]",
	Callback = function()
      		print("button pressed")
  	end    
})
Tab:AddTextbox({
	Name = "Godly duper",
	Default = "Godly name",
	TextDisappear = true,
	Callback = function(Value)
		print(Value)
	end	  
})
Tab:AddButton({
	Name = "Dupe Godly",
	Callback = function()
      		print("button pressed")
  	end    
})
Tab:AddTextbox({
	Name = "Ancient duper",
	Default = "Ancient name",
	TextDisappear = true,
	Callback = function(Value)
		print(Value)
	end	  
})
Tab:AddButton({
	Name = "Dupe Ancient",
	Callback = function()
      		print("button pressed")
  	end    
})
local Tab = Window:MakeTab({
	Name = "Information ⭐",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})
--Slider:Set(2)
 Tab:AddLabel("Information ⭐")
--CoolLabel:Set("Label New!")
Tab:AddParagraph("Adopt me","More Features to go, Banned alt abusing, Will not work if u don't have any pets")
-- CoolParagraph:Set("Paragraph New!")
Tab:AddParagraph("MM2","Will not work if u don't have any godly to dupe")
-- CoolParagraph:Set("Paragraph New!")
