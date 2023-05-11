Container launch command:

docker run -it -d -p 9090:9090 --mount type=bind,source=$Path-to-folder,target=/home/fileshare lukasjonikas01/prometheus:latest

