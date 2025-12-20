<p align="center">
  <a href="https://github.com/jmgogo/bun-devcontainer">
    <img src="imgs/Bun.png" alt="Logo">
  </a>
</p>
<h3 align="center">Foreword</h3>
<p align="center">
  A series of bun dev container setups to use for your projects.
  <br>
  <a href="https://github.com/jmgogo/bun-devcontainer/issues">Report Bug</a>
  ·
  <a href="https://github.com/jmgogo/bun-devcontainer/issues">Request Feature</a>
</p>
<br>

## About Bun

Bun is a fast all-in-one toolkit designed for developing, testing, running, and bundling JavaScript and TypeScript projects.

## Getting Started

This repository provides development environments for [Bun](https://bun.sh/) using [Dev Containers](https://containers.dev/). To get started, select the branch that best matches your project requirements.

- **`bun`**: setup with bun and a volume mount to clone projects into for long term development
- **`bun-bind`**: setup with bun and a bind mount which is intended for quick prototyping
- **`bun-postgres`**: the same setup as the `bun` branch with a postgresql database service

Open Docker Desktop to run the Docker daemon, a background process that manages and coordinates Docker containers on your system. On VS Code, start the development container by running `Dev Containers: Rebuild and Reopen In Container` in the command palette. It can be accessed with the keyboard shortcut `ctrl + shift + P` on your keyboard.

## License

This project is licensed under the MIT License.

---

_Checkout the [bun docs](https://bun.sh/docs) or [devcontainer docs](https://containers.dev/overview) for more information!_