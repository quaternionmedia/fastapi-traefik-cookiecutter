# fastapi-traefik-cookiecutter
boilerplate code for FastAPI app attached to Traefik reverse proxy

## install

`cookiecutter https://github.com/quaternionmedia/fastapi-traefik-cookiecutter.git`

## use
With a running traefik instance and 'web' network in docker (see [moat](https://github.com/quaternionmedia/moat) ):

`docker-compose up`

then `curl localhost -H Host:your.domain` should return "Welcome home!"
