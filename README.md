## Run a Wyoming Faster Whisper Docker container on a CUDA GPU

Clone the repository and navigate into it:
```
git clone https://github.com/BramNH/wyoming-faster-whisper-docker-cuda \
cd wyoming-faster-whisper-docker-cuda
```
Build the image:
```
docker build --tag wyoming-whisper .
```
Start container with Docker Compose:
```
docker compose up -d
```
