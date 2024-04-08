loadstring(game:HttpGet(("https://raw.githubusercontent.com/REDzHUB/LibraryV2/main/redzLib")))()
MakeWindow({
  Hub = {
    Title = "Zeus X | Discord nao ta pronto",
    Animation = "Por BaconExility"
  },
  Key = {
    KeySystem = true,
    Title = "Sistema de Key",
    Description = "Tu precisa da key irmao",
    KeyLink = "https://tubaroscripts.blogspot.com/2024/03/blog-post.html",
    Keys = {"Zeus_X142"},
    Notifi = {
      Notifications = false,
      CorrectKey = "Carregando o Script...",
      Incorrectkey = "Tua key ta incorreta..",
      CopyKeyLink = "Copiado o link"
    }
  }
})

MinimizeButton({
  Image = "Waffles",
  Size = {40, 40},
  Color = Color3.fromRGB(10, 10, 10),
  Corner = true,
  Stroke = false,
  StrokeColor = Color3.fromRGB(255, 0, 0)
})


local Main = MakeTab({Name = "Discord + Creditos"})

local Paragraph = AddParagraph(Main, {"Olá pessoa!", ""})
local Paragraph = AddParagraph(Main, {"Obrigado por usar meu hub", ""})
local Paragraph = AddParagraph(Main, {"Inspirado em Redz hub e em +Leen - Roblox Scripts", ""})

local Main = MakeTab({Name = "Blox Fruit"})

MakeNotifi({
  Title = "Waffles Hub",
  Text = "Este E um script Hub:D",
  Time = 5
})

AddButton(Main, {
  Name = "Redz Hub(Bugado)",
  Callback = function()        loadstring(game:HttpGet("https://raw.githubusercontent.com/REDzHUB/BloxFruits/main/redz9999"))()

    
  end
})

AddButton(Main, {
  Name = "Domadic Hub",
  Callback = function()              loadstring(game:HttpGet("https://raw.githubusercontent.com/Domadicoof/Domadicoof/main/Domadichub/NottoGay/Start.ranscript"))()
    
  end
})

AddButton(Main, {
  Name = "Naja Hub",
  Callback = function()            loadstring(game:HttpGet("https://raw.githubusercontent.com/NaJaxHub/M/main/%3F.lua"))() 

    
  end
})

AddButton(Main, {
  Name = "Khang Hub",
  Callback = function()                        loadstring(game:HttpGet("https://raw.githubusercontent.com/Nguyenchikhangg/YTB_Khang_Mod_Game/main/Khang_Mod_Game_Version_1.2.txt"))()                       
    
  end
})

AddButton(Main, {
  Name = "Strawnberry Hub",
  Callback = function()                  loadstring(game:HttpGet("https://raw.githubusercontent.com/CheemsNhuChiAl/Sotringhuhu/main/StrawberryHup"))() 
   
  end
})

local Main = MakeTab({Name = "King Legacy"})

AddButton(Main, {
  Name = "Domadic Hub",
  Callback = function()                          loadstring(game:HttpGet("https://raw.githubusercontent.com/Domadicoof/Domadicoof/main/Domadichub/NottoGay/Start.ranscript"))()
    
  end
})

local Main = MakeTab({Name = "Blade Ball"})

AddButton(Main, {
  Name = "Drakay Hub (key)",
  Callback = function()                       loadstring(game:HttpGet("https://raw.githubusercontent.com/poolist/Foolds/main/Bladd"))() 
    
  end
})

 AddButton(Main, {
  Name = "NS Hub",
  Callback = function()                 loadstring(game:HttpGet("https://raw.githubusercontent.com/HenSeu87PofghYT/Blade-Ball2/main/Nameless%20Scripts"))() 

    
  end
})

local Main = MakeTab({Name = "Murder Misery 2"})

AddButton(Main, {
  Name = "Folder Hub",
  Callback = function()                           loadstring(game:HttpGet("https://raw.githubusercontent.com/Gregory909/FolderGui-FolderHub/main/loader.lua", true))()

     
  end
})
