Roblox Scripts Compilation 

Load FPS Booster:

-- Copy This

-- CONFIG 
_G.Settings = {
    Players = {
        ["Ignore Me"] = true,
        ["Ignore Others"] = true
    },
    Meshes = {
        Destroy = true,
        LowDetail = true
    },
    Images = {
        Invisible = true,
        LowDetail = true,
        Destroy = true,
    },
    Other = {
        ["No Particles"] = true,
        ["No Camera Effects"] = true,
        ["No Explosions"] = true,
        ["No Clothes"] = true,
        ["Low Water Graphics"] = true,
        ["No Shadows"] = true,
        ["Low Rendering"] = true,
        ["Low Quality Parts"] = true
    }
}
loadstring(game:HttpGet("https://raw.githubusercontent.com/FoxyelperroDJ/MHSB/main/Booster"))()
