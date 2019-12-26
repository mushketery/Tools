#Docker build
docker build -t jenkins .

#Docker tag
docker tag 4997991c5cfb rameca231190/hub.docker.com

#Docker push
docker push rameca231190/hub.docker.com
