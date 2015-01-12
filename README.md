Automated_Music_Transcription
=============================

A program that automatically transcribes a music file with polyphonic piano music in .wav format to sheet notes.

You need to install <a href=http://www.lilypond.org/>lilypond</a> for plotting notes
and aubioonset for finding note onsets: `sudo apt-get install aubio-tools`

Afterwards just run:

`python music_transcriber.py music_file_name.wav`


### Example
#### Monophonic
Input example: twinkle_short.wav

Corresponding example output with sheet notes: twinkle_short.pdf

If you'd like to hear the MIDI output:

`sudo apt-get install timidity`

`timidity twinkle_short.mid`

#### Polyphonic
Input example: Mozart_Polonaise_part.wav

Output example: Mozart_Polonaise_part.pdf





