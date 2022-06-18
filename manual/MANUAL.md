# Toad On Fire - Game Instruction Manual
Thank you for downloading and playing!

1. Controls
2. Getting Started
3. Basic Gameplay / Flamethrower Mechanics
4. Money / Loot
5. Upgrades

## 1. Controls
#### Keyboard
```
Move...........................Arrow keys
Strafe.........................Left Shift
Drop Item......................D
Shoot Flamethrower.............F / SPACE
Charge Flamethrower............C
Special Attack (Cannonball)....Charge until full, then press F (or SPACE) while C is still held down
Use Shield.....................D
Throw Grenade..................G
Talk to NPC....................F / SPACE while close-up and facing NPC
Toggle Switch..................F / SPACE while close-up and facing switch
Access Game Menu...............ESC
```
### Xbox 360 Controller
```
Move...........................Analog stick or D-pad
Strafe.........................LB
Drop Item......................X
Shoot Flamethrower.............A
Charge Flamethrower............B
Special Attack (Cannonball)....Charge until full, then press A while B is still held down
Use Shield.....................X
Throw Grenade..................Y
Talk to NPC....................A while close-up and facing NPC
Toggle Switch..................A while close-up and facing switch
Access Game Menu...............Start
```
### Other Game Controllers
I have not tested with many controllers, but the layout should be similar to the Xbox 360 configuration.

## 2. Getting Started
_If you'd like to compile the game from source, then first compile `build.bas`, then run `build.exe` to compile the game._
_Optionally, there is also a bash script `build` that you can run on Linux systems._

Run toadonfire.exe. Select **Start** and then choose a **New Game** slot. You can come back later and load your game from this slot. The game auto saves. You start with nothing. As the game progresses, you'll acquire new items and abilities.

## 3. Basic Gameplay / Flamethrower Mechanics

Use the arrow keys or the d-pad/analog-stick to move around. The primary action is **F** / **Space bar** for the keyboard and **A** for the Xbox 360 controller. The primary action will allow you to talk to NPCs, toggle switches, and fire your flamethrower.

Your main weapon will be the flamethrower. You can set things on fire, destroy trees, blow up barrels, and destroy enemies with it. Be cautious though, because the flamethrower can overheat.
### Overheating
There is a bar in the bottom-left corner of the screen. This is your **heat bar**. It tells you how hot your flamethrower is. The more you fire, the hotter it gets and the heat bar will continue to fill up. When you stop firing, the heat bar will drain, meaning that your flamethrower is cooling off. If the heat bar fills up completely, you'll lose the ability to fire for a few seconds, until the flamethrower cools down and the heat bar completely drains.

### Experience Points
Right above the heat bar is the **xp bar**. As you destroy enemies, you'll see sparkles that fly towards you. As you collect these, your xp bar will fill up. When it fills up completely, your flamethrower will automatically level-up to the next level and become more powerful. Level three is the highest level you can attain from the start. Later in the game, you can purchase upgrades that'll let you access higher levels. Once you reach the highest level, if your xp bar fills up again, you'll be rewarded with an extra life.

Dying will cause your xp bar to reset and your flamethower to revert to the first level.

## 4. Money / Loot

Toad On Fire uses food and gems for its currency. Gems are much more valuable than food. Move over the item to pick it up and it'll add to your total money/loot amount (shown in the bottom-right corner of the screen). You need to complete the level to keep the loot that you found.
You can play the same level again to collect more loot. However, you can only take the gems once.

#### Loot Value
```
Fruit.....................1
Corn......................1
Food Crate................5
Yellow Gem................5
Green Gem.................10
Blue Gem..................25
Red Gem..................100
```

## 5. Upgrades
As you play the game, you'll acquire new upgrades and abilities. However, some upgrades and abilities must be purchased. So collect as much loot as you can so you can afford it when the time comes.
Upgrades are found in shops. Shops are levels that have the dollar-sign icon on the world map. You can talk to NPCs to purchase items. Other items can be found locked in chests that can only be opened if you have enough money. The amount will be displayed to you when you are close-up and facing the chest.

## 6. Mobs

### Looter

<table>
    <tbody>
        <tr>
            <td rowspan="4"> <img src="./doc/images/mob-pikefrog.png" /> </td>
            <td><strong> Hostile </strong></td><td> Yes <br>
        </tr>
        <tr>
            <td><strong> Actions </strong></td><td> Pike Stab <em>( light damage )</em> </td>
        </tr>
        <tr>
            <td><strong> HP </strong></td><td> &#9646;&#9646;&#9646; </td>
        </tr>
        <tr>
            <td><strong> Comments </strong></td>
            <td>
                Looters are made up of mostly militia forces. Having little-to-no formal training<br>
                training, they don't pose much of a threat in small numbers, and must get close<br>
                before they can employ the use of their melee weapon.
            </td>
        </tr>
    </tbody>
</table>

### Marauder

<table>
    <tbody>
        <tr>
            <td rowspan="4"> <img src="./doc/images/mob-marauder.png" /> </td>
            <td><strong> Hostile </strong></td><td> Yes <br>
        </tr>
        <tr>
            <td><strong> Actions </strong></td><td> Dual Plasma Blasters <em>( light damage )</em> </td>
        </tr>
        <tr>
            <td><strong> HP </strong></td><td> &#9646;&#9646;&#9646; </td>
        </tr>
        <tr>
            <td><strong> Comments </strong></td>
            <td>
                Marauders are trained in firearms and close-quarters combat.
            </td>
        </tr>
    </tbody>
