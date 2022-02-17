# Niko-Pepper-Lovebirds
A small turn-based JRPG where you play as two parakeets looking to save the world from an evil cockatiel.

BASIC GAMEPLAY
* Each bird gets one action in a turn.
* To select an ability, click on one of the ability icons or press '1', '2', '3', or '4'.
* To use a selected ability, click the GO! button or press 'c'.
* If an ability specifies that it has a target, click on an enemy bird to target them. Click on a targeted enemy again to untarget them.
* Once you have used an ability, the NEXT button should appear. Click it or press 'n' to procede to the next turn. You must also do this after
  an enemy bird uses their ability.
* You get a few turns in between enemy encounters, so make sure to heal up!
* If one of your birds is defeated, it will respawn with 1 health.
  
EFFECT CHAINING
* Effects will disappear at the end of a bird's turn.
* If a bird's effects are sustained (marked by a blue diamond next to their health values) then the effects will not disappear. Instead, the 
  sustain will go away.
* When a bird gains an effect, its effects are sustained.
* Every effect can be sustained, including bad ones.
 
EFFECTS
* Bleed - This bird takes one damage at the start of its turn. Does not kill the bird until the end of its turn.
* Shield - This bird takes one less damage for every point of shield whenever it takes damage. Bleed is not affected by shield.
* Damage (DAM) - This bird's damage is modified by their damage number. Can be positive or negative.
* Retaliate (RET) - When this bird is attacked, it deals this much damage back to the enemy that attacked them. Retaliate is not triggered by
  retaliate.
  
TECHINICAL ISSUES
* No volume control
* Only displays at 1920x1080p in fullscreen
* Windows Defender may prevent you from running it. Unsure if this is because the files don't have an entity tied to them or what.

CREDITS
* Niko and Pepper: Lovebirds
* A game by Andrew Hunter
* Music and Sound Effects by Daniel Speal
* Thank you to EminYILDIRIM on freesounds.org for the following sound effect:
	https://freesound.org/people/EminYILDIRIM/sounds/611193/
* Thank you to colorsCrimsonTears on freesounds.org for the following sound effect:
	https://freesound.org/people/colorsCrimsonTears/sounds/580307/
* Thank you to Borgory on freesounds.org for the following sound effect:
	https://freesound.org/people/Borgory/sounds/548367/
* Thank you to Tairblenn on freesounds.org for the following sound effect:
	https://freesound.org/people/Tairblenn/sounds/540151/
* Thank you to alanmcki on freesounds.org for the following sound effect:
	https://freesound.org/people/alanmcki/sounds/461017/
* Thank you to Tofu on Lospec.com for the following color palette:
	https://lospec.com/palette-list/tofu-20k
* Thank you to rodrigosrtz on dafont.com for the following font:
	https://www.dafont.com/i-pixel-u.font
* Thank you to kikito on GitHub for middleclass.lua:
	https://github.com/kikito/middleclass
* And of course, special thank you to the LOVE2D framework and their forums:
	https://love2d.org/
