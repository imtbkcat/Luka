![luka](https://i.loli.net/2020/06/08/Sng2LXTsPUD6aod.jpg)

<p></p>

[![Build Status](https://travis-ci.com/dxyinme/Luka.svg?branch=master)](https://travis-ci.com/dxyinme/Luka)

<h3>a golang IM service</h3>



**deployment Keeper (server is unnecessary)**
    
        confirm your port 10137 is free, client-coder can
    reference clientSample/WS.html

```
<in linux>
export GO111MODULE=on
export GOPROXY=https://goproxy.io
go build main/KeeperDeployment.go
./KeeperDeployment
```