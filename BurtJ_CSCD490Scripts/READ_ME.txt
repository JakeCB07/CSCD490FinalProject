Jacob Burt
CSCD490
Prof. Tappan
3/27/2023


These are the scripts for all of the Unity modules I was responsible for creating.


Animation

AnimationHandler.cs: The purpose of this script is to change the animation state of overworld enemies and flip thier sprites towards the direction that they are moving.

Character Creation

CharacterCreationMenu.cs: This script is responsible for handling the UI logic for the Character Creation Menu.


Character Stats

Character.cs: This script is responsible for holding the player and enemy stats. 

Stat.cs: A object used for creating character statistics. 

Pickup.cs/StatTestUIManager: Test scripts responsible for making sure the Character.cs and Stat.cs scripts work properly. 


Combat

BattleManager: A script responsible for starting, handling, and ending combat. 

BattleUI: A script responsible for updating the player and enemy portions of the Battle UI.

Enemy: A script attached to enemies that allows them to start combat on contact with the player.


Interaction and Dialogue

Dialogue.cs: A data container for lines of dialogue and the speakkers name.

DialogueManager: Responsible for providing the UI logic for dialogue.

DialogueTrigger: Responsible for starting dialogue and setting lines of new dialogue.

IInteract.cs: An interface for interactable objects in the game.

Interaction: Responsible for detecting if the player is near by and if the interact key was pressed.


Level Up Menu

LevelUpMenu: Contains the UI logic for the Level Up Menu.


Magic System

ICastable: An interface for spells to use.

Spell.cs: An abstrasct class that contains information about a spell.

Firebolt.cs: Deals damage to the target character.

MendWounds.cs: Heals the target character

Swift.cs: Raises the DEX stat of the target character.


Pause Menu

Pause Menu.cs: Contains the UI logic for the Pause Menu.
 

If you would like to see a demo video of the final project go here:
https://drive.google.com/file/d/1nwkIKjwc19xjT5xn8ZBu_29fsJIcjgqm/view?usp=sharing

If you would like to download and play the project yourself go here:
https://drive.google.com/file/d/1ShBOtO3YGkzfNueKkNW1M63LFD3crCM8/view?usp=share_link

The User Manual for the project can be found here:
https://drive.google.com/file/d/1u9EhSdiJ2knCrlKocPt5WHvHSsNTCMzr/view?usp=share_link

