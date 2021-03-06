# Audio Programming
* Monthly Music Hackathon NYC: http://monthlymusichackathon.org
* Brian Whitman: https://notes.variogr.am
* Tristan Jehan: http://web.media.mit.edu/~tristan/
* Music Machinery: https://musicmachinery.com
* Stanford CCRMA: https://ccrma.stanford.edu
* Kadenze: https://www.kadenze.com
* Jython Music: https://jythonmusic.me
* JMusic: http://explodingart.com/jmusic/
* JSyn: http://www.softsynth.com/jsyn/index.php
* RTcmix: http://rtcmix.org
* RackAFX: http://www.willpirkle.com
* The Audio Programmer youtube channel: https://www.youtube.com/channel/UCpKb02FsH4WH4X_2xhIoJ1A
* KVR Forum: https://www.kvraudio.com/forum/
* Making Audio Plug ins: http://www.martin-finke.de/blog/tags/making_audio_plugins.html
* Cockos (makers of Reaper): https://www.cockos.com
* Kimatica (maker of AUM): http://kymatica.com & http://lijon.github.io
* Hack Audio: http://www.hackaudio.com
* Oli Larkin (Reaper, WDL/iPlug): http://www.olilarkin.co.uk
* Awesome Music DSP by Oli Larkin: https://github.com/olilarkin/awesome-musicdsp
* Acoustic and Audio Group @ Edinburgh: http://www.acoustics.ed.ac.uk
* Ear Level Engineering (DSP): http://www.earlevel.com/main/
* How to do realtime recording with effect processing on iOS (Teragon Audio): http://teragonaudio.com/article/How-to-do-realtime-recording-with-effect-processing-on-iOS.html 
* Julius O Smith home page at CCRMA: https://ccrma.stanford.edu/~jos/
* Free pubs by Julius O Smith: https://ccrma.stanford.edu/~jos/pubs.html

## Audio Basics
* Learn about waveforms: https://pudding.cool/2018/02/waveforms/
* https://www.khanacademy.org/science/physics/mechanical-waves-and-sound

## Advice for getting into audio programming
* https://www.reddit.com/r/learnprogramming/comments/1n05ff/learning_audio_programming/
* https://ask.metafilter.com/308083/Best-books-resources-for-learning-audio-programmingalso
* http://designingsound.org/2016/07/self-teaching-your-way-into-the-audio-world/
* https://www.youtube.com/watch?v=Kpk67-nfpR0 - The Audio Programmer
* https://www.kvraudio.com/forum/viewtopic.php?f=33&t=329696 - KVR

## More audio programming advise
* http://atastypixel.com/blog/four-common-mistakes-in-audio-development/ - Michael Tyson, maker of Loopy and Audiobus
* http://www.rossbencina.com/code/real-time-audio-programming-101-time-waits-for-nothing - Ross Bencina

## Audio related videos (tutorials, talks, etc...)
* DAFx17 Tutorial 4: Julian Parker - From Algorithm to Instrument: https://www.youtube.com/watch?v=NuKRZ2-bsKQ
* Dr Julian Parker on Virtual Analog Modelling: https://www.facebook.com/nordicsmc/videos/450642712037855/
* Great talk about iOS audio apps: https://www.youtube.com/watch?v=KAXss-zmCsU&t=76s

## Audio Gold Nuggets
* The CD-quality sample rate is 44.1kHz, which means there needs to be 44100 samples per second per channel sent to the audio hardware for playback. Rather than being passed to the audio hardware a single sample at a time, the samples are passed in buffers — or blocks — containing a certain number of samples. For example, at 44.1kHz and a block size of 441 our AudioAppComponent::getNextAudioBlock() function would be called 100 times per second. (From JUCE Tutorial)

* Just download the Ableton Link sample code, the Audiobus examples or the Apple AU sample code and you get something that works right out of the box. Added benefits: you learn exactly how stuff works because it's not some mysterious black box and you won't get weird license restrictions getting in the way."

