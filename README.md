loadstring(game:HttpGet(("https://raw.githubusercontent.com/REDzHUB/LibraryV2/main/redzLib")))()
MakeWindow({
  Hub = {
    Title = "Waffles Hub | Script Hub",
    Animation = "Por Waffles Exility"
  },
  Key = {
    KeySystem = true,
    Title = "Key System",
    Description = "",
    KeyLink = "https://tubaroscripts.blogspot.com/2024/03/blog-post.html",
    Keys = {"Tubaro142"},
    Notifi = {
      Notifications = false,
      CorrectKey = "Running the Script...",
      Incorrectkey = "The key is incorrect",
      CopyKeyLink = "Copied to Clipboard"
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

local Main = MakeTab({Name = "Blox Fruit"})

MakeNotifi({
  Title = "Waffles Hub",
  Text = "Este E um script Hub:D",
  Time = 5
})

AddButton(Main, {
  Name = "Redz Hub(Fecha a interface talvez)",
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
