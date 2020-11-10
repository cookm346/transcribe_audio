ffmpeg -i audio_only.m4a output.wav
sox output.wav split.wav trim 0 30 : newfile : restart