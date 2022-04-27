# DevOps Cheatsheet

A list of commands DevOps engineers find useful for their daily activities.

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
|Check memory/swap usage (available and free) |`free -m` <br> `free -h` <br> `swapon --show` <br> `swapon --summary` | |
| | | |
|Set proxy |`export HTTPS_PROXY="http://example.com:80"` <br> `export HTTP_PROXY="http://example.com:80"` <br> `export NO_PROXY=".example.com"` <br> `export http_proxy="http://example.com:80"` <br> `export https_proxy="http://example.com:80"` <br> `export no_proxy=".example.com"` | |
| | | |
|Set proxy on a single line|`export HTTPS_PROXY="http://example.com:80" && \` <br> `export HTTP_PROXY="http://example.com:80" && \` <br> `export NO_PROXY=".example.com" && \` <br> `export http_proxy="http://example.com:80" && \` <br> `export https_proxy="http://example.com:80" && \` <br> `export no_proxy=".example.com"` | |
| | | |
|Unset proxy |`unset HTTPS_PROXY` <br> `unset HTTP_PROXY` <br> `unset NO_PROXY` <br> `unset http_proxy` <br> `unset https_proxy` <br> `unset no_proxy` | |
| | | |
|Unset proxy on a single line |`unset HTTPS_PROXY && \` <br> `unset HTTP_PROXY && \` <br> `unset NO_PROXY && \` <br> `unset http_proxy && \` <br> `unset https_proxy && \` <br> `unset no_proxy` | |
| | | |
|Check folder size |`du -sh ./file.txt` | |
| | | |
