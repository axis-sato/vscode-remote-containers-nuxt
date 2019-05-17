# vscode-remote-containers-nuxt

This project is the [Visual Studio Code Remote - Containers](https://code.visualstudio.com/docs/remote/containers) environment for Nuxt.js.

You can take syntax highlighting, autocompletion, linting, formatting ([Prettier](https://github.com/prettier/prettier)) and jumping to definitions without any configuration.

## Getting Started

### Prerequisites

- [Visual Studio Code Insiders](https://code.visualstudio.com/insiders/)
    - [Remote Development extensions](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.vscode-remote-extensionpack)

### Setup

1. Clone this project.
2. Start VS Code and open your project folder.
3. Select __Remote-Containers: Reopen Folder in Container__ from the command palette.
4. Open a terminal in VS Code and create your Nuxt.js project to run: `yarn create nuxt-app .`.
    - Check `Linter / Formatter` and `Prettier`.
5. Run dev server to run: `yarn run dev` and then you can access `localhost:3000`.