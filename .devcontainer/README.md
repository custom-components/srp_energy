# Devcontainer

_The easiest way to contribute to and/or test this repository._

## Requirements

- [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
- [docker](https://docs.docker.com/install/)
- [VS Code](https://code.visualstudio.com/)
- [Remote - Containers (VSC Extention)](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)

[More info about requirements and devcontainer in general](https://code.visualstudio.com/docs/remote/containers#_getting-started)

## How to use Devcontainer for development/test

1. Make sure your computer meets the requirements.
1. Fork this repository.
1. Clone the repository to your computer.
1. Open the repository using VS Code.

When you open this repository with VSCode and your computer meets the requirements you are asked to "Reopen in Container", do that.

![reopen](data:image/png;base64,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)

If you don't see this notification, open the command pallet (ctrl+shift+p) and select `Remote-Containers: Reopen Folder in Container`.

_It will now build the devcontainer._

The container have some "tasks" to help you testing your changes.

## Custom Tasks in this repository

_Start "tasks" by opening the the command pallet (ctrl+shift+p) and select `Tasks: Run Task`_

Running tasks like `Start Home Assistant on port 8124` can be restarted by opening the the command pallet (ctrl+shift+p) and select `Tasks: Restart Running Task`, then select the task you want to restart.

### Start Home Assistant on port 8124

This will copy the configuration and the integration files to the expected location in the container.

And start up Home Assistant on [port 8124.](http://localhost:8124)

### Upgrade Home Assistant to latest dev

This will upgrade Home Assistant to the latest dev version.

### Set Home Assistant Version

This allows you to specify a version of Home Assistant to install inside the devcontainer.

### Home Assistant Config Check

This runs a config check to make sure your config is valid.
