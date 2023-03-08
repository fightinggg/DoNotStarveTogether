# DoNotStarveTogether

```bash
git clone git@github.com:fightinggg/DoNotStarveTogether.git && cd DoNotStarveTogether
```

```bash
docker run -v ${PWD}:/data/DoNotStarveTogether -p 10999-11000:10999-11000/udp -p 12346-12347:12346-12347/udp -it jamesits/dst-server:latest
```

# 获取token
steam启动游戏-(游戏中的'账号')-（顶部的'游戏'）-(左侧‘《饥荒：联机版》的游戏服务器’)
类似于：
```
pds-g^aaaaaaaaa-q^jaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa=
```
# 参考
https://hub.docker.com/r/jamesits/dst-server
