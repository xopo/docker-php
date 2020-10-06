How to use it: 
- install Docker 
- start docker

CLI
- run existing configs: $> docker-composer up
- build/rebuild $> docker-composer build

Structure:
    conf - folder for configuration files
    logs - files where logs should be available ( logs from docker )
    Dockerfile - file used to build docker ( add packages to the image )
    docker-composer.yml - file use by docker to setup the image