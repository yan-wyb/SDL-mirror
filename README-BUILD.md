### Build

```
$ sudo touch /usr/include/stropts.h
$ dpkg-buildpackage -us -uc
```

### Build Tests

```
$ cd test/
$ ./configure
$ make -j6
```                                
