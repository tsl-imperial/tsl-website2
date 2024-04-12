[**Documentation**](https://greene-lab.gitbook.io/lab-website-template-docs)


Issues - posix-spown issues on macOS. if they appear, you can address using

bundle config build.cbor --with-cflags="-Wno-incompatible-function-pointer-types"
bundle config build.posix-spawn --with-cflags="-Wno-incompatible-function-pointer-types"
