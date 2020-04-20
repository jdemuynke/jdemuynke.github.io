---
layout: project
type: researchtopics
image: images/Miro_300px.jpg
title: Room Acoustics
<!-- permalink: projects/BINCI -->
# All dates must be YYYY-MM-DD format!
date: 2017-01-01
labels:
  - Reverberation
  - Acoustics measurements
  - HRTFs
  - Ambisonics Room Impulse Response
summary: The interaction between a sound source and the room creates a series of echoes depending on its geometry and materials, referred to as room reverberation.
---


<img class="ui image" src="../images/standrews_500px.jpg">


The reverberation of a room is composed of a series of reflexions of the original impulsive sound onto the room boundaries, each having its own time of arrival, direction of arrival, level and spectral content. Partially depending on the source position and listening position, the reverberation pattern of a room is unique and thereby can be seen as its *acoustic signature*.<br />

<div class="ui medium images">
<img class="ui image" src="../images/standrews2_500px.jpg">
<img class="ui image" src="../images/standrews3_500px.jpg">
</div>

The reverberation pattern of a room is retrieved from its impulse response, which can be measured by different well-known techniques. Most of them involve using a loudspeaker for playing back a specific stimulus signal and a microphone for capturing the series of subsequent echoes. The microphone can be of various type among single capsule microphones with a variety of directivity patterns, Ambisonics microphones of different orders, and Head And Torso Simulators (HATS). Depending on the type of used microphone, the impulse response is called either Room Impulse Response (RIR), Ambsionics Room Impulse Response (ARIR), Binaural Room Impulse Response (BRIR) or Head Related Room Impulse Response (HRIR) in the case of anechoic conditions.<br />

<div class="ui medium images">
<img class="ui image" src="../images/pinakotheke_500px.png">
<img class="ui image" src="../images/eurecat_500px.jpg">
<img class="ui image" src="../images/deluxe2_500px.jpg">
</div>

Measuring the impulse response measurement of a room has several fields of application: it may be used for analysing the acoustic characteristics of a room like the reverberation time and the room modes, or it can be used for simulating the acoustics of a desired room in an auralisation process.<br />

The impulse response measurement campaigns performed in the demonstration sites of BINCI project aimed to auralise the content of the audio guides intended to enhance the visitor experience. The room impulse responses were measured with a 1rst order Ambisonics microphone from several listening positions and with several source positions, leading to an authentic cartography of the room reverberation in the spherical harmonics domain, by then allowing a dynamic rendering of the binaural audio content supporting head rotations and with a variety of possible sound source positions within the rooms.<br />
In Die Alte Pinakotheke, the narrator's voice was processed with the acoustic signature of the rooms to be visited during the tour, thereby achieving of high level of realism of the audio scene, what created the illusion of having a virtual guide standing next to oneself. In StAndrews Castle, the story of the most dramatic events in the castle’s history was illustrated by using soundscapes made of typical sounds (main characters voice, kitchen's daily sounds, battle sounds etc.) augmented with the acoustic signature of the corresponding rooms offering a vivid and immersive experience.
Some demos of the binaural audio guides created for BINCI are available [here](https://www.youtube.com/watch?time_continue=24&v=AfFsXqODqOQ&feature=emb_logo) and [there](https://www.youtube.com/watch?time_continue=165&v=ijhN34Jwkw0&feature=emb_logo).



The main outcome of BINCI was the audio content in binaural of the audio guides of 3 cultural sites throughout Europe:
- Die Alte Pinakotheke, Munich, Germany
- La Fundació Miró, Barcelona, Spain
- StAndrews Castle, StAndrews, Scotland

With this objective in mind, a suite of plugins allowing to create head-tracked binaural audio content has been developed in the project, validated by a carefully chosen users group, and provided to audio producers who designed the content of the audio guides. For the storytelling to reach a high level of realism and immersiveness, we gave the producers the possibility to mimic the exact acoustics of the rooms included in the visit of the targeted sites by using their unique reverberation patterns, captured beforehand in Ambisonics. On site, the visitors would be provided with a mobile device embedding an Ambisonic player and a pair of headphones equipped with a headtracker, thereby offering a dynamic and immersive binaural experience. Moreover, a software tool has been developed that allows the visitors to select the HRTFs among an HRTFs database that match best their own physiology for an even increased binaural experience. Opinion polls conducted at the end of the visit clearly showed that the immersive storytelling was well received and even left its mark to most of the visitors.<br />
More information about BINCI can be found [here](https://binci.eu/).<br /><br />
Measurement campaigns of Ambisonics Room Impulse Responses were established in all sites mentioned above: some exhibition galleries and halls of Die Alte Pinakotheke and La Fundació Miró, as well as the different spots of StAndrews Castle: entrance porch, guard chambers, kitchen cellars, mine and countermine (underground tunnels), bottle dungeon.<br /><br />
These measurement datasets were [published in Zenodo](https://zenodo.org/record/1299894#.XSHGfNMzbMU) and subject to a [proposal of a new Convention of SOFA](http://www.aes.org/e-lib/browse.cfm?elib=19560) (Spatially Oriented Format for Acoustics) presented at the 144th AES Convention in Milan, Italy in 2018.
