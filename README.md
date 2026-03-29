# ROMO_pika_hybridization_aduio
Contains .txt annotation files (compatible with RavenLite) for ROMO AudioMoth and other recorder-collected acoustic data, extracted calls, and code


## Data description and background

There are two subspecies of pika in RMNP; data collection was focused on collecting calls from each of these two subspecies (which have distinct calls) and from their hybrid offspring, expected to make distinct, intermediate calls indicating hybrid status. AudioMoths are small, portable ARUs that were deployed for short periods of time - typically a few hours to a day - in RMNP in 2024 and 2025. Recordings were typically gathered at 48kHz, and varied in # of pika calls collected. In addition to AudioMoths ARUs, RODE portable ARUs were used in 2024 and 2025 at both NWT and RMNP, often overlapping with AudioMoths in time and space. 

AudioMoths were deployed at multiple locations on Niwot Ridge and in Rocky Mountain National Park (RMNP) in 2024 and 2025. Although the RMNP dataset is not from pikas on Niwot Ridge, this dataset is notably useful for this project as most data is annotated and cleaned: meaning that a human (often my undergraduate research assistant, Jules Hamlin) has gone through the raw data in RavenLite (PC application) and verified the occurrence and timing of a pika call from ARU-collected data (.WAV files), then drew a bounding box around the spectrogram (with frequency, time, and amplitude data) and added that to an annotation table (a '.txt' file containing all other annotations (bounding boxes) for the .WAV file). AudioMoth recordings were listened to in full when they were less than four hours. Recordings longer than this were slowly skimmed in 30 minute intervals. When a sound or call was found, that section was listened to until the calls/sounds ended. Annotation files can be used within RavenLite or in Python, R scripts, etc. to extract the calls from the original .WAV file and save them as individual .WAV files. Annotation files are .txt files, and very small. Audio data is very large, so only a small portion of data (individual pika calls and short continuous files) for each of the entire datasets is included in this repository. 



