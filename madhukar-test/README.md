# madhukar-test

## Description
madhukar-test description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] madhukar-test`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree madhukar-test`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init madhukar-test
kpt live apply madhukar-test --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
