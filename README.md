# **MagicMirror²**

is an open source modular smart mirror platform. This project packs MagicMirror into a docker image.

You can find the [documentation here](https://khassel.gitlab.io/magicmirror/).

# Quick Instructions to get this running in server mode

Before anything, please install [Docker](https://docs.docker.com/get-docker/).
If running on Windows 10 please install [Windows Subsystem 2 for Linux](https://pureinfotech.com/install-windows-subsystem-linux-2-windows-10/).
If you're a mac user, you should be fine. If issues arise, please issue them on the Github repository [here](https://github.com/ll-O-ll/MirrorMirror/issues)

Steps:

☝️ Navigate to the `~/magicmirror/run` directory

```shell 
cd ./magicmirror/run
```

✌️ Execute! 

```shell
docker-compose up -d
```

To view the server open up a web browser and navigate to http://localhost:8080

---

To view logs

```shell
docker logs mm
```

To view all docker containers

```shell
docker ps -a
```

To remove the MagicMirror container:

```shell
docker-compose down
```
