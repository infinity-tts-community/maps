# Tabletop Simulator maps designed for Infinity the Game.

A work-in-progress collection of user submitted maps for tabletop simulator.

The scope of this documentation doesn't cover how to use tabletop simulator
or the Infinity workshop mod. I recommend watching the tutorials posted by
VaulSC on YouTube for a very good introduction into these topics.  
[VaulSC Channel](https://www.youtube.com/user/VaulSC/featured)

## Getting the maps into TTS
There are a couple of ways to get these maps into tabletop simulator.

### "I only want one or two maps."
Just go to "Clone or download" at the top of this page and download the
contents of the repository as a ZIP file. Then take whichever maps you
wish and place them into the tabletop simulator saved objects directory.
The location of this directory will vary by system.

*Windows*
```
C:\Users\<username>\Documents\My Games\Tabletop Simulator\Saves\Saved Objects
```

*MacOS*
```
/Users/<username>/Library/Tabletop Simulator/Saves/Saved Objects
```

### "I want all of these and would like to keep up to date as they're added."
Either check out the map-sync tool [here](https://github.com/infinity-tts-community/map-sync)
or use Git directly to clone the repository into your TTS saved objects.

*Windows Example*  
Git for Windows required
```
# open command prompt.
> cd Documents\My Games\Tabletop Simulator\Saves\Saved Objects
> git clone https://github.com/infinity-tts-community/maps.git Community\ Maps
> # to update with latest changes ensure you're in the "Community Maps" folder
> git pull
```

## How to contribute
Depending on levels of technical bravery you can either:
- Open an "Issue" in Github with your contribution zipped and added as an attachment.
- Submit the map on the VaulSC infinity-map-bags channel and mention "d1j1t".
- Create yourself a Github account, fork a copy and open a pull-request containing your changes.
- Help out and submit directly by requesting to become a team member.

Please include screenshots where possible to make browsing the maps easier.

## Reporting an issue
These maps are community contributions. Assets may go missing from hosting providers over time
and result in loading errors in TTS. Please open an Issue in Github to report such problems.
As the assets aren't mine I may not be able to always fix the maps and may have to remove problematic
maps entirely.

---

This collection is completely unofficial and not associated with either Corvus Belli or
Berserk Games.
