FROM ubuntu:16.04
MAINTAINER rudi.broekhuizen@naturalis.nl

RUN apt-get -qq update && \
  apt install -y lsb curl unzip && \
  curl https://assets.geneious.com/installers/licensingUtility/2_1_2/GeneiousFloatingLicenseManager_linux64_2_1_2_with_jre.sh
  
RUN bash -c "./GeneiousFloatingLicenseManager_linux64_2_1_2_with_jre.sh"
