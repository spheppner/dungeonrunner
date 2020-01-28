# dungeonRunner
A 2D rogue-like dungeon game with a random generated dungeon. <a href = "https://www.youtube.com/watch?v=9r1kl7rWhjo">Video of gameplay</a>

![image](https://github.com/spheppner/dungeonRunner/blob/master/screenshot4.png)

## Dungeon of Math
Rumors say that in the dungeon on the 15th level you will be teleported out to freedom. So that's your goal. On your way out you will need to fight against monsters, collect coins and heal yourself if you get injured. Good Luck!

## Legend
###### "@": that is the player
###### "<": a stair leading down into the next level (next dungeon)
###### "1, 2, 3, 4": Monsters, the higher the number of it, the stronger it is
###### "#": Wall, you can't go against it, except you dig it (digging mode, see "#Control")
###### "0": Coin, you can collect
###### "+": shop
###### "-": exit sign

## Control
###### "W": up
###### "A": left
###### "S": down
###### "D": right
###### "LShift" + "W", "A", "S" or "D": digging mode (you dig in the direction that you pressed LShift with)

## Fight between Monster and Player
###### Option 1: 
If the monster attacks the player, the player can flee
###### Option 2: 
If the player engages the fight, he must end the fight or die in it, but he can't flee
If fight is engaged player needs to enter the answer to a multiplication that is randomly generated and shown in the lower left corner. Player has ten seconds to answer
Damage that is dealen = left time * multiplicant variable that is defined in class of Player()

## Award Winning Game
This game won the "Ars Electronica Create Your World U19" competition in 2019. Thank you!
