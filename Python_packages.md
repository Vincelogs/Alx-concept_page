## Python packages

Read:[Packages](https://docs.python.org/3.4/tutorial/modules.html#packages)

A Python file can be a **module** but when this file is in a folder, we call this folder a **package**.

File organization is really important in a big project. This means for Python: packages everywhere.

### Compare with C

(file organization, not prototype vs code etc.)

In C: ```#include``` ``"abs.h"``

In Python:
```
import abs
abs.my_abs(89)
```
or
```
from abs import my_abs
my_abs(89)
```
In C: ```#include``` ```"my_math/abs.h"```

In Python:
```
from my_math.abs import my_abs
my_abs(89)
```
or
```
import my_math.abs
my_math.abs.my_abs(89)
```
