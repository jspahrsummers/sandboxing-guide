# Containers _(e.g., [Docker](https://www.docker.com/))_

![security: high](https://img.shields.io/badge/security-high-blue) ![usability: medium/high](https://img.shields.io/badge/usability-medium%2Fhigh-yellow)

As far as I'm concerned, [containerization](https://www.docker.com/resources/what-container) is one of the best things to happen to computing in general—and [developer tools](/use-cases/development.md) in particular. Although it can be a slow-building, space-hogging, pain in the ass sometimes, the isolation benefits are extremely powerful.

## Windows

Make sure to use the [WSL 2 Docker backend](https://docs.docker.com/desktop/windows/wsl/) to achieve native Linux performance in your containers!

## macOS

Docker supports [Apple Silicon](https://docs.docker.com/desktop/mac/apple-silicon/), and many images are available for `arm64`, which will offer much better performance than using `x86-64` emulation.