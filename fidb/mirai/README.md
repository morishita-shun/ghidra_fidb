# mirai
- Ghidra 12.0
- url
  - Mirai: https://github.com/jgamblin/Mirai-Source-Code
  - uClibc/0.9.30.1: https://uclibc.org/downloads/binaries/0.9.30.1/
  - uClibc/SliTaz: http://distro.ibiblio.org/slitaz/sources/packages/c/
  - uClibc/Aboriginal_1.2.6: http://landley.net/aboriginal/downloads/old/1.2.6/
  - musl/Aboriginal_1.4.5: http://landley.net/aboriginal/downloads/old/1.4.5/

## mirai_arm.fidb
- ARM:LE:32:v8

library | version | variant
--|--|--
Mirai_uClibc | 0.9.30.1 | armv4l, armv5l
Mirai_uClibc | SliTaz | armv4l, armv5l, armv6l
Mirai_uClibc | Aboriginal_1.2.6 | armv4l, armv5l, armv6l, armv7l
Mirai_musl | Aboriginal_1.4.5 | armv4l, armv5l, armv6l

## mirai_x86.fidb
- x86:LE:32:default

library | version | variant
--|--|--
Mirai_uClibc | 0.9.30.1 | i586, i686
Mirai_uClibc | SliTaz | i486
Mirai_uClibc | Aboriginal_1.2.6 | i486, i586, i686
Mirai_musl | Aboriginal_1.4.5 | i486, i586, i686

## mirai_mips.fidb
- MIPS:BE:32:default

library | version | variant
--|--|--
Mirai_uClibc | 0.9.30.1 | mips
Mirai_uClibc | SliTaz | mips
Mirai_uClibc | Aboriginal_1.2.6 | mips
Mirai_musl | Aboriginal_1.4.5 | mips

