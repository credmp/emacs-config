# Deprecated

I have started using [Doom Emacs](https://github.com/hlissner/doom-emacs) and as a result have a completely new configuration. This is left here as an archive.

# Emacs Config

This is my emacs configuration. It was crafted from 2000 until
now. Once in a while I throw away all my configuration just to start
over.

This version uses literal programming with org-babel.

It is heavely influenced by [Sacha Chua's configuration](http://pages.sachachua.com/.emacs.d/Sacha.html)

Go ahead, read the entire configuration by opening [loader.org](loader.org).

## Setup

```
~ $ git clone git@gitlab.com:buildfunthings/emacs-config.git .emacs.d
~/.emacs.d $ git submodule init
~/.emacs.d $ git submodule update
```

When you start GNU Emacs it will start downloading all the required packages. It might take some time, depending on your internet connection and machine.

Afterwards, restart GNU Emacs and it will load up very speedy.
