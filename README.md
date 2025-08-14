# Claude Code Demo

This is a simple site to demonstrate the steps to run Claude Code in a dev container in VSCode.

The intention was to provide a way to develop with Claude Code on Windows, but this approach could also work on Mac or Linux.

## Prerequisites

* [Docker Desktop](https://www.docker.com/products/docker-desktop/)
* [VSCode](https://code.visualstudio.com/)
  * With extension [Dev Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)
* [Anthropic dev container template](https://github.com/anthropics/claude-code)

## AWS Interaction
The dev container template has been modified so that it can
* Connect AWS Bedrock to Claude Code
* Carry the AWS SSO session from the source machine to the container (Note: This may only work on Windows)

## Reference
* Inspired by this video - [How to install and run Claude Code in a Container (Windows, Mac, or Linux)](https://www.youtube.com/watch?v=VB68aY71bTI)
* [Developing inside a Container](https://code.visualstudio.com/docs/devcontainers/containers)
