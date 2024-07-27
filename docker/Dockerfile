FROM rocker/verse:4.3.3

RUN apt-get update -qq
RUN apt-get -y install cmake
RUN apt-get -y --no-install-recommends install libglu1-mesa-dev
RUN apt-get -y install libxml2-dev
RUN apt-get -y install ghostscript
RUN apt-get -y install libxt-dev
RUN apt-get -y install libfontconfig1-dev
RUN apt-get -y install libpng-dev
RUN apt-get -y install libtiff-dev
RUN apt-get -y install libharfbuzz-dev
RUN apt-get -y install libfribidi-dev
RUN apt-get -y install -y python3
RUN apt-get -y install python3-pip
RUN apt-get -y install python3-venv

RUN install2.r –error \
--deps TRUE \
quarto \
reticulate \
ggpubr \
ez \
jpeg \
grid \
plotrix \
lavaan \
cowplot \
rstatix \
moments \
tiff \
tinytex \
osfr
