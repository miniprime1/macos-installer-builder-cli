[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

# macOS Installer Builder (for CLI excutables)
Generate macOS installers for command-line applications and products from one command.
Modified from [KosalaHerath/macos-installer-builder](https://github.com/KosalaHerath/macos-installer-builder)

## How to use
1. clone this repository:
  ```
  git clone https://github.com/miniprime1/macos-installer-builder-cli
  ```
2. change directory to macos-installer-builder-cli/macOS-x64/:
  ```
  cd macos-installer-builder-cli
  ```
3. make directory application/:
  ```
  mkdir application
  ```
4. put your CLI executable in macOS-x64/application/:
  ```
  cp /path/to/your/program application/
  ```
5. run script:
  ```
  sudo sh build-macos-x64.sh <PROGRAM> <VERSION>
  ```
6. output will be at target/pkg/:
  ```
  open target/pkg/
  ```
