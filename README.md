## Installation

To install luaenv-each, clone this repository into your ~/.luaenv/plugins
directory. (You'll need a recent version of luaenv that supports plugin
bundles.)

```
$ mkdir -p ~/.luaenv/plugins
$ cd ~/.luaenv/plugins
$ git clone https://github.com/cehoffman/luaenv-each.git
```

## Usage

You can get help for the `each` command by passing the `-h` option.

```
$ luaenv each -h
Usage: luaenv each [-q] ...
	-q Don't print header for each version run
```

Verbose mode will print a header for each lua so you can distinguish
the output.

### Examples:

```
$ luaenv each lua test/test_suite.lua
$ luaenv each -v lpm test
```
