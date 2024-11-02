(:mini 100x400 :)

(:table border=0 width=100% :)
(:cell width=80% :) 
!! NOISE
[[ https://www.tangiblewaves.com/store/p7/NOISE.html | View Product Page]]

The NOISE module generates ... yes ... noise!

There are three types of noise in the module: analog, digital and crackle.  See '''outputs''' below for details.

!!! Inputs
* '''CV''' - control voltage input for RATE (see below)

!!! Outputs [[#outputs]]
* '''A OUT''' (2x) - analog noise: a fluctuating voltage between about 1v and 4V
* '''D OUT''' - digital noise: a random changing 0V / 5V
* '''CR OUT''' - crackle noise: random triggers (on newer versions)
* '''MULT''', labelled '''Thru''' on the picture here - passive signal splitter/multiplier 
* '''BUS CV''' - MIDI pitch signal from the bus 
* '''BUS CTRL''' - MIDI control signal from the bus (CH1 - CC20)

!!! Controls
* '''RATE Knob''' - controls the color of the noise, which goes from almost white noise on A output and knob fully clockwise to a rather harsh and digital sound on D output and RATE counter-clockwise.​  It also controls the density of the crackle on CR output.

!!! Patch Suggestions

A popular patch is to connect A OUT to a VCA (IN) controled by an envelope to get percusive sounds.

Use D OUT for harsher bit-crushed sounds.

Connecting CR OUT to S&H (TRIG1) and A OUT to [[https://wiki.aemodular.com/pmwiki.php/AeManual/SAMPLEHOLD| S&H ]] outputs random voltages at  intervals set by the trig input on that module.

When used as audio, CR OUT gives a nice vinyl-like crackle sound.

If used through an attenuator (e.g. [[2ATTCV]]) it can be nice as a random modulation source on things like filter cut off. 

(:cell:) Mini:noise.png
(:tableend:)

[[AeManual/Modules | <-- Back to the Module Index]]

This manual is a community work in progress. If you would like to help out with completing this manual please send a PM to @admin at the [[http://forum.aemodular.com | AE Modular Forum]].  The status of each page can be seen on the Trello board at [[https://trello.com/b/HNd0dBt7/ae-manuals]]