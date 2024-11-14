```
561  docker run -it --name stg-1 mynetwork-ubuntu:v1
  562  docker ps
  563  docker ps -a
  564  docker start stg-1
  565  docker ps
  566  docker attach stg-1
  567  docker ps
  568  docker rm $(docker ps -aq)
  569  docker ps -a
  570  docker volume ls
  571  docker volume ls -q
  572  docker volume rm $(docker volume ls -q)
  573  ls
  574  docker volume ls
  575  docker volume create myvol1
  576  docker volume ls
  577  docker volume inspect myvol1
  578  ls -ltr /var/lib/docker/volumes/myvol1/_data
  579  docker run -it --name stg-2  -v myvol1:/myapp mynetwork-ubuntu:v1
  580  ;s
  581  docker ps
  582  ls -ltr /var/lib/docker/volumes/myvol1/_data
  583  ls -ltr /var/lib/docker/volumes/myvol1/_data/ey-11-nov-2024/
  584  cat  /var/lib/docker/volumes/myvol1/_data/ey-11-nov-2024/info
  585  docker ps
  586  docker kill stg-2
  587  docker rm stg-2
  588  docker ps
  589  docker ps -a
  590  docker volume ls
  591  cat  /var/lib/docker/volumes/myvol1/_data/ey-11-nov-2024/info
  592  docker run -itd --name stg-3  -v myvol1:/myapp mynetwork-ubuntu:v1
  593  docker run -itd --name stg-4  -v myvol1:/myapp mynetwork-ubuntu:v1
  594  docker ps
  595  docker exec -it stg-3 bash
  596  docker run -itd --name stg-5  -v myvol1:/var/www/html/amit mynetwork-ubuntu:v1
  597  docker exec -it stg-5 bash
  598  cat  /var/lib/docker/volumes/myvol1/_data/ey-11-nov-2024/info
  599  docker run -itd --name stg-6  -v myvol1:/var/www/html/amit:ro mynetwork-ubuntu:v1
  600  docker exec -it stg-6 bash
  601  ls
  602  pwd
  603  docker run -itd --name stg-7  -v /root/docker-k8s-ey-second-11-Nov-2024:/var/www/html/amit:ro mynetwork-ubuntu:v1
  604  docker exec -it stg-7 bash
  605  docker volume ls
  606  docker run -itd --name stg-8  -v /myapp mynetwork-ubuntu:v1
  607  docker volume ls
  608  docker exec -it stg-8 bash
  609  docker ps
  610  docker volume ls
  611  docker volume inspect
  612  docker volume inspect 69f6b22d2719ef2cbde901304442ef623739cda4688ef10be4b06227d55a6c9b
  613  ls -ltr /var/lib/docker/
  614  ls -ltr /var/lib/docker/volumes/
  615  ls -ltr /var/lib/docker/volumes/69f6b22d2719ef2cbde901304442ef623739cda4688ef10be4b06227d55a6c9b/
  616  ls -ltr /var/lib/docker/volumes/69f6b22d2719ef2cbde901304442ef623739cda4688ef10be4b06227d55a6c9b/_data/info
  617  cat /var/lib/docker/volumes/69f6b22d2719ef2cbde901304442ef623739cda4688ef10be4b06227d55a6c9b/_data/info
  618  docker volume inspect 69f6b22d2719ef2cbde901304442ef623739cda4688ef10be4b06227d55a6c9b
  619  docker ps
  620  docker inspect stg-8
  621  sl
  622  ls
  623  man ls
  624  ls
  625  ls -ltr /var/lib/docker/volumes/69f6b22d2719ef2cbde901304442ef623739cda4688ef10be4b06227d55a6c9b/_data/info
```
