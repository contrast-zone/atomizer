# atomizer

![](media/ssh-320-atomizer.png)

## about the project

*Atomizer* is a s-expression fractal like structuring visualization tool. In computer programming, an [S-expression](https://en.wikipedia.org/wiki/S-expression) (or symbolic expression, abbreviated as sexpr or sexp) is an expression in a like-named notation for nested list (tree-structured) data. S-expressions were invented for and popularized by the programming language Lisp, which uses them for source code as well as data. This application graphically displays s-expressions.

## application specifics

The application is consisted of two panes. Left pane resembles input prompt for entering s-expressions. Multiline input is obtained by holding `shift` while hitting `enter`. Standard pasting s-expressions from clipboard should also work fine. History of previously entered s-expressions is accessed by pressing up and down arrows. On hitting `enter` on its own in the input pane, if valid, inputted s-expression is sent to the right pane visualizer. Refer to built in application instructions for learning about navigating visualizer (click the bottom-right questionmark). Invalid expressions that include unmatched braces are reported as errors.

## testing the application

Online link for testing the application is [here](contrast-zone.github.io/atomizer).

## installing and running the application

This package contains the whole *Atomizer* application. To run *Atomizer*, download this package, unzip it to a folder of your choice, and load included `index.html` into a web browser. There is no build procedure, there are no third party dependencies, and the application should work as it is, even from local file system.

## licensing information

The project is licenced under [MIT License](LICENSE).
