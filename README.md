# I am Best Skidder

-- config Auto Bounty -- 
getgenv().c = {
    ["Team"] = "Marines", -- team select
    ["Buso"] = true, -- allow buso
    ["Ken"] = true, -- allow ken(observation)
    ["V3"] = true, -- allow v3 race
    ["V4"] = true, -- allow v4 race 
    ["SkipFruit"] = { -- will skip all player using one of this fruit (Leave it blank if want hunt all)
        "Buddha-Buddha", "Venom-Venom", "Leopard-Leopard"
    },
    ["Main"] = {"Melee", "Sword"}, -- select weapon
    ["MainSkillToggle"] = {
        ["Delay"] = 0.7, -- Delay per skill
        ["Z"] = true, -- toggle z
        ["X"] = true, -- toggle X
        ["C"] = true, -- toggle c
        ["V"] = true -- toggle v
    },
    ["Webhooks"] = {
        ["Link"] = "https://discord.com/api/webhooks/1024986424262529124/HhT-6dzFBRfKxABZD5z1fBfO2f3ZfY-F31w3G3zLuO9ZGL24_P47yuh6L42qtqtKse9n",
        ["Banner"] = {
            ["KillTarg"] = "https://media-cdn-v2.laodong.vn/storage/newsportal/Uploaded/lethanhhuyen/2012_07_07/Adolf-Hitler.jpg?w=800&crop=auto&scale=both",
            ["StartScript"] = "https://media-cdn-v2.laodong.vn/storage/newsportal/Uploaded/lethanhhuyen/2012_07_07/Adolf-Hitler.jpg?w=800&crop=auto&scale=both",
            ["Hop"] = "https://media-cdn-v2.laodong.vn/storage/newsportal/Uploaded/lethanhhuyen/2012_07_07/Adolf-Hitler.jpg?w=800&crop=auto&scale=both"
        }
    },
    ["ToggleWebhook"] = true, -- toggle webhook
    ["ChatSpam"] = {"a"}, -- chat while killed 
    ["MinBountyHunt"] = 0, -- min bounty (for scanning target)
    ["MaxBountyHunt"] = 30000000, -- like in
    ["SafeHealth"] = 4000, -- safe health while hide 
    ["YTween"] = true, -- y tween (more fast)
    ["FixingTicks"] = 1200, -- time auto hop while script has error(s)
    ["FixingTicksPerPlayer"] = 100 -- next times per player (s)
}

