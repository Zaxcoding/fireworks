Going Out With a Bang
=========
A BossCoding collaboration with Andy Beers: http://www.github.com/bosstweed1.
<br>
<br>
How to Build and Run
=========
Although exclusively built and tested on OSX, there should be no issues on other platforms as all component parts claim to be cross-platform.

**To Use**:<br>
  1) Clone the repo.<br>
  2) cd to 'final'<br>
  3) 'make fireworks'<br>
  4) ./fireworks<br>
<br>
Controls
=========
**1234567** - Launch firework out of nozzle 1-7 <br>
**qwertyu** - Launch a 'nozzle sparkler' out of nozzle 1-7 <br>
**z**       - Play/pause the music <br>
**m**       - Quit (yeah, I know, it should be 'q', but we already use that) <br>
<br>
Frameworks
=========
This project uses **OpenGL** and **GLUT** for graphics, window management, and input handling.<br>
**BASS**, an open-source, cross-platform audio library was used for sound. To get started, check out the BASS_StreamCreateFile (http://www.un4seen.com/doc/bass/BASS_StreamCreateFile.html) and BASS_ChannelPlay (http://www.un4seen.com/doc/bass/BASS_ChannelPlay.html) commands in the documentation.
