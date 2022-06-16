# kpt-hello

## Description
sample description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] kpt-hello`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree kpt-hello`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init kpt-hello
kpt live apply kpt-hello --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
