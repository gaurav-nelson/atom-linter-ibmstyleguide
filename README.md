# linter-ibmstyleguide
An Atom package for the [retext-ibmstyleguide](https://github.com/gaurav-nelson/retext-ibmstyleguide) module. It uses the Atom Linter package to highlight errors and provide usage advice while writing and editing documents in Atom.

## Dependencies
* [Atom](https://atom.io/)
* [Atom Linter Package](https://atom.io/packages/linter)

## Features (v 2.0.0)
* Highlights incorrect words as you type marked as 'Use it: no' and 'Use it: with caution'.
* Option to ignore words by adding them to 'Ignore Words' list in settings.
* Options to enable or disable product specific conventions.
* Move mouse over an incorrect word to read description and correct word usage.
* Works for ASCIIDOC, DOCXML, MARKDOWN files and can be configured to work with other filetypes as well.

## Configuration Options
* **Show errors as you type**: This behavior can be changed by unchecking `Lint on Change` checkbox for the Atom Linter package settings. The errors will then only be highlighted when you save the file.
* **Set severity**: The default level is `Warning`. Setting the severity level to `Error` or `Info` helps distinguish its highlighting from the highlighting of an ordinary spell checker, or higher priority linter.
* **Ignore Files**: Add filenames for which you do not want this package to show errors. 
* **Ignore Words**: Add comma-seperated list of words for which you do not want to see errors. 
* **Enable or Disable product specifc conventions**: Select all the produts for which you want to show product specific errors.
* **Enable for other filetypes**: Enable it for other filetypes by adding the [scope name](https://atom.io/packages/file-types) for a grammar. For example, add `source.gfm` to enable this package for Markdown files.
