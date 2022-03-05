local Config = {

    WindowName = "BEAMMODZ HUB -- [ Script More ]",

                Color = Color3.fromRGB(255, 0, 255),

                                        Keybind = Enum.KeyCode.RightControl

                                                                            }

                                                                                                                local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/AlexR32/Roblox/main/BracketV3.lua"))()

                                                                                                                                                    local Window = Library:CreateWindow(Config, game:GetService("CoreGui"))

                                                                                                                                                    -------------

local Tab1 = Window:CreateTab("Script Menu")

local Tab2 = Window:CreateTab("UI Toggle")

local Section1 = Tab1:CreateSection("Blox Fruit")

local Section2 = Tab1:CreateSection("King Legacy")

local Section3 = Tab2:CreateSection("Menu")

local Label1 = Section1:CreateLabel("Label 1")

Label1:UpdateText("Blox  Fruit")

                    -------------

local Button1 = Section1:CreateButton("HOHO  HUB", function() loadstring(game:HttpGet('https://raw.githubusercontent.com/acsu123/HOHO_H/main/Loading_UI'))()

            end)

            -------------

local Button2 = Section1:CreateButton("NETNA  HUB", function() loadstring(game:HttpGet("https://raw.githubusercontent.com/natoppo044/modzcaster/main/new.lua"))()

            end)

            -------------

local Button3 = Section1:CreateButton("SMZ  HUB", function() loadstring(game:HttpGet("https://raw.githubusercontent.com/Frerfgzz/free-script/main/SMZHUBv2BETA"))()

            end)

            -------------

local Button4 = Section1:CreateButton("MARU  x  HUB", function()

    loadstring(game:HttpGet('https://pastebin.com/raw/mUw5xC3J'))()

            end)

            -------------

local Button5 = Section1:CreateButton("MAX  HUB", function() loadstring(game:HttpGet('https://raw.githubusercontent.com/MaxHub1/GOD-MAX-HUM/main/1.0.0'))()

                end)

                            -------------

local Button6 = Section1:CreateButton("RIPPER  HUB", function() loadstring(game:HttpGet('https://raw.githubusercontent.com/hajibeza/RIPPER-HUB/main/BFMobile.lua'))()

                    end)

                                                -------------

local Button7 = Section1:CreateButton("ROCKET  HUB", function() loadstring(game:HttpGet"https://raw.githubusercontent.com/FinerGG/Free-Rocket-Hub/main/BloxFruit-Script")()

                    end)

                                                -------------

local Button8 = Section1:CreateButton("FUSION  HUB", function() loadstring(game:HttpGet"https://raw.githubusercontent.com/natoppo044/modzcaster/main/Ful.lua")()

                    end)

                                                -------------

local Button9 = Section1:CreateButton("POWER  HUB", function() loadstring(game:HttpGet(("https://raw.githubusercontent.com/MASTERHUB2/P-O-W-E-R-X/main/README.md"), true))()

                    end)

                                                -------------

local Label1 = Section2:CreateLabel("Label 1")

Label1:UpdateText("King  Legacy")

                                                -------------

local Button1 = Section2:CreateButton("REN  HUB", function() loadstring(game:HttpGet("https://raw.githubusercontent.com/SHAREHACK/script/main/Kinglegacy"))()

                    end)

                                                -------------

local Button2 = Section2:CreateButton("RIPPER  HUB", function()

loadstring(game:HttpGet("https://raw.githubusercontent.com/hajibeza/RIPPER-HUB/main/King%20Leagacy"))()

                    end)

                                                -------------

local Button3 = Section2:CreateButton("HULK  U  HUB", function()

loadstring(game:HttpGet"https://raw.githubusercontent.com/HULKUexe/-mobileMAX-/main/FreeScript.lua")()

                    end)

                                                -------------

local Button4 = Section2:CreateButton("KING  LEGACY  HUB", function()

loadstring(game:HttpGet"https://raw.githubusercontent.com/xDepressionx/Free-Script/main/AllScript.lua")()

                    end)

                                                -------------

local Button5 = Section2:CreateButton("MASTER  HUB", function() loadstring(game:HttpGet(('https://raw.githubusercontent.com/AltsegoD/script/master/KingPiece.lua')))()

                end)

                            -------------

local Button6 = Section2:CreateButton("SPACE  HUB", function() loadstring(game:HttpGet"https://raw.githubusercontent.com/sadwawin/KINGLAGACY/main/README.md")()

                end)

                            -------------

local Label2 = Section2:CreateLabel("Label 2")

Label2:UpdateText("Pet Simulator")

-------------

local Button7 = Section2:CreateButton("SAZA  HUB", function()

    loadstring(game:HttpGet("https://pastebin.com/raw/kB7CVpBd"))()

                end)

                            -------------

local Button8 = Section2:CreateButton("DINO  HUB", function()

loadstring(game:HttpGet('https://raw.githubusercontent.com/SHAREHACK/script/main/psx'))()

                end)

                            -------------

local Toggle3 = Section3:CreateToggle("UI Toggle", nil, function(State)

    Window:Toggle(State)

            end)

                        Toggle3:CreateKeybind(tostring(Config.Keybind):gsub("Enum.KeyCode.", ""), function(Key)

                                            Config.Keybind = Enum.KeyCode[Key]

                                                                        end)

                                                                                                            Toggle3:SetState(true)
