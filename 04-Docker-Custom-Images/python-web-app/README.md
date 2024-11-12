```
 227  mkdir python-web-app
  228  ls
  229  cd python-web-app/
  230  ls
  231  vim Dockerfile
  232  ls
  233  vim app.py
  234  ls
  235  vim req.txt
  236  ls
  237  docker build -t python-web-app:r1 .
  238  vim Dockerfile
  239  docker build -t python-web-app:r1 .
  240  docker images
  241  docker run -d --name test-4 python-web-app:r1
  242  docker ps
  243  docker inspect --format '{{.Name}} {{.State.Status}} {{.NetworkSettings.IPAddress}}' $(docker ps -qa)
  244  curl 172.17.0.5
  245  curl 172.17.0.4
  246  curl 172.17.0.5
  247  docker ps
  248  curl 172.17.0.5
  249  ls
  250  mkdir r1
  251  mv * r1
  252  ls
  253  cp -rf r1 r2
  254  ls
  255  cd r2/
  256  ls
  257  cat app.py
  258  curl 172.17.0.5:5000
  259  docker ps
  260  ls
  261  vim Dockerfile
  262  ls
  263  docker build -t python-web-app:r2 .
  264  ls
  265  docker run -d --name test-5 python-web-app:r2
  266  docker ps
  267  docker inspect --format '{{.Name}} {{.State.Status}} {{.NetworkSettings.IPAddress}}' $(docker ps -qa)
  268  curl 172.17.0.6:5000
  269  ls
  270  cd ..
  271  ls
  272  cp -rf r2 r3
  273  ls
  274  cd r3/
  275  ls
  276  vim Dockerfile
  277  docker build -t python-web-app:r3 .
  278  docker run -d --name test-6 python-web-app:r3
  279  docker images
  280  docker ps
  281  docker inspect --format '{{.Name}} {{.State.Status}} {{.NetworkSettings.IPAddress}}' $(docker ps -qa)
  282  curl -v 172.17.0.7:80
  283  curl -v 172.17.0.7:5000
```
