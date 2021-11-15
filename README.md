
local DiscordLib = loadstring(game:HttpGet"https://raw.githubusercontent.com/dawid-scripts/UI-Libs/main/discord%20lib.txt")()

local win = DiscordLib:Window("funny")

local serv = win:Server("Dog Pi", "")

local tgls = serv:Channel("Dog Fruit")
local idk = serv:Channel("Dog Flame Sword")
local idk2 = serv:Channel("Movement")
local dog = serv:Channel("Flame Awaken No CD")
tgls:Toggle("Z",false, function(bool)
getgenv().skill = bool
while skill == true do
    wait(.5)
game:GetService("Players").LocalPlayer.Character.DogDF.Skill1.Fire:FireServer()
end
end
)


tgls:Toggle("X",false, function(bool)
getgenv().skill = bool
while skill == true do
    wait(.5)
game:GetService("Players").LocalPlayer.Character.DogDF.Skill2.Fire:FireServer()
end
end
)


tgls:Toggle("C",false, function(bool)
getgenv().skill = bool
while skill == true do
    wait(.5)
game:GetService("Players").LocalPlayer.Character.DogDF.Skill3.Fire:FireServer()
end
end
)


tgls:Toggle("V",false, function(bool)
getgenv().skill = bool
while skill == true do
    wait(.5)
game:GetService("Players").LocalPlayer.Character.DogDF.Skill4.Fire:FireServer()
end
end
)

tgls:Toggle("F",false, function(bool)
getgenv().skill = bool
while skill == true do
    wait(.5)
local args = {
    [1] = game:GetService("Players").LocalPlayer
}

game:GetService("Players").LocalPlayer.Character.DogDF.Tranform.Fire:FireServer(unpack(args))

end
end
)
idk:Toggle("Z",false,function(bool)
    getgenv().skill = bool 
    while skill == true do
        wait(.25)
game:GetService("Players").LocalPlayer.Character.DogFlameSword.Skill1.Fire:FireServer()
end
end
)

idk:Toggle("X",false,function(bool)
    getgenv().skill = bool 
    while skill == true do
        wait(.5)
game:GetService("Players").LocalPlayer.Character.DogFlameSword.Skill2.Fire:FireServer()
end
end
)

idk:Toggle("Z",false,function(bool)
    getgenv().skill = bool 
    while skill == true do
        wait(.5)
game:GetService("Players").LocalPlayer.Character.DogFlameSword.Skill3.Fire:FireServer()
end
end
)
idk2:Toggle("No Dash CD",false,function(bool)
    getgenv().dash = bool
    while dash == true do
        wait(.5)
game:GetService("ReplicatedStorage").DashEvent:FireServer()
end
end
)
idk2:Toggle("Dupe Dog Fruit",false,function(bool)
    getgenv().dupe = bool 
    while dupe == true do
    wait(.5)
local args = {
    [1] = "Buy",
    [2] = "Flame Awaken Dog",
    [3] = 0
}

game:GetService("ReplicatedStorage"):FindFirstChild("\224\184\163\224\185\137\224\184\178\224\184\153\224\184\130\224\184\178\224\184\162\224\184\156\224\184\165"):FireServer(unpack(args))
end
end
)
dog:Toggle("Z",false,function(bool)
    getgenv().skill = bool 
    while skill == true do
        wait(.5)
game:GetService("Players").LocalPlayer.Character.FlameAwakenDog.Skill1.Fire:FireServer()
end
end
)

dog:Toggle("X",false,function(bool)
    getgenv().skill = bool 
    while skill == true do
        wait(.5)
game:GetService("Players").LocalPlayer.Character.FlameAwakenDog.Skill2.Fire:FireServer()
end
end
)

dog:Toggle("C",false,function(bool)
    getgenv().skill = bool 
    while skill == true do
        wait(.5)
game:GetService("Players").LocalPlayer.Character.FlameAwakenDog.Skill3.Fire:FireServer()
end
end
)
dog:Toggle("V",false,function(bool)
    getgenv().skill = bool 
    while skill == true do
        wait(.5)
game:GetService("Players").LocalPlayer.Character.FlameAwakenDog.Skill4.Fire:FireServer()
end
end
)

dog:Toggle("F",false,function(bool)
    getgenv().skill = bool 
    while skill == true do
        wait(.5)
game:GetService("Players").LocalPlayer.Character.FlameAwakenDog.Skill5.Fire:FireServer()
end
end
)
