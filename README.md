# Dockerfiles for Flowspace

These are used by our CI builds.

## Building and publishing images

You might need to first sign in using `docker login`.
You will need to be a member of the Flowspace team on Docker Hub.

Build and push the docker image:

```sh
docker build -t flowspace/ruby:2.7.2-node-browsers ruby/images/2.7.2/node-browsers
docker push flowspace/ruby:2.7.2-node-browsers
```
