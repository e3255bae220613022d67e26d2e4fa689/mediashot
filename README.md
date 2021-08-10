# mediashot
ffmpeg screenshot native resolution

# prelimary steps
apply chmod x to mediashot

chmod +x mediashot

install mediainfo and ffmpeg

apt-get install mediainfo
wget http://johnvansickle.com/ffmpeg/releases/ffmpeg-2.4.3-64bit-static.tar.xz
tar xfv ffmpeg-2.4.3-64bit-static.tar.xz
cp /home/user/ffmpeg-2.4.3-64bit-static.tar.xz/ffmpeg /usr/bin/
cp /home/user/mediashot /usr/bin/


# use
mediashot [your video file] [newfolder] [name of your video]

# example
mediashot example.mkv example-screenshots example
