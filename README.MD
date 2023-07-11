### Dockerfile

Dockerfile is a declarative ways of creating our own images. docker will gives us some sytax to create our own images

File name should Dockerfile. docker command will only run where your dockerfile exists.

### How to build image from Dockerfile

...

docker build -t [docker-hub-URL]/[your-username]/[image-name]:version
...

### How to push image to docekrhub/ecr/local

...

docekr push [docker-hub-URL]/[your-username]/[image-name]:version