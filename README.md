Auto Pairs
==========
Insert or delete brackets, parens, quotes in pair.

About Fork
----------
Because my [PR](https://github.com/jiangmiao/auto-pairs/pull/172) didn't get any response for a long long time, so I change my `auto-pairs` plugin to source to this repo.

The mainly difference is my fork will close pairs more cleanly, it is.

Original behavior of `jiangmiao/auto-pairs`

```javascript
input: [_]|
output: [__]|
```

But now

```javascript
// Useful with GitHub markdown
input: [_]|
output: [_]|

input: [__]|
output: [__]|

input: {_foo: bar}|
output: {_foo: bar_}|
```

Installation
------------

#### Vundle

```vimrc
Plugin 'shirohana/auto-pairs'
```

#### Pathogen

```bash
$ git clone https://github.com/shirohana/auto-pairs ~/.vim/bundle/-auto-pairs
```

Features
--------

Please go back to [jiangmiao/auto-pairs](https://github.com/jiangmiao/auto-pairs), I don't want to steal the original repo.

Original License
----------------

Copyright (C) 2011-2013 Miao Jiang

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
