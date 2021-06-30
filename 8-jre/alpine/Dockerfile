FROM openjdk:8-jre-alpine

RUN apk upgrade --update && apk add --no-cache --virtual .build-deps imagemagick ffmpeg vim python3 python-pip rtmpdump mplayer mpv aria2 atomicparsley

RUN pip install --no-cache-dir --upgrade pip && \
    pip install --no-cache-dir youtube-dl
 
