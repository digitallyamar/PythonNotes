# PythonNotes
Tid bits on Python programming
# 1. Store a set of items without duplicates
If order is not important, this can be achieved using Sets.
  
  Example:  
  ```
        python3
        Python 3.6.9 (default, Jul  3 2019, 15:36:16) 
        [GCC 5.4.0 20160609] on linux
        Type "help", "copyright", "credits" or "license" for more information.
        >>> Items = set()
        >>> Items.add(1)
        >>> Items
        {1}
        >>> Items.add(2)
        >>> Items
        {1, 2}
        >>> Items.add(1)
        >>> Items
        {1, 2}
  ```
***
