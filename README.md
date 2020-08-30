# `ncat` - Docker mod for openssh-server

This mod adds `ncat` to openssh-server, to be installed/updated during container start.

In openssh-server docker arguments, set an environment variable `DOCKER_MODS=registry.fyvm.org/openssh-server-ncat:master`

If adding multiple mods, enter them in an array separated by `|`, such as `DOCKER_MODS=linuxserver/mods:openssh-server-openssh-client|registry.fyvm.org/openssh-server-ncat:master`