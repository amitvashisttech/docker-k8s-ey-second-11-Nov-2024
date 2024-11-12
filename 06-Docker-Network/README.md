```
 343  docker kill $(docker ps -q)
  344  ip addr
  345  docker network ls
  346  docker network inspect c498ebdcf305
  347  docker run -d --name test-1 amitvashist7/docker-k8s-ey-second-11-nov-2024-python-web-app:r2
  348  docker start test-1
  349  docker ps
  350  docker inspect test-1
  351  ip addr
  352  docker run -d --name test-2 amitvashist7/docker-k8s-ey-second-11-nov-2024-python-web-app:r2
  353  ip addr
  354  ls
  355  docker ps
  356  curl localhost:5000
  357  curl 172.17.0.2:5000
  358  ip addr
  359  curl 10.4.3.185:5000
  360  ls
  361  docker ps
  362  docker run -d --name test-3 -p 8080:5000 amitvashist7/docker-k8s-ey-second-11-nov-2024-python-web-app:r2
  363  docker ps
  364  curl 10.4.3.185:5000
  365  curl 10.4.3.185:8080
  366  netstat -tulnp
  367  systemctl status docker
  368  docker ps
  369  docker run -d --name test-4 -p 8080:5000 amitvashist7/docker-k8s-ey-second-11-nov-2024-python-web-app:r2
  370  docker run -d --name test-5 -P amitvashist7/docker-k8s-ey-second-11-nov-2024-python-web-app:r2
  371  docker ps
  372  curl 10.4.3.185:32768
  373  ls
  374  cd 04-Docker-Custom-Images/
  375  ls
  376  cd apache/
  377  ls
  378  cp -rf v3 v4
  379  cd v4/
  380  ls
  381  vim MyDocker
  382  ls
  383  docker build -t myapache:v2 -f MyDocker .
  384  docker images
  385  docker run -d -P  --name test-apache1 myapache:v4
  386  docker run -d -P  --name test-apache1 myapache:v2
  387  docker ps
  388  curl 10.4.3.185:32768
  389  curl 10.4.3.185:32769
  390  curl 10.4.3.185:32769/info.html
  391  ls
  392  cd ..
  393  ls
  394  cd v4/
  395  cat MyDocker
  396  cd ..
  397  ls
  398  cd v3/
  399  ls
  400  cat MyDocker
  401  docker ps
  402  docker images
  403  docker history 019f634ba5d4
  404  docker inspect 019f634ba5d4
  405  019f634ba5d4ls
  406  docker images
  407  docker inspect 59ab366372d5 | grep -i expose
  408  docker inspect 59ab366372d5
  409  ls
  410  docker images
  411  docker run -itd -P --name ubuntu-test-1 ubuntu:24.04
  412  docker ps
  413  docker run -itd -p 8081:80 --name ubuntu-test-2 ubuntu:24.04
  414  docker ps

```
