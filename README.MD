# Khopesh #

Khopesh is a very simple wrapper around cli tools that allow you to have pre and post hooks for any subcommands.

Hooks are local to a folder, give you the possibility to behave differently in different locations

# Install #

    pip install khopesh

# How it works #

- Create a hooks folder
- Inside the hooks folder, create a folder with the name of the executable you want to be hooked by khopesh
- Add an alias in your .bashrc / .zshrc file to replace the command to be hooked by "khopesh thecommand"