## Courses
* MIT - Interactive Music Systems: https://ocw.mit.edu/courses/music-and-theater-arts/21m-385-interactive-music-systems-fall-2016/index.htm
* MIT - Music and Technology: Algorithmic and Generative Music: https://ocw.mit.edu/courses/music-and-theater-arts/21m-380-music-and-technology-algorithmic-and-generative-music-spring-2010/
* MIT - Music and Technology: Live Electronics Performance Practices: https://ocw.mit.edu/courses/music-and-theater-arts/21m-380-music-and-technology-live-electronics-performance-practices-spring-2011/
* MIT - Composing with Computers I (Electronic Music Composition): https://ocw.mit.edu/courses/music-and-theater-arts/21m-361-composing-with-computers-i-electronic-music-composition-spring-2008/
* MIT - Music and Technology: Sound Design: https://ocw.mit.edu/courses/music-and-theater-arts/21m-380-music-and-technology-sound-design-spring-2016/
* Coursera - Audio Signal Processing: https://www.coursera.org/learn/audio-signal-processing

## Books
* The Theory and Techniques of Electronic Music (Miller Puckette)
* The Audio Programming Book (Richard Boulanger/Victor Lazzarini)
* Programming Electronic Music in Pure Data (Johannes Kreidler)
* Electronic Music and Sound Design V1 & V2 (Alessandro Cipriani/Maurizio Giri)
* Musimathics: The Mathematical Foundations of Music (MIT Press) (Volume 1) (Gareth Loy)
* Musimathics: The Mathematical Foundations of Music (MIT Press) (Volume 2) (Gareth Loy)
* Designing Software Synthesizer Plug-Ins in C++: For RackAFX, VST3, and Audio Units (Will Pirkle)
* Designing Audio Effect Plug-Ins in C++: With Digital Audio Signal Processing Theory (Will Pirkle)
* Physical Audio Signal Processing: for Virtual Musical Instruments and Digital Audio Effects (Julius O. Smith III)
 * Free at: https://ccrma.stanford.edu/~jos/pasp/pasp.html
* Spectral Audio Signal Processing (Julius O. Smith III)
* Introduction to Digital Filters: with Audio Applications (Julius O. Smith III)
* Mathematics of the Discrete Fourier Transform (DFT): with Audio Applications ---- Second Edition (Julius O. Smith III)
* Audio Effects: Theory, Implementation, and Application
* DAFX: Digital Audio Effects
* Numerical Sound Synthesis: Finite Difference Schemes and Simulation in Musical Acoustics 1st Edition
by Stefan Bilbao (Author)


## Open Source CS resources
* http://zynaddsubfx.sourceforge.net
* https://github.com/ossu/computer-science - open source computer science
* https://see.stanford.edu - Standford Computer Science/engineering courses

## Languages
* MAX - https://cycling74.com
* Csound - http://csound.com
* Supercollider - http://supercollider.github.io
* Pure Data - https://puredata.info
* C
* C++
  * C++ Certificate: https://www.pce.uw.edu/certificates/c-plus-plus-programming
  * Awesome C++: https://github.com/fffaraz/awesome-cpp
* Sporth - https://github.com/PaulBatchelor/Sporth
* Faust (DSP) - http://faust.grame.fr
* Haskell - http://haskellformac.com/haskell-for-mac-learning-haskell.html
* Wiki: https://en.wikipedia.org/wiki/List_of_audio_programming_languages

## Make music with code
* Make music with Haskell: https://tidalcycles.org
* Make music with Ruby: https://sonic-pi.net

## Frameworks and libraries
* https://juce.com - C++ framework
* https://github.com/AudioKit/AudioKit - iOS framework
* https://github.com/PaulBatchelor/Soundpipe - Soundpipe
* https://github.com/micknoise/Maximilian - Maximillian
 * Info on Maximilian: https://quod.lib.umich.edu/cgi/p/pod/dod-idx/maximillian-an-easy-to-use-cross-platform-c-toolkit-for.pdf?c=icmc;idno=bbp2372.2011.054;format=pdf
* http://openframeworks.cc - Open Framework
* https://github.com/olilarkin/wdl-ol - Cockos iPlug
* https://github.com/lijon/TheAmazingAudioEngine - for mobile & documentation: http://theamazingaudioengine.com/doc/
* https://ccrma.stanford.edu/software/stk/ - Synthesis ToolKit info
* https://github.com/thestk/stk - Synthesis ToolKit github
* https://github.com/superpoweredSDK/Low-Latency-Android-iOS-Linux-Windows-tvOS-macOS-Interactive-Audio-Platform - SuperPowered SDK

## JUCE tutorials
* Make a distortion app: https://www.youtube.com/watch?v=iNCR5flSuDs
* The Audio Programmer (Best JUCE tuts): https://www.youtube.com/watch?v=OPSKfPWdr90
* JUCE at youtube: https://www.youtube.com/channel/UCaF6fKdDrSmPDmiZcl9KLnQ
* JUCE tutorials at their homepage: https://juce.com/learn/tutorials

