local Lib = loadstring(game:HttpGet("https://raw.githubusercontent.com/AbstractPoo/Main/main/Library"))()
local UI = Lib:Create{
 Theme = "Dark", -- or "Light"
 Size = UDim2.new(0, 555, 0, 400) -- default
}
local Main = UI:Tab{
 Name = "Dropdown"
}
local Divider = Main:Divider{
 Name = "Main"
}

local Players = game:GetService("Players")
local humanoid = Players.LocalPlayer.Character.Humanoid
local humanoidDescription = humanoid.HumanoidDescription

local emoteTable = {
["Shrug"] = {3576968026},
["Point2"] = {3576823880},
["Tilt"] = {3360692915},
["Robot"] = {3576721660},
["Stadium"] = {3360686498},
["Salute"] = {3360689775},
["Hello"] = {3576686446},
["Jacks"] = {3570649048},
["Around Town"] = {3576747102},
["Twirl"] = {3716633898},
["Monkey"] = {3716636630},
["Sneaky"] = {3576754235},
["Side to Side"] = {3762641826},
["Greatest"] = {3762654854},
["Louder"] = {3576751796},
["Dizzy"] = {3934986896},
["Get Out"] = {3934984583},
["Fishing"] = {3994129128},
["Tree"] = {4049634387},
["Line Dance"] = {4049646104},
["Haha"] = {4102315500},
["Idol"] = {4102317848},
["T"] = {3576719440},
["Top Rock"] = {3570535774},
["Zombie"] = {4212496830},
["Dorky Dance"] = {4212499637},
["Fast Hands"] = {4272351660},
["Baby Dance"] = {4272484885},
["Celebrate"] = {3994127840},
["Fancy Feet"] = {3934988903},
["Y"] = {4391211308},
["Shuffle"] = {4391208058},
["Shy"] = {3576717965},
["Bodybuilder"] = {3994130516},
["Fashionable"] = {3576745472},
["Godlike"] = {3823158750},
["Curtsy"] = {4646306583},
["Air Dance"] = {4646302011},
["Happy"] = {4849499887},
["Sad"] = {4849502101},
["Sleep"] = {4689362868},
["Disagree"] = {4849495710},
["Power Blast"] = {4849497510},
["Agree"] = {4849487550},
["Keeping Time"] = {4646306072},
["Jumping Wave"] = {4940602656},
["Confused"] = {4940592718},
["Hero Landing"] = {5104377791},
["Tantrum"] = {5104374556},
["Cower"] = {4940597758},
["Bored"] = {5230661597},
["Beckon"] = {5230615437},
["Swish"] = {3821527813},
["High Wave"] = {5915776835},
["Rock On"] = {5915782672},
["Applaud"] = {5915779043},
["Floss Dance"] = {5917570207},
["Dolphin Dance"] = {5938365243},
["Jumping Cheer"] = {5895009708},
["Break Dance"] = {5915773992},
["Panini Dance"] = {5915781665},
["HOLIDAY Dance"] = {5938396308},
["Rodeo Dance"] = {5938397555},
["Old Town Road Dance"] = {5938394742},
["Rock Guitar"] = {6532155086},
["Rock Star"] = {6533100850},
["Drum Master"] = {6531538868},
["Drum Solo"] = {6532844183},
["Air Guitar"] = {3696761354},
["Cha-Cha"] = {3696764866},
["Heisman Pose"] = {3696763549},
["Hype Dance"] = {3696757129},
["Superhero Reveal"] = {3696759798},
["Country Line Dance"] = {5915780563},
["It Ain't My Fault"] = {6797948622},
["Take Me Under"] = {6797938823},
["Hips Poppin'"] = {6797919579},
["Cha Cha"] = {6865013133},
["Samba"] = {6869813008},
["Block Partier'"] = {6865011755}
}

humanoidDescription:SetEmotes(emoteTable)

local emoteoptions =
{
"Shrug",
"Point2",
"Tilt",
"Robot",
"Stadium",
"Salute",
"Hello",
"Jacks",
"Around Town",
"Twirl",
"Monkey",
"Sneaky",
"Side to Side",
"Greatest",
"Louder",
"Dizzy",
"Get Out",
"Fishing",
"Tree",
"Line Dance",
"Haha",
"Idol",
"T",
"Top Rock",
"Zombie",
"Dorky Dance",
"Fast Hands",
"Baby Dance",
"Celebrate",
"Fancy Feet",
"Y",
"Shuffle",
"Shy",
"Bodybuilder",
"Fashionable",
"Godlike",
"Curtsy",
"Air Dance",
"Happy",
"Sad",
"Sleep",
"Disagree",
"Power Blast",
"Agree",
"Keeping Time",
"Jumping Wave",
"Confused",
"Hero Landing",
"Tantrum",
"Cower",
"Bored",
"Beckon",
"Swish",
"High Wave",
"Rock On",
"Applaud",
"Floss Dance",
"Dolphin Dance",
"Jumping Cheer",
"Break Dance",
"Panini Dance",
"HOLIDAY Dance",
"Rodeo Dance",
"Old Town Road Dance",
"Rock Guitar",
"Rock Star",
"Drum Master",
"Drum Solo",
"Air Guitar",
"Cha-Cha",
"Heisman Pose",
"Hype Dance",
"Superhero Reveal",
"Country Line Dance",
"It Ain't My Fault",
"Take Me Under",
"Hips Poppin'",
"Cha Cha",
"Samba",
"Block Partier'"
}

local Players = Divider:SearchDropdown{
 Name = "First set",
 Options = emoteoptions,
 Callback = function(choice)
    choice1 = choice
 end
}

local Players = Divider:SearchDropdown{
 Name = "Second set",
 Options = emoteoptions,
 Callback = function(choice)
    choice2 = choice
 end
}

local Players = Divider:SearchDropdown{
 Name = "Third set",
 Options = emoteoptions,
 Callback = function(choice)
    choice3 = choice
 end
}

local Players = Divider:SearchDropdown{
 Name = "Fourth set",
 Options = emoteoptions,
 Callback = function(choice)
    choice4 = choice
 end
}

local Players = Divider:SearchDropdown{
 Name = "Fifth set",
 Options = emoteoptions,
 Callback = function(choice)
    choice5 = choice
 end
}

local Players = Divider:SearchDropdown{
 Name = "Sixth set",
 Options = emoteoptions,
 Callback = function(choice)
    choice6 = choice
 end
}

local Players = Divider:SearchDropdown{
 Name = "Seventh set",
 Options = emoteoptions,
 Callback = function(choice)
    choice7 = choice
 end
}

local Players = Divider:SearchDropdown{
 Name = "Eighth set",
 Options = emoteoptions,
 Callback = function(choice)
    choice8 = choice
 end
}

local setemotes = Divider:Button{
 Name = "Set emotes",
 Description = "",
 Callback = function()
      local equippedEmotes = {choice1, choice2, choice3, choice4, choice5, choice6, choice7, choice8}
      humanoidDescription:SetEquippedEmotes(equippedEmotes)
 end
}

local Quit = Divider:Button{
 Name = "Close",
 Callback = function()
     UI:Quit{
         Message = "GODBYEEEEEEEEEE",
         Length = 1
     }
 end
}
