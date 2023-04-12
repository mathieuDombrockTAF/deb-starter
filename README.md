## Deb Starter
A starter repo for building Debian packages.

Contains everything needed to setup a basic Deb package. 

**Note: This is meant to be used with interpreted languages (Like NodeJS). Because of this, there is no compile step.**

## Layout
The `./deb` directory contains the application source code as well as the `DEBIAN` directory which contains the package meta data. 

Everything aside from the `DEBIAN` directory will copied to the corresponding location on the host system when the package is installed.

## Build Package
```
./package.sh
```

The built package will go in:
```
./build/
```