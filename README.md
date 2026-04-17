# setup-yq

[![LICENSE](https://img.shields.io/github/license/freenet-actions/setup-yq)](https://github.com/freenet-actions/setup-yq/blob/main/LICENSE)

This action sets up the yq tool. It downloads yq binaries from https://github.com/mikefarah/yq/releases and adds path to PATH

If you're using GitHub-hosted runners in your workflow, you probably don't need this (see "Included Software" on https://github.com/actions/runner-images), unless you want to downgrade/pin the version.

# Usage
## Set up yq with default version (v4.52.5)
```yaml
- uses: freenet-actions/setup-yq@v4.0.0
```
## Set up specific yq version
```yaml
- uses: freenet-actions/setup-yq@v4.0.0
  with:
    version: 4.52.5
```
