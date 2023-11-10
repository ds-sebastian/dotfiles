# Dotfiles Repository

This repository contains a collection of dotfiles and scripts to quickly set up a Linux environment with my preferred configuration and tools. It includes settings for the Fish shell, the Starship prompt, and other common tools and utilities.

## Structure

- `README.md` - This file, explaining the repository and its usage.
- `scripts/` - Contains all the setup scripts.

## Scripts

- `bootstrap.sh` - The main script that sets up the environment. It installs basic tools, clones the dotfiles, and runs other scripts.
- `install_fish.sh` - Installs the Fish shell and sets it as the default shell.
- `install_mambaforge.sh` - Downloads and installs Mambaforge, a package manager for managing conda packages.
- `install_starship.sh` - Installs the Starship prompt, a minimal and extremely fast shell prompt.

## Usage

To use these dotfiles and scripts, simply clone the repository to your local machine and execute the `bootstrap.sh` script:

```sh
git clone https://github.com/yourusername/dotfiles.git ~/dotfiles
cd ~/dotfiles
bash scripts/bootstrap.sh
