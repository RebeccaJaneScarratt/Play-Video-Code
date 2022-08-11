# Play-Video-Code

With the video named '1_metronome.mp4', the code plays the video. I can hear sound, see the video and they are synchronized.

I also want to play video '1_mans.wav' and I can hear the osund, but I can't see the video, only a black screen and I get the error:
File ~\OneDrive - Aarhus Universitet\Documents\PhD Rebecca\Behavioural experiment\tests psychopy\pyvidplayer.py:28 in get_file_data
    info = MediaInfo.parse(self.path).video_tracks[0]

IndexError: list index out of range

I thought maybe it doesn't work because it's a wav file so I converted it online (https://www.freeconvert.com/wav-to-mp4) to an mp4 file (1_mans.mp4) but the same error appears. 

Maybe it's because the conversion wasn't of good quality, but I would prefer the wav files to work because I have many videos (88) that need to be played by the code I will write and I don't really want to convert them all :p
