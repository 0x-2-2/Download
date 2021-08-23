# Download
Here is the copy and paste for the hack

player.onChat(".cps", function() {
    loops.forever(function() {
        while (true)    {
    mobs.execute(
    mobs.playerByName(user),
    pos(0, 0, 0), "gamemode c" + " " + user)
    mobs.execute(
    mobs.playerByName(user), 
    pos(0, 0, 0), "gamemode s" + " " + user)
        }
    })
})

mobs.execute(
mobs.target(NEAREST_PLAYER),
pos(0, 0, 0), "gamerule sendcommandfeedback false")

let user = "VicenteR"
