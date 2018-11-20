### Zalenium
---
https://github.com/zalando/zalenium

```sh
docker pull elgalu/selenium
docker pull dosel/zalenium
docker run --rm -ti --name zalenium -p 4444:4444 \
  -v /var/run/docker.sock:/var/run/docker.sock \
  -v /tmp/videos:/home/seluser/videos \
  --privileged dosel/zalenium start
  
curl -sSL https://raw.githubusercontent.com/dosel/t/i/p | bash -s start
```

```
```

```
```

