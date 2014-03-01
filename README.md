# My Docker Files

## My Dcoker

[Docker Index](https://index.docker.io/u/catatsuy/)

    sudo ./my-mkimage-debian.sh catatsuy/wheezy wheezy http://ftp.jp.debian.org/debian


## Usage


    docker images
    docker run -i -t catatsuy/wheezy /bin/bash
    # detach: C-p C-q
    docker run catatsuy/wheezy echo "hello"
    docker ps -a -notrunc
    docker attach ********
    docker commit -m "message" ******* catatsuy/newimage


## Dockerfile
