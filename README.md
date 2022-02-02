# docker-tutorial

# what is docker?

```
a platform for building, running and shipping applications

```

# virtual machines vs containers

```
container: an isolated environment for running an application
allow running multiple apps in isolation
are lightweight
use os of the host
start quickly
need less hardware resources

------------------------

virtual machine: an abstraction of a machine ( physical hardware )
( Hypervisor ) ->
 each vm needs a full blown OS,
 slow to start,
 resource intensive

```

# architecture of docker

```
client  -->  server
       REST
       API
containers
[ process process process ]
[      kernal             ]

```

# installing docker

```
1. docs.dockers.com/get-docker

2. start docker engine
```

# development workflow

```
Application -> dockerize
1. add Dockerfile - plain text file used to packge up an application into an image, image contains everything app needs to run
Image -> [ a cut-down OS, a runtime env( eg Node), Application files, thirdparty libs, env variables]

2. Dev -> registry -> Test/Prod
docker hub

```

# commands

```

start: docker-compose up

down: docker-compose down --rmi all

run: docker run

```
