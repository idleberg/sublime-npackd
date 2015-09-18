# Npackd for Sublime Text

[![The MIT License](https://img.shields.io/badge/license-MIT-orange.svg?style=flat-square)](http://opensource.org/licenses/MIT)
[![GitHub release](https://img.shields.io/github/release/idleberg/Npackd-Sublime-Text.svg?style=flat-square)](https://github.com/idleberg/Npackd-Sublime-Text/releases)
[![Travis](https://img.shields.io/travis/idleberg/Npackd-Sublime-Text.svg?style=flat-square)](https://travis-ci.org/idleberg/Npackd-Sublime-Text)

Sublime Text snippets to create [Npackd](https://code.google.com/p/windows-package-manager) XML files.

## Installation

### Package Control

1. Make sure you already have [Package Control](http://wbond.net/sublime_packages/package_control/) installed
2. Choose “*Install Package*” from the Command Palette (<kbd>Super</kbd>+<kbd>Shift</kbd>+<kbd>p</kbd>)
3. Type “*Npackd*” and press <kbd>Enter</kbd>

### GitHub

1. Change to your Sublime Text `Packages` directory
2. Clone repository `git clone https://github.com/idleberg/Npackd-Sublime-Text.git Npackd`

### Manual installation

1. Download the latest [stable release](https://github.com/idleberg/Npackd-Sublime-Text/releases)
2. Unzip the archive to your Sublime Text `Packages` directory

## Usage

By default, SublimeText does not show the completion pop-up when working in the text scope, yet the completions still work. To enable the pop-up, add `text.xml` to `auto_complete_selector` in your user settings.

### Snippets

All available [Npackd XML](https://code.google.com/p/windows-package-manager/wiki/RepositoryFormat) elements are prefixed witj `npackd:` and will complete as you press the `Tab` key. Special elements are available for `npacked:license` and `npacked:url`.

Examples:

* `npacked:file…Install.bat` completes to a file element with a path set to *.Npackd\Install.bat*

* `npacked:license>MIT` completes to a license node for the the MIT License

* `npacked:url>GitHub` completes to an URL element for a GitHub project

### Scaffolding

You can use `scaffold:Npackd` to scaffold an empty XML file. Use `Tab` to jump between the available fields. The `cheatsheet:Npackd` snippet will display all available commands.

## License

This work is licensed under the [The MIT License](LICENSE).

## Donate

You are welcome support this project using [Flattr](https://flattr.com/submit/auto?user_id=idleberg&url=https://github.com/idleberg/Npackd-Sublime-Text) or Bitcoin `17CXJuPsmhuTzFV2k4RKYwpEHVjskJktRd`
