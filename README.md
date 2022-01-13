# Tequila

> refactor analysis tools

## Usage

```
tequila viz command line

Usage:
  tequila [command]

Available Commands:
  call        icall grpah
  coll        full collaboration grpahh
  dc          database call chain grpah
  dd          database dependencies
  help        Help about any command
  include     include dependencies of source code
  jc          java code package dependencies
  jd          java code to database dependencies
  sp          query sql parse
  tar         full collaboration graph from tar file

Flags:
      --config string   config file (default is $HOME/.tq_viz_cli.yaml)
  -h, --help            help for tequila
  -t, --toggle          Help message for toggle

Use "tequila [command] --help" for more information about a command.
```

## Doxygen

1. install doxygen

```
brew instal doxygen
```

2. create Doxyfile

copy from examples

3. change `INPUT` & `OUTPUT_DIRECTORY` in config

```
INPUT                  = examples/inheritance-tree-code
OUTPUT_DIRECTORY       = examples/inheritance-tree-code
```

LICENSE
---

Copyright (c) Li Xin. All rights reserved.

Licensed under the MIT license.