## DSP
* http://dspguide.com
* https://www.youtube.com/watch?v=tx_cjBjZ2zM - DSP Videos with good links
* https://www.youtube.com/watch?v=RgVFseTftOQ - Audio DSP Programming Basics
* https://www.youtube.com/watch?v=hVOA8VtKLgk - Great DSP Lecture by Rich Radke of Rensselaer Polytechnic Institute (video 1 of 28)
* https://www.dsprelated.com
* Matlab clones (free dsp software): https://dspguru.com/dsp/links/matlab-clones/
* https://dspguru.com
* https://hackaday.com/2016/06/30/tutorial-on-signal-processing-in-linux-with-octave/
* Scilab - signal processing: https://help.scilab.org/docs/6.0.0/en_US/section_dbbac6be408104de3049eddefaf6b9c9.html
* https://www.quora.com/What-programming-languages-are-most-useful-for-digital-signal-processing-specifically-with-audio

## Math refreshers
* http://tutorial.math.lamar.edu (great cheat sheets)
* https://artofproblemsolving.com
* https://brilliant.org (learn math through problem solving)
* https://sites.google.com/site/butwhymath/home (But Why Math - great explanation of different math topics)
* https://betterexplained.com (Excellent explanation of math concepts)

## Physics of Sounds
* https://www.khanacademy.org/science/physics/mechanical-waves-and-sound

## C++ audio
* OneLoneCoder - Sound Synthesizer: https://www.youtube.com/watch?v=tgamhuQnOkM
* Code examples for the video above: https://github.com/OneLoneCoder/synth/tree/master
* VSTGUI: https://github.com/steinbergmedia/vstgui


# iOS music app development
## Good Advice for iOS Development
* Advice from Brambos: "If you're staying on iOS, I would avoid using 3rd party APIs and simply stick to the system audio APIs. That way you can at least fix things when Apple breaks something in an iOS update without you having to wait for others to fix the frameworks for you."
** "The biggest trick is to learn how to eat an elephant: in many tiny little bites In other words: learn how to break down the project into a collection of many small problems that need to be solved one by one. It will make the learning curve more manageable and rewarding as it will give you a long chain of gratifying victories"

* More advice from Brambos: "Making something that produces sound is probably not too hard (altough quite a bit harder than making a website with a Wordpress template).

Making a decent music app is really hard. There are a couple of things you need to master:

Programming the app (the basic framework of an app, coding the UI behavior and handling of user interaction). Ideally done in Objective-C, mixed with lots of C/C++ for the realtime audio bits. Swift is not yet a real option since most low-level frameworks are still built around (Objective-)C. Also, you need to be good at optimizing code in really clever ways if you have any hopes of doing stuff in real time with low latency.

DSP: generating and manipulating sound. Nothing about this is easy. If something seems simple, you're probably doing it wrong and soon you're in for a world of aliasing and distortion :D Lots of physics and maths involved here. Be prepared to put lots of hours into studying highly arcane aspects of physics and signal theory and brushing up on your trigonometry. Again, knowing the physics is not enough. You need to be able to build your DSP code so efficiently that it can be run in realtime without cutting corners wrt sound quality. You and Mr. Niquist are going to be very close friends.

Design: underestimated by many app developers. It can be the little things that make or break a workflow. And that's before you even get into the aesthetics, established interaction design patterns and how to deal with device fragmentation. Particularly hard on iOS because no two workflows are the same and people expect you to consider even the most obscure use cases of how your app will be used in conjunction with a chain of other apps.

The crazy intricacies of low level audio tech, i.e. CoreAudio, AudioUnits, CoreMidi, Ableton Link, etc. Many aspects of this are barely documented and need to reverse engineered by looking at C header files and labyrinthine sample code. Sometimes bugs in the OS (or third party libraries/apps) will have you pulling out your hair for days. And you have to understand low-level system stuff like threading priorities and locking to make sure your fancy GUI doesn't clash with realtime audio processing causing inexplicable glitches and clicks.

Sorry if this sounds off-putting, but there really is nothing easy about it if your ambition is to go beyond the point of an app that just plays a WAV file when you press a button on the screen B)

If you've already covered some of the above to some extent you have a pretty good starting point, however, and everything can be learned if you put your heart into it. If you're starting from scratch I would recommend beginning with something a bit simpler. :)

To counterbalance with a slightly more encouraging suggestion: I would start with a MIDI app because that would get the nasty real-time DSP out of the equation and be a more gentle introduction into the world of iOS music.

