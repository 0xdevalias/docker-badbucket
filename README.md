# docker-badbucket

Automated minimal docker build of [@zuBux's](https://github.com/zuBux) [badbucket](https://github.com/zuBux/badbucket) by [Glenn 'devalias' Grant](http://devalias.net/) ([@_devalias](https://twitter.com/_devalias))

## Usage

```
docker run --rm -it -v "/Users/TODOCHANGEME/.aws:/.aws" devalias/badbucket -h
docker run --rm -it --env AWS_ACCESS_KEY_ID=TODOCHANGEME --env AWS_SECRET_ACCESS_KEY=TODOCHANGEME devalias/badbucket -h
```

You can pass your AWS credentials through in various ways:
* http://docs.aws.amazon.com/cli/latest/userguide/cli-chap-getting-started.html#config-settings-and-precedence

## DockerHub

* https://hub.docker.com/r/devalias/docker-badbucket/

## badbucket

badbucket is a quick-n-dirty tool to test the configuration of your S3 bucket, by @zuBux.

* https://github.com/zuBux/badbucket
