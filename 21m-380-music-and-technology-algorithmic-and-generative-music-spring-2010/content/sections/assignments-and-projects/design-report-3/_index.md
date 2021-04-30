---
course_id: 21m-380-music-and-technology-algorithmic-and-generative-music-spring-2010
layout: course_section
menu:
  leftnav:
    identifier: 6989e57d2a83ca148d259e22f19e5141
    name: Design Report 3 sample
    parent: 6e81c0bd4e525a461f0535f350963ca7
    weight: 70
parent_title: Assignments and Projects
title: Design Report 3 sample
type: course
uid: 6989e57d2a83ca148d259e22f19e5141

---

Cat sounds source, PD generated
-------------------------------

_Courtesy of MIT student, used with permission._

This assignment was generated completely in PD. I based the patch on one I used to play sounds at an event in early April. That piece was a series of cat purrs and I used the same source material for this piece (purrs, meows, and field sound). Most of the material sampled I found online in free sound databases (notably freesound.org) but I also spent a significant amount of time capturing sounds from my own cat, Eegloo. None of those sounds are used except for the "bird" sound that contains some birds outside my window that start talking at about 4:00 a.m.

The piece mainly uses array-controlled multiple granular synthesizers to cut up material. Both the phasor and pitch shift aspects are controlled by arrays. Each one moves at a different speed to create some interesting aspects when the values are at a maximum together, for example. A base of purrs is used to give some bottom to the sound where the granular synthesis is the top. The purrs have a low-pass filter on them to isolate them. The piece sounds the best on headphones or on a floor populated with transducers. Two different purrs begin (one in each channel) and then a faster, more frantic purr provides a setting for the other sounds. The granulated sounds are allowed to mingle for the main section of the piece before being removed and only the bird sound and a purr is left. The bird sound is then slowed to almost its recorded speed and pitch before exiting and allowing the purrs to finish the piece. The PD file does contain some objects to allow me to "punch" in meow sounds via MIDI input but I decided not to use them.

I am pleased with the sounds in the piece, though they do move slowly. More sculpting of the granular synthesis parameters could always strengthen their use, including developing more precise graphs in athenaCL to use in PD. I also think using a variable metro rate would be interesting too (using the reading of one graph to control the reading speed of another graph). Maybe another granular synthesizer would add more texture and could be used in the middle of the piece to have something super dense that is just a knot of sound and then it untangles back to discernible noises.

Design Report 3 sample: Cat sounds source, PD generated

Code file ([PD](/coursemedia/21m-380-music-and-technology-algorithmic-and-generative-music-spring-2010/2d1cc967b575490007c4c08a85e8e973_assn3_a.pd))