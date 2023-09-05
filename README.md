# setup-yq
[![LICENSE](https://img.shields.io/github/license/freenet-actions/setup-yq)](https://github.com/freenet-actions/setup-yq/blob/main/LICENSE)

This action sets up the yq tool. It downloads yq binaries from https://github.com/mikefarah/yq/releases and adds path to PATH

   
# Usage
## Set up default yq version (v4.35.1)
```yaml
- uses: freenet-actions/setup-yq@v3
```
## Set up specific yq version
```yaml
- uses: freenet-actions/setup-yq@v3
  with:
    version: 4.35.1
```
