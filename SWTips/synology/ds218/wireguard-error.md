~~~
:/volume1/docker$ git clone https://github.com/runfalk/synology-wireguard.git
Cloning into 'synology-wireguard'...
remote: Enumerating objects: 319, done.
remote: Counting objects: 100% (57/57), done.
remote: Compressing objects: 100% (40/40), done.
remote: Total 319 (delta 19), reused 44 (delta 13), pack-reused 262
Receiving objects: 100% (319/319), 100.78 KiB | 4.80 MiB/s, done.
Resolving deltas: 100% (163/163), done.
:/volume1/docker$ dir
total 0
drwx------ 1 sd4admin root   36 Jun  7 22:14 .
drwxr-xr-x 1 root     root  736 Jun  7 21:29 ..
drwx------ 1 sd4admin users 338 Jun  7 22:14 synology-wireguard
:/volume1/docker$ cd synology-wireguard/
:/volume1/docker/synology-wireguard$ sudo docker build -t synobuild .
Password:
Sending build context to Docker daemon  255.5kB
Step 1/6 : FROM ubuntu:latest
latest: Pulling from library/ubuntu
ed02c6ade914: Pull complete
Digest: sha256:b6b83d3c331794420340093eb706a6f152d9c1fa51b262d9bf34594887c2c7ac
Status: Downloaded newer image for ubuntu:latest
 ---> a7870fd478f4
Step 2/6 : VOLUME [ "/toolkit_tarballs" ]
 ---> Running in beb4d1d362db
INFO[2022-06-07T22:15:28.036598277+09:00] Layer sha256:76021784cc589a55d543a5094538a36f39ff13c72d397cad529c141d591e6eec cleaned up
Removing intermediate container beb4d1d362db
 ---> 9a89849a7199
Step 3/6 : ENV IS_IN_CONTAINER 1
 ---> Running in d7f123f9c123
INFO[2022-06-07T22:15:33.472085588+09:00] Layer sha256:76021784cc589a55d543a5094538a36f39ff13c72d397cad529c141d591e6eec cleaned up
Removing intermediate container d7f123f9c123
 ---> fc1e2d96da11
Step 4/6 : RUN apt-get update  && apt-get -qy install git python3 wget ca-certificates xz-utils
 ---> Running in c2f57d20bff2
WARN[2022-06-07T22:15:36.540224307+09:00] seccomp is not enabled in your kernel, running container without default profile
time="2022-06-07T22:15:36.670913096+09:00" level=info msg="loading plugin \"io.containerd.event.v1.publisher\"..." runtime=io.containerd.runc.v2 type=io.containerd.event.v1
time="2022-06-07T22:15:36.671157766+09:00" level=info msg="loading plugin \"io.containerd.internal.v1.shutdown\"..." runtime=io.containerd.runc.v2 type=io.containerd.internal.v1
time="2022-06-07T22:15:36.671226544+09:00" level=info msg="loading plugin \"io.containerd.ttrpc.v1.task\"..." runtime=io.containerd.runc.v2 type=io.containerd.ttrpc.v1
time="2022-06-07T22:15:36.671688290+09:00" level=info msg="starting signal loop" namespace=moby path=/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c2f57d20bff21e768872ad331c8196999d894aea447dec7467128b5f0b7d3d1f pid=25789 runtime=io.containerd.runc.v2
Ign:1 http://ports.ubuntu.com/ubuntu-ports jammy InRelease
Ign:2 http://ports.ubuntu.com/ubuntu-ports jammy-updates InRelease
Ign:3 http://ports.ubuntu.com/ubuntu-ports jammy-backports InRelease
Ign:4 http://ports.ubuntu.com/ubuntu-ports jammy-security InRelease
Ign:1 http://ports.ubuntu.com/ubuntu-ports jammy InRelease
Ign:2 http://ports.ubuntu.com/ubuntu-ports jammy-updates InRelease
Ign:3 http://ports.ubuntu.com/ubuntu-ports jammy-backports InRelease
Ign:4 http://ports.ubuntu.com/ubuntu-ports jammy-security InRelease
Ign:1 http://ports.ubuntu.com/ubuntu-ports jammy InRelease
Ign:2 http://ports.ubuntu.com/ubuntu-ports jammy-updates InRelease
Ign:3 http://ports.ubuntu.com/ubuntu-ports jammy-backports InRelease
Ign:4 http://ports.ubuntu.com/ubuntu-ports jammy-security InRelease
Err:1 http://ports.ubuntu.com/ubuntu-ports jammy InRelease
  Temporary failure resolving 'ports.ubuntu.com'
Err:2 http://ports.ubuntu.com/ubuntu-ports jammy-updates InRelease
  Temporary failure resolving 'ports.ubuntu.com'
Err:3 http://ports.ubuntu.com/ubuntu-ports jammy-backports InRelease
  Temporary failure resolving 'ports.ubuntu.com'
Err:4 http://ports.ubuntu.com/ubuntu-ports jammy-security InRelease
  Temporary failure resolving 'ports.ubuntu.com'
Reading package lists...
W: Failed to fetch http://ports.ubuntu.com/ubuntu-ports/dists/jammy/InRelease  Temporary failure resolving 'ports.ubuntu.com'
W: Failed to fetch http://ports.ubuntu.com/ubuntu-ports/dists/jammy-updates/InRelease  Temporary failure resolving 'ports.ubuntu.com'
W: Failed to fetch http://ports.ubuntu.com/ubuntu-ports/dists/jammy-backports/InRelease  Temporary failure resolving 'ports.ubuntu.com'
W: Failed to fetch http://ports.ubuntu.com/ubuntu-ports/dists/jammy-security/InRelease  Temporary failure resolving 'ports.ubuntu.com'
W: Some index files failed to download. They have been ignored, or old ones used instead.
Reading package lists...
Building dependency tree...
Reading state information...
Package ca-certificates is not available, but is referred to by another package.
This may mean that the package is missing, has been obsoleted, or
is only available from another source

Package xz-utils is not available, but is referred to by another package.
This may mean that the package is missing, has been obsoleted, or
is only available from another source

E: Unable to locate package git
E: Unable to locate package python3
E: Unable to locate package wget
E: Package 'ca-certificates' has no installation candidate
E: Package 'xz-utils' has no installation candidate
INFO[2022-06-07T22:15:44.194302671+09:00] shim disconnected                             id=c2f57d20bff21e768872ad331c8196999d894aea447dec7467128b5f0b7d3d1f
WARN[2022-06-07T22:15:44.194510748+09:00] cleaning up after shim disconnected           id=c2f57d20bff21e768872ad331c8196999d894aea447dec7467128b5f0b7d3d1f namespace=moby
INFO[2022-06-07T22:15:44.194559674+09:00] cleaning up dead shim
INFO[2022-06-07T22:15:44.194582749+09:00] ignoring event                                container=c2f57d20bff21e768872ad331c8196999d894aea447dec7467128b5f0b7d3d1f module=libcontainerd namespace=moby topic=/tasks/delete type="*events.TaskDelete"
WARN[2022-06-07T22:15:44.214848895+09:00] cleanup warnings time="2022-06-07T22:15:44+09:00" level=info msg="starting signal loop" namespace=moby pid=25852 runtime=io.containerd.runc.v2
The command '/bin/sh -c apt-get update  && apt-get -qy install git python3 wget ca-certificates xz-utils' returned a non-zero code: 100
:/volume1/docker/synology-wireguard$
~~~
