LETS GO!!1
AMIGOS MOD CHANGELOG

v2.8.1 (I DONT EVEN KNOW WHEN IT STARTED):
- i forgor

v2.8.2 (STARTED 1/31/2025):
        [ CHANGES ]
- Moved some mod assets to lonlihh folder
- Overhauled ext_funcs.hx (probably the backbone of the mod) functions to not be event-reliant
- Window icon changes upon entering the mod (unfortunately does not go back to original icon upon exiting because idk how)
- Moved opponent strums behind opponent in Insubordination song
- Strums are now 40% transparent due to layering issues in Insubordination song
- Made options_list.txt more readable
- Reorganized menu scene scripts
- Made adjustments for the week logo for Kaboom song
- Changed the week logo for Mania Maniac song
- Made adjustments for the freeplay song status bar
- Reorganized menu code (again)
- Menu nowplaying.lua now changes the bar status immediately instead of queueing
- Easter egg's exit scene now uses glitch shader instead of grid wave shader
- Optimized easter egg's communication method
- Reorganized menu code (AGAIN #2), moved easter egg functions to its respective script file
- Made the combo counters to match the color of the player's notes
- Made option menu's resize method more accurate
- Made the circle mechanic to be compatible with playbackRate adjustments
- Updated debug console (Version: 1.0.1)
- Adjusted circle mechanic scaling speed to slightly be more accurate to the hit time
- Changed the icon to another version from one of my libGDX projects
- Did some slight adjustments to the Instrumental and Vocal tracks of Blue cover song
- Changed the general save path for the mod

        [ FIXES / OPTIMIZATIONS ]
- Fixed decaching functions
- Fixed "optStrumDance" option being flipped in Tutorial song
- Fixed wonky camera movements in Insubordination song
- Fixed camThing.lua script not allowing any external camera manipulation other than itself
- Optimized some animations in menu
- Fixed finish bypass when botplay is on
- Optimized pause menu backend code
- In certain circumstances, only the needed menu scenes will load (That is if the optimization option is enabled)
- Fixed scene change events being called more than once
- Fixed health and time bar assets having an extra pixel outside the bar outlines
- Fixed accidentally stacked notes in Abuse song
- Fixed save system messing up and completely making the menu noninteractive
- Fixed Quick Death Restart option crashing the game upon player death
- Fixed circle mechanic rating system not showing up when playing on Botplay
- Optimized song tag to title conversion in Freeplay menu
- Fixed Psych Engine throwing errors whenever player misses a note and has "One-Miss Hold Notes" option enabled
- Backend code optimizations (Subversion 6)
- Backend code cleanup (Subversion 7)
- When an error occurs, it only restarts the current state of the game instead of reloading everything now (Subversion 9)

        [ ADDED ]
- Added a set of strums (arrows) for Red in 2beep2meow cover song
- Added a set of strums for Keep in Blue cover song
- Added SaveType 2 (Psych Engine options) to Options screen
- Added an easter egg to the menu... :)
- Added "Unforgiving Hold Notes" and "One-Miss Hold Notes" as options
- Added a rating system for the circle mechanic in Mania Maniac song
- Added a blended accuracy between notes and circle accuracy in Mania Maniac song (80% - notes, 20% - circles)
- Continuation countdown option
- Combo counter now has animation for hold notes
- Added a pop-up screen informing the user about the changing of the save path (Subversion 7)
- Added a disclaimer screen (Subversion 8)
- Removed the 0.0001 second delay when loading up the easter egg of the menu (Subversion 9)

        [ TO BE ADDED / TO BE FIXED / IN PROGRESS ]
- [30%] Added credits screen
- Fix dusky disappearing when walking to the right side and then interrupting his walk by going into freeplay, options, or credits
- Animate strums not working because of custom countdown script
- [50% Blue Cover song sprites and cutscene]
- [5% Story Mode: Storyline, Voice Acting, Background work, Animation, Dialogue UI Design, Gameplay Design, Coding]
