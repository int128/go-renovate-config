# go-renovate-config [![validate](https://github.com/int128/go-renovate-config/actions/workflows/validate.yaml/badge.svg)](https://github.com/int128/go-renovate-config/actions/workflows/validate.yaml)

This is a config of Renovate for Go and Kubernetes project.

## Getting Started

```json5
{
  "$schema": "https://docs.renovatebot.com/renovate-schema.json",
  "extends": [
    "config:recommended",
    "github>int128/go-renovate-config",
  ],
}
```

## Flavors

### GitHub Actions workflows

```json5
    "github>int128/go-renovate-config:github-actions",
```

### Kubernetes specific rules

```json5
    "github>int128/go-renovate-config:kubernetes",
```

### Update GitHub Releases in README

```json5
    "github>int128/go-renovate-config:doc-github-releases",
```

### Update GitHub Releases in kustomization.yaml

```json5
    "github>int128/go-renovate-config:kustomization-github-releases",
```
