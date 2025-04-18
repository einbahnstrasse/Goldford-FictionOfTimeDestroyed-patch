# Goldford-FictionOfTimeDestroyed-patch

## _The Fiction of Time Destroyed_ — Performance Patch

for alto flute, bass clarinet, cello, and electronics

Composed by Louis Goldford (2015)  
Version for MaxMSP designed by Louis Goldford (2015)  

### Contact  
* louis.goldford@columbia.edu 
* +49.152.2101.4084 (DE) 
* +1.415.967.3531 (US) 
* +1.314.629.7913 (WhatsApp)  

### Installation   

Download & unzip folder `Goldford-FictionOfTimeDestroyed-patches` and place in your Max packages folder (`Applications/Max 8/Packages`) or elsewhere in your Max search path.  

Alternatively, if you're running `git`, you can clone this repo:

```
git clone https://github.com/einbahnstrasse/Goldford-FictionOfTimeDestroyed-patch.git    
```

### Requirements    

In order to run the software in performance, you will need free Max package `Spat5` from the IRCAM forum at [https://forum.ircam.fr/projects/detail/spat/](https://forum.ircam.fr/projects/detail/spat/). Without `Spat5`, onboard reverb may be substituted at mix position.

It is strongly advised that a small USB/MIDI mixer be used to control the faders in the patch, but one can also use the mouse when necessary. The patch is configured for a Korg nanoKONTROL2.

See the TECH RIDER located in the subfolder `docs`, and the SCORE (`Goldford-TheFictionOfTimeDestroyed-FSD7_19-08-2020.pdf`), located in the subfolder `score-and-parts`, for additional setup requirements.

### Running    

Before attempting to run the piece, review the tech rider (`Fiction-TechRider-InterfaceInstructions.pdf`) which also includes an introduction to the patch’s interface as well as mappings for the nanoKONTROL2.

1. Open `Goldford-FictionOfTimeDestroyed-MAIN-03.maxpat`, from the main folder, to launch the patch. 
2. Test and set levels for the 3 instrument mics, the soundfile playback level, reverb, main outputs, and dry levels.
3. Click on the `init!` button once all audio drivers and mics are configured. 
4. Conductor cues the start of the piece, and computer assistant follows throughout.

### Change Log    

_All notable changes to this project will be documented in this file._   

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

#### [2.1] 2025-04-05   
_revised for Meiter Ensemble, Tel Aviv_   

##### Added  
- PANIC! Button to stop sound files midway through playback. 
- live.drop object inside init.spat subpatch to override spat file loading if necessary. 
  
##### Changed   
##### Removed  


#### [2.0] 2024-05-13   
_revised for Meiter Ensemble, Tel Aviv_   

##### Added  
- v2.0 individual cues now have listed time stamps, rehearsal letters, and score page numbers to facilitate rehearsals   
- v2.0 `spat5.oper` receives initialization from a converted text file based on old `ircamverb` parameters 
- v.20 `spat5.oper` can be double-clicked on to easily adjust source positions and reverb settings  
- v2.0 instrumental parts (PDFs) have been added to a new `score-and-parts` subfolder, together with the score  
- v2.0 tech rider added to a new `docs` subfolder 
- v2.0 subfolder `spat5` contains all new spat settings to be saved and loaded using commands like `/preset/export` within the patch
  
##### Changed  
- v2.0 Score PDF updated to version `Goldford-TheFictionOfTimeDestroyed-FSD7_19-08-2020.pdf`. 
- v2.0 `ircamverb` replaced by Spat5 objects: `spat5.oper` and `spat5.spat~`  
- v.20 dry signal monitor metering is more clear: these `live.meter~` objects have a gray background  
  
##### Removed  
- v2.0 `ircamverb` 

#### [1.1] 2016-10-16   
_patch revised for ICMC, Utrecht_   

##### Added  
- v1.1 Score PDF added: `Goldford-TheFictionOfTimeDestroyed-FSD7.pdf`. 

##### Changed  
- v1.1 Main patch introduces **JUMP CUEING** to facilitate rehearsals.
- v1.1 `qlist`’s rewind problem has been solved. Now the user may launch an individual cue mid-piece (from the `p cuez` subpatch) without launching the cues that came before it.
- v1.1 (This has only been tested on a few cues, however; there may be further problems due to preloading a sound file a cue earlier, prior to launching that sound file’s cue. If this becomes a problem I will need to redesign the `qlist` to reflect this.)

##### Removed  

#### [1.0] 2015-07-18  
_initial version for Ensemble NOMOS, Valencia, Spain_  

##### Added  
- v1.0 Everything

##### Changed  
##### Removed  

