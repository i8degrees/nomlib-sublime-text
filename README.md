# nomlib's integrated build system for Sublime Text

**NOTE:** This package is **incomplete** and should not be used at the moment! I have published it so that I can continue testing things and wrap up the last remaining TODO issues.

## TODO

- [ ] rbenv path issue in xcode_nomlib.sublime-build
- [ ] clean up xcode_nomlib.sublime-build, i.e.: 'Test', 'Run'
- [ ] README.md
- [ ] Color scheme?
- [ ] C.tmLanguage, C++.tmLanguage clean up && integration ..?
  * Ensure that we remove the original files from Packages/User once we are
ready for the transition!

- [ ] Verify package-metadata.json is complete
  * "platforms": ["*"]
  * "sublime_text": "*"

This [Sublime Text](http://www.sublimetext.com/) package adds build tools, ... for the [nomlib](https://github.com/i8degrees/nomlib) game engine.

## Installation

### Package Control

1. Make sure you already have [Package Control](http://wbond.net/sublime_packages/package_control/) installed.
2. Choose “*Install Package*” from the Command Palette (`Ctrl+Shift+P` on Windows/Linux, `⇧⌘P` on OS X).
3. Select “*nomlib-sublime-text*” and press `Enter`.

### GitHub

1. Change to your Sublime Text `Packages` directory.
2. Clone repository `git clone https://github.com/i8degrees/nomlib-sublime-text.git`.

### Manual installation

1. Download the files using the GitHub .zip download option.
2. Unzip the files to your Sublime Text `Packages` directory.

## Usage

### Build System

A build system works on Mac OS X only and should be available by default. To run your script press `⌘+B` or build from the *Tools* menu.
