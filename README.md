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


### Requirements    

In order to run the software in performance, you will need IRCAMverb from the IRCAM forum (http://forumnet.ircam.fr/). Without IRCAMverb, onboard reverb may be substituted at mix position.

It is strongly advised that a small USB/MIDI mixer be used to control the faders in the patch, but one can also use the mouse when necessary. The patch is configured for a Korg nanoKONTROL2.

See the SCORE (`Goldford-TheFictionOfTimeDestroyed-FSD7.pdf`), located in the patch folder, for additional setup requirements.


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

#### [2.0] 2024-05-08   
_revised for Meiter Ensemble, Tel Aviv_   

##### Added  

##### Changed  
- v2.0 Score PDF updated to version `Goldford-TheFictionOfTimeDestroyed-FSD7_19-08-2020.pdf`. 

##### Removed  

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

