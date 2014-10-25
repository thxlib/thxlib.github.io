---
name: thx.core
license: MIT
path: thx/core
tags: 
  - thx
  - general
  - cross
  - std
layout: library
classPath: src
description: General purpose library. It contains extensions to many of the types contained in the standard library as well as new complementary types.
contributors: 
  - fponticelli
releasenote: minor
version: 0.10.2
url: "https://github.com/fponticelli/thx.core"
title: thx.core

---

# thx.core

[![Build Status](https://travis-ci.org/fponticelli/thx.core.svg?branch=master)](https://travis-ci.org/fponticelli/thx.core)

[![Sauce Test Status](https://saucelabs.com/browser-matrix/thx-core.svg)](https://saucelabs.com/u/thx-core)

Generic multi-purpose library. `thx.core` aims to be the [lodash](http://lodash.com/) library for Haxe.

## helper classes

It contains a lot of useful helper classes to simplify dealing with a lot of types from the standard library.

## new basic types

It also provides new common types that should probably be part of the standard library: [Error](http://thx-lib.org/api/thx/core/Error.html), [Nil](http://thx-lib.org/api/thx/core/Nil.html), [Set](http://thx-lib.org/api/thx/core/Set.html) and [Tuple](http://thx-lib.org/api/thx/core/Tuple.html).

## macro helpers

`thx.core` also includes a few helpers to more easily write and deal with macros.

## install

From the command line just type:

```bash
haxelib install thx.core
```

To use the `dev` version do:

```bash
haxelib git thx.core https://github.com/fponticelli/thx.core.git
```
