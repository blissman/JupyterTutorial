# Jupyter Tutorial
This repo contains machine learning exercises for Jupyter Notebook.

# Prerequisites
## Anaconda
Install [Anaconda](https://www.anaconda.com/) from this link, or by using homebrew:
```zsh
$ brew install anaconda
```
You could install python, Jupyter Notebook, etc. independently as well, but this is easier.

## Graphviz
Use Graphviz to convert your .dot files to .png to view your model.
```zsh
$ brew install graphviz
```
Graphviz usage:
```zsh
$ dot -Tpng <path-to-input.dot> -o <path-to-output.png>
```