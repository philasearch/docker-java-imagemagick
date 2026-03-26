FROM eclipse-temurin:8-jre-alpine

RUN apk upgrade --update && apk add --no-cache --virtual .build-deps imagemagick ffmpeg vim python3 py3-virtualenv py3-pip gcc libc-dev rtmpdump mplayer mpv aria2 bash curl ca-certificates 

RUN python3 -m venv /opt/venv
ENV PATH="/opt/venv/bin:$PATH"

RUN pip3 install --no-cache-dir --upgrade pip && \
    pip3 install --no-cache-dir yt-dlp
 
