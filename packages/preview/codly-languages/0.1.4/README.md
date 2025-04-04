# `codly-languages` - Language configurations for `codly`

Provides a set of predefined language configurations for use with the `codly`
code listing package. For each supported language, this package defines a
name, icon, and color to use when displaying code.

## Usage

Pretty simple. Import `codly`. Initialize it. Import `codly-languages`.
Configure `codly` with the languages. Like this:

```typst
#import "@preview/codly:1.1.1": *
#show: codly-init

#import "@preview/codly-languages:0.1.4": *
#codly(languages: codly-languages)
```

Then use code blocks as you normally would and the output, for supported
languages, should look like this:

![Example code listings](thumbnail.png)

## Contributing

The following languages are still missing. All contributions welcome.

- ASP
- ActionScript
- Ada
- AppleScript
- AsciiDoc
- Batch File
- CFML
- CSV
- Cabal
- Crontab
- D
- Diff
- DotENV
- Email
- Fish
- Fstab
- GLSL
- Graphviz
- Groff
- Group
- INI
- Jinja2
- Jsonnet
- Lean
- LiveScript
- Makefile
- MediaWiki
- NSIS
- Ninja
- Org mode
- Pascal
- Passwd
- Protobuf
- Puppet
- QML
- Racket
- Rego
- Regular Expressions
- Resolv
- RestructuredText
- Robot
- SLS
- SML
- Slim
- Strace
- SublimeEthereum
- SublimeJQ
- SystemVerilo
- TCL
- TOML
- Textile
- TodoTxt
- Verilog
- WGSL
- cmd-help
- gnuplot
- hosts
- http-request-response
- varlink
- vscode-wgsl

## Icon Attribution

The `typst-small.png` icon included in this package came from the MIT-licensed
[codly](https://github.com/Dherse/codly) project.

The `lisp.svg` icon comes [from
Wikipedia](https://commons.wikimedia.org/wiki/File:Lisp_logo.svg), attribution:
Jooja, CC BY-SA 4.0 <https://creativecommons.org/licenses/by-sa/4.0>, via
Wikimedia Commons.

The `cuda.svg` icon included in this package came from the MIT-licensed
[vscode-icons](https://github.com/vscode-icons/vscode-icons) project.

All other icons included here came from the MIT-licensed
[devicon](https://github.com/devicons/devicon/) project.

## License

This package is released under the MIT License.
