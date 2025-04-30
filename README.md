# pcre 8.45 "for IRIX"

The "for IRIX" part so far is a bit humorous as the source, or at least the C part of it, builds and passes tests as is.

## Installation

Unpack somewhere, then:

```
$ mkdir build
$ cd build
$ export CC=cc
$ ../configure --disable-cpp
$ make
$ make test
```

Then, ascend to root and:

```
# make install
```

## Todo

Try what happens with C++ part.
