Bash Enhancments
----------------

##Installation (CYGWIN)
Add the following to your $HOME/.bashrc
```
# Bash Enhance
export DEV_TOOLBOX=/cygdrive/c/workspace/dev-toolbox
if [ -f "${DEV_TOOLBOX}/bash/.bash_enhance-cygwin" ]; then
  source "${DEV_TOOLBOX}/bash/.bash_enhance-cygwin"
fi
```

##Bookmarks Sample
```
cd /cygdrive/c/workspace
b workspace #adds bookmark
g workspace #goto bookmark
```

