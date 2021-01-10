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
# 2. Python change user agent in requests module
call requests.url with headers info. You can set it to something like this:
  Example:  
  ```
  headers = {'User-Agent': 'Mozilla/5.0 (Macintosh; Intel Mac OS X 10_10_1) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/39.0.2171.95 Safari/537.36'}
  response = requests.get(url, headers = headers)
  
  ```
***
