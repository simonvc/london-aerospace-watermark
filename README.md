# london-aerospace-watermark
Code and image to watermark videos.

Tested on a Mac.

Use homebrew to install ffmpeg

```brew install ffmpeg```


Run this command to water mark you MP4 file

```ffmpeg -i inputfile.mp4 -i LondonAerospaceWatermark.png -filter_complex "overlay=1000:525" outputfile.mp4```

Works with videos size 1280:720. For other sizes you'll need to change the overlay numbers to get the position right.
