# docker-shout

Dockerized [Shout](https://github.com/erming/shout) IRC Client

## Build

    docker build -t bencevans/shout .

## Run

    docker run --name shout -d --publish 9000:9000 bencevans/shout
