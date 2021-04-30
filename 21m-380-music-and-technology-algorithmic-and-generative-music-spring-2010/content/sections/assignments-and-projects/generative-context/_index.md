---
course_id: 21m-380-music-and-technology-algorithmic-and-generative-music-spring-2010
layout: course_section
menu:
  leftnav:
    identifier: e0285a658bce669a777ea93b6267e32d
    name: 'Project Sample: Generative Context-free Grammars'
    parent: 6e81c0bd4e525a461f0535f350963ca7
    weight: 80
parent_title: Assignments and Projects
title: 'Project Sample: Generative Context-free Grammars'
type: course
uid: e0285a658bce669a777ea93b6267e32d

---

_Courtesty of MIT student, used with permission._

For my final project, I made a system for defining context-free grammars (CFGs) and expanding a sequence of terminals into non-terminals using randomized productions. This contrasts with the more common activity of parsing a string of already-generated terminals into higher-level nonterminals,which is essentially the reverse process. A sequence of terminals can then be processed to produce some sort of output, such as a sound or a song. Using this system, complex definitions can be easily created as a series of productions, each of which maps a symbol to one or more probabilistically-weighted expansions, in order to create complex randomized, but structured, behavior.

Complete report ([PDF]({{< baseurl >}}/sections/assignments-and-projects/generative-context/mit21m_380s10_assn_ss_c))

Code files and sample audio outputs ([ZIP](/coursemedia/21m-380-music-and-technology-algorithmic-and-generative-music-spring-2010/7de6a29d925396d01871c50cb184b878_assn_ss_c_files.zip)) (This ZIP file contains 3 .py, 4 .yaml, and 2 .wav files). The audio files are a 1-second sound and a 4-second song.