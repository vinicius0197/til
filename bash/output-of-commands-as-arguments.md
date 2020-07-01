If you want to pipe the output of some shell command into another shell command, you can use the following syntax:

```
export EMACS=$(which emacs26)
```

In this example, I'm running `which emacs26` to find out which is the path to the Emacs 26 path, and using it as an argument
for the `export` command, by creating an enviroment variable.
