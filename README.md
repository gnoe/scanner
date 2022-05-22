# scanner
Scanner tries to be a generic Scanner or Lexer implementation written in Go
that will allow you to focus only on the logic of the source you want to scan.
This implementation is built upon the scanner from the `go/scanner` package and the lexer from the `text/template` package from the standard library.
I think that a mix of this two implementations can fit as a perfect framework for building lexers without worrying too much about how to navigate throughout your input source. As well it provides you a handful functions to ease the inspection of your data.
