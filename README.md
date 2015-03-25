# Integrated Build System for nomlib (Sublime Text)

**IMPORTANT:** This package is **incomplete** and should not be used at the moment! I have published it so that I can continue testing things and wrap up the last remaining TODO issues.

**NOTE:** This package has only been tested under Mac OS X, ...

This [Sublime Text](http://www.sublimetext.com/) package adds build tools, ... for the [nomlib](https://github.com/i8degrees/nomlib) game engine.

## Installation

### Package Control

1. Make sure you already have [Package Control](http://wbond.net/sublime_packages/package_control/) installed.
2. Choose “*Install Package*” from the Command Palette (```Ctrl+Shift+P``` on Windows/Linux, ```⇧⌘P``` on OS X).
3. Select “*nomlib_sublime_text*” and press ```Enter```.

### GitHub

1. Change to your Sublime Text ```Packages``` directory.
2. Clone repository ```git clone https://github.com/i8degrees/nomlib_sublime_text.git```.

### Manual installation

1. Download the files using the GitHub ```.zip``` download option.
2. Unzip the files to your Sublime Text ```Packages``` directory.

## Usage

*...STUB...*

### Build System

A build system works on Mac OS X only and should be available by default. To run your script press ```⌘+B``` or build from the *Tools* menu.

## Contributing

*...STUB...*

## TODO

- [x] Rename package to **nomlib_sublime_text**; this implies that we probably ought to rename our package directory, too. We might as well rename the github repository, since it hasn't been around very long.

- [ ] xcode_nomlib.sublime-build: figure out what we want to do with the potential dependency [xcpretty](https://github.com/supermarin/xcpretty) -- in any case, an absolute path to the local rbenv / gem path isn't going to cut it!
- [ ] xcode_nomlib.sublime-build: clean up variants, i.e.: 'Test', 'Run'.

- [ ] Finish writing README.md.
- [ ] Distribute our local color scheme (Dark Soda)?
- [ ] Pull out local nom types from our C.tmLanguage, C++.tmLanguage files and 
distribute?

- [ ] Review [Package Control: Submitting a Package](https://packagecontrol.io/docs/submitting_a_package) documentation.
- [ ] Make mention of this repository in nomlib's README.md once published.
