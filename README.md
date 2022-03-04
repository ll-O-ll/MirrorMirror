# **MagicMirror²**

is an open source modular smart mirror platform. This project packs MagicMirror into a docker image.

You find the [documentation here](https://khassel.gitlab.io/magicmirror/).

# Quick Instructions to get this running in server mode

Before anything, please install [Docker](https://docs.docker.com/get-docker/)
If running on Windows 10 please install [Windows Subsystem for Linux](https://docs.docker.com/get-docker/) 
If you're a mac user, you should be fine. If issues arise, please issue them on the Github repository [here](https://github.com/ll-O-ll/MatrixMirrors/issues)

Steps ☝️:

☝️ Navigate to the `~/magicmirror/run` directory

`cd ./magicmirror/run`

✌️ Create a file called `docker-compose.yml` in that directory and copy the contents of the `serveronly.yml` into that file


`cp serveronly.yml docker-compose.yml`

👌 Execute!

`docker-compose up -d`

To view the server open up a web browser and navigate to http://localhost:8080

---

To view logs

`docker logs mm`

To view all docker containers

`docker ps -a`

To remove the MagicMirror container:

`docker-compose down`