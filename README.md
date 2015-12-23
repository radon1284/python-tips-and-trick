# python-tips-and-trick

**work with multiple versions of Python installed in parallel?**

On Linux, Mac OS X and other POSIX systems, use the versioned Python commands in combination with the -m switch to run the appropriate copy of pip:

```
python2   -m pip install SomePackage  # default Python 2
python2.7 -m pip install SomePackage  # specifically Python 2.7
python3   -m pip install SomePackage  # default Python 3
python3.4 -m pip install SomePackage  # specifically Python 3.4
```
