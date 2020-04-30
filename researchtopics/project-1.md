---
layout: researchtopic
type: researchtopics
image: images/Miro_300px.jpg
title: Room Acoustics
<!-- permalink: projects/BINCI -->
# All dates must be YYYY-MM-DD format!
labels:
  - Reverberation
  - Room Impulse Response
  - HRTFs
  - MPARIR
  - 6DoF
summary: The interaction between a sound source and the room creates a series of echoes whose characteristics depend on its geometry and materials, and is referred to as room reverberation.
---


<img class="ui image" src="../images/standrews_500px.jpg">


The reverberation of a room is composed of a series of reflections of the original impulsive sound onto the room boundaries, each having its own time of arrival, direction of arrival, level and spectral content. Partially depending on the source position and listening position, the reverberation pattern of a room is unique and thereby can be seen as its *acoustic signature*.

<br />
<div class="ui grid">
  <div class="ui medium centered images">
    <img class="ui image" src="/images/standrews2_500px.jpg">
    <img class="ui image" src="/images/standrews3_500px.jpg">
  </div>
</div>
<br />

The reverberation pattern of a room is retrieved from its impulse response, which can be measured by different well-known techniques. Most of these involve using a loudspeaker for playing back a specific stimulus signal and a microphone for capturing the series of subsequent echoes. The microphone can be of various type among single capsule microphones with a variety of directivity patterns, ambisonic microphones of different orders, or Head And Torso Simulators (HATS). Depending on the type of used microphone, the impulse response is called either Room Impulse Response (RIR), Ambsionic Room Impulse Response (ARIR), Binaural Room Impulse Response (BRIR) or Head Related Room Impulse Response (HRIR) in the case of anechoic conditions.

<br />
<div class="ui grid">
  <div class="ui medium centered images">
    <img class="ui image" src="/images/pinakotheke_500px.png">
    <img class="ui image" src="/images/eurecat_500px.jpg">
  </div>
</div>
<br />

<div class="ui grid">
  <div class="ui medium centered images">
    <img class="ui image" src="/images/deluxe2_500px.jpg">
    <img class="ui image" src="/images/standrews4_500px.jpg">
  </div>
</div>
<br />

Carrying out room impulse response measurements has several fields of application: it may be used for analysing the acoustic characteristics of a room like the reverberation time and the room modes, or it can be used for simulating the acoustics of a desired room in an auralisation process.<br />

The impulse response measurement campaigns performed in the demonstration sites of BINCI project aimed to auralise the content of the audio guides for an enhanced visitor's experience. The room impulse responses were measured with a 1rst order ambisonic microphone from several listening positions and with several source positions, leading to an authentic map of the room reverberation in the spherical harmonics domain. This allowed for a dynamic rendering of the binaural audio content supporting head rotations and with a variety of possible sound source positions within the rooms.<br />

The measurement datasets of BINCI were [published in Zenodo](https://zenodo.org/record/1417727#.XqsOThMzZ24).<br />

In Die Alte Pinakothek, the narrator's voice was processed with the acoustic signature of the rooms to be visited during the tour, thereby creating the illusion of having a virtual guide standing next to oneself. In StAndrews Castle, the story of the most dramatic events in the castle’s history was illustrated by using soundscapes made of typical sounds (main characters voice, screams from the bottle dungeon, kitchen's daily sounds, battle sounds etc.) augmented with the acoustic signature of the corresponding rooms, by then offering a vivid and immersive visitor experience. The benefit of using binaural audio content for audio guides and the underlying methods for capturing the room reverberation and using it for mixing the audio content will be published under the name *Binaural sound for audio guides: an enhanced visitor’s experience in museums and archeological sites* in the session *Archaeology of Soundscapes and Soundscapes for Archaeology* in the [2020 meeting of the European Association of Archaeologists](https://www.e-a-a.org/EAA2020/Programme.aspx?WebsiteKey=4245c0d1-9c0e-4a58-bfa2-906885ad5f28&hkey=e2646dc0-ed23-404c-ad20-24129c9e69c3&Program=3#Program).<br />

Some demos of the binaural audio guides (head-locked) created for BINCI are available [here](https://www.youtube.com/watch?time_continue=24&v=AfFsXqODqOQ&feature=emb_logo) and [there](https://www.youtube.com/watch?time_continue=165&v=ijhN34Jwkw0&feature=emb_logo).<br />

 The IRS measurements done in BINCI paved the way for a [proposal of a new Convention of SOFA](http://www.aes.org/e-lib/browse.cfm?elib=19560) (Spatially Oriented Format for Acoustics) meant for ambisonic room impulse responses, presented at the 144th AES Convention in Milan in 2018. After the presentation we were suggested by Franz Zotter and Angelo Farina to include ambisonic sources in the proposed SOFA convention, which I have worked on in order to present soon an updated SOFA convention named *Multi Perspective Ambisonic Room Impulse Response* (MPARIR), fully supporting ambisonic sources and receivers from/to multiple positions. It makes MPARIR SOFA convention well suited for storing a multidimensional map of the reverberation of a room in Ambisonics, which proves to be an appropriate tool in the field of preservation of acoustic heritage.<br />

 Moreover, for the good of virtual acoustics, the description of the source in the spherical harmonic domain makes possible to simulate a sound source exhibiting any desired directivity pattern and orientation. In addition, the support of multiple listening positions along a discrete sampling grid makes MPARIR convention a good starting point for further interpolation of the IRs in the ambisonic domain. This opens the way for a fluid navigation of the listener through the whole recording area which, combined with the possibility of rotating the head already offered by the spherical harmonic description of each IR, is often referred to as *6 Degrees of Freedom* navigation (6DoF).<br />

MPARIR SOFA convention will be discussed in a Standard Committee during the 2020 146th AES Convention.
