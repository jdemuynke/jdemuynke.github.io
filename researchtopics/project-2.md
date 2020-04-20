---
layout: project
type: researchtopics
image: images/owl.jpg
title: Binaural Hearing
<!-- permalink: projects/BINCI -->
# All dates must be YYYY-MM-DD format!
labels:
  - Binaural cues
  - Near field
  - HRTFs
  - BRIRs
  - HRTFs individualisation
summary: Binaural hearing mainly rests on the pair of acoustic sensors located on either side of our head, among other physical attributes.
---


<div class="ui medium images">
<img class="ui image" src="../images/listening_test.jpeg">
<img class="ui image" src="../images/binaural_cues.png">
</div>


Binaural hearing allows every human being to localise sound sources in its surroundings, from left to right, front and back, up and down. This ability is due to some binaural cues that dictate an incoming direction when processed by our brain. The two main binaural cues are the Interaural Time Difference (ITD) and the Interaural Level Difference (ILD).<br />

The ITD refers to the timing difference for a sound to reach our two ears and is mainly effective at low frequencies, whereas the ILD refers to the level difference of a sound when it reaches our two ears and is mainly effective at high frequencies. For example, a sound that reaches the right ear before the left ear was probably emitted by a source located on the right of the subject. If the frequency is high enough, the signal reaching the right ear exhibits a higher level than the signal reaching the left ear due to the masking effect of the head and the distance-dependent attenuation.

The reverberation pattern of a room is retrieved from its impulse response, which can be measured by different well-known techniques. Most of these involve using a loudspeaker for playing back a specific stimulus signal and a microphone for capturing the series of subsequent echoes. The microphone can be of various type among single capsule microphones with a variety of directivity patterns, ambisonic microphones of different orders, or Head And Torso Simulators (HATS). Depending on the type of used microphone, the impulse response is called either Room Impulse Response (RIR), Ambsionic Room Impulse Response (ARIR), Binaural Room Impulse Response (BRIR) or Head Related Room Impulse Response (HRIR) in the case of anechoic conditions.<br />



Carrying out room impulse response measurements has several fields of application: it may be used for analysing the acoustic characteristics of a room like the reverberation time and the room modes, or it can be used for simulating the acoustics of a desired room in an auralisation process.<br />

The impulse response measurement campaigns performed in the demonstration sites of BINCI project aimed to auralise the content of the audio guides for an enhanced visitor's experience. The room impulse responses were measured with a 1rst order ambisonic microphone from several listening positions and with several source positions, leading to an authentic cartography of the room reverberation in the spherical harmonics domain. This allowed for a dynamic rendering of the binaural audio content supporting head rotations and with a variety of possible sound source positions within the rooms.<br />

In Die Alte Pinakotheke, the narrator's voice was processed with the acoustic signature of the rooms to be visited during the tour, thereby creating the illusion of having a virtual guide standing next to oneself. In StAndrews Castle, the story of the most dramatic events in the castle’s history was illustrated by using soundscapes made of typical sounds (main characters voice, screams from the bottle dungeon, kitchen's daily sounds, battle sounds etc.) augmented with the acoustic signature of the corresponding rooms, by then offering a vivid and immersive experience.
Some demos of the binaural audio guides (head-locked) created for BINCI are available [here](https://www.youtube.com/watch?time_continue=24&v=AfFsXqODqOQ&feature=emb_logo) and [there](https://www.youtube.com/watch?time_continue=165&v=ijhN34Jwkw0&feature=emb_logo).<br />

The measurement datasets of BINCI were [published in Zenodo](https://zenodo.org/record/1299894#.XSHGfNMzbMU) and subject to a [proposal of a new Convention of SOFA](http://www.aes.org/e-lib/browse.cfm?elib=19560) (Spatially Oriented Format for Acoustics) meant for ambisonic room impulse responses, presented at the 144th AES Convention in Milan in 2018. After the presentation we were suggested by Franz Zotter and Angelo Farina to include ambisonic sources in the proposed SOFA convention, which we have worked on in order to present soon an updated SOFA convention named MultiPerspectiveAmbisonicRoomImpulseResponse (MPARIR), fully supporting ambisonic sources and receivers from/to multiple positions, thereby allowing for an accurate cartography of the reverberation of a room in Ambisonics. MPARIR convention will be discussed in a Standard Committee during the 2020 146th AES Convention.
