# Niksi

Niksi is a package management system that aims to help at the installation of development environments.
Niksi depends heavily on NixOS and the Nix package manager and ecosystem.

In the context of education, Niksi allows course staff to create a Git repository containing the
course files and a flake.nix file that describes the development environment for that course
(including all the programs that should be available)

## Installation

Niksi is currently available as PoC for any Windows machine that supports WSL.
For now, there exists no installer-program. Below is a step-by-step guide for installing.

1. Install Git on the host system (Niksi depends on git)
2. Install [WSL](https://learn.microsoft.com/en-us/windows/wsl/install) with `wsl --install`
3. Download the WSL image from [here](https://lajp.fi/static/niksi/nixos-wsl.tar.gz)
4. Import the image with `wsl --import .\NixOS\ nixos-wsl.tar.gz --version 2`
5. Install the plugin according to the [instructions](https://github.com/Niksi-tunk/vscode)
