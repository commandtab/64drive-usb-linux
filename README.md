# 64drive USB tool for Linux and macOS

A tool to upload to/from 64drive development cartridge over USB.

## Building on macOS

1. Install the [Xcode Command Line Tools](https://developer.apple.com/download/more/) (which includes the `gcc` compiler) by running `xcode-select --install`
1. Install [Homebrew](https://brew.sh)
1. Install libftdi by running `brew install libftdi`
1. Compile this tool by running `make`
1. Invoke the compiled executable by running `./64drive`
