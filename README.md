# Godot Devcontainer

## Overview

Devcontainer with Godot utilities.

I didn't want to mess with Python in my local machine just to use linter.

## What's in the container

- Godot 4.3 (stable)
- Python 3

## Which extensions are installed?

- gdtoolkit
- godotFormatterAndLinter
- gut-extension (You need to install Gut in your Godot editor first)

## Usage

1. Copy .devcontainer/ and .vscode/ into your Godot project directory.
2. Start Godot editor locally.
3. Open your project directory with VSCode.
4. Reopen the directory with container.
5. Have fun.

## FAQ

- Q. Why do I need this?
    - A. It installs python to make the linter work, 
      plus sets up devcontainer so nicely that the Gut works even in the container.
- Q. Why is there a Godot executable in the container?
    - A. gdtoolkit and Gut depend on an executable.

