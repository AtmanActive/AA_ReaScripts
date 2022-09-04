This is a bundle of LUA scripts for the most advanced DAW in the world: Reaper.

The purpose of this action (script) is to automate adding of SendFX in one go to a selected track.
Also, the script(s) have been enhanced to enable non-destructive behavior when called on a track that already has one or more send FX established.
In this way, even invoking the script can be automated, from a toolbar button in Reaper or from a button on a MIDI control surface.
My ultimate goal with this is to find the way to execute-action-only-once-per-track-per-session which would then enable a real analog mixer-like workflow where you don't have to add sendFX manually for each track but as soon as you touch sendFX pot, the effect is already there.
On the other hand, if you have a brand new track and you don't touch the sendFX pot (i.e. you don't execute this action), then, your track has no sendFX established, therefore saving precious CPU usage.

Here is how to use it:
When you a starting your project, create four tracks and name them "SendFX1", "SendFX2", "SendFX3" and "SendFX4".
Please note that these required names are just prefixes. You are free to name your tracks "SendFX1: Reverb", or "SendFX2: Delay", or however you wish, as long as the "SendFX1" part is there.
Now you add insertFX on these four tracks to create your actual effects (reverb, delay, chorus, flanger...). If you are not yet sure which sound you are after, you can just leave the tracks muted, for now.
That's it. That's all preparation needed.
Later in your workflow, whenever you want to add sendFX to a track, all you need to do is to select that track and execute the action "SendFX1234".
You can execute it from a toolbar, or you can create a keyboard shortcut, or you can assign it to a button on a MIDI surface controller using either CSI or ReaLearn.
When you execute it on the selected track, the track will get sent to those four SendFX tracks and you can now adjust sendFX levels to taste.
If you later on execute the same action on a track that already has four sendFX established - nothing will happen. The script is safe to be executed infinite number of times.
