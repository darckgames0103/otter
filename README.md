--Name: "Murder Mystery 2 Script | AUTO FARM COINS"

local vu = game:GetService("VirtualUser") game:GetService("Players").LocalPlayer.Idled:connect(function() vu:Button2Down(Vector2.new(0,0),workspace.CurrentCamera.CFrame) wait(1) vu:Button2Up(Vector2.new(0,0),workspace.CurrentCamera.CFrame) end) getgenv().Coin = true getgenv().GodMode = true loadstring(game:HttpGet("https://raw.githubusercontent.com/BaconLords/Random-Shit/main/mm2.lua%22))()
