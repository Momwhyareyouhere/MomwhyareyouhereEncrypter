# MomwhyareyouhereEncrypter

This is a python package called 'MomwhyareyouhereEncrypter' and you can download this package by running this command:
```
pip install MomwhyareyouhereEncrypter
```

So to encrypt any files you put this to script:
```
from mom_encrypter import MomwhyareyouhereEncrypter

MomwhyareyouhereEncrypter.encrypt("example.py")

```
Replace example.py with you file

So to decrypt it you put this script:
```
from mom_encrypter import MomwhyareyouhereEncrypter

MomwhyareyouhereEncrypter.decrypt("example.mom")

```

It has also a feature to run it even its encrypted:
```
from mom_encrypter import MomwhyareyouhereEncrypter

MomwhyareyouhereEncrypter.run("example.mom")
```

So this looks like when you put all of them together:
```
from mom_encrypter import MomwhyareyouhereEncrypter

MomwhyareyouhereEncrypter.encrypt("example.py")

MomwhyareyouhereEncrypter.unencrypt("example.mom")

MomwhyareyouhereEncrypter.run("example.mom")
```

Pypi Website:
[Website](<https://pypi.org/project/MomwhyareyouhereEncrypter>)
