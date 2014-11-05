## compiler-polyfill

A [yotta](http://github.com/ARMmbed/yotta) module to smooth over some of the
differences between compilers.

### API

#### Attributes
##### `__packed`
Pack a structure, preventing any padding from being added between fields.

##### `__align(N)`
Declare a type to be aligbned on an N-byte boundary.

##### Examples
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