Still not trivial, but a more realistic goal for a novice project :)"

* More advice: "A basic delay, flanger or distortion effect though? Probably a lot easier. The guts of the C/C++ code for the core DSP algorithms are out there. Sort out how to wire it up. Then add stuff. If I'm not mistaken, this is how Holderness got started! For sure, the somewhat obtuse notion of 'a good flanger' will likely not come from pulling a repo on github. But it can get you started if you're interested. A little more complicated but not in the Phasemaker realm: a basic VA subtractive synth. One OSC, a LPF and an envelope where the pitch of the osc is mapped to a keyboard. There are tutorials out there for this. And these days you can cook one up with Javascript. Will not be of much practical use on iOS but the core concepts are the same and you can learn on any OS without needing to deal with compilers."

### Programming Audio Units
* https://developer.apple.com/library/content/documentation/MusicAudio/Conceptual/AudioUnitProgrammingGuide/AudioUnitDevelopmentFundamentals/AudioUnitDevelopmentFundamentals.html - Audio Unit Development Fundamentals
* http://ruismaker.com/au-midi-plugins/ - AUv3 MIDI
* https://developer.apple.com/library/content/documentation/MusicAudio/Conceptual/CoreAudioOverview/Introduction/Introduction.html - Core Audio Overview
* How to setup AUv3: https://www.kvraudio.com/forum/viewtopic.php?f=33&t=482362
* Creating AUv3 midi, part 0: http://www.rockhoppertech.com/blog/auv3-midi/
* Creating AUv3 midi, part 1: http://www.rockhoppertech.com/blog/audio-units-auv3-parameters-part-1/

### iOS Audio apps
* Core Audio Overview: https://developer.apple.com/library/content/documentation/MusicAudio/Conceptual/CoreAudioOverview/Introduction/Introduction.html#//apple_ref/doc/uid/TP40003577-CH1-SW1
* libPD: https://github.com/libpd/libpd
* Audiobus sdk: https://developer.audiob.us
* Using RemoteIO audio unit: http://atastypixel.com/blog/using-remoteio-audio-unit/
* iPhone Core Audio Brain Dump: http://subfurther.com/blog/2009/04/28/an-iphone-core-audio-brain-dump/
* Real-time Digital Effects Processing using iOS: http://digitalcommons.calpoly.edu/cgi/viewcontent.cgi?article=1185&context=cpesp
* Functional Signal Processing with Swift: https://www.objc.io/issues/24-audio/functional-signal-processing/
* How to capture audio samples in iOS with Swift?: https://stackoverflow.com/questions/30957434/how-to-capture-audio-samples-in-ios-with-swift
* Create your first AudioUnitv3: http://subfurther.com/blog/2017/04/28/brain-dump-v3-audio-units/
* How to do realtime recording with effect processing on iOS: http://teragonaudio.com/article/How-to-do-realtime-recording-with-effect-processing-on-iOS.html
* https://forum.audiob.us/discussion/17445/how-difficult-is-it-to-develop-a-musical-app
* https://www.kvraudio.com/forum/viewtopic.php?f=33&t=482362

#### AVAudioEngine
* Advise: https://stackoverflow.com/questions/30957434/how-to-capture-audio-samples-in-ios-with-swift
* Audio Manipulation Using AVAudioEngine: https://blog.metova.com/audio-manipulation-using-avaudioengine

#### iOS frameworks
* TAAE2 (deprecated): https://github.com/TheAmazingAudioEngine/TheAmazingAudioEngine2
* Novocaine: https://github.com/alexbw/novocaine
* NVDSP: https://github.com/bartolsthoorn/NVDSP

#### AudioKit
* https://github.com/AudioKit/AnalogSynthX

#### Tutorials
* Using The Amazing Audio Engine with the Synthesis Toolkit in C++: https://arielelkin.github.io/articles/mandolin

## MAX related
* Max4Live (user made instruments): http://maxforlive.com/index.php
* Max Objects: http://www.maxobjects.com

### GEN
* Gen plug in export: https://github.com/Cycling74/gen-plugin-export

## Arduino Audio
* Mozzi (Audio synthesis library for Arduino): http://sensorium.github.io/Mozzi/

## Web Audio
* Web Audio Weekly: https://www.webaudioweekly.com
* Web Audio School: http://mmckegg.github.io/web-audio-school/
* Web Audio Modules: https://www.webaudiomodules.org

