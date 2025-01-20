TERMS:

- feel free to modify the shell (feel free to ask me for the psd!)
- you can include this in your distributed ghost, but don't redistribute the shell by itself, please
- do NOT use for commercial work, please!
- do NOT claim as your own work. please keep the credit below in the readme.

Hammock Buddies v1.0.2, by WhatAPhantasia
https://whataphantasia.github.io/projects/ukagaka

NOTE:
- kero SHOULD snap into place, at top of sakura's hips. (if kero is not already there)
    - i like putting the kero on top of the sakura's head ^_^
- z-order is set up shell descript side, but sticky-window is not. feel free to add that in your own projects!
- don't be afraid to contact me to tell me abt bugs or whatnot ^^

--------
EXPRESSION GUIDE

kiiinda follows standard surface convention (no singing surface)
all of these surfaces support intervals!

\s[0] - default sakura
\s[1] - embarrassed sakura
\s[2] - surprised sakura
\s[3] - worried sakura
\s[4] - sad sakura
\s[5] - smiling sakura
\s[6] - content sakura
\s[7] - angry sakura
\s[8] - thinking sakura
\s[9] - bored sakura

and just add a 1 before the number if you want kero surfaces.

there's some extra surfaces for idle animations!
\s[20] - sakura leg swing neutral
\s[21] - sakura leg swing smile
\s[25] - kero tail idle
you can also use intervals with these surfaces, and are expected to if you want to do different expressions with them. more details about animations under interval guide.

--------
COLLISION GUIDE

sakura has three collisions: 1 - pet, 2 - face, 3 - hair.
kero has two collisions: 1 - pet, 2 - face. 
use display hit rect for more help.
this shell uses regions, feel free to alter it to add/remove collisions.

--------
INTERVAL GUIDE

i recommend using: 
- \s[0] to apply intervals to the neutral mouth for the sakura
- \s[5] to apply intervals to the smile mouth for the sakura
- \s[10] to apply intervals to the kero 
- the 20, 21, and 25 surfaces mentioned earlier are free to interval use as well

open surfaces.txt if you want to do more indepth editing. 
there's more comments scattered in there if there's:
- an animation you want to remove/alter
    - particularly, you can delete the big back hair if you'd like.

interval list:
---- SAKURA
	5-9: back hair
        5: basic hair
        (OPTIONAL HAIR INTERVALS COMMENTED IN SURFACES.TXT, SEARCH FOR "BACK HAIR ANIMATION")
	10-14: back leg
        10: back
	15-19: front leg
        15: out
        16: middle
        17: back
        18: misc interval to make 19 work
        19: leg swing anim
	20-24: mouth
        20: neutral close
        21: neutral open
        22: happy close
        23: happy open
	25-34: eyes
        25: normal
        26: look
        27: normal lid
        28: look lid
        29: normal close
        30: happy close
        34: blinking anim
	35-39: eyebrows 
        35: neutral
        36: surprised
        37: angry
        38: sad
        39: huh?
	40-59: back arm
        40: recline
        41: hmm (in front of mouth)
	70-89: front arm
        70: recline
	90-99: extras!!
        90: blush
    199: start leg kick animation, when not 20/21.
---- KERO
	20-39: tail
        20: tail relax
        21: tail mid
        37: set up idle
        38: trigger tail idle
        39: set up idle
	40-59: eyes
        40: normal
        41: look
        42: normal lid
        43: look lid
        44: normal close
        45: happy close
        59: blinking anim
	60-79: eyebrows
        60: neutral
        61: surprised
        62: angry
        63: sad
        64: huh?
	80-99: extras
        80: blush 
        (SORRY yeah kero intervals don't line up with sakura's)
as always, use ctrl + t when focused on the ghost to explore the shell!

thanks for reading! have fun!
my next freeshell idea is a bookspider and a lectern ^_^