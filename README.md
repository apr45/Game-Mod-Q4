## Midterm Turn-Based Game

### How to Launch:
Click on the .bat file 'launch.mod' to start up the modded version of Quake 4.

---
### How to Begin:
Once launched and loaded, navigate to create a new game as you do in the original version.

---
### Player Movement Controls:
* W - Move Forward
* A - Move Left
* S - Move Backward
* D - Move Right
* Space Bar - Jump
* Touchpad/Mouse - Move Camera
<br></br>
---
### How to Play:
Battle against monsters in a one-to-one approach after advancing within a certain range. Once near an opponent, regular player movement is frozen, and gameplay enters into a turn-based combat system until either you or the opponent dies. 'Right Shift' to move forward with dialogue detailing actions occurring during battle.

On the opponent's turn, they will attack you with a possibility to either miss or land a critical hit. You will take damage and lose health based on their attack.

On your turn, you are presented with three options to choose:
* Act (1) = Upon choosing "Act", you are to select between five different actions:
    1. Medikit (1): Gain a few health points back for a turn.
    2. Poison (2): The opponent will receive minimal damage for two turns.
    3. Double Credits (3): On next turn, receive twice the amount of credits depending on the action chosen.
    4. Flee (4): A 5% chance to flee from the enemy and win the battle.
    5. Gamble (5): A 10% chance to deal 50 points damage to the enemy; otherwise, you will take 25 points in damage.
* Block (2) = You will dodge the opponent's attack on their turn for one round and avoid any damage taken.
* Attack (3) = You will attack the opponent, dealing harm based on your weapon. On the start of the game, you are given a default blaster, dealing 5 points in damage. You have a certain chance to land a critical hit, inflicting higher damage.

To confirm your decision, press the keys '1', '2', '3', '4', or '5' corresponding to action.

By the end of your turn, you will receive a certain amount of credits and experience depending on your choices.
* Credits: You can purchase permanent special equipment from the store only available during your turn.
    1. Armor (6) = Take 20% less damage from opponents.
    2. Medikit+ (7) = Increase healing by 10%.
    3. Lucky Dice (8) = Increase chance of critical hits by 15%.
    4. Exp Ring (9) = Receive double experience.
    5. Venom (0) = Increase poison damage by 5%.
* Experience: Once you reach a certain threshold, you level up and gain a new weapon with higher attack damage. Experience gained previously resets to 0.
    1. Shotgun (Level 1): 10 damage points
    2. Machine Gun (Level 2): 15 damage points
    3. Hyper Blaster (Level 3): 20 damage points
    4. Rocket Launcher (Level 4): 25 damage points
    5. Nailgun (Level 5): 30 damage points

Hit keys '6', '7', '8', '9', or '0' to select equipment and confirm purchase by pressing down on key 'B'.

On every seven cycles that pass during the turn-based battle, the monster's attack damage will increase by 5 points.

Once you defeat the opponent by decreasing their health to 0, gameplay will resume to normal, and player movement will be unfrozen until you encounter another monster. However, if your health reaches 0, the game closes automatically.