# shell


# take video using terminal
streamer -q -c /dev/video0 -f rgb24 -r 3 -t 00:00:10 -o ~/myvideo.avi



# take photo using terminal
mplayer -vo png -frames 1 tv://


