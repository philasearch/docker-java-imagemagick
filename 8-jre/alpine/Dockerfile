FROM openjdk:8-jre-alpine

RUN apk upgrade --update && apk add --no-cache --virtual .build-deps imagemagick ffmpeg vim python3 gcc libc-dev rtmpdump mplayer mpv aria2 

RUN pip3 install --no-cache-dir --upgrade pip && \
    pip3 install --no-cache-dir yt-dlp
 
