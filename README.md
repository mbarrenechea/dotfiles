# David Inga's dotfiles

My own dotfiles based on [Mathias’s dotfiles](https://github.com/mathiasbynens/dotfiles).

## Installation

First, we need [Homebrew](http://brew.sh).

  ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

Then we can install brew dependencies:

  ./brew.sh

## Usage

You can clone the repository wherever you want. (I like to keep it in ~/Projects/dotfiles, with ~/dotfiles as a symlink.) The bootstrapper script will pull in the latest version and copy the files to your home folder.

  git clone https://github.com/mathiasbynens/dotfiles.git && cd dotfiles && source install.sh

To update, cd into your local dotfiles repository and then:

  source install.sh

Alternatively, to update while avoiding the confirmation prompt:

  set -- -f; source bootstrap.sh

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b feature/my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin feature/my-new-feature`
5. Submit a pull request :D

## License

The MIT License (MIT)

Copyright (c) 2015 David Inga

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

