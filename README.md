# HungryBobGame 🤖

## 🗒️ Backstory

-> In a  pixelated world far from our own, lives Bob, a lovable, always-hungry character. His once peaceful home is now overrun by enemies creating chaos. Bravely, Bob steps up to outsmart these foes, seeking to restore peace and satisfy his constant hunger.

-> The game draws inspiration from classic arcade games, blending nostalgia with modern creativity. It's a tale of bravery and quick reflexes.

## 🛠️ Game description
Navigate through a dynamic 16x16 map world, filled with dangers and delights. Your mission is to help Bob consume food while dodging enemy bullets. As you progress, the challenges grow, testing your agility and strategic thinking.

## ▶️ Instruction on how to play:
There are 4 types of elements in the game: 
- **Player (Bob):** Blinks slowly, representing your character.
- **Enemy:** Blinks rapidly, indicating imminent danger.
- **Food:** Blinks at the slowest pace, waiting to be devoured.
- **Wall:** A static obstacle that doesn’t blink.

The player has to move around using the joystick and eat food (15 to win) while avoiding the bullets from the enemies. The enemies can shoot up to 3 LEDs distance (depending on
the difficulty of the game) and only on the x and y axes. The bullets have a delay and
the player can avoid them. The player cannot pass through walls. Depending on the level
of difficulty more food will be generated on the map. The map has a 16x16 dimension and it's surrounded by walls. When the player approaches the edge of the physical matrix, the displayed part of the 16x16 map will change (fog of war).

## ✏️ Menu requirements:
- **Intro message**
- **Start Game:**
  * Shown details while playing
  * Screen upon game ending with input in order to move on
  * Informs you when highscore is achieved
- **Highscore:** top 3 in eeprom with name and score
- **Settings:**
  * Enter name 
  * LCD brightness control (eeprom)
  * Matrix brightness control (eeprom).
  * Sound control on/off (eeprom)
  * Reset high scores button in settings
- **About:** github user, developer name and game name
- **How to play:** short and informative description

## ⚙️ Components:
- Arduino board
- Joystick 
- 8x8 LED Matrix 
- MAX7219 
- LCD Display
- Buzzer
- Button
- resistors and capacitors
- wires

## 📷 Setup and code:

[💻 <b>Code</b>](https://github.com/anamariapanait10/HungryBobGame/blob/main/hungrybobgame/hungrybobgame.ino)

<details>
 <summary><b>Photo</b></summary>

 <div align="center"> 
  <img width="480px" src="https://github.com/anamariapanait10/HungryBobGame/blob/main/SetupPhoto.jpeg" alt="Photo">
 </div>
</details>

<details>
 <summary><b>Video</b></summary>

 <div align="center"> 
   <a href="https://youtu.be/tppwd_xsm20"><img src="https://img.youtube.com/vi/tppwd_xsm20/0.jpg" alt="Video"></a>
 </div>
</details>