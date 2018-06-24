# webpagetest
> A linux web performance benchmark using webpagetest server & agent

## Dependencies
* [docker](https://docs.docker.com/install/)
* [docker-compose](https://docs.docker.com/compose/install/)
* [yarn](https://yarnpkg.com/lang/en/docs/install/#debian-stable)

## Running
```bash
# install nodejs dependencies
$ yarn install
# start webpagetest server & agent
$ docker-compose up -d
# export webpagetest server's url
$ export WPT_SERVER_URL="http://127.0.0.1:4000/"
# run benchmarks
$ ./run_benchmarks
# stop webpagetest server & agent
$ docker-compose down
```
