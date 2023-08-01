FROM        openjdk:7-slim

LABEL       author="Softwarenoob" maintainer="admin@softwarenoob.com"

RUN         useradd -d /home/container -m container
 
USER        container
ENV         USER=container HOME=/home/container

USER        container
ENV         USER=container HOME=/home/container

WORKDIR     /home/container

COPY        ./entrypoint.sh /entrypoint.sh

CMD         ["/bin/bash", "/entrypoint.sh"]
