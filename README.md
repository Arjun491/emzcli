emzcli
======

Commandline interface to do some 8mylez shopware stuff

[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/emzcli.svg)](https://npmjs.org/package/emzcli)
[![Downloads/week](https://img.shields.io/npm/dw/emzcli.svg)](https://npmjs.org/package/emzcli)
[![License](https://img.shields.io/npm/l/emzcli.svg)](https://github.com/8mylez/emzcli/blob/master/package.json)

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g emzcli
$ emz COMMAND
running command...
$ emz (-v|--version|version)
emzcli/1.2.1 darwin-x64 node-v10.12.0
$ emz --help [COMMAND]
USAGE
  $ emz COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`emz help [COMMAND]`](#emz-help-command)
* [`emz lde:create`](#emz-ldecreate)
* [`emz plugin:create`](#emz-plugincreate)
* [`emz plugin:prepare`](#emz-pluginprepare)

## `emz help [COMMAND]`

display help for emz

```
USAGE
  $ emz help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v2.1.4/src/commands/help.ts)_

## `emz lde:create`

Creates local development environment!

```
USAGE
  $ emz lde:create

OPTIONS
  -n, --projectName=projectName  Name of domain
```

_See code: [src/commands/lde/create.js](https://github.com/8mylez/emzcli/blob/v1.2.1/src/commands/lde/create.js)_

## `emz plugin:create`

Bootstraping for shopware 5.2 plugin.

```
USAGE
  $ emz plugin:create

OPTIONS
  -p, --pluginName=pluginName  name of plugin
```

_See code: [src/commands/plugin/create.js](https://github.com/8mylez/emzcli/blob/v1.2.1/src/commands/plugin/create.js)_

## `emz plugin:prepare`

Prepares the plugin for upload in the shopware backend.

```
USAGE
  $ emz plugin:prepare

OPTIONS
  -p, --pluginName=pluginName  name of plugin
```

_See code: [src/commands/plugin/prepare.js](https://github.com/8mylez/emzcli/blob/v1.2.1/src/commands/plugin/prepare.js)_
<!-- commandsstop -->
