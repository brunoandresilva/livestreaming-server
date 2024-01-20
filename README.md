# Livestreaming Server Using nginx

Using a docker image of an nginx proxy I added a simple configuration to redirect any video input like an *OBS* video capture into port 1935 using RTMP(Real Time Message Protocol).

### Technologies Used
- Docker
- Nginx

### Instructions
1. Execute the following command in this directory: `docker-compose up`
2. Change streaming server in your video capture software to `rtmp://localhost:1935/live`
3. Open your browser and search for `http://localhost:8081/live/.m3u8` (Depending on your browser you may need to install an extension to view *HLS* transmissions)

### References
To make this, I followed a youtube tutorial in order to learn more about docker. To watch the video, you can access the following link: `https://youtu.be/CrEzeBwLZPU`.
