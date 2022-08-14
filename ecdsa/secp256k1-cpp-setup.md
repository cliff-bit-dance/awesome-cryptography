- build dependencies
```
brew install automake  ## Which should also install autoconf and allow rvm to finish installing
brew install libtool
```

- build
```
./autogen.sh
./configure
make
make check  # run the test suite
sudo make install  # optional
```

To compile optional modules (such as Schnorr signatures), you need to run ./configure with additional flags (such as --enable-module-schnorrsig). Run ./configure --help to see the full list of available flags.

