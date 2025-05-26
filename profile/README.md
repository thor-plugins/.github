# THOR Plugins

## Introduction

This organisation hosts THOR plugins, which are extensions to the THOR malware scanner.

Plugins allow users to extend THOR's functionality by adding custom features. For more information on how to write and use plugins, refer to the [THOR Plugin Interface](http://github.com/NextronSystems/thor-plugin).

## Using plugins

Plugins are distributed as ZIP files and placed in the `plugins/` directory of your THOR installation. Each ZIP file is treated as a separate plugin.

> **Warning**: Plugins contain executable code that is run by THOR. Only use plugins from trusted sources.

## Writing plugins

To develop a new plugin, create a new repository using the [template](https://github.com/thor-plugins/template) and follow the instructions in the `README.md` file of the template repository.
