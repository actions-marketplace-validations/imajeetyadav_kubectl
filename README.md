# kubectl

GitHub Action to manage a Kubernetes cluster.

## Usage
To use this action, add the following step to your GitHub Action workflow:
```yaml
- uses: imajeetyadav/kubectl@v1
  with:
    version: v1.25.5 # optional
- run: kubectl get pods
```

## Authors

Created and maintained by [Ajeet Yadav](https://github.com/imAjeetYadav)
