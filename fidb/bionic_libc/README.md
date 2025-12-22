# bionic_libc
- Ghidra 12.0
- toolchains/llvm/prebuilt/<host>/sysroot/usr/lib/<ABI>/libc.a -> *.o
- url
  - r21e: https://github.com/android/ndk/wiki/Unsupported-Downloads#r21e
  - r23c: https://github.com/android/ndk/wiki/Unsupported-Downloads#r23c
  - r25c: https://github.com/android/ndk/wiki/Unsupported-Downloads#r25c
  - r27c: https://github.com/android/ndk/releases/tag/r27c

## bionic_libc_aarch64.fidb
- AARCH64:LE:64:v8A

library | version | variant
--|--|--
bionic | r21e | aarch64
bionic | r23c | aarch64
bionic | r25c | aarch64
bionic | r27c | aarch64

## bionic_libc_arm.fidb
- ARM:LE:32:v8

library | version | variant
--|--|--
bionic | r21e | arm
bionic | r23c | arm
bionic | r25c | arm
bionic | r27c | arm

## bionic_libc_x86.fidb
- x86:LE:32:default

library | version | variant
--|--|--
bionic | r21e | i686
bionic | r23c | i686
bionic | r25c | i686
bionic | r27c | i686

## bionic_libc_x86_64.fidb
- x86:LE:64:default

library | version | variant
--|--|--
bionic | r21e | x86_64
bionic | r23c | x86_64
bionic | r25c | x86_64
bionic | r27c | x86_64
