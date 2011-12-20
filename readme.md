# LESS TextMate bundle

Syntax highlighting for `.less` files. To learn more about [LESS][], see <http://lesscss.org>.

This bundle is similar to `appden/less.tmbundle` but requires `node` (and `less` to be installed in `node_modules`)


## Saving to CSS (⌘S)

Runs `less.render()` on the current file, saving to the same file name with a .css extension (e.g. style.less => style.css). 


## TextMate 2 Alpha Install

This bundle should work in the TM2 alpha. If you run into path errors, try adding the following to your `~/.tm_properties` file:

    PATH = "$PATH:/usr/local/bin:/usr/bin"
    NODE_PATH = "$NODE_PATH:/usr/local/lib/node_modules"


## Authors

* Tim Caswell (creationix) <http://howtonode.org/>
* Rasmus Andersson (rsms) <http://hunch.se/>
* Scott Kyle (appden) <http://appden.com/>


## License (MIT)

Copyright (c) 2010 Tim Caswell, Scott Kyle, Rasmus Andersson

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
