# Run Docker commands without sudo

```console
$ sudo groupadd docker
$ sudo gpasswd -a $USER docker
$ which docker | xargs sudo chmod a+x
$ sudo reboot 
```
