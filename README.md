# How to install Jupyter Notebook & Numpy & etc. on Android via Termux

## 1. Jupyter Notebook

``` shell
pkg install python python libzmq libcrypt clang
pip install jupyter
```
Reference: https://gist.github.com/gatopeich/8debf57e4fd8188f2f6610c6f5b0cf55

#### [Tips]
- Find more Jupyter themes and learn more about how to use them: https://github.com/dunovank/jupyter-themes
- Use Extensions: ` pip install jupyter_contrib_nbextensions `


##  2. Termux

``` shell
MATHLIB=m pip install numpy
```
Reference: https://wiki.termux.com/wiki/Python

## 3. matplotlib
``` shell
pkg install matplotlib
```


## 4. etc.

... 