FROM ubuntu:14.04
RUN sudo apt-get -y update && sudo apt-get install -y gcc libc6-dev mercurial

#Install Go from source
RUN hg clone -u release https://code.google.com/p/go && hg update default
RUN cd go/src && ./all.bash
