```
  657  mkdir 02-Docker-Compose/00-Setup -p
  658  cd 02-Docker-Compose/00-Setup/
  662  sh install-compose.sh
  668  cd 01-Ngnix/
  671  cat docker-compose.yaml
  673  docker-compose up -d
  674  docker ps
  675  curl localhost:8080
  676  docker ps
  677  docker-compose ps
  678  docker-compose stop
  679  docker-compose ps
  680  docker-compose rm
  681  docker-compose ps
  682  docker ps
  683  docker ps -a
``` 

``` 
  690  cd 02-MyApp/
  693  cat docker-compose.yaml
  694  ls
  695  docker-compose up -d
  696  docker-compose ps
  697  curl localhost:8082
  698  curl localhost:8080
  699  curl localhost:8081
  700  curl localhost:8081/info
  702  docker-compose ps
  705  cd ../01-Ngnix/
  706  ls
  707  cat docker-compose.yaml
  708  docker-compose up -d
  709  docker-compose ps
  710  docker ps
  711  ls
  712  docker-compose ps
  713  docker-compose kill
  714  docker-compose rm
  715  docker-compose ps
  716  docker ps
  717  ls
  718  cd ..
  719  ls
  720  cd 02-MyApp/
  721  ls
  722  docker-compose ps
  723  docker-compose kill 02-myapp-python-1
  724  docker-compose kill python-1
  725  docker-compose kill
  726* docker-compose kill -s
  727  docker-compose up -d
  728  docker-compose ps
  729  docker-compose kill python
  730  docker-compose ps
  731  docker-compose rm
  732  docker-compose kill
  733  docker-compose rm
  734  docker-compose ps
```
```

735  ls
  736  cd ..
  737  ls
  738  cat 02-MyApp/docker-compose.yaml
  742  cd 02-Docker-Compose/
  744  mkdir 03-Build
  746  cd 03-Build/
  748  cp -rf ../../01-Docker/04-Docker-Custom-Images/apache/v4/* .
  750  cat info.html
  752  cat docker-compose.yaml
  754  mv MyDocker MyDockerfile
  755  cat docker-compose.yaml
  757  docker-compose up -d
  758  docker images
  759  docker ps
  760  curl localhost:8092
  761  curl localhost:8092/info.html
  763  cat info.html
  765  docker-compose up -d
  766  cat MyDockerfile
  767  docker-compose up -d
  768  cat MyDockerfile
  769  docker-compose up -d --build
  770  docker-compose up -d --build --help
  771  docker-compose up -d --build --force-recreate
  772  curl localhost:8092/info.html
  773  cat info.html
  774  docker-compose up -d --build --force-recreate
  775  curl localhost:8092/info.html
```
