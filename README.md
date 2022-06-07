# Hoomie

Hoomie is an PoC for what I called homeOS, a simple suite of home administration tools from cooking to inventory.

## Setup Environment

This repository is setup to use vscode's Remote Containers. So install the extention on your vscode installation.

To setup application's environment run in a terminal tab:
```shell
bin/setup
```

To run develoment server run in a new terminal tab:
```shell
rails s -b 0.0.0.0
```

To run webpack builds run in a new terminal tab:
```shell
yarn build --watch
```

To run sass builds run in a new terminal tab:
```shell
yarn build:css --watch
```