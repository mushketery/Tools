#Install docker cli on mac:
brew install docker docker-compose docker-machine xhyve docker-machine-driver-xhyve\n
sudo chown root:wheel $(brew --prefix)/opt/docker-machine-driver-xhyve/bin/docker-machine-driver-xhyve
#To login to your private repository run:
docker login --username=<username> --password=<password>