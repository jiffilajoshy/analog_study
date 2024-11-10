<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

This design contains the following modules: 

- Experimental VCO with divide by 10 out
- Mixer
- 4bit Current Controlled DAC

## How to test

- VCO control line can be injected voltage between 1.2v to 1.8v to generate frequencies (~690MHz to ~1600MHz in simulation). The output is divided by 10 to be taken out through Analog Out Pin.
- Mixer has RF1 in, RF2in and IF Mix Out
- DAC has 4 bit input and output has to be pulled up.

## External hardware

Signal Generator, Spectrum Analyzer 
