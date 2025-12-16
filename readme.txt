XTX- GFR (Going For Real)

GFR is based on 25 years of being a truck driver.

MIRRORS FOV

This mod is Convoy optional!

This mod works in all trucks.
 
Changes made by this mod...

MIRRORS
1. Draws the environment seen in the mirror much closer to you. Very much closer to realistic!
2. Removes the skewed (vertically stretched) visual of the environment in the main mirrors. Very realistic!

Usage recommendation: 
- Always place higher than truck mods or other mods that include changes to mirrors. If in doubt, highest.

NOTE:
- Many mods you may not suspect include this file. Including the common "Realistic Brutal Graphics And Weather". If this isn't higher than that, this won't work.
- This will change the way any mod looks with mirror files, if it is higher than it in your list.
- I can't possibly account for every possible desire of every modder's values in this file.
For example the popular Brutal Weather mod changes this file to his liking in his mod, and this will remove those changes and return them default.
- This will drastically reduce your horizontal view angle just like RL, and you will likely need to crank your main mirrors in quite a lot.
- Just like RL mirrors, your visual view in these mirrors is that restricted, and now you may understand why a truck didn't see you there.
- It seems that all the available trucks for us to play with, have a varying degree of default differences in how they are modeled.
In this case some may not look as realistic as I hoped. And some may not allow you to turn your mirrors in far enough to your desire. Keep reading.
- Modern factory aerodyne mirrors may not be modeled in the 44:100 aspect ratio, and may look skewed.
- I made this mod while using head tracking and I can move my head to see more in the mirror. If you do not have head tracking you may find this unappealing.

SOME ADVICE about mirrors and what you see in them before you read on...
- I will spend hours adjusting mirrors in a real truck to accomplish what many feel is the best view for your mirrors.
The goal is to see just the top outer edge of your two outside drive tires (or at least the rear one) in the lower inside corner of the main mirror at a glance.
This way at a glance you have a reference for your brain to measure distance from objects. Moving your head little will allow you to see more of your tires
in a problem situation.
This should also put that annoying trailer's front corner marker light just out of your peripheral vision at night. But a slight head movement can see the trailer is there.

- The two convex mirrors should be set to allow you to see what is close to your fuel tanks at about 5 and 7 o'clock in the mirror.
The truck body showing a sliver of it in the 3 and 9 o'clock position.

- Cranking your mirrors in to see the side of your cab does you no good, since it's likely you are not going to have a problem with the side of your cab.
If you do, you might consider buying a new truck at that point.

- Protecting your fuel tanks is crucial in trucking. Punching a hole in it with a pallet, rock, or stump is never a good thing.
Not being able to see what is close to them is a bad idea.

- I have a friend who uses this mod and he ran across a truck mod that didn't allow the mirrors to come in enough for him to see what is advised above.
So very close though. So I showed him how to adjust the mirror file to fix it. He changed the value up by 1 on the main mirrors.
And turned my mod into a seperate one just for that truck, by copying my mod contents to a new folder, giving it a name, and changed the name in the "manifest.sii" file.
It took him about a minute to do it.

- If there is something you don't like or need to change to make this work better for you...
It is not hard to change this file to see more and you won't make it look skewed again. Things will just look smaller and farther away.
- I have made many notes in the files for your convenience, and to help you make changes. You just have to figure out what to change, and how much.

CHANGE IT TO SEE MORE...
- Open the mod folder and find the "game_data.sii" file.
- Open that file in any text editor...
Change these lines to your desire... Higher values increase the amount of view you have, but make things look smaller and farther away.
Do small increments of 1-2 in your changes until you reach your desired outcome.

mirror_fov[]:		11.0f 	// close mirror	 	#Left main mirror. Default was 30.
mirror_fov[]:		28.0f 	// close small mirror	#Left small mirror. Default was 90.
mirror_fov[]:		11.0f 	// far mirror		#Right main mirror. Default 30
mirror_fov[]:		28.0f 	// far small mirror	#Right small mirror. Default 90
mirror_fov[]:		60.0f 	// side mirror		#Mirror above right door. Default 60		
mirror_fov[]:		25.0f 	// front mirror		#Left hood. Default 45
mirror_fov[]:		25.0f 	// front2 mirror	#Right hood. Default 45

