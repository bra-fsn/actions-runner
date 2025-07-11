# actions-runner

This repository produces a GitHub Actions runner image with Ubuntu 24.04 (Noble) and the latest version of the runner.

See https://github.com/actions/runner/issues/3623 for more details.

You can use this by replacing

```
image: ghcr.io/actions/actions-runner:latest
```

with

```
image: ghcr.io/bra-fsn/actions-runner:latest
```
