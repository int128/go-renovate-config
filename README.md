# go-renovate-config [![validate](https://github.com/int128/go-renovate-config/actions/workflows/validate.yaml/badge.svg)](https://github.com/int128/go-renovate-config/actions/workflows/validate.yaml)

This is a config of Renovate for Go and Kubernetes project.

## Getting Started

```json
{
  "$schema": "https://docs.renovatebot.com/renovate-schema.json",
  "extends": [
    "config:recommended",
    "github>int128/go-renovate-config",
  ],
}
```

## Flavors

### Update `go` directive in go.mod

```json
    "github>int128/go-renovate-config:go-directive",
```

### GitHub Actions workflows

```json
    "github>int128/go-renovate-config:github-actions",
```

### Kubernetes specific rules

```json
    "github>int128/go-renovate-config:kubernetes",
```

### Kubebuilder specific rules

```json
    "github>int128/go-renovate-config:kubebuilder",
```

### Update GitHub Releases in README

```json
    "github>int128/go-renovate-config:doc-github-releases",
```

### Update GitHub Releases in kustomization.yaml

```json
    "github>int128/go-renovate-config:kustomization-github-releases",
```
