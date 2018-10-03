User Guide for Ubuntu 16.04 amd64 Desktop

1. Clone binary file and opencv library
2. Install dependency
    sudo apt-get install libtbb2 libgstreamer0.10-0 libgstreamer-plugins-base0.10-0 libdc1394-22 libavcodec-ffmpeg56 libavformat-ffmpeg56 libswscale-ffmpeg3 
3. run command
    export LD_LIBRARY_PATH=libopencv
4. Run execute file
    ./object-tracking
