A [Docker](https://www.docker.com/) container with

- node 0.12
- grunt-cli (latest, installed globally)
- chrome for karma headless testing


```bash
# run it

$ docker run -it --rm -v $(pwd):/src -w /src -e NODE_ENV=CI emmenko/nodejs-karma npm -v
Starting virtual X frame buffer: Xvfb.
Executing command npm -v
2.11.3
```
