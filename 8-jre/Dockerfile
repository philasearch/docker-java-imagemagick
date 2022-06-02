FROM openjdk:8-jre

RUN apt-get update && apt-get install -y imagemagick ffmpeg vim python3 python3-pip python3-brotli rtmpdump mplayer mpv aria2 atomicparsley

RUN pip3 install --no-cache-dir --upgrade pip && \
    pip3 install --no-cache-dir yt-dlp 
