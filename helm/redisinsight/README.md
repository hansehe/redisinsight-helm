# Redisinsight

## Introduction

- https://hub.docker.com/r/redis/redisinsight

## Installing the Chart

To install the chart with the release name `redisinsight` run:

```bash
$ helm repo add redisinsight https://raw.githubusercontent.com/hansehe/redisinsight-helm/master/helm/charts
$ helm install redisinsight redisinsight/redisinsight
```

Alternatively, a YAML file that specifies the values for the parameters can be provided while installing the chart. For example,

```bash
$ helm install redisinsight -f values.yaml redisinsight/redisinsight
```

## Configuration

Find all possible configuration values here:
- https://github.com/hansehe/redisinsight-helm/blob/master/helm/redisinsight/values.yaml
