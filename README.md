# express-js-docker
Fresh Express generated app with docker compose

To get it running:
1. Install [docker toolkit](https://www.docker.com/toolbox), which includes docker-machine and docker-compose.
- install the node packages in the web container:
```sh
project-folder> docker-compose run web npm install
```
Docker will download all of the images for the container.
- start up the app:
```sh
project-folder> docker-compose up
```
- Open the app: (OS/X)
```sh
project-folder> open http://$(docker-machine ip default):5000/
```
