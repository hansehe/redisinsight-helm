# Redisinsight

[![Artifact HUB](https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/redisinsight)](https://artifacthub.io/packages/search?repo=redisinsight)

## Run With Docker
```bash
docker-compose -f docker-compose.yml up
```

Access Redisinsight at: 
- http://localhost:5540/

## Use Helm Repo
```bash
helm repo add redisinsight https://raw.githubusercontent.com/hansehe/redisinsight-helm/master/helm/charts
helm repo update
```
```bash
helm install redisinsight redisinsight/redisinsight
```

