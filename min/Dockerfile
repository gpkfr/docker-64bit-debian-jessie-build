FROM debian:jessie
MAINTAINER Jason Hsu

COPY usr_local_bin/docker-* /usr/local/bin/

# sync: needed to avoid "text file busy" error
RUN chmod +x /usr/local/bin/*; sync; /usr/local/bin/docker-action

USER winner

WORKDIR /home/winner
