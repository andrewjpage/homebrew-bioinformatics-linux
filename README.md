# homebrew-bioinformatics-linux

_The too hard basket for Linux bioinformatics brew formulae_!

[Homebrew](http://brew.sh/) is the software packaging system for Mac OS X that Apple should have written. [Linuxbrew](https://github.com/Homebrew/linuxbrew) is a fork of Homebrew for Linux. One of the best features of Brew is that a user without root privileges can install packages in their own home directory.

Packages are described by _formulae_ which are simple to write, and based on
Ruby.  Formulae are kept in _taps_.  There are lots of good taps.  The one I
use a lot is [homebrew-science](https://github.com/Homebrew/homebrew-science).  
However to get into an offical tap like that one, a tool needs to be capable of being
compiled and/or run on Mac OS X.  I use Linuxbrew for my servers, and some
of our tools are too hard to compile for OS X or simply only exist as Linux
binaries.  So that's why I started this project.

If you have brew installed, you can enable this repository like this:

    brew tap tseemann/homebrew-bioinformatics-linux
    
Then you can install any formulae I have written, for example:

    brew install blast-legacy

If you are on OS X, some of these formulae _may_ work, but many won't. 

I'm happy to accept pull requests for new packages, but if it would not take
too much effort to work on OS X too, then I will suggest you contribute it
to [homebrew-science](https://github.com/Homebrew/homebrew-science) instead. 
This repository is really just a "too hard basket" for Linux bioinformatics
tools.

