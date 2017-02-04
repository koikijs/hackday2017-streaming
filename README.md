This repository forked from https://github.com/iizukanao/node-rtsp-rtmp-server

```
npm i
sudo node server.js
open index.html with local host server

ffmpeg -re -i input.m4v -c:v copy -c:a copy -f flv rtmp://${rtmp server IP address}/live/input
```
