# london-aerospace-watermark
Code and image to watermark videos.

Tested on a Mac.

Use homebrew to install ffmpeg

```brew install ffmpeg```


Run this command to water mark you MP4 file

```ffmpeg -i inputfile.mp4 -i LondonAerospaceWatermark.png -filter_complex "overlay=1000:525" outputfile.mp4```
