# go-renovate-config [![validate](https://github.com/int128/go-renovate-config/actions/workflows/validate.yaml/badge.svg)](https://github.com/int128/go-renovate-config/actions/workflows/validate.yaml)

Renovate config for Go and Kubernetes.

```json5
{
  "$schema": "https://docs.renovatebot.com/renovate-schema.json",
  "extends": [
    "github>int128/renovate-base",
    "github>int128/go-renovate-config",
  ],
}
```

Here are some flavors.

```json5
{
  "$schema": "https://docs.renovatebot.com/renovate-schema.json",
  "extends": [
    "github>int128/go-renovate-config:kubernetes",
    "github>int128/go-renovate-config:kustomization-github-releases",
    "github>int128/go-renovate-config:doc-github-releases",
  ],
}
```
