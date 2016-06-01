# git-hooks
A git hook or two

This is a very small pre-commit script that runs `cloc` and `tree` to show the number of lines of code per language and the directory tree.

To install, copy `pre-commit` to the `.git/hooks` folder of your repo.

This requires [CLOC](http://cloc.sourceforge.net/) (Count Lines of Code) and [tree](http://mama.indstate.edu/users/ice/tree/) to be installed.

On OSX, they can be installed with Homebrew:

```
brew install cloc
brew install tree
````


