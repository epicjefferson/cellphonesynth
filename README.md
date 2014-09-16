cellphonesynth
==============

Audio synthesis part of a cellphone synth project for Hybrid Instrument Building, CMU.

PD receives OSC from openFrameworks indicating each phones' 
id, x position, y position, red, green, blue, and hue. 

Each of these parameters is mapped to a parameter in the synthesis system and then 
passed on to a Processing sketch for visualization.
