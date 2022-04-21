# devops-cheatsheet

|Description|Linux command|Windows command|
|--|--|--|
|Get git URL|`git config --get remote.origin.url`|same as linux|
| | | |
|Git checkout specific branch |`git clone --single-branch --branch <branchname> <remote-repo>` | |
| | | |
|Docker cleanup|`docker image prune` <br> `docker container prune` <br> `docker volume prune` <br> `docker network prune` <br> `docker system prune`|same as linux |
| | | |
|Check CPU usage |`lscpu` <br> `cat /proc/cpuinfo` | |
| | | |
|Check memory usage (available and free) |`free -m` | |
| | | |
|Set proxy |`export HTTPS_PROXY="http://your-proxy-server.com:your-proxy-port" && \` <br> `export HTTP_PROXY="http://your-proxy-server.com:your-proxy-port" && \` <br> `export NO_PROXY=".your-proxy-server.com" && \` <br> `export http_proxy="http://your-proxy-server.com:your-proxy-port" && \` <br> `export https_proxy="http://your-proxy-server.com:your-proxy-port" && \` <br> `export no_proxy=".your-proxy-server.com"` | |
| | | |
|Unset proxy |`unset HTTPS_PROXY && \` <br> `unset HTTP_PROXY && \` <br> `unset NO_PROXY && \` <br> `unset http_proxy && \` <br> `unset https_proxy && \` <br> `unset no_proxy` | |
|Check folder size |du -sh file_path | |
| | | |
