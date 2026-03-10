# FinalCut Utils

A collection of utilities for Final Cut Pro and video editing workflows.

## Submodules

This repository uses git submodules to manage the following projects:

- [gob2json](https://github.com/334456777/gob2json) - Go to JSON converter
- [gsp](https://github.com/334456777/gsp) - GSP utility
- [ime](https://github.com/334456777/ime) - Input Method Editor
- [srt2fcpxml](https://github.com/334456777/srt2fcpxml) - SRT to FCPXML subtitle converter
- [vcmp](https://github.com/334456777/vcmp) - Video comparison tool

## Cloning

To clone this repository with all submodules:

```bash
git clone --recurse-submodules https://github.com/334456777/finalcut-utiles.git
```

If you've already cloned without submodules:

```bash
git submodule update --init --recursive
```
