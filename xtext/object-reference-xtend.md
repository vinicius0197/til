In Xtend, the triple equal is equivalent to Java object reference equality:

```
  def isStringType(SomeType type) {
    type === STRING_TYPE // checks if type and STRING_TYPE point to the same object
  }
```
