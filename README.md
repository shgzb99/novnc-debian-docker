# novnc-debian-docker
A lightweight desktop environment for Debian docker image that can be accessed from any browser. The image is based on the following>- Debian Linux distribution
- Xfce Desktop environment
- TigerVNC VNC server (default port 5903)
- noVNC VNC client web application (default port 6903)
# Usage
```
docker build -t novnc-debian-desktop .
docker run -d --name=linux-desktop -p 6903:6903 -p 5903:5903 novnc-debian-desktop
```
```
docker-compose up -d --build
```
