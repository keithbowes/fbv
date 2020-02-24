THIS IS ARCHIVED.  PLEASE USE THE SUPERIOR nfbv REPOSITORY INSTEAD.

## fbv
A framebuffer image viewer.   
fork from `http://s-tech.elsat.net.pl/fbv/`   
remove GIF support, for the libungif library is obsolete.   

------------
1. OVERVIEW   
  fbv (FrameBuffer Viewer) is a simple program to view pictures on a Linux
framebuffer device. In 2000, when fbv was created, there were no other
suitable programs performing the same task, so the authors decided to
follow the rule: 'If you need a tool, write it yourself.' :-)

2. REQUIREMENTS
  - Linux, configured to provide the framebuffer device interface
  - libjpeg for JPEG support
  - libpng for PNG support
  - built-in BMP support

3. INSTALLATION
  - run ./configure
  - type: make
  - type: make install

4. USAGE   
  Just run fbv without any arguments, and a short help message will appear.

5. AUTHORS   
  Tomasz 'smoku' Sterna <tomek@smoczy.net>
  Mateusz 'mteg' Golicz <mtg@elsat.net.pl>
  
  Feel free to send any comments, patches, bug fixes, suggestions, etc. The authors are not native English speakers, and they are aware of the fact that their English is far from perfect. Because of that, reports on grammar and vocabulary mistakes in this file are also welcome.

