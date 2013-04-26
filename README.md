ghcmod-vim\_cabal-dev
====================

Rudimentary ghcmod-vim support for cabal-dev via ftplugin.

The script checks for the existence of a cabal\_dev directory in the current directory and its root folders and sets up the necessary variables.

In order to avoid issues with package shadowing, it forces the usage of the packages registered in the cabal\_dev directory by setting the corresponding -package-id options, as cabal-dev build would do.

Usage
=====

Copy in your .vim/ftplugin folder.

Limitations
===========

Multiple compiler versions are _NOT_ supported.
Windows is _NOT_ supported.

Dependencies
============

Requires ghcmod-vim

https://github.com/eagletmt/ghcmod-vim

