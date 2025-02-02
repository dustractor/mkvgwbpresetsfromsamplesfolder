# mkvgwbpresetsfromsamplesfolder
---
*"Make Voxglitch Wavbank Presets from Samples Folder"*

scan your samples folder and make voxglitch wavbank presets for every directory containing a minimum number of wavs



VCV Rack2 modules store presets in text files with the ``.vcvm`` extension and they are just json so that means it is fairly straightforward to use python to edit/analyze/create them.

####Usage:
    python mkvgwbpresetsfromsamplesfolder.py --samples-dir <path-to-your-sample-library> --min-wavs <ignore-folders-with-less-than-this-number-of-samples>

####Arguments:
``--samples-dir`` The default points to where I keep my samples so unless you also keep your samples on drive D: in a folder named zSamples you will want to change this.

``--min-wavs`` The default is 24 meaning if a folder has less than 24 wav files in it it will be ignored.

