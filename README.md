# LESS TextMate bundle

Syntax highlighting for `.less` files. To learn more about [LESS][], see <http://lesscss.org/docs.html>.

This bundle was forked from `appden/less.tmbundle`

## Installation

1. [Install node.js](https://github.com/joyent/node/wiki/Installation)
2. Install [npm](https://github.com/isaacs/npm) with `curl http://npmjs.org/install.sh | sh`
3. Install [LESS](http://lesscss.org/) with `sudo npm install less`
4. Install the bundle

### 

    mkdir -p ~/Library/Application\ Support/TextMate/Bundles
    cd ~/Library/Application\ Support/TextMate/Bundles
    git clone git://github.com/parrish/less.tmbundle.git
    osascript -e 'tell app "TextMate" to reload bundles'

## Compiling to CSS (⌘S)

Runs `lessc` on the current file, saving to the same file name with a .css extension (e.g. style.less => style.css).

Compiling requires some version of `lessc` to be in your `PATH`.

## Authors

* Rasmus Andersson <http://hunch.se/> rsms@github
* Scott Kyle <http://appden.com/> appden@github

## License (MIT)

Copyright (c) 2010 Scott Kyle and Rasmus Andersson

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.


[LESS]: http://lesscss.org
