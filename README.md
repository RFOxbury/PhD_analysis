# Introduction
This repository contains the code for the statistical analysis for my PhD.

# How the data were processed

The data in this repo come from my PhD analysis.

At a later date I'll upload the R notebook I used for cleaning the data and getting it into a usable format, but there were actually several steps required before that to get the raw data into .csv files. The process was as follows:

- In 2017, I conducted speech recordings with adolescents and children in Ealing, West London. These were recorded as .wav files.

- I transcribed the data in ELAN, an annotation tool commonly used in Linguistics (https://archive.mpi.nl/tla/elan). It allows you to produce transcriptions that are time-aligned to the original recordings.

- I force-aligned the transcriptions using the FAVE tool (https://github.com/JoFrhwld/FAVE/wiki/FAVE-align). If you have a sentence-level transcription and an audio file, FAVE adds word-level and phone-level annotations.

- FAVE also has the option to extract vowel formant measurements, but I (perhaps foolishly) chose to annotate the vowels manually. I made this decision because the recordings had various levels of background noise and I wanted to be able to visually inspect the vowel segments and check that the formants were visible as I went along. There is a nice explanation of what formants are here: https://swphonetics.com/praat/tutorials/what-are-formants/

# Codebook
