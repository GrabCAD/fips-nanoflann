# fips-nanoflann
FIPS-ified version of nanoflann.


* [nanoflan](https://github.com/MODit3D/nanoflann)
* [fips](https://github.com/flooh/fips)

This is a header-only library, simply edit your fips.yml to import this repository:

```yaml
imports:
    fips-nanoflann:
        git:   git@github.com:modit3d/fips-nanoflann

```

```c++
#include "nanoflann.hpp"
```
