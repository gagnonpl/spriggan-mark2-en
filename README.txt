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
patch: https://github.com/gagnonpl/spriggan-mark2-en/releases/download/v1.0/spriggan-mark2-english-v1.0.xdelta
cue file: https://github.com/gagnonpl/spriggan-mark2-en/releases/download/v1.0/spriggan-mark2-english-v1.0.cue
xdelta3: https://github.com/jmacd/xdelta-gpl/releases
xdelta3 GUI: https://github.com/Moodkiller/xdelta3-gui-2.0/releases

Patching
========

Apply the patch with xdelta3:

  xdelta3 -d -s original.img spriggan-mark2-english-v1.0.xdelta spriggan-mark2-english-v1.0.img

Then use the included CUE file to launch the patched image.

Use the exact source image listed below. The patch will not apply correctly to a different dump.


Checksums
=========

Expected source image:

  TOSEC set:  NEC PC-Engine CD & TurboGrafx-16 CD - Games - [IMG]
  TOSEC name: Spriggan Mark 2 - Re Terraform Project (1992)(Naxat)(JP)
  CRC32:      DBE38C87
  MD5:        bf28ca897aebb9a8c0f49589edc3d6a9
  SHA-1:      93e68a7202ebd31f84ab173458ba61060a6bebb5

Patched output image:

  CRC32:      5BAE39BD
  MD5:        19ff41061bbacd4b4a2ad5d129200670
  SHA-1:      7438773a6038c05807393c1259548486b77485cf


ROMhacking.net
==============
https://www.romhacking.net/translations/7662/


Credits
=======

English version by Luke Gagnon.
