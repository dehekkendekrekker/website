+++
title = "MFOS Voltage controlled oscillator"
summary = "Modular synth series: VCO"
date = "2023-07-25"
author = "DHK"
+++

## Intro

I have been interested in analog synths lately, and since I am a solder junkie in need of a fix, I figured will build one of my own.

A surprisingly short journey led me to the late Ray Wilson's [music from outer space site](http://musicfromouterspace.com/)

This site is a treasure trove of schematics, explanations, alternative part indication and more.

I picked up his book [Make: Analog synthesizers](https://www.amazon.com/Make-Analog-Synthesizers-Ray-Wilson/dp/1449345220/), which is a good introduction for the budding electronics enthusiast as well as more experienced power users who are just getting into analog. 

Having no idea what VCO mean, or LFO and VCA for that matter a couple of weeks worth of evenings were spent getting my bearings, so how does of all of this work?

VCO means voltage controlled oscillator and is the part in a synth that makes a sound. So it takes an input voltage, and the oscillator goes bzzz, making a tone. By manipulating the voltage you can change the pitch of the tone! 

So Ray's oscillator is a 1V/Oct VCO, which means that for every volt change, the pitch changes one octave.

It has some features such as, sawtooth, square, sine and ramp wave shape generation as well as temperature compensation.

## Plan
The designs are ready, the parts are ordered. I will make a protoboard version of the VCO first. Then I will make a PCB design,
have a bunch made, order  more parts and build some more VCO for a litte oomph. Think polyphonic, chords, etc.


## Status
As of yet, I have transposed his design into KiCAD. This gives me better control over which parts to use and the generation of the bill of materials. I have ordered the parts from mouser, which should ship them soon.



## Download design files
The transposed MFOS VCO design as well as other MFOS designs are available on [github](https://github.com/dehekkendekrekker/synth/)

Keep in mind that the work is Ray Wilson's IP, on the bottom of the [MFOS site](http://musicfromouterspace.com/index.php) he specifies:

```
Please feel free to use the information presented on the MFOS website to the fullest extent for non-commercial uses.
You can make your own PCBs from the layouts and drawings we provide or design your own if you prefer.
```

So this also goes for the KiCAD designs that I made. **Non-commercial use only.**





