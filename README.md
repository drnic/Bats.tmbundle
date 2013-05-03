# TextMate bundle for Bats tests.

Bash Automated Testing System ([Bats](https://github.com/sstephenson/bats)) is a test library running in Bash/Shell, created by [@sstephenson](https://github.com/sstephenson).

## Usage

All `.bats` files should automatically be assigned the `Bats` language/grammar. Alternately, you can manually change to it using `Shift+Ctrl+Alt+B`.

The following snippets/commands exist:

* `!env` - use at the top of a file to set the environment to `#!/usr/bin/env bats`
* `test` - inserts a `@test "name" { ... }` test block
* `line` - inserts a `[ "${lines[0]}" = "something" ]` assertion

## Installation

To install via Git:

    mkdir -p ~/Library/Application\ Support/TextMate/Bundles
    cd ~/Library/Application\ Support/TextMate/Bundles
    git clone https://github.com/drnic/Bats.tmbundle.git
    osascript -e 'tell app "TextMate" to reload bundles'

Source can be viewed or forked via GitHub: [https://github.com/drnic/Bats.tmbundle](https://github.com/drnic/Bats.tmbundle)


## License

(The MIT License)

Copyright (c) 2013 Dr Nic Williams, Stark & Wayne LLC

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
'Software'), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
