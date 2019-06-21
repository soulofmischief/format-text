# format-text (ft)
A wrapper around tput which provides a sane, compact way to format shell text.

## Prerequisites

* `tput` (part of the `ncurses` package, installed on most distributions)

## Usage:
`ft [OPTION] INPUT`
  
## Examples:

`ft -b 'This text will be bold.'`

`ft -u "$(ft -b 'This text will be bold and underlined.')"`

`echo $(ft -B 'This is blinking') and $(ft -i 'this is invisible')`

## Options:
```
-b:  Bold
-B:  Blink
-h:  Help
-i:  Invisible
-r:  Reverse
-s:  Standout mode
-u:  Underline
```
