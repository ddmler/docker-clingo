# docker-clingo

A docker image for [clingo](https://potassco.github.io/), an answer set programming solver with [examples](https://github.com/potassco/clingo/tree/master/examples) to play around.

## How to use

#### Pull the latest image
```sh
docker pull ddmler/docker-clingo
```

#### Try an example
```sh
docker run ddmler/docker-clingo clingo examples/gringo/subset/example.lp
```