</table>

### Firestarter

<table>
    <tbody>
        <tr>
            <td rowspan="4"> <img src="./doc/images/mob-fireknight.png" /> </td>
            <td><strong> Hostile </strong></td><td> Yes <br>
        </tr>
        <tr>
            <td><strong> Actions </strong></td><td> Dual Flame Pistols <em>( light damage - rapid fire )</em> </td>
        </tr>
        <tr>
            <td><strong> HP </strong></td><td> &#9646;&#9646;&#9646;&#9646;&#9646;&#9646;&#9646;&#9646;&#9646;&#9646;&#9646;&#9646; </td>
        </tr>
        <tr>
            <td><strong> Comments </strong></td>
            <td>
                Firestarters dual wield a pair of flame cannons to unleash a hellish blaze.
                They are<br>much tougher than marauders and looters, and so are likely to
                strike back before<br>they are dispatched.
            </td>
        </tr>
    </tbody>
</table>

### Cyclops

<table>
    <tbody>
        <tr>
            <td rowspan="4"> <img src="./doc/images/mob-bishop.png" /> </td>
            <td><strong> Hostile </strong></td><td> Yes <br>
        </tr>
        <tr>
            <td><strong> Actions </strong></td><td> Magic Fireball <em>( light damage )</em> </td>
        </tr>
        <tr>
            <td><strong> HP </strong></td><td> &#9646;&#9646;&#9646;&#9646;&#9646;&#9646;&#9646;&#9646;&#9646;&#9646;&#9646;&#9646;&#9646;&#9646;&#9646; </td>
        </tr>
        <tr>
            <td><strong> Comments </strong></td>
            <td>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Cras vel<br>sapien ullamcorper,
                malesuada lorem sed, faucibus nibh. Aenean<br>malesuada, turpis quis eleifend malesuada,
                sem odio. 
            </td>
        </tr>
    </tbody>
</table>

### Tree Hugger

<table>
    <tbody>
        <tr>
            <td rowspan="4"> <img src="./doc/images/mob-treehugger.png" /> </td>
            <td><strong> Hostile </strong></td><td> Yes <br>
        </tr>
        <tr>
            <td><strong> Actions </strong></td><td> Avoids danger </td>
        </tr>
        <tr>
            <td><strong> HP </strong></td><td> &#9646;&#9646;&#9646;&#9646;&#9646;&#9646;&#9646;&#9646;&#9646;&#9646;&#9646;&#9646;&#9646;&#9646;&#9646; </td>
        </tr>
        <tr>
            <td><strong> Comments </strong></td>
            <td>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Cras vel<br>sapien ullamcorper,
                malesuada lorem sed, faucibus nibh. Aenean<br>malesuada, turpis quis eleifend malesuada,
                sem odio. 
            </td>
        </tr>
    </tbody>
</table>

### Pygmy

<table>
    <tbody>
        <tr>
            <td rowspan="4"> <img src="./doc/images/mob-yellowjacket.png" /> </td>
            <td><strong> Hostile </strong></td><td> Yes <br>
        </tr>
        <tr>
            <td><strong> Actions </strong></td><td> Toxic Bite <em>( light damage )</em> </td>
        </tr>
        <tr>
            <td><strong> HP </strong></td><td> &#9646;&#9646;&#9646;&#9646;&#9646;&#9646;&#9646;&#9646;&#9646;&#9646;&#9646;&#9646;&#9646;&#9646;&#9646; </td>
        </tr>
        <tr>
            <td><strong> Comments </strong></td>
            <td>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Cras vel<br>sapien ullamcorper,
                malesuada lorem sed, faucibus nibh. Aenean<br>malesuada, turpis quis eleifend malesuada,
                sem odio. 
            </td>
        </tr>
    </tbody>
</table>

### Sheep Bomb

<table>
    <tbody>
        <tr>
            <td rowspan="4"> <img src="./doc/images/mob-sheepbomb.png" /> </td>
            <td><strong> Hostile </strong></td><td> Yes <br>
        </tr>
        <tr>
            <td><strong> Actions </strong></td><td> Proximity Bomb <em>( light damage )</em> </td>
        </tr>
        <tr>
            <td><strong> HP </strong></td><td> &#9646;&#9646;&#9646;&#9646;&#9646;&#9646;&#9646;&#9646;&#9646;&#9646;&#9646;&#9646;&#9646;&#9646;&#9646; </td>
        </tr>
        <tr>
            <td><strong> Comments </strong></td>
            <td>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Cras vel<br>sapien ullamcorper,
                malesuada lorem sed, faucibus nibh. Aenean<br>malesuada, turpis quis eleifend malesuada,
                sem odio. 
            </td>
        </tr>
    </tbody>
</table>

### Hellhound
![ ](./doc/images/mob-hellhound.png)
### Scout Probe
![ ](./doc/images/mob-probe.png)
### Drone
![ ](./doc/images/mob-drone.png)
### Armored Arthropod
![ ](./doc/images/mob-arthropod.png)

