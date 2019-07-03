---
layout: project
type: project
image: images/logo_binci_v4.jpg
title: Binaural Tools for the Creative Industries, H2020 Project
permalink: projects/micromouse
# All dates must be YYYY-MM-DD format!
date: 2017-01-01
labels:
  - Binaural audio
  - Ambisonics Room Inpulse Response
summary: For BINCI project we developed a suite of plugins for mixing in binaural the audio guides content of some museums and cultural sites, plus an ambisonics player supporting head tracking for an enhanced visitor experience.
projecturl: https://binci.eu/
---

<div class="ui small rounded images">
  <img class="ui image" src="../images/StAndrews_porch_reduced.jpg">
</div>

```js
byte ADCRead(byte ch)
{
    word value;
    ADC1SC1 = ch;
    while (ADC1SC1_COCO != 1)
    {   // wait until ADC conversion is completed   
    }
    return ADC1RL;  // lower 8-bit value out of 10-bit data from the ADC
}
```


