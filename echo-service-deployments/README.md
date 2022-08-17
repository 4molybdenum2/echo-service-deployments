# echo-service-deployments

## Description
echo-service-deployments description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] echo-service-deployments`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree echo-service-deployments`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init echo-service-deployments
kpt live apply echo-service-deployments --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
