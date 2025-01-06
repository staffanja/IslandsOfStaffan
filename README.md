# IslandsOfStaffan

Developed for iPhone.

The app starts in Play mode ready to play scenes, import samples and bounce to file. 

To create a new scene, press the plus button. Note that the app always starts with scene 00, while this scene can be freely edited, changes to it will be lost unless it is saved to another slot using the plus button. Scenes 01 - 63 are autosaved when switching between scenes and when the app is minimized. Scenes can be reset by pressing the minus button. There is no undo button.

Press the waveform button to import wav files. The app supports WAV 48kHz with 32, 24, 16 or 8 bits. Internal channels are mono, so only the left channel is imported if samples are stereo or interleaved. Selected files are automatically assigned to next available slot. The sample memory is about 4MB with 256 sample slots grouped into banks of 8.

The two pink buttons below the grid switces back and fourth between the scenes. The mix out put can be bounced to file by pressing the pink button above the grid, press it again to stop recording. Whenever a bounce file is available for export, the folder button will be highlighted, press it to export the file for later use.

Swipe sideways to open the Edit and Mix modes. In Edit mode, sequence samples and set track specific sound parameters. In Mix mode, apply filter and do additional mixing. 

The simplest way to test sound output is to press the purple TRIG pattern button in Edit mode, this will output the default sound playing in 16th notes, to alter the rhythm press the PATTERN +/- buttons, add other pattern types to create more complex rhythmics.

Each track have 7 pattern types, each type can use a single pattern or alternate between pattern A and B. Track length sets the overall length for all pattern types. If the track length is greater then the length of pattern A it will switch to pattern B. If the track length is greater than the length of both A and B they will cycle. The pattern with the greatest length IN FRAMES! (see GATE pattern below) will acts as master and trigger a reset of all other tracks to step 1.

Pattern length can be set from 0 to 32 steps and each pattern can be shifted +/- a number of steps.

Track shift moves the track - 1/16th to + 1/16th in very fine increments. 

Tempo is global and can be set from 20 - 20 000 bpm.

Pattern types
GATE    : Sets a gate pattern that acts as a master for all the other patterns**
SWING   : Adds a swing pattern that affects the gate pattern by the amount of swing.
TRIG    : Sets a trig pattern for the steps, can be inverted.
MUTE    : Applies a mute pattern on the trig pattern.
RETRIG  : Adds up to 8 retrigs on selected steps.
ACCENT  : Applies an accent pattern.
STATE   : Acts in two modes***

** Gate patterns alternate between two different gate lengths from 1/32 to 1/1, setting both to the same note length will remove the rythmic effect of the pattern.

*** When set to pattern 1 it only plays the sample that is assigned to the active state. Samples are assigned to states just be selecting them. It can also switch between up to 8 samples (states) to enable even more complex rhythms or melodic behaviour depending on the type of sounds.

Edit mode also have a track level encoder, a track pan encoder and two group assign buttons which leads us to the Mix mode.

In Mix mode each group has its own level fader and filter. There is also a crossfader and and lfo that can be assigned to the filters. The filters can switch between 7 different modes by pressing the purple buttons. The pink buttons are for on/bypass. Cutoff and filter resonance can be adjusted with encoders.

Final note. All sequence programming is done with preset patterns, this is by design.
