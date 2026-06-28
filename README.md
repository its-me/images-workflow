# Image Workflow

Template repository demonstrating a multi-arch Docker image CI/CD workflow with GitHub Actions.

## Workflow

- Builds on every push, pull request, and daily schedule
- Deploys to all registries on `main` branch and `v*` tag pushes; build-only on other branches and PRs
- Supports 8 platforms: `linux/amd64`, `linux/arm64`, `linux/arm/v7`, `linux/arm/v6`, `linux/386`, `linux/ppc64le`, `linux/s390x`, `linux/riscv64`

## Images

| Tag | Description |
|---|---|
| `base` | Minimal image built from busybox |
| `base-X.Y.Z` | Versioned base image |
| `successor` | Extends base, demonstrating image inheritance |
| `successor-X.Y.Z` | Versioned successor image |

## Registries

| Registry | Repository |
|---|---|
| GitHub Container Registry | [ghcr.io/its-me/workflow](https://ghcr.io/its-me/workflow) |
| Docker Hub | [hub.docker.com/r/1tsme/workflow](https://hub.docker.com/r/1tsme/workflow) |
| Quay.io | [quay.io/repository/itsme/workflow](https://quay.io/repository/itsme/workflow) |

## License

[MIT](LICENSE)
