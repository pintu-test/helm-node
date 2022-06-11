## Helm NodeJS

Setup service be-nodejs-service manifest and deploy to Kubernetes Cluster, with:
  - Autoscalling
  - Export service with Load Balancer
  - Limit resource cpu: 100m and memory: 128Mi

You can access this services from public with load balancer, and this IP http://34.101.85.158:3000

## Running Command

Install or Upgrade
```bash
helm upgrade  --install be-nodejs-service ./helm-node --values ./helm-node/values.yaml -n pintu
```


## References
  - https://helm.sh/docs/helm/helm_create/
  - https://keel.sh/docs/#policies
