FROM debian:bullseye

RUN apt update && apt install -y \
    python3 \
    python3-pip\
    && rm -rf /var/lib/apt/lists/*

RUN pip install imutils

WORKDIR /motion-dock

CMD pip show imutils
