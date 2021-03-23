# fleet-test

```
kind: GitRepo
apiVersion: fleet.cattle.io/v1alpha1
metadata:
  name: helm
  namespace: fleet-local
spec:
  repo: https://github.com/bentastic27/fleet-test
  paths:
  - one
  - two
```
