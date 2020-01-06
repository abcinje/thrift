## RESEARCH

### Prerequisites
- autoconf
- automake
- autotools-dev
- pkg-config
- m4
- libtool
- libtbb2
- libtbb-dev
- libboost-dev 
- libssl-dev 
- libgtest-dev
- bison
- flex
- ruby-dev
- python-dev
- php5-dev

### To build and install
```
$ ./bootstrap.sh
$ ./configure --with-libevent
$ make
$ sudo make install
```

### Troubleshooting
- `event.h`: No such file or directory:  
  Install `libevent-dev` package.
  
- `libcrypto` required:  
  Install `libssl1.0-dev` package.

- *** No rule to make target `libthriftnb.la`:  
  Configure with `--with-libevent` option.

- `libboost_unit_test_framework.a`: No such file or directory:  
  Install `libboost-test-dev` package.
