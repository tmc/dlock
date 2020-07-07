# dlock
Package for distributed locks. At the moment, the available implementations are [Redis](https://redis.io/topics/distlock) and Kubernetes using the [LeaseLock](https://kubernetes.io/docs/reference/generated/kubernetes-api/v1.18/#lease-v1-coordination-k8s-io) resource.

A simple [`Locker`](https://github.com/flowerinthenight/dlock/blob/master/dlock.go) interface is also provided. All lock objects in this package implement this interface.

# Usage
### LeaseLock
