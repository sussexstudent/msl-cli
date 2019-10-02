msl-cli
=======



[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/msl-cli.svg)](https://npmjs.org/package/msl-cli)
[![CircleCI](https://circleci.com/gh/sussexstudent/msl-cli/tree/master.svg?style=shield)](https://circleci.com/gh/sussexstudent/msl-cli/tree/master)
[![Downloads/week](https://img.shields.io/npm/dw/msl-cli.svg)](https://npmjs.org/package/msl-cli)
[![License](https://img.shields.io/npm/l/msl-cli.svg)](https://github.com/sussexstudent/msl-cli/blob/master/package.json)

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g msl-cli
$ msl COMMAND
running command...
$ msl (-v|--version|version)
msl-cli/0.1.0 darwin-x64 node-v12.10.0
$ msl --help [COMMAND]
USAGE
  $ msl COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`msl hello [FILE]`](#msl-hello-file)
* [`msl help [COMMAND]`](#msl-help-command)

## `msl hello [FILE]`

describe the command here

```
USAGE
  $ msl hello [FILE]

OPTIONS
  -f, --force
  -h, --help       show CLI help
  -n, --name=name  name to print

EXAMPLE
  $ msl hello
  hello world from ./src/hello.ts!
```

_See code: [src/commands/hello.ts](https://github.com/sussexstudent/msl-cli/blob/v0.1.0/src/commands/hello.ts)_

## `msl help [COMMAND]`

display help for msl

```
USAGE
  $ msl help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v2.2.1/src/commands/help.ts)_
<!-- commandsstop -->
