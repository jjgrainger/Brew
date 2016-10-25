# Brew

Manage your Mac OS Dependencies with [Homebrew](http://brew.sh/), [Casks](https://caskroom.github.io/) and a [Brewfile](https://github.com/Homebrew/homebrew-bundle).

The following setup allows you to automatically install homebrew and the dependencies and apps defined in `Brewfile`.

## Installation

Either [download the repository](https://github.com/jjgrainger/brew/archive/master.zip) or clone it:

```
$ git clone https://github.com/jjgrainger/Brew.git
```

## Usage

When on a new machine, jump into the directory and execute `install.sh` 

```
$ cd path/to/Brew

$ ./install.sh
```

This will install Homebrew if it hasn't been already, then run `$ brew bundle` to install everything listed in `Brewfile`.

For more information, see this [blog post](http://jjgrainger.co.uk/2016/10/25/homebrew-casks-and-a-brewfile/)
