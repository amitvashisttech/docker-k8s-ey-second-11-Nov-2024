```
299  docker images
  300  docker push python-web-app:r1
  301  docker login
  302  docker push python-web-app:r1
  303  docker tag python-web-app:r1 amitvashist7/docker-k8s-ey-second-11-nov-2024-python-web-app:r1
  304  docker ps
  305  docker images
  306  docker tag python-web-app:r2 amitvashist7/docker-k8s-ey-second-11-nov-2024-python-web-app:r2
  307  ls
  308  docker images
  309  docker push amitvashist7/docker-k8s-ey-second-11-nov-2024-python-web-app:r1
  310  docker push amitvashist7/docker-k8s-ey-second-11-nov-2024-python-web-app:r2
  311  docker logout
  312  docker kill $(docker ps -q)
  313  docker rm $(docker ps -q)
  314  docker rm $(docker ps -qa)
  315  docker images
  316  docker rmi $(docker images -q) --force
  317  docker images
  318  docker run -d --name test-1 amitvashist7/docker-k8s-ey-second-11-nov-2024-python-web-app:r2
  319  docker images
  320  docker ps
  321  curl 172.17.0.2:5000
  322  docker images
  323  docker pull ubuntu:22.04
  324  docker pull ubuntu:nobel
  325  docker pull ubuntu:noble
  326  docker images
  327  docker pull ubuntu:focal
  328  docker images
  329  docker pull ubuntu:24.04
  330  docker images
```
