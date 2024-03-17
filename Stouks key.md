local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()
local Window = OrionLib:MakeWindow({Name = "Stouks X V0.1🔓", HidePremium = false, SaveConfig = true, ConfigFolder = "OrionTest"})
local Tab = Window:MakeTab({
	Name = "Inicio",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

OrionLib:MakeNotification({
	Name = "Stouks X",
	Content = "Esse script e um script hub:D",
	Image = "rbxassetid://4483345998",
	Time = 25
})

Tab:AddButton({
	Name = "Feche A interface",
	Callback = function()
      		print("button pressed")                  OrionLib:Destroy()
  	end    
})

OrionLib:MakeNotification({
	Name = "Stouks X",
	Content = "Versão: V0.1",
	Image = "rbxassetid://4483345998",
	Time = 25
})

Tab:AddParagraph("Aviso!","Esse script e um Script Hub,A interface pode mudar completamente pois esta nas primeiras versões e pode ficar instavel")

Tab:AddParagraph("Executores","A interface esta funcionando em:Delta,Fluxus,Arcerus,Codex.Executores não testados:Vegas X,Hydrogen, Ro-Exec, Krampus")

Tab:AddParagraph("Ultimo Aviso","Se você usa um executor Não testado ou um que nao ta na lista:c desculpe mais não posso fazer nada a respeito")

local Tab = Window:MakeTab({
	Name = "Status",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})



Tab:AddParagraph("Funcionando,Precisa atualizar","Fora do ar,Descontinuado")

Tab:AddParagraph("Clique no botão para verificar","pfv:D")

Tab:AddButton({
	Name = "Verifique",
	Callback = function()                     OrionLib:MakeNotification({
	Name = "Verificação Stouks X",
	Content = "Funcionando",
	Image = "rbxassetid://4483345998",
	Time = 15
})
      		print("button pressed")
  	end    
})


Tab:AddToggle({
	Name = "Anti Cheat V0.1",
	Default = false,
	Callback = function(Value)                                  OrionLib:MakeNotification({
	Name = "Stouks X",
	Content = "Estara vindo mais Anti Cheats",
	Image = "rbxassetid://4483345998",
	Time = 5
})
		print(Value)
	end    
})


OrionLib:Init()
