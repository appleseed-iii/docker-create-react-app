# a docker container for the latest node 16 version

replaces [fleek/create-react-app](https://hub.docker.com/layers/create-react-app/fleek/create-react-app/node-16/images/sha256-c29e5ede95b3e86d85c1196dced0914c6a19f2193bb19090ae32a4913e8c2555?context=explore), which is out of date.

## how this works

1. in DockerHub click on your repo and, in the build tab, click on Configure Automated Builds.
2. in the build settings on Docker Hub set the name of the Docker tags according to convention. For instance, *my-image:node-10* will use node 10, *my-image:node-11* will use node 11 and *my-image:latest* will use the latest version available.

## built with inspiration from

1. [blog post](https://dev.to/samuelea/automate-your-builds-on-docker-hub-by-writing-a-build-hook-script-13fp)
2. [github repo](https://github.com/SamueleA/docker-hub-auto-build-tutorial)
