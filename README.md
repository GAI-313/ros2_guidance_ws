# ROS2 Guidance
```bash
git clone git@github.com:GAI-313/ros2_guidance_ws.git
```

## Linux
```bash
xhost +

docker compose up -d linux
```


## mac
```bash
open -a docker
open -a XQuartz

docker compose --env-file mac.env up -d mac
```
