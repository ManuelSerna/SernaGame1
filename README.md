# SernaGame1
A simple game written in Java

Rather basic game Ideas:
1) Asteroids-like game
  -In-game loop...
   -player starts off in center of screen, and is able to move about freely
   -enemies (whose max number can be defined in its class) accumulate on screen and
    close in on the player's location.
    - in that case, should player's health be one HP, or a full health bar?
  -2 entities: player sprite and enemy sprite (inherit from entity class)
   -entity: appear, move, fire, explode, create/delete sprite, handle collisions within children(?)
   -unique to player: take input & update sprite, possibly handle temp upgrades(?)
   -unique to enemies: movemeny dependent on player's location, fire randomly(?), max num of entities on screen should be set
   
2) Some side scroller
  -something galaga-like(?)
  -entity classes act very similarly as in idea #1
  -background loops, change in background with level
  -unique bosses with each level

3) RPG
  -top-down game with sprites (think 1985 Legend of Zelda, sprites obviously more modern)
  -Define what characters can do
   -standard entity: move, talk (dialogue options like in Elder Scrolls, interact with world, heal, attack (physical: swords, bows and arrows; or magic), defend, contiain basic inventory,other moves(?)
    -player: more advanced inventory system, receive input from user, change armor(?), choose traits(?), companions
    -allies/NPCs: can follow player, independently move, attack when provoked (NPCs)
    -enemy: attack on sight, can alert other enemies, maybe a boss class can inherit from this?
   -animals/creature: completely different class(?): also would have sprite generation, movement, interaction (moving, attacking, defending), maybe talk
