# Batch scripts for simplifying ffmpeg conversions

## Requirements

FFMPEG must be located in `/ffmpeg/bin/ffmpeg/ffmpeg.exe` relative to the script's directory. Builds can be downloaded from [https://www.ffmpeg.org/](https://www.ffmpeg.org/).

### convert-image-sequence.bat
Takes a folder containing either PNG or JPG (not both!) images and converts them to a video (MP4 or WebM). 
The sequence is assumed a framerate of 12, and the output video has a framerate of 24.

Follow the on-screen instructions.

### convert-video.bat
Takes a video file and converts it to either MP4 (H.264) or WebM (VP9)

Follow the on-screen instructions.
