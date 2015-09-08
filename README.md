# express-js-docker
Fresh Express generated app with docker compose

To get it running:

1. Install [docker toolkit](https://www.docker.com/toolbox), which includes docker-machine and docker-compose.
2. install the node packages in the web container:
```sh
→ docker-compose run web npm install
```
> Docker will download all of the images for the container.

3. start up the app:
```sh
→ docker-compose up
```
4. Open the app: (OS/X)
```sh
→ open http://$(docker-machine ip default):5000/
```
