# docker-calibre

A Docker-file to create a calibre server with automatic books import

## Build the image 

`sudo docker build -t ekito/calibre-server`

## Run the container

`sudo docker run -d --restart=always -t -i -p 80:8080 -v ~/ebooks:/opt/calibre/import ekito/calibre-server`
