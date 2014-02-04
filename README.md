autocue
=======

A small utility to generate .cue-files from chapter-marks found in media files.


Requirements
-------
* bash
* ffmpeg

Usage
-------

Autocue is very easy to use:

    autocue file1 file2 ...

This will generate file1.cue and file2.cue in the same directory as the original files.
The cue-file will contain a track for each chapter found in the respective file. 



Todo
-------

* Write proper filetype to cue, instead of MP3


Version History
-------

0.2 handle files without chapters
0.1 initial release
