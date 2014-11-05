## compiler-polyfill

A [yotta](http://github.com/ARMmbed/yotta) module to smooth over some of the
differences between compilers.

### API

### Attributes
```C
#include "compiler-polyfill/attributes.h"

struct foo{
   char x;
   int y;
} __packed;

struct bar{
   int x;
} __align(16);
```


