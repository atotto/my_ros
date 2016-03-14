# Failed to mount folders in Linux guest. This is usually because the "vboxsf" file system is not available.

fix vbguest:

```
$ vagrant up
$ vagrant ssh -c 'sudo apt-get update'
$ vagrant vbguest
$ vagrant plugin install vagrant-vbguest
$ vagrant vbguest
$ vagrant reload
```
