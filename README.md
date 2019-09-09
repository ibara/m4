[![Build Status](https://travis-ci.org/ibara/m4.svg?branch=master)](https://travis-ci.org/ibara/m4)

m4
==
`m4`, or `om4`, is a portable version of the OpenBSD m4 program.

It is suitable for ensuring standard m4 compliance, for older Unix machines
that do not have a free m4 or have a very old m4.

`m4` requires a C compiler, a Yacc program, a Lex program, and a make program
to build.

If you need a Yacc program, a dependency-free `yacc` is available here:
https://github.com/ibara/yacc/

`m4` is known to build and run on all *BSD flavors, Linux, Mac OS X, Cygwin,
AIX, and Solaris. It is very likely to run on other Unix flavors; please let
me know if you are using this on a Unix not listed here so that I may add it
to the list.

Compiling
---------
To build, first install `lex` and `yacc`, then run:
```
$ ./configure
$ make
# make install
```

Testing
-------
Tested on Linux and Mac OS X using TravisCI. *BSD, Cygwin, AIX, and Solaris
testing done manually. AIX 5.1L and Solaris 8 are used to help ensure
backwards compatibility.

Licensing
---------
All files are a combination of BSD and ISC licensed files.

Get a tarball
-------------
See releases tab. Latest is `om4-6.6`.