## Good Blogs
* http://darwingrosse.com - Darwin is a Cycling 74 employee and musician
* http://allthingsmodular.blogspot.com - A blog by Darwin
* http://cdm.link
* http://www.synthtopia.com
* http://derelict.computer
* https://adamtcroft.com
* https://www.peterbatchelor.com/maxtuts
* http://audanika.tumblr.com
* https://christianfloisand.wordpress.com
* http://trashaudio.com
* http://www.earlevel.com/main/ - Amazing DSP blog going back a few years, still current
* http://www.jackcampbellsounds.com/programming/2017/3/17/posts-to-come - Audio Engine in C++

## Podcasts
* http://artmusictech.libsyn.com - Art + Music + Technology podcast made by Darwin

## Great Projects
#### Arduino base
* https://meeblip.com - Open source Synth
* https://github.com/MeeBlip - Meeblip repo

#### littleBits
* https://littlebits.cc/meet-darwin

## Employers - besides the usual suspects and major audio/music complanies
* https://artandlogic.com

## Resources
* https://newt.phys.unsw.edu.au/jw/notes.html - MIDI to Frequency table

## Misc
### Sound Design
* https://www.pointblankmusicschool.com/courses/online/professional-programmes/complete-sound-design/

### Ideas/Interests
1. algorithmic/generative music (in addition: processes that ‘tracks’ parameters) 
2. build interactive synthesis objects that allows OS to control sound parameters dynamically
3. Start several distinct music processes that respond to actions upon particular game objects/user interactions 

### Focus areas/Goals for music technology (taken from Calarts website)
The Music Technology program aims to built strong musical skills while promoting the mastery of a variety of music-related technologies in the context of pursuing creative work. Specifically, Music Technology students will have opportunities to:

* become trained musicians able to work in a variety of musical ensembles and global music productions, with appropriate competencies in music theory and musicianship skills, while emphasizing the specialties of 21st Century music technology;
* develop professional-level skills allowing them to produce concerts, stage-manage, understand sound mixing and diffusion, and run stage monitoring and main audience sound;
* become skilled in and know how to run music studios at a high level for album and media production, including microphone techniques, software editors, audio effects, mixing, mastering, and the use of the Internet for audio production;
* develop thorough historical knowledge of electro-acoustic music as well as knowledge of the theory and operation of algorithms for traditional synthesis and audio effects production;
* become software engineers able to write computer code for websites for the Internet and understand advanced object-oriented computer languages for artistic expression;
* learn to design and build basic electronic circuits and make human computer interface designs for artistic practices;
* acquire knowledge of basic digital signal processing and how it relates to audio, including time and frequency domain processing and how these may be manipulated for artistic practices;
* develop high-level practical and professional skills, including the ability to synthesize diverse studies, project planning, execution, time management, and documentation of both technical and musical work at a level suitable for publication in a professional journal.

### Music technology MFA degree requirement
#### Program Requirements

* MTEC600 Topics in Music Technology (2 classes)
* MFOR506 Creative Technology Forum (4 classes)
* MTEC613 & MTEC614 Introduction to Programming I & II (2 classes)
* MTEC621 C++ for Electronic Music I (1 class)
* MTEC630 & MTEC631 Interface Design I & II (2 classes)
* MTEC660 Audio Signal Processing (1 class)
* MTEC685 Teaching in Technology (2 classes)
* MHST525 Survey of Sound Art (1 class)
* MTEC690 Music Technology MFA Project (variable units; must enroll each semester in residence)
##### 2 Music Technology electives, chosen from (2 classes):
* MTEC580 Advanced Web Application Development
* MTEC680 Music Information Retrieval & Machine Learning for Art
* MTEC616 Visual Programming
* MTEC550 Robotic Design for Music
* MTEC612 Mobile Music Computing
* MTEC622 C++ for Electronic Music II
* MTEC635 Advanced Circuit Design
* MTEC640 Programming for Raspberry Pi
* MTEC650 Sound Synthesis
* MTEC655 Advanced Synthesis
##### 2 Digital Performance Ensemble electives, chosen from (2 classes):
* IIMC550 SoundGameSpace
* MBLE625 Creative Electronic Ensemble
* MCMP615 Choreographers & Composers
* MTEC540 Machine Orchestra
* MTEC618 Data Driven Art & Visuals
* MTEC619 Experience Design & Technology
* MTEC520 Grids, Beats, and Groups
* MTEC530 21st-Century Raga & Tala
* MTEC541 Composition for Robots
