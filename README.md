# docker-badbucket

Automated minimal docker build of @zuBux's badbucket by Glenn 'devalias' Grant (@_devalias)

## Usage

```
docker run --rm -it -v "/Users/TODOCHANGEME/.aws:/.aws" devalias/badbucket -h
docker run --rm -it --env AWS_ACCESS_KEY_ID=TODOCHANGEME --env AWS_SECRET_ACCESS_KEY=TODOCHANGEME devalias/badbucket -h
```

You can pass your AWS credentials through in various ways:
* http://docs.aws.amazon.com/cli/latest/userguide/cli-chap-getting-started.html#config-settings-and-precedence

## badbucket

badbucket is a quick-n-dirty tool to test the configuration of your S3 bucket, by @zuBux.

* https://github.com/zuBux/badbucket
