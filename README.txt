Spriggan Mark 2 English Version
================================

English version patch for Spriggan Mark 2: Re-Terraform Project on PC Engine Super CD-ROM².

This version provides the following:

  English subtitles for voiced cutscenes
  Translated title cards and character labels
  Translated in-level dialogue
  Translated menus, ending sequence, and credits
  Auto-save QoL feature: Continue from last finished level

Downloads
=========
patch: https://github.com/gagnonpl/spriggan-mark2-en/releases/download/v1.1/spriggan-mark2-english-v1.1.xdelta
cue file: https://github.com/gagnonpl/spriggan-mark2-en/releases/download/v1.1/spriggan-mark2-english-v1.1.cue
xdelta3: https://github.com/jmacd/xdelta-gpl/releases
xdelta3 GUI: https://github.com/Moodkiller/xdelta3-gui-2.0/releases
(optional) CCD file: https://github.com/gagnonpl/spriggan-mark2-en/releases/latest/download/spriggan-mark2-english-v1.1.ccd

Patching
========

Apply the patch with xdelta3:

  xdelta3 -d -s "Spriggan Mark 2 - Re Terraform Project (1992)(Naxat)(JP).img" spriggan-mark2-english-v1.1.xdelta spriggan-mark2-english-v1.1.img

Then use the included CUE file to launch the patched image.

Use the exact source image listed below. The patch will not apply correctly to a different dump.

Optionally, a corrected CCD file is provided since the patched image is slightly bigger, but most people shouldn't need that.

Checksums
=========

Expected source image:

  TOSEC set:  NEC PC-Engine CD & TurboGrafx-16 CD - Games - [IMG]
  TOSEC name: Spriggan Mark 2 - Re Terraform Project (1992)(Naxat)(JP)
  CRC32:      DBE38C87
  MD5:        bf28ca897aebb9a8c0f49589edc3d6a9
  SHA-1:      93e68a7202ebd31f84ab173458ba61060a6bebb5

Patched output image:

  CRC32:      A10B9B00
  MD5:        547c50946df7b59bf9d44cad8efdc79c
  SHA-1:      63a9090f69ccb0abbf1a2f2049564ea9f7b54c1f


ROMhacking.net
==============
https://www.romhacking.net/translations/7662/


Credits
=======

English version by Luke Gagnon.
