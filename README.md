# Description
Dockerfile which installs Node-SASS in an Alpine Linux image.

# Pull image
docker pull blairguk/node-sass-alpine

# Run image
docker run blairguk/node-sass-alpine:<NODE_VERSION> node-sass-alpine

# Upgrade Node

* `docker build -t blairguk/node-sass-alpine:<NODE_VERSION> .`
* `docker push blairguk/node-sass-alpine:<NODE_VERSION> .`
