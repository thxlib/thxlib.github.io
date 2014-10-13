---
name: thx.core
license: MIT
path: thx/core
tags: 
  - thx
  - general
  - cross
layout: library
classPath: src
description: "Generic multi-purpose library"
contributors: 
  - fponticelli
releasenote: added Error helper classes
version: 0.10.0
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

It also provides new common types that should probably be part of the standard library: [Error](src/thx/core/Error.hx), [Nil](src/thx/core/Nil.hx), [Set](src/thx/core/Set.hx) and [Tuple](src/thx/core/Tuple.hx).

## macro helpers

`thx.core` also includes a few helpers to more easily write and deal with macros.