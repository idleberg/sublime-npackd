# Npackd for Sublime Text

Syntax completions and snippets for creating [Npackd](https://code.google.com/p/windows-package-manager) XML files.

## Installation

### Package Control

1. Make sure you already have [Package Control](http://wbond.net/sublime_packages/package_control/) installed
2. Choose *Install Package* from the Command Palette (`Ctrl+Shift+P` on Windows and Linux, `⇧⌘P` on OS X)
3. Select *Npackd* and press `Enter`

### GitHub

1. Change to your Sublime Text `Packages/User` directory
2. Clone repository `git clone https://github.com/idleberg/Npackd-Sublime-Text.git`

### Manual installation

1. Download the files using the GitHub .zip download option
2. Unzip the files to your Sublime Text `Packages/User` directory

## Usage

By default, SublimeText does not show the completion pop-up when working in the text scope, yet the completions still work. To enable the pop-up, add `text.xml` to `auto_complete_selector` in your user settings.

### Completions

All available [Npackd XML](https://code.google.com/p/windows-package-manager/wiki/RepositoryFormat) elements are prefixed witj `npackd:` and will complete as you press the `Tab` key. Special elements are available for `npacked:license` and `npacked:url`.

Examples:

* `npacked:file…Install.bat` completes to a file element with a path set to *.Npackd\Install.bat*

* `npacked:license>MIT` completes to a license node for the the MIT License

* `npacked:url>GitHub` completes to an URL element for a GitHub project

### Snippets

You can use `scaffold:Npackd` to scaffold an empty XML file. Use `Tab` to jump between the available fields.

## License

The MIT License (MIT)

Copyright (c) 2014 Jan T. Sott

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

## Donate

You are welcome support this project using [Flattr](https://flattr.com/submit/auto?user_id=idleberg&url=https://github.com/idleberg/Npackd-Sublime-Text) or Bitcoin `17CXJuPsmhuTzFV2k4RKYwpEHVjskJktRd`