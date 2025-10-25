# go-renovate-config [![validate](https://github.com/int128/go-renovate-config/actions/workflows/validate.yaml/badge.svg)](https://github.com/int128/go-renovate-config/actions/workflows/validate.yaml)

This is a config of Renovate for Go and Kubernetes project.

## Getting Started

```json
{
  "$schema": "https://docs.renovatebot.com/renovate-schema.json",
  "extends": ["config:recommended", "github>int128/go-renovate-config"]
}
```

## Flavors

### Update go version in go.mod

```json
    "github>int128/go-renovate-config:go-version",
```

### Update go version in go.mod and Dockerfile together

```json
    "github>int128/go-renovate-config:go-version-with-dockerfile",
```

### Kubernetes specific rules

```json
    "github>int128/go-renovate-config:kubernetes",
```

### Kubebuilder specific rules

```json
    "github>int128/go-renovate-config:kubebuilder",
```

### Update GitHub Releases URLs

```json
    "github>int128/go-renovate-config:github-releases(**/kustomization.yaml)",
    "github>int128/go-renovate-config:github-releases(README.md)",
```
