# Image Workflow

Template repository demonstrating a multi-arch Docker image CI/CD workflow with GitHub Actions.

Source: [github.com/its-me/image-workflow](https://github.com/its-me/image-workflow)

## Images

| Tag | Description |
|---|---|
| `base` | Minimal image built from busybox |
| `base-X.Y.Z` | Versioned base image |
| `successor` | Extends base, demonstrating image inheritance |
| `successor-X.Y.Z` | Versioned successor image |

## Platforms

`linux/amd64` · `linux/arm64` · `linux/arm/v7` · `linux/arm/v6` · `linux/386` · `linux/ppc64le` · `linux/s390x` · `linux/riscv64`

## Registries

- [GitHub Container Registry](https://ghcr.io/its-me/workflow)
- [Docker Hub](https://hub.docker.com/r/1tsme/workflow)
- [Quay.io](https://quay.io/repository/itsme/workflow)
