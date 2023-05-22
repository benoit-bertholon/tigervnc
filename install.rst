# Ubunutu 22.04

## install notes

dependencies:
```
sudo apt install build-essential cmake libx11-dev   libpixman-1-dev   libjpeg-dev   libjpeg-turbo8-dev   libffmpeg-nvenc-dev   libfltk1.3-dev  libpam0g-dev  libgmp-dev  libmpfr-dev libboost-all-dev libavcodec-dev  libavutil-dev libswscale-dev  gnutls-dev nettle-dev  gettext    zlib1g-dev  zlib1g-dev  libxext-dev  libjpeg8-dev  libcconv-dev  libpam-dev libedit-dev libxrender-dev  libxcb-xinput-dev  libxi-dev  libpam0g-dev
```

repo clone and build:
```
git clone https://github.com/benoit-bertholon/tigervnc.git
cd tigervnc
cmake -G "Unix Makefiles"
cd vncviewer/
make vncviewer
```

run vncviewer:
```
./vncviewer
```

