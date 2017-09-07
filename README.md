# shell


<B>take video using terminal </B> <br>
streamer -q -c /dev/video0 -f rgb24 -r 3 -t 00:00:10 -o ~/myvideo.avi

<br><br>

<B> take photo using terminal </B><br>
mplayer -vo png -frames 1 tv://

<B> take video using mencoder </B><br>
mencoder tv:// -tv driver=v4l2:width=320:height=240:device=/dev/video0 -nosound -ovc lavc -o myvideo.avi

http://www.linuxintro.org/wiki/Set_up_a_Webcam_with_Linux
