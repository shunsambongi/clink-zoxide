# zoxide support for clink

Adds `z` and `zi` aliases for using zoxide within clink.  

## Installation

Add the `zoxide.lua` script to your clink [lua scripts location](https://chrisant996.github.io/clink/clink.html#location-of-lua-scripts).

## Configuration

This script uses [clink settings](https://chrisant996.github.io/clink/clink.html#clink-settings) for the options that are usually supplied via command line flags to `zoxide init`. Run the `clink set` command to set the options:

- `zoxide.cmd` maps to the `zoxide init --cmd` option
- `zoxide.hook` maps to the `zoxide init --hook` option
- `zoxide.no_aliases` maps to the `zoxide init --no-aliases` option

