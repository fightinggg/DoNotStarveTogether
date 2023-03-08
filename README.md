# DoNotStarveTogether

```bash
git clone git@github.com:fightinggg/DoNotStarveTogether.git && cd DoNotStarveTogether
```

```bash
docker run -v ${PWD}/data:/data -p 10999-11000:10999-11000/udp -p 12346-12347:12346-12347/udp -d --name dst jamesits/dst-server:latest
```

```bash
crontab -e
0 0 * * * cd /home/s/src/DoNotStarveTogether && git pull && git add . && git commit -m '-'&& git push
```

# 获取token
steam启动游戏-(游戏中的'账号')-（顶部的'游戏'）-(左侧‘《饥荒：联机版》的游戏服务器’)
类似于：
```
pds-g^aaaaaaaaa-q^jaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa=
```

# 配置mod
http://blog.ttionya.com/article-1235.html


# 参考
https://hub.docker.com/r/jamesits/dst-server
