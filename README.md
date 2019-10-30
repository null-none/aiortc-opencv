# aiortc OpenCV example using Docker

Just run https://github.com/aiortc/aiortc/tree/master/examples/server on Docker.

```
docker build ./ -t aiortc-opencv
docker run -p 8080:8080 aiortc-opencv
```

Then open http://localhost:8080/ on your browser.
