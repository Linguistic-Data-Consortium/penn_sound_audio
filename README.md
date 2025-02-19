This repository contains a sample of audio from [PennSound](https://writing.upenn.edu/pennsound/), an online poetry collection.

The data directory contains 100 flac files; each file is an excerpt from a recording on PennSound.  The mp3s from the website were converted to 16 kHz pcm mono, and the levels were normalized using the `--norm=-1` option with sox.  The table `excerpts.tsv` describes the excerpts with four columns:

1. `file`  full recording name
2. `excerpt`  excerpt name
3. `offset`  start time of excerpt within full recording
4. `duration`  excerpt duration

The original files were chosen as an approximately random sample of full recordings available on PennSound.  The excerpts were chosen to contain approximately five minutes of speech from the middle of the recording.  Details can be found in the penn_sound_eval repository.

Portions © 2025 These sound recordings are being made available for noncommercial and educational use only. All rights to this recorded material belong to the authors. Used with permission of the authors. Distributed by [PennSound](https://writing.upenn.edu/pennsound/).

