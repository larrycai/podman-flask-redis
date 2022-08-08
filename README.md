# Introduction

The code is copied from [awesome-compose flask-redis](https://github.com/docker/awesome-compose/tree/master/flask-redis) and modified for `podman` to use

````
$ podman play kube --replace pod.yaml
$ curl localhost:5000
This webpage has been viewed 1 time(s)
$ curl localhost:5000
This webpage has been viewed 2 time(s)
````

If you update the `flask/app.py`, it will be auto-reloaded

# difference

* network is difference, so use `localhost` instead of `redis`
* volume is slight difference

# reference 
* https://github.com/docker/awesome-compose/tree/master/flask-redis
* https://www.redhat.com/sysadmin/podman-play-kube-updates
