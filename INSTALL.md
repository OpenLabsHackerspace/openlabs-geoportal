# MapServer

<http://mapserver.org/installation/unix.html>

## Install required librairies

    sudo apt-get install build-essential cmake \
      libpng++-dev libfreetype6-dev libjpeg-dev \
      libproj-dev libcurl4-gnutls-dev \
      libgeos-dev libxml2-dev libpq-dev libgif-dev libfcgi-dev libfribidi-dev libharfbuzz-dev \
      libcairo2-dev

## Download MapServer

    wget http://download.osgeo.org/mapserver/mapserver-7.0.6.tar.gz
    tar -zxvf mapserver-7.0.6.tar.gz
    cd mapserver-7.0.6
    
## Build MapServer

    mkdir build
    cd build
    cmake -DWITH_CLIENT_WMS=ON -DWITH_CLIENT_WFS=ON -DWITH_CURL=ON ..
    make

## Install MapServer

    sudo make install
    
## Test

    mapserv -v
    
It should display :

    MapServer version 7.0.6 OUTPUT=PNG OUTPUT=JPEG SUPPORTS=PROJ SUPPORTS=AGG SUPPORTS=FREETYPE SUPPORTS=CAIRO SUPPORTS=ICONV SUPPORTS=FRIBIDI SUPPORTS=WMS_SERVER SUPPORTS=WMS_CLIENT SUPPORTS=WFS_SERVER SUPPORTS=WFS_CLIENT SUPPORTS=WCS_SERVER SUPPORTS=FASTCGI SUPPORTS=GEOS INPUT=JPEG INPUT=POSTGIS INPUT=OGR INPUT=GDAL INPUT=SHAPEFILE
