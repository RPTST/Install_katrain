# How-to Install katrain on Ubuntu 18.04

# Update and upgrade your system

    $sudo apt update && sudo apt upgrade

# Install pre-reqs
    $sudo apt install build-essential zlib1g-dev libncurses5-dev libgdbm-dev libnss3-dev libssl-dev libreadline-dev libffi-dev wget
    
    $sudo apt install build-essential libssl-dev libffi-dev python3-dev xclip xsel python3.6 python-pip3 cython3 -y
    
    $sudo apt install libsdl2-dev libsdl2-2.0-0 -y
    
    $sudo apt install libmikmod-dev libfishsound1-dev libsmpeg-dev liboggz2-dev libflac-dev libfluidsynth-dev libsdl2-mixer-dev libsdl2-mixer-2.0-0 -y
    
    $sudo apt install ffmpeg libavcodec-dev libavdevice-dev libavfilter-dev libavformat-dev libavutil-dev libswscale-dev libswresample-dev libpostproc-dev libsdl2-dev libsdl2-2.0-0 libsdl2-mixer-2.0-0 libsdl2-mixer-dev python3-dev
    
    $sudo apt install libjpeg-dev libwebp-dev libtiff5-dev libsdl2-image-dev libsdl2-image-2.0-0 -y
    
    $sudo apt install libfreetype6-dev libsdl2-ttf-dev libsdl2-ttf-2.0-0 -y
    
    $sudo apt-get install python3-pip build-essential git python3 python3-dev ffmpeg libsdl2-dev libsdl2-image-dev\
    libsdl2-mixer-dev libsdl2-ttf-dev libportmidi-dev libswscale-dev libavformat-dev libavcodec-dev zlib1g-dev\
    libgstreamer1.0 gstreamer1.0-plugins-base gstreamer1.0-plugins-good libpulse\
    pkg-config libgl-dev opencl-headers ocl-icd-opencl-dev
    
    $sudo apt install software-properties-common

# Install katrain
    $sudo add-apt-repository ppa:deadsnakes/ppa
    $sudo apt update
    $python3 -m pip install ffpyplayer
    $python3 -m pip install clipboard
    $python3 -m pip install pygame
    $python3 -m pip install -U katrain
    $python3 -m pip uninstall kivy
    $python3 -m pip install --no-binary kivy kivy==2.0.0rc2
    
# Install if needed / get an error
    $python3.6 -m venv my_env

# Run katrain
    $python3 -m katrain
