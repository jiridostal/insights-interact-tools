# Insights Interact Toolkit

## Install

  1. Clone the repository

```shell
  $ git clone git@github.com:bastilian/insights-interact-tools.git $HOME/.insights-interact
```

  2. Install node packages via

```shell
  $ cd $HOME/.insights-interact && npm install
```

  3. Add an alias to your `.bashrc` or `.zshrc`:
```
  alias insights-interact="node $HOME/.insights-interact/index.js"
```

**Note:** The repo can be cloned to anywhere. `$HOME` is used as default for a global installation.

# CLI Usage

To see a list of commands and flags use `--help`

```shell
  $ insights-interact --help
```


MIT License

Copyright (c) 2022 The contributors

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
