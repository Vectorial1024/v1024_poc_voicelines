# v1024_poc_voicelines
X4 Foundations Proof-Of-Concept: voice-line changing

This is a POC mod that changes all the X4 v5.0 vanilla sector-name English voicelines to the Gawr Gura "A". This is to show that changing vanilla voice lines is possible through a mod.

The Gawr Gura "A" sound is obtained from:

https://www.youtube.com/watch?v=1Uzw1Zr1FE4

The sound file is then edited to reduce its length, so that the famous "A" sound is played at the beginning of the sound file.

I do not claim ownership to Gawr Gura or their related brand names and etc. This is for illustrative purposes only. Fair use!

## Special Note

As specified in this "precursor" mod for X Rebirth (https://forum.egosoft.com/viewtopic.php?t=362561), you must install this mod to the game's base directory (e.g. `C:\Program Files (x86)\Steam\SteamApps\common\X4 Foundations` ) and add `-prefersinglefiles` to the launch options.

It seems currently impossible to install this mod as a regular `extensions` mod and make it work: the Gawr Gura's "A" simply would not load. (If you are replacing other types of sound, then there is a workaround that allows you to "replace" the sound effects with something else so that it is still installable as a regular `extensions` mod. It is to replace the sound-producing elements in the various relevant macros with custom sound definitions in `libraries/sound_library.xml`. However, this workaround does not seem to work for voice lines.)

Also, while this mod does not include lipsyncs for the voice lines, it should still be stressed that a complete voiceline mod should include lipsyncs. Not that I am able to make lipsyncs...

## Sound Note

For this specific case (Betty's sector names), the sound files should all be mono-channel.

## Directory Guide

WIP

```
/content.xml
/cropped_a.ogg       <- Cropped "A"
/source_a.ogg        <- Original "A"
/propagate_a.py      <- Python file to help copy the Gura "A" to the many known places in the repo
/voice-l044          <- Root of English voices
```
