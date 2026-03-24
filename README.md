# FinalCut Utils

Final Cut Pro utilities collection - video analysis, subtitle conversion, and editing tools.

## Submodules

This repository uses git submodules to manage the following projects:

- [gob2json](https://github.com/334456777/gob2json) - Video silent/static interval detection and merging tool
- [gsp](https://github.com/334456777/gsp) - AI-powered static video segment analyzer using Google Gemini
- [ime](https://github.com/334456777/ime) - SRT subtitle correction tool using pinyin similarity matching
- [srt2fcpxml](https://github.com/334456777/srt2fcpxml) - SRT to Final Cut Pro FCPXML subtitle converter
- [vcmp](https://github.com/334456777/vcmp) - Video static scene detection tool with FCPXML export for Final Cut Pro

## Cloning

To clone this repository with all submodules:

```bash
git clone --recurse-submodules https://github.com/334456777/finalcut-utiles.git
```

If you've already cloned without submodules:

```bash
git submodule update --init --recursive
```
