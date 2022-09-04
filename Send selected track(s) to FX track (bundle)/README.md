This is a bundle of LUA scripts for the most advanced DAW in the world: Reaper.

The purpose of this action (script) is to automate adding of SendFX in one go to a selected track.
Also, the script(s) have been enhanced to enable non-destructive behavior when called on a track that already has one or more send FX established.
In this way, even invoking the script can be automated, from a toolbar button in Reaper or from a button on a MIDI control surface.
My ultimate goal with this is to find the way to execute-action-only-once-per-track-per-session which would then enable a real analog mixer-like workflow where you don't have to add sendFX manually for each track but as soon as you touch sendFX pot, the effect is already there.
On the other hand, if you have a brand new track and you don't touch the sendFX pot (i.e. you don't execute this action), then, your track has no sendFX established, therefore saving precious CPU usage.

