## cgo crossbuild

Dockerfile for cgo cross compiling environments

This is a multiarch Docker build environment image. You can use this image to produce binaries for multiple architectures.

## Supported targets

| Triple                | Aliases                             | linux | osx  | windows |
| --------------------- | ----------------------------------- | ----- | ---- | ------- |
| x86_64-linux-gnu      | **(default)**, linux, amd64, x86_64 | x     |      |         |
| i386-linux-gnu        | linux, i386                         | x     |      |         |
| arm-linux-gnueabi     | arm, armv5                          | TBD   |      |         |
| arm-linux-gnueabihf   | armhf, armv7, armv7l                | TBD   |      |         |
| aarch64-linux-gnu     | arm64, aarch64                      | TBD   |      |         |
| mipsel-linux-gnu      | mips, mipsel                        | TBD   |      |         |
| powerpc64le-linux-gnu | powerpc, powerpc64, powerpc64le     | TBD   |      |         |
| x86_64-apple-darwin   | osx, osx64, darwin, darwin64        |       | x    |         |
| x86_64h-apple-darwin  | osx64h, darwin64h, x86_64h          |       | x    |         |
| i386-apple-darwin     | osx32, darwin32                     |       | TBD  |         |
| x86_64-w64-mingw32    | windows, win64                      |       |      | x       |
| i686-w64-mingw32      | win32                               |       |      | x       |

## Credit

This project is inspired by the [cross-compiler](https://github.com/multiarch/crossbuild) by [Multiarch](https://github.com/multiarch)

## Donation

If this project help you reduce time to develop, you can give me a cup of coffee ;)

[![](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://paypal.me/ngoxuanloc)

## License

MIT