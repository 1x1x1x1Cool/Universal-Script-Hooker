# Universal-Script-Hooker
Concept of searching in all scripts a required method, or searching how events are fired


There are 2 main variables; the METHOD one is the method you have to check in every single localscript of the game; The "check" one is instead for veryifing who is being kicked/destroyed.
example:

METHOD = "Kick"
check = "LocalPlayer"

This will check every kick function fired on the localplayer.

In future the aim point of all this is to search how remoteEvents are fired, and general anticheat functions.

In this beta version there are only local scripts, but the concept is to add modulescripts too, that are easier to hook and modify.
