# c++clean
c++clean is a tiny experimental script to automate reappearing metadata formating tasks.

## Features
- Copyright information
- Author information from git history
- File name information

## Example

The script uses regular expressions to match and replaces metadata in C++ code.

```bash
% ./c++clean.py examples/ugly1.cpp
```

```c++
/* c++clean example
 * Copyright (C) 2021  EPFL
 */

/*!
  \file ugly1.cpp
  \brief Some description

  \author Heinz Riener
*/
