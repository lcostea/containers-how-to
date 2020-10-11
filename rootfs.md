## Download the root file system

* mkdir alpine3.12
* curl -o alpine.tar.gz http://dl-cdn.alpinelinux.org/alpine/v3.12/releases/x86_64/alpine-minirootfs-3.12.0-x86_64.tar.gz
* tar xvf alpine.tar.gz
* rm alpine.tar.gz

## Run chroot on alpine

* chroot alpine3.12 sh
* ls -al
* apk
* exit