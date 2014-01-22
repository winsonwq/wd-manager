wdm
==========

## How to use

Installation

```
$ npm install wdm -g
```
Then check

```
$ wdm

Usage: wdm <command>
Commands:
  update: install or update selected binaries
  start: start up the selenium server
  status: list the current available drivers

Options:
  --out_dir       Location to output/expect                         [default: "/Users/yourname/wd-manager/selenium"]
  --seleniumPort  Optional port for the selenium standalone server
  --standalone    install or update selenium standalone             [default: true]
  --chrome        install or update chromedriver                    [default: true]
  --ie            install or update IEDriver                        [default: false]

Please specify one command
```

## Use selenium default arguments

_Only being used in `start` command_

```
$ wdm start -- -role node -hub http://localhost:4444/grid/register
```
