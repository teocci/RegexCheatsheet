## Cheatsheet for regex syntaxes

This is a very simple and straight-forward cheat-sheet lists for [Perl Compatible Regular Expressions (PCRE)][1] and [Portable Operating System Interface (POSIX)][2] regular expression syntaxes.

### Disclaimer

This repository contains a cheat-sheet, which is still a work in progress; a lot of entries need some details in some kind of tooltip. Errors or missing data contributions, or just want to make this prettier/more accurate, don't hesitate to open an [issue][3] or a [pull request][4]. 

### Specifications

Many programs use regular expression to find & replace text. However, they tend to come with their own different flavor.

You can probably expect most modern software and programming languages to be using some variation of the Perl flavor, "PCRE"; however command-line tools (grep, less, ...) often use the POSIX flavor (sometimes with an extended variant, e.g. `egrep` or `sed -r`). ViM also comes with its own syntax (a superset of what Vi accepts).

The rendered cheatsheet is available here: [regex cheatsheet][5]

### Contributing
If you would like to contribute code, you can do so through GitHub by forking the repository and sending a pull request.
When submitting code, please make every effort to follow existing conventions and style in order to keep the code as readable as possible.

## Credits

* [Regular Expressions (Regex) Cheat Sheet][6]

## License

The code supplied here is covered under the MIT Open Source License..


[1]: http://www.pcre.org/
[2]: http://standards.ieee.org/develop/wg/POSIX.html
[3]: https://github.com/teocci/RegexCheatsheet/issues/new
[4]: https://github.com/teocci/RegexCheatsheet/compare
[5]: https://teocci.github.io/RegexCheatsheet/
[6]: http://www.petefreitag.com/cheatsheets/regex