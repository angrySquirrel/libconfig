libconfig
=========

A simple library for processing structured configuration files.

This is a fork of [libconfig-1.4.9](http://www.hyperrealm.com/libconfig/) by [Mark Lindner and others](AUTHORS).

The purpose of this fork is to provide a library for **Windows packaging**, in support of cross platform projects that want to share this dependency.

The original library has been modified in the following ways:

* All test and example code removed. See original library for this code.
* Solution and project files modified for `Visual Studio 2013` builds using the `v120` compiler.
* Files not contributing or otherwise relevant the Windows build removed, including Lex and Yacc source.
* Directory structure reorganized for a more traditional layout.
* Authors file updated and version referred to as libconfig-1.4.9 bis, as there are no source changes.

Donations should be directed to the [original project](http://www.hyperrealm.com/libconfig/).
