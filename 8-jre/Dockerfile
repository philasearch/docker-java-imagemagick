FROM openjdk:8-jre

RUN apt-get update && apt-get install -y imagemagick ffmpeg vim python3 python-pip rtmpdump mplayer mpv aria2 atomicparsley

RUN pip install --no-cache-dir --upgrade pip && \
    pip install --no-cache-dir youtube-dl 
