# Sound-structure (Final Coursework)


- INTRODUCTION

This report will detailed explain both, theoretical and historical background about live coding, music programming and how to use Sonic Pi in order to be able to create my own live-coding musical piece. Furthermore, the weaknesses and strenghts of the project will be considered in order to obtain criticism about the experience.

- THEORETICAL BACKGROUND

The computer has for some time been viewed as an amazingly appealing tool for making and controlling sound. Its exactness, opportunities for new tones, and potential for fantastical robotization make it a captivating stage for exploring different avenues regarding and making music. A programming language is an assortment of syntactic and semantic guidelines for indicating these directions, and in the long run for giving the interpretation from human-composed projects to the comparing guidelines PCs complete. The programming language goes about as an intermediary between human goal and the relating directions that sound good to a computer.

Live coding is a programming practice that works through the constant execution of code and in this manner incomprehensibly changes the view of traditional computer programming regarding merging structure, coding and investigating stages into one single procedure. This means that immediately putting code into action and turning out results enables a direct verification of whether a program works at all, and if the results make sense as expected or need to be modified. Melodic live coding may in this manner motivate individuals through catching the expertise of figuring out how to code their own spontaneous creations or structures.

- HISTORICAL BACKGROUND


BEFORE COMPUTERS - The idea of programming computational automata to make music can be traced back to as early as 1843. Ada Lovelace, while working with Charles Babbage, expounded on the utilizations of the hypothetical Expository Motor, the replacement to Babbage's well known Contrast Motor. The first Distinction Engine was mainly a "calculating machine" while the Analytic Scientific (which was never designed) was to contain systems for choice and circling, both essential to genuine programmability.

As electronic music evolved, analog synthesizers gained popularity (around  the  1960s). They supported interconnecting and interchangeable sound processing modules. There is a  certain level of programmability involved, and this block-based paradigm  influenced later design of digital synthesis systems. One significant pattern in this setting is that as computers expanded in computational power and capacity, programming dialects would in general become progressively high-level, abstracting more details of the hidden framework. This, as we will see, enormously affected the development of how we program music.

THE COMPUTER ERA - Our first era of computers based on music programming frameworks resembled the period of "mainframes" (the principal generations of "current" computers being used from 1950 to the late 1970s) and the start of individual workstations (mid 1970s).

The mainframes computers were huge, frequently occupying rooms or even whole floors. Early models had no screens or monitors, programs must be submitted by means of punch cards, and the outcomes conveyed as printouts. Processing assets were seriously compelled. It was troublesome even to access a centralized server. However,  the mainframes were the pioneering computers andthe individuals who utilized them took advantage of their relatively pitiful assets. Projects were deliberately planned and tuned to yield the highest effectiveness.

The earliest programming environment for sound synthesis, called  MUSIC, appeared in 1957. It was not exactly a full programming language as we would consider today, however more of an “acoustic compiler”, developed by Max Mathews. In those early days, the programming languages themselves were executed as low-level gathering directions (basically human-readable machine code), which successfully coupled a language to the specific equipment it was implemented on.

THE COMPUTER ERA (PART II) - This second period of computer programming for music partially overlaps with the first one. The main distinction is that the method of collaboration moved from disconnected programming and group handling to constant sound combination frameworks, regularly constrained by outside melodic controllers. By the mid-1980s, computers have become quick enough and small enough to permit workstation work areas to outperform the more established, huge centralized servers. As computers multiplied, so did new programming tools and applications for music generation. The apparation of programs such as Max/Msp, SuperCollider belongs to this era.  


THE COMPUTER ERA (PART III) - With the growth of low-cost, high-performance computers, the ongoing and intelligent music programming ideal models are more alive than ever and growing with the proceeded with the creation and refinement of new interfaces for musical expression. Nearby the constant trend of unstable development in computing power is the desire to discover better approaches to use programming for real-time interaction. With the pervasiveness of equipment and the apparition of new elevated level programming instruments, more composers and artists are making programming to make music, but also new software to program music. This is the ascent of dynamic language and thus of utilizing the demonstration of programming itself as an instrument. 

The idea of the run-time alteration of programs to make music (interchangeably  called live coding,  on-the-fly  programming,  interactive  programming) is not a completely new one. As ahead of schedule as the start of the 80s, analysts have tried different things with runtime modifiable music frameworks. The quick computers of today empower an extra key segment: sound synthesis and real-time. This third period is promising in light of the fact that it encourages and supports new compositional and execution prospects accessible not exclusively to proficient performers, scientists, and academics, yet in addition to anybody ready to learn and investigate programming and music. Additionally, the new unique situations for writing computer programs are changing how we approach increasingly "conventional" computer music composition.

- SONIC PI

Sonic Pi is a live coding environment based on Ruby, originally designed to support both computing and music lessons in schools. This program is simple enough for computing and music lessons and powerful for professional musicians. Furthermore, it has a huge community of over two million live coders, therefore the process of learning is easier and diverse. From my personal experience, I would consider Sonic Pi as a window with a view on SuperCollider. Sonic Pi offers everything you need to play with some synthesizers or samples. There is no need to write everything to trigger a sound, therefore making this program handy and funny to use. The real value of Sonic Pi lies in its emphasis to play. Programming becomes attractive because appears as something fun to use instead of something serious. The idea of programming using Sonic Pi removes the fear to be wrong, therefore making the concept of this program a interesting approach for education, where science and art will be combined.

- MY PROJECT 

The idea of my project is based on live coding by using Sonic Pi. Additionally, I decided to record my screen in order to have a more rich and dynamic final result, therefore obtaining a visual and sonorous outcome. The project itself might be seen basic as I did not have any knowledge prior to start the module. However, it could be noticed that there is a huge improvement in terms of memorizing, improvising, or self-confidence.  The idea of the project is based on improvising using tools such as live_loops, samples, or changing parameters during the performance. The code itself must be seen as rudimentary, however, the action of changing the parameters made me feel as I was jamming during its course. Attached is the code that I have been using during my performance, which obviously was changing constantly in order to enjoy and learn through programming.


use_bpm 100

live_loop :drums do

sample :drum_heavy_kick

sleep 1

sample :drum_snare_hard

sleep 1

end

live_loop :hithat do

sample :drum_cymbal_closed

sleep 0.5

sample :drum_cymbal_pedal

sleep 1

end

live_loop :keys do

use_synth :dark_ambience

play (scale :a2, :minor_pentatonic, num_octaves: 4).tick, release:20

sleep 0.5

end

live_loop :bass do

use_sythn :hoover

play (chord :G2, :maj11).choose, release: 0.5

sleep 2

end

live_loop :gui_e_slide do

use_synth :blade

play (chord :D2, :minor7).choose, release: 0.1

sleep 2

end


- CONCLUSION

On one hand, this project gave me the chance to discover a new world, where I can feel as a musician behind my computer. Furthermore, I strongly believe that the knowledge acquired during the semester will be really helpful for the future. Now, I believe that programming could be interesting as it is full of possibilities for many goals. On the other hand, I certainly believe if more time would have inverted a more complex project would have done, however, I have not doubted that this is just the start of a new hobby, which hopefully, it will be improved in the future. 


