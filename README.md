## Overview
A Risk Of Rain 2 Soundtrack Replacement Mod themed after Bayonetta!

![](https://i.imgur.com/jwYN1mS.png)

Experience the magic of a Universe of Light and Dark with this Risk fo Rain 2 Bayonetta Music Replacement Mod! Find over 70 tracks from *Bayonetta* and *Bayonetta 2*.

The following mod has made possible thanks to the [OriginalSoundTrack By Kyle](https://thunderstore.io/package/Kyle/OriginalSoundTrack/). If you would like to make your own music mod, see that mod.

**NOTE:** This is a comprehensive collection of songs from *Bayonetta* and *Bayonetta 2* **only**. **There are no songs from *Bayonetta 3* or *Bayonetta Origins*** and I have no interest in adding any at current.

---

**If you're curious what songs have been included and where**, click [Here](https://docs.google.com/spreadsheets/d/1KRSQxnq1TqzPpFNwExTA0xBNTxOudpyIDwLs8gW07WY/edit?usp=sharing) for a comprehensive list of all songs and their set Scene IDs.

## Contact
If you wish to report any music requests, bugs, or any music that seems to play too loudly or too quitely by default, you can find me on the [Risk of Rain 2 Modding Discord](https://discord.gg/NgZh8RCQ). [My Discord is **Silver_Diamonds#3080**].

## Customize

**If you want to replace or alter any of the songs in this mod, you can! Here's how:**
* Find the Mod in your R2ModMan file. The path to it should be: ` C:\Users\USERNAME\AppData\Roaming\r2modmanPlus-local\RiskOfRain2\profiles\PROFILENAME\BepInEx\plugins\Bayonetta_Soundtrack `
   * For Manual Downloads, the path should be: `  C:\Program Files (x86)\Steam\steamapps\common\Risk of Rain 2\BepInEx\plugins `
* Uplaod your music to the folder ` Bayonetta_Soundtrack ` (Must be either .mp3 or .wav)
* Copy your file's name
* Open the ` settings.md ` file in a text editor (e.g. Notepad)
* Add a new instance for when a song is to play. For example, if you want the song "My Song" to play on the character selection screen at max volume, you would add:
``` 
<song
    name="My Song.mp3"
    scenes="lobby"
    boss="false"
    volume="1"
/> 
```
* That's it, you've added your own song!
  * If you want to replace a song rather than just add a new one, paste your file name over the name in the original instance (Make sure so always include the .mp3 or .wav extention).
  * Click [Here](https://risk-of-thunder.github.io/R2Wiki/Mod-Creation/Developer-Reference/Scene-Names/) for a full list of all Scene IDs
  * Volume Ranges from 0 to 1 as a decimal.
  * Setting the "boss' string to "true" means the song will only play when a boss activates in that "scene" (Note that you cannot set boss specific songs for Hidden Relams).
  * The ` <loop>true</loop> ` string sets songs to loop when finished playing.
  * The ` <volume>1</volume> ` string is the Master Volume Setting for the Mod (also ranging from 0 to 1 as a decimal).
  * Do NOT include any special characters in your file names (!&-_, *etc.*), otherwise the mod will select a random song rather than the one that is supposed to be called.
  
---
## P.S.
I should also note, this mod was made out of a passion for *Bayonetta*, and a hope to spur on the  a whole character mod for her (I personally belive she has a lot of potential for a *Risk of Rain 2* character). So if you are an experienced *Risk of Rain 2* modder and like the music you hear in this mod, maybe consider checking out her home games! It just might give you the inspiration to impliment her as her own character! (I personally have a lot of ideas as to how she could work).

## Change Log
` 1.0.0 `
- Initial Release
   
   *"Let's dance, boys!"*
