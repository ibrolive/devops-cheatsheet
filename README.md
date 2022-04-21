# devops-cheatsheet

|Description|Linux command|Windows command|
|--|--|--|
|Get git URL|`git config --get remote.origin.url`|same as linux|
|Docker cleanup|`docker image prune` <br> `docker container prune` <br> `docker volume prune` <br> `docker network prune` <br> `docker system prune`|same as linux |
|Check CPU usage |`lscpu` <br> `cat /proc/cpuinfo` | |
|Check memory usage |`free -m` | |
|Set proxy |`export HTTPS_PROXY="http://your-proxy-server.com:your-proxy-port" && \` <br> `export HTTP_PROXY="http://your-proxy-server.com:your-proxy-port" && \` <br> `export NO_PROXY=".your-proxy-server.com" && \` <br> `export http_proxy="http://your-proxy-server.com:your-proxy-port" && \` <br> `export https_proxy="http://your-proxy-server.com:your-proxy-port" && \` <br> `export no_proxy=".your-proxy-server.com"` | |
