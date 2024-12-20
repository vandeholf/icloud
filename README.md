# icloud

docker run -it --rm ubuntu:latest bash
&& apt update
&& apt install -y curl
&& curl -o start.sh https://console.icn.global/downloads/install/start.sh
&& bash start.sh -p <private key>



