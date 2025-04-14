# Shiki
**White Noise Instrument**

_Shiki_ is a customizable virtual instrument with two white noise oscillators developed by Austin Oting Har and Kurt Mikolajczyk, beginning in summer 2024 and premiered  at the Center for New Music and Audio Technologies (CNMAT) in October 2024. This NIME (New Instrument for Musical Expression) is capable of rhythmic and timbral gestures, blending composition and sound design across diverse solo, ensemble, and multimodal contexts, including noise, ambient, EDM, and other musical genres, and data sonification. 

_Shiki_ requires a host environment (Max/MSP) and can be MIDI-mapped to interfaces (see below). A version of shiki for _Renga for White Noise_, which involves the integration of evolutionary algorithms as AI collaborators, will be released soon. Although originally developed for this renga project (premiered at CNMAT: https://www.austinotinghar.com/RengaforWhiteNoise.html), this present code for shiki 1.0 is for "musicians generally", for use in other solo, ensemble and multimedia contexts. As a polysemic Japanese word, _shiki_ acknowledges the instrument’s origins in our renga project alongside its customizability for and artistic applications across diverse contexts. 

**MIDI-Mapping to the Dials and Buttons of an Interface**

This patch is currently MIDI-mapped to the Ableton Push (image provided in patch), and basic controls are provided in presentation mode for users to play it without a Push. As a virtual instrument, _shiki_ can be MIDI-mapped to a variety of musical interfaces with dials and buttons (e.g. Ableton Push and Native Instruments Maschine). Rhythm: volume, acceleration, deceleration, phasing, and note lengthening. Timbre: four filter types (low pass, high pass, bandpass, and band-stop), filter sweeping and widening, reverb length and size, LFO, and attack. 

Users are encouraged to customize parameter ranges and add additional  controls as needed—individual rhythm and timbre controls organized as subpatches in Max, with the main patch organized for MIDI-mapping. Users may explore as many or as few components (e.g. just one white noise oscillator, just one timbre or rhythm parameter) for their work. Further details on the current MIDI-mapping of the 11 Push dials and 13 buttons on this code provided will be available in our paper in NIME 2025, due out shortly after the conference proceedings in June 2025.

The _Renga for White Noise_ panel is customized to the four filter types on the two white noise oscillators. This panel will be updated with the timer and evolutionary algorithms for the AI collaborators in the next release specifically for _Renga for White Noise_.
