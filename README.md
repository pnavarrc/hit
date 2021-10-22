# @pnavarrc/hit

Git for Humans

[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/@pnavarrc/hit.svg)](https://npmjs.org/package/@pnavarrc/hit)
[![Downloads/week](https://img.shields.io/npm/dw/@pnavarrc/hit.svg)](https://npmjs.org/package/@pnavarrc/hit)
[![License](https://img.shields.io/npm/l/@pnavarrc/hit.svg)](https://github.com/pnavarrc/hit/blob/master/package.json)

<!-- toc -->

- [Usage](#usage)
- [Commands](#commands)
<!-- tocstop -->

# Usage

<!-- usage -->

```sh-session
$ npm install -g @pnavarrc/hit
$ hit COMMAND
running command...
$ hit (-v|--version|version)
@pnavarrc/hit/0.0.1 darwin-x64 node-v12.22.0
$ hit --help [COMMAND]
USAGE
  $ hit COMMAND
...
```

<!-- usagestop -->

# Commands

<!-- commands -->

- [`hit hello [FILE]`](#hit-hello-file)
- [`hit help [COMMAND]`](#hit-help-command)

## `hit hello [FILE]`

describe the command here

```
USAGE
  $ hit hello [FILE]

OPTIONS
  -f, --force
  -h, --help       show CLI help
  -n, --name=name  name to print

EXAMPLE
  $ hit hello
  hello world from ./src/hello.ts!
```

_See code: [src/commands/hello.ts](https://github.com/pnavarrc/hit/blob/v0.0.1/src/commands/hello.ts)_

## `hit help [COMMAND]`

display help for hit

```
USAGE
  $ hit help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v3.2.3/src/commands/help.ts)_

<!-- commandsstop -->
