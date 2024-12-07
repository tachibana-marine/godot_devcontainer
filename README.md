# Godot Devcontainer

## Overview

Devcontainer with Godot utilities.

Runs Godot Editor on the container by sharing /tmp/.X11-unix with the host machine.

For linux only (might work on WSL but not too sure).

## What's in the container

- Godot 4.3 stable
- Python 3
- gdtoolkit
- godotFormatterAndLinter

## Usage

1. (Optional if you don't need audio) Install PulseAudio
2. Clone this repo
3. Open the cloned directory with VS Code
    - Godot editor will open up automatically
    - You might want to remove .git for this repo
4. Create a new project and have fun
