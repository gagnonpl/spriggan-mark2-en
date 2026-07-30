# Spriggan Mark 2 English Version

English version patch for **Spriggan Mark 2: Re-Terraform Project** on PC Engine Super CD-ROM².

This version provides the following:
- English subtitles for voiced cutscenes
- Translated title cards and character labels
- Translated in-level dialogue
- Translated menus, ending text, and credits

English text that was already present in the game hasn't been modified except for obvious errors.

<p align="center">
  <a href="https://github.com/gagnonpl/spriggan-mark2-en/raw/main/screenshots/title.png">
    <img src="screenshots/title.png" width="320" alt="Title screen" />
  </a>
  <a href="https://github.com/gagnonpl/spriggan-mark2-en/raw/main/screenshots/cutscenes.png">
    <img src="screenshots/cutscenes.png" width="320" alt="Cutscenes subtitles" />
  </a>
</p>
<p align="center">
  <a href="https://github.com/gagnonpl/spriggan-mark2-en/raw/main/screenshots/level.png">
    <img src="screenshots/level.png" width="320" alt="In-level dialogue" />
  </a>
  <a href="https://github.com/gagnonpl/spriggan-mark2-en/raw/main/screenshots/cutscenes-2.png">
    <img src="screenshots/cutscenes-2.png" width="320" alt="Cutscenes subtitles 2" />
  </a>
</p>
<p align="center">
  <a href="https://github.com/gagnonpl/spriggan-mark2-en/raw/main/screenshots/weapons.png">
    <img src="screenshots/weapons.png" width="320" alt="Weapons selection menu" />
  </a>
  <a href="https://github.com/gagnonpl/spriggan-mark2-en/raw/main/screenshots/credits.png">
    <img src="screenshots/credits.png" width="320" alt="Ending credits" />
  </a>
</p>

## Downloads

| File | Description |
| --- | --- |
| [`spriggan-mark2-english-v1.0.xdelta`](/releases/latest/download/spriggan-mark2-english-v1.0.xdelta) | xdelta3 patch |
| [`README.txt`](/releases/latest/download/README.txt) | Instructions and checksums |
| [`xdelta3`](https://github.com/jmacd/xdelta-gpl/releases) | Patching tool |
| [`xdelta3 GUI`](https://github.com/Moodkiller/xdelta3-gui-2.0/releases) | Patching tool (GUI) |

## Patching

Apply the patch with `xdelta3`:

```sh
xdelta3 -d -s original.img spriggan-mark2-english-v1.0.xdelta spriggan-mark2-english-v1.0.img
```

Then use the included CUE file to launch the patched image.

Use the exact source image listed below. The patch will not apply correctly to a different dump.

## Checksums

### Expected source image

| Hash | Value |
| --- | --- |
| CRC32 | DBE38C87
| MD5 | bf28ca897aebb9a8c0f49589edc3d6a9
| SHA-1 | 93e68a7202ebd31f84ab173458ba61060a6bebb5


### Patched output image

| Hash | Value |
| --- | --- |
| CRC32 | 5BAE39BD |
| MD5 | 19ff41061bbacd4b4a2ad5d129200670 |
| SHA-1 | 7438773a6038c05807393c1259548486b77485cf |

## Credits

English version by **Luke Gagnon**.
