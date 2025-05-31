# C-script language (C*)
Javascript style version of C-language.

* All code is in nested scopes
* Variables, arrays, structs and functions are defined inside scopes
* Functions behave like nested scopes for variable visibility
* No global variables, top scope stack variables visible to all levels directly

Example code (example.cst):
```
int var = 1;
int entry(int ivar) {
  int ovar = ivar + var;
  return ovar;
}
int rvar = entry(var);
```
