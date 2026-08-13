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
patch: https://github.com/gagnonpl/spriggan-mark2-en/releases/download/v1.2/spriggan-mark2-english-v1.2.xdelta
xdelta-multifile: https://github.com/gagnonpl/xdelta-multifile/releases

Patching
========

The patch modifies Tracks 02 and 37 of the Redump disc image. Apply it with xdelta-multifile:

1. Extract the complete Redump BIN/CUE set.
2. Make a copy of the set in a separate directory, e.g. `patched`.
3. Run:
  xdelta-mf -f -d \
    -s "original/Spriggan Mark 2 - Re Terraform Project (Japan) (Track 02).bin" \
    -t "patched/Spriggan Mark 2 - Re Terraform Project (Japan) (Track 02).bin" \
    -s "original/Spriggan Mark 2 - Re Terraform Project (Japan) (Track 37).bin" \
    -t "patched/Spriggan Mark 2 - Re Terraform Project (Japan) (Track 37).bin" \
    spriggan-mark2-english-v1.2.xdelta
4. If there's no error, the files are patched and the archive in patched/ is usable as-is.

Use the exact source files listed below. The patch will not apply correctly to a different dump.

Hashes
=========

Expected original files:

Redump set:   NEC - PC Engine CD & TurboGrafx CD
Redump name:  Spriggan Mark 2 - Re Terraform Project (Japan)

Spriggan Mark 2 - Re Terraform Project (Japan) (Track 02).bin
  CRC32:        EB604489
  MD5:          8679be50ee1c2d12e3d6cd5a0a3d1707
  SHA-1:        6db64581490afbd5f7c538f31bc63a6f0695dcb7

Spriggan Mark 2 - Re Terraform Project (Japan) (Track 37).bin
  CRC32:        D66E0920
  MD5:          fc8d1356ea9f828c5a466f29524e6493
  SHA-1:        eb9b3d55b0acb7e477fd2b262096863c31aacf4d

Patched output images:
Spriggan Mark 2 - Re Terraform Project (Japan) (Track 02).bin
Spriggan Mark 2 - Re Terraform Project (Japan) (Track 37).bin

ROMhacking.net
==============
https://www.romhacking.net/translations/7662/


Credits
=======

English version by Luke Gagnon.
