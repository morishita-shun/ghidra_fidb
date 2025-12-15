# iot_libc
- Ghidra 12.0
- libc.a -> *.o
- url
  - uClibc/0.9.30.1: https://uclibc.org/downloads/binaries/0.9.30.1/
  - uClibc/SliTaz: http://distro.ibiblio.org/slitaz/sources/packages/c/
  - uClibc/Aboriginal_1.2.6: http://landley.net/aboriginal/downloads/old/1.2.6/
  - musl/Aboriginal_1.4.5: http://landley.net/aboriginal/downloads/old/1.4.5/

## iot_libc_arm.fidb
- ARM:LE:32:v8

library | version | variant
--|--|--
uClibc | 0.9.30.1 | armv4l, armv5l
uClibc | SliTaz | armv4l, armv5l, armv6l
uClibc | Aboriginal_1.2.6 | armv4l, armv5l, armv6l, armv7l
musl | Aboriginal_1.4.5 | armv4l, armv5l, armv6l

## iot_libc_mips.fidb
- MIPS:BE:32:default

library | version | variant
--|--|--
uClibc | 0.9.30.1 | mips
uClibc | SliTaz | mips
uClibc | Aboriginal_1.2.6 | mips
musl | Aboriginal_1.4.5 | mips

## iot_libc_mipsel.fidb
- MIPS:LE:32:default

library | version | variant
--|--|--
uClibc | 0.9.30.1 | mipsel
uClibc | SliTaz | mipsel
uClibc | Aboriginal_1.2.6 | mipsel
musl | Aboriginal_1.4.5 | mipsel

## iot_libc_x86.fidb
- x86:LE:32:default

library | version | variant
--|--|--
uClibc | 0.9.30.1 | i586, i686
uClibc | SliTaz | i486
uClibc | Aboriginal_1.2.6 | i486, i586, i686
musl | Aboriginal_1.4.5 | i486, i586, i686

