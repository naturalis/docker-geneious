FROM ubuntu:16.04
MAINTAINER rudi.broekhuizen@naturalis.nl

RUN apt-get -y update && \
  apt install -y lsb wget curl unzip && \
  wget https://assets.geneious.com/installers/licensingUtility/2_1_2/GeneiousFloatingLicenseManager_linux64_2_1_2_with_jre.sh && \
  chmod +x ./GeneiousFloatingLicenseManager_linux64_2_1_2_with_jre.sh

ADD /answers .

RUN bash -c "./GeneiousFloatingLicenseManager_linux64_2_1_2_with_jre.sh"
