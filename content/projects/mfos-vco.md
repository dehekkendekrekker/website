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

The parts have arrived in the mean time, and once I have found a way to store it all, I will start breadboarding.

### Update 2024-01-31
The breadboarding is pretty much done. The beasty works on the scope. I have not been able to actually get some audio out of it yet,
because I have not built the module that will adapt the signal to something that can be used by an amp or headphones.
Also, I do not have an amp yet, nor monitor speaker yet, nor any idea of what to get :)

Calibration turns out to be a bit of a SoB. It is hard to get a good wave-form that will persist. When I tap one of the pots,
ever so slightly, the shape distorts. This was giving me a head-ache, and I'm blaming the breadboard. 
I have made a PCB design. (available [here](https://github.com/dehekkendekrekker/synth/)). It's just for the VCO at this  moment. 
When it is ordered, I'll build it and I hope the problem magically goes away.

### Update 2024-03-26
The design of the PCB is complete and PCB's have been manufactured

### Update 2024-04-08
PCB has been assembled and tested. 


## Download design files
The transposed MFOS VCO design as well as other MFOS designs are available on [github](https://github.com/dehekkendekrekker/synth/)

Keep in mind that the work is Ray Wilson's IP, on the bottom of the [MFOS site](http://musicfromouterspace.com/index.php) he specifies:

```
Please feel free to use the information presented on the MFOS website to the fullest extent for non-commercial uses.
You can make your own PCBs from the layouts and drawings we provide or design your own if you prefer.
```

So this also goes for the KiCAD designs that I made. **Non-commercial use only.**


## Pics
{{<load-photoswipe>}}
{{<gallery>}}
{{<figure link="https://res.cloudinary.com/direflzw1/image/upload/w_0.5/v1694083845/img/synths/bypl749eawngmhqax5la.jpg">}}
{{<figure link="https://res.cloudinary.com/direflzw1/image/upload/w_0.5/v1706683289/img/synths/IMG_20240123_162430_116_moy5mw.jpg">}}
{{<figure link="https://res.cloudinary.com/direflzw1/image/upload/w_0.5/v1706683289/img/synths/IMG_20240106_165756_472_vqimwr.jpg">}}
{{<figure link="https://res.cloudinary.com/direflzw1/image/upload/w_0.5/v1706683288/img/synths/IMG_20231129_175325_350_h5tx92.jpg">}}
{{<figure link="https://res.cloudinary.com/direflzw1/image/upload/w_0.5/v1706683288/img/synths/IMG_20231128_184712_433_yn14px.jpg">}}
{{<figure link="https://res.cloudinary.com/direflzw1/image/upload/w_0.5/v1706683287/img/synths/IMG_20231128_175853_996_ojoyzj.jpg">}}
{{<figure link="https://res.cloudinary.com/direflzw1/image/upload/w_0.5/v1706683287/img/synths/IMG_20231128_184704_481_ivhtxk.jpg">}}
{{<figure link="https://res.cloudinary.com/direflzw1/image/upload/w_0.5/v1706683286/img/synths/IMG_20231128_175823_622_rbbc3d.jpg">}}
{{<figure link="https://res.cloudinary.com/direflzw1/image/upload/w_0.5/v1706683286/img/synths/IMG_20231128_151529_982_ijkyt9.jpg">}}
{{<figure link="https://res.cloudinary.com/direflzw1/image/upload/w_0.5/v1706683285/img/synths/IMG_20231128_151521_145_fua5gw.jpg">}}
{{<figure link="https://res.cloudinary.com/direflzw1/image/upload/w_0.5/v1706683284/img/synths/IMG_20231128_114907_157_rjigvx.jpg">}}
{{<figure link="https://res.cloudinary.com/direflzw1/image/upload/w_0.5/v1706683284/img/synths/IMG_20231127_125952_840_vpwrvw.jpg">}}
{{<figure link="https://res.cloudinary.com/direflzw1/image/upload/w_0.5/v1706683283/img/synths/IMG_20231125_165128_780_w9glcq.jpg">}}
{{<figure link="https://res.cloudinary.com/direflzw1/image/upload/w_0.5/v1706683283/img/synths/IMG_20231127_125946_004_btgu9c.jpg">}}
{{<figure link="https://res.cloudinary.com/direflzw1/image/upload/w_0.5/v1706683283/img/synths/IMG_20231125_165120_063_f4ntdb.jpg">}}
{{<figure link="https://res.cloudinary.com/direflzw1/image/upload/w_0.5/v1706683283/img/synths/IMG_20231128_143158_430_nrbzra.jpg">}}
{{<figure link="https://res.cloudinary.com/direflzw1/image/upload/w_0.5/v1711486133/img/synths/IMG_20240326_154445_829_rxr7qo.jpg">}}
{{<figure link="https://res.cloudinary.com/direflzw1/image/upload/w_0.5/v1711486169/img/synths/IMG_20240326_154459_499_nqzht4.jpg">}}
{{<figure link="https://res.cloudinary.com/direflzw1/image/upload/w_0.5/v1711486079/img/synths/IMG_20240326_154508_346_af893a.jpg">}}
{{<figure link="https://res.cloudinary.com/direflzw1/image/upload/w_0.5/v1711486133/img/synths/IMG_20240326_154445_829_rxr7qo.jpg">}}
{{<figure link="https://res.cloudinary.com/direflzw1/image/upload/v1712579952/img/synths/IMG_20240326_175937_898_mwuhvj.jpg">}}
{{<figure link="https://res.cloudinary.com/direflzw1/image/upload/v1712579952/img/synths/IMG_20240326_171701_778_r1c1ji.jpg">}}
{{<figure link="https://res.cloudinary.com/direflzw1/image/upload/v1712579952/img/synths/IMG_20240331_153507_044_pkgms7.jpg">}}
{{<figure link="https://res.cloudinary.com/direflzw1/image/upload/v1712579952/img/synths/IMG_20240331_181119_450_st4zhf.jpg">}}
{{<figure link="https://res.cloudinary.com/direflzw1/image/upload/v1712579953/img/synths/IMG_20240402_171243_033_jv0dlz.jpg">}}
{{<figure link="https://res.cloudinary.com/direflzw1/image/upload/v1712579954/img/synths/IMG_20240403_152335_232_uhoi9c.jpg">}}
{{<figure link="https://res.cloudinary.com/direflzw1/image/upload/v1712579955/img/synths/IMG_20240403_152256_668_zezday.jpg">}}
{{<figure link="https://res.cloudinary.com/direflzw1/image/upload/v1712579954/img/synths/IMG_20240403_152154_149_m0jimf.jpg">}}
{{<figure link="https://res.cloudinary.com/direflzw1/image/upload/v1712579954/img/synths/IMG_20240403_152053_777_uaqqve.jpg">}}
{{<figure link="https://res.cloudinary.com/direflzw1/image/upload/v1712579954/img/synths/IMG_20240403_152121_065_aagyao.jpg">}}

{{</gallery>}}